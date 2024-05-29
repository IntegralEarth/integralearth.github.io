---
layout: single
title: Development
permalink: /development/
---

Exciting things are coming down the pipe!
![Methane](/assets/images/Development_Page/methanepipe.jpeg){: .align-center, style="width: 100%; border-radius: 15px;" }

## Integral Earth Website

We are a group of researchers at Harvard University who have spent years developing reliable, peer-reviewed algorithms for quantifying and monitoring methane emissions. We have developed a new, open-source tool that allows anyone to quantify methane emissions anywhere in the world: the [Integrated Methane Inversion](https://imi.seas.harvard.edu). Our tool is based on the latest scientific research and is used globally by scientists around the world.

![DashboardFull](/assets/images/Development_Page/Dashboard – Full.png){: .align-center, style="width: 100%; border-radius: 15px;" }

## IMI 2.0

Led by Lucas Estrada, the IMI 2.0 represents a **significant advancement in the field of atmospheric methane monitoring and modeling**. Building upon the foundation of its predecessor, IMI 2.0 introduces a **range of new capabilities** designed to **enhance accuracy, performance, and usability** for both scientific and stakeholder applications. One of the most notable developments is the integration of a **new blended TROPOMI+GOSAT dataset**, which combines the **high spatial resolution of TROPOMI** with the **high accuracy of GOSAT** to mitigate data artifacts and provide more **reliable emission estimates**.

IMI 2.0 also incorporates point source observations, enabling the system to **better capture and quantify emissions from individual methane sources**. This is **particularly important for regions with significant industrial activity**, where large point sources can contribute disproportionately to overall emissions. The updated system offers a **tenfold speedup** in Jacobian matrix construction, a critical component of the inversion process, through optimized computational techniques. This enhancement **significantly reduces the computational burden** and allows for **faster, more efficient processing** of large datasets.

Another key feature of IMI 2.0 is the **improved error characterization through the use of super-observations**, which average multiple satellite observations to provide a **more accurate representation of observational errors**. This, combined with adaptive spatial resolution linked to observational information content, ensures that the model can **dynamically adjust its resolution** to match the data density and quality, **providing high-resolution results where needed most**. Additionally, IMI 2.0 supports global inversion capabilities and includes a Kalman filter option for **continuous, low-latency monitoring** of methane emissions on a weekly or monthly basis.

---

Looking ahead, the IMI team is already planning further enhancements to the system. These include **increasing spatial resolution to 12x12 km²**, **reducing latency to just 2-3 days**, and **integrating methane observations from upcoming satellite instruments such as MethaneSAT, GOSAT-GW, and Sentinel-5**. The incorporation of dense point source imagery from sensors like GHGSat and Carbon Mapper will further refine the accuracy and granularity of emission estimates.

Additionally, there are plans to extend the capabilities of IMI to **include CO2 emissions**, making it a more comprehensive tool for greenhouse gas monitoring. This extension will leverage the same advanced inversion techniques and high-resolution satellite data that have made IMI a leading tool for methane emission monitoring. With these ongoing and future developments, **IMI 2.0 is poised to become an even more powerful resource for researchers, policymakers, and stakeholders** working to understand and mitigate the impacts of greenhouse gas emissions on the global climate.

---

## Looking for more?

- [IMI Paper](https://gmd.copernicus.org/articles/15/5787/2022/gmd-15-5787-2022-discussion.html)
- [IMI Documentation](https://imi.readthedocs.io/en/latest/)
- [IMI GitHub Repository](https://github.com/geoschem/integrated_methane_inversion)
