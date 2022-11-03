---
title: "DeepSolar++"
excerpt: "What is critically needed but lacking today to understand the technology diffusion of solar PVs over time is a highly granular spatiotemporal dataset for solar installations, as well as the method to efficiently construct and maintenance it. In this project, we bridge this gap by developing computer vision models to deal with low-resolution historical satellite and aerial images to identify when each solar PV system was installed. With this model, we constructed a nationwide spatiotemporal dataset for solar PVs. We further demonstrated the value of this dataset by analyzing it for the technology adoption lifecycle perspective to answer the questions such as: What factors are associated with the onset of solar adoption? What factors are associated with the saturated adoption level? What types of financial incentives are associated with higher saturated adoption levels, especially for low-income communities?
<br/><img src='/images/6037_timelapse_notated.gif'>"
collection: portfolio
---

Solar photovoltaic (PV) systems are being deployed at a rapid yet non-uniform pace. To explain this heterogeneity across space and time, in the DeepSolar++ project, we applied computer vision to historical satellite and aerial images to uncover **when** solar PVs have been installed on top of the DeepSolar project that investigated the problem of **where**. We, therefore, constructed a spatiotemporal dataset of PV deployment in the United States. We analyzed the data using a technology diffusion model and found that low-income communities are not only delayed in their PV adoption onset but also saturate more quickly at lower levels. We also found that certain types of incentives are associated with a high saturated adoption level in low-income communities, whereas other types are not. The computer vision model we developed can be scaled to any location on Earth where historical aerial or satellite images are available at a sufficient resolution. Additionally, we make our dataset publicly available as a resource for researchers, policymakers, and other stakeholders to understand PV adoption dynamics and customize policy design.

**Publication**:

* **Zhecheng Wang**, Marie-Louise Arlt, Chad Zanocco, Arun Majumdar, and Ram Rajagopal (2022). 
DeepSolar++: Understanding Residential Solar Adoption Trajectories with Computer Vision and Technology Diffusion Models. 
**Joule**. 
[(link)](https://doi.org/10.1016/j.joule.2022.09.011)

[(code)](https://github.com/wangzhecheng/DeepSolar_timelapse)