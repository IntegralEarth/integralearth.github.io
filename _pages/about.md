---
layout: single
title: About
permalink: /about/
---

Integral Earth is a user-friendly web interface for monitoring methane emissions with satellite data. It can be applied to regions of interest ranging in scale from small urban areas to countries or continents, and global applications are also supported. It is currently available for free while we prototype the system and develop a funding model.

## Methodology

Integral Earth is built on the open-source <a href = "https://integratedmethaneinversion.github.io" target = "#">Integrated Methane Inversion (IMI)</a> facility. The IMI infers methane emissions from users’ regions of interest at up to 25-km resolution by inverse analysis (“inversions”) of satellite observations from the TROPOspheric Monitoring Instrument (TROPOMI).

<!-- ![integrated methane inversion logo](/assets/images/logos/imi_logo_fullres.png){: .align-center, style="width: 30%; border-radius: 15px; margin-left: 35%; margin-top: 7%" } -->

![integral earth form](/assets/images/model.png){: .align-center, }

## Requesting an inversion

Users can submit an inversion request by filling out a form detailing their region and period of interest. The form requires just an outline of the region (submitted via an interactive portal or by shapefile upload), a start day, and an end day. Advanced settings are available for users access to all of the features of the research-grade IMI software, including continuous near-real-time emission monitoring.

![integral earth form](/assets/images/About_Page/inversion_form.png){: .align-center, }

![integral earth form](/assets/images/About_Page/interactive_bounds.png){: .align-center, }

Submitting the form sends a job to our Amazon Web Services (AWS) backend for evaluation by our team. We assess whether the requested inversion is likely to succeed, based on the available satellite observations and best prior emission estimates, and then share our evaluation with the user. Some adjustments may be needed for the job to be successful, in which case we work with the user to identify a useful configuration.

Once the job is confirmed, we run the IMI and return the results to the user’s Integral Earth dashboard. All data analysis happens behind the scenes on the AWS cloud.

## Viewing inversion results

Users can view or download the results of their inversions through the Integral Earth dashboard. The dashboard makes it easy to visualize the optimized emission estimates, trends, differences with official inventories, and the TROPOMI data themselves. Users can have multiple dashboards for different regions/periods of interest.

![integral earth form](/assets/images/Development_Page/Dashboard – Full.png){: .align-center, }
