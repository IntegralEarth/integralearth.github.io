---
layout: single
title: Contact Us
permalink: /contact/
---

We look forward to hearing from you!

<form id="contact-form">
  <label for="name">Name:</label>
  <input type="text" id="name" name="user_name" required>

<label for="email">Email:</label>
<input type="email" id="email" name="user_email" required>

<label for="message">Message:</label>
<textarea id="message" name="message" style = "height: 150px !important;" required></textarea>

<button type="submit">Send</button>

</form>

<p id="response-message"></p>

<style>
  form {
    /* max-width: 600px; */
    margin: 0 auto;
  }

  label {
    display: block;
    margin-bottom: 0.5em;
  }

  input, textarea {
    width: 100%;
    padding: 0.5em;
    margin-bottom: 1em;
    border: 1px solid #ccc;
    border-radius: 4px;
  }

  button {
    background-color: #0073e6;
    color: white;
    padding: 0.5em 1em;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }

  button:hover {
    background-color: #005bb5;
  }
</style>

<script type="text/javascript">
  document.getElementById('contact-form').addEventListener('submit', function(event) {
    event.preventDefault();

    emailjs.sendForm('service_s3myfef', 'template_12be4ug', this)
      .then(function() {
        document.getElementById('response-message').innerHTML = 'Message sent successfully!';
      }, function(error) {
        document.getElementById('response-message').innerHTML = 'Failed to send message: ' + JSON.stringify(error);
      });
  });
</script>
