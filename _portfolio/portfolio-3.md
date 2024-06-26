---
title: "DeepGrid"
excerpt: "Detailed and location-aware distribution grid information is a prerequisite for various power system applications such as renewable energy integration, wildfire risk assessment, and infrastructure planning. However, a generalizable and scalable approach to obtain such information is still lacking. In this project, we developed a machine-learning-based framework to map both overhead and underground distribution grids using widely-available multi-modal data geospatial data. It is developed with the data in the U.S. but can be directly transferred to Africa without any re-training or fine-tuning. By applying this model to California, we not only identified multiple levels of disparities in distribution grid vulnerability to wildfire, but also proposed a cost allocation scheme that can make distribution grid protection projects equitably affordable to communities at all income levels.
<br/>
<br/><img src='/images/deepgrid_old.png'>"
collection: portfolio
---

Electrical grids are not only essential in the integration of solar energy to support energy transition, but also vulnerable to climate-induced extreme events, such as wildfires, hurricanes, and floods. Compared to transmission grid of which the information is more readily available, the information of distribution grid is rather scarce, despite its importance in a wide variety of power system applications, such as electricity access expansion, renewable energy integration, and risk assessment, in both developing and developed countries.
 
In this project, we developed a machine-learning-based framework for the geospatial mapping of distribution grid by integrating widely-available multi-modal geospatial data. The proposed framework provides a non-intrusive, scalable, and generalizable approach for obtaining granular distribution grid information. Compared to previous works relying on power grid measurements or solely on imagery data, the framework proposed in this project is able to predict the entire distribution grid map—including both overhead and underground parts—completely from scratch relying on the integration of multi-modal open data. The framework, trained with the data in the U.S., can be transferred to Africa where both electricity access and electricity infrastructure data are quite limited, and maintain the same level of precision without re-training or fine-tuning, which demonstrates the generalizability of the framework. 

By applying this model to California, we not only identified multiple levels of disparities in distribution grid vulnerability to wildfire, but also proposed a cost allocation scheme that can make distribution grid protection projects equitably affordable to communities at all income levels.

**Publication**:

* **Zhecheng Wang**, Arun Majumdar, and Ram Rajagopal (2023). 
Geospatial Mapping of Distribution Grid with Machine Learning and Publicly-Accessible Multi-Modal Data. **Nature Communications**. 
[(link)](https://www.nature.com/articles/s41467-023-39647-3)

* **Zhecheng Wang**, Michael Wara, Arun Majumdar, and Ram Rajagopal (2023). 
Local and Utility-Wide Cost Allocations for a More Equitable Wildfire-Resilient Distribution Grid. 
**Nature Energy**.
[(link)](https://doi.org/10.1038/s41560-023-01306-8) 
[(Stanford News)](https://news.stanford.edu/2023/08/07/resilient-power-grids/) 
[(The Hill)](https://thehill.com/policy/equilibrium-sustainability/4141541-california-undergrounding-approach-leaves-lower-income-populations-disadvantaged/)
    
* Qinghu Tang\*, **Zhecheng Wang**\*, Arun Majumdar, and Ram Rajagopal (2019). 
Fine-Grained Distribution Grid Mapping Using Street View Imagery.
**NeurIPS Tackling Climate Change with Machine Learning Workshop**. (\* Equal contribution)
[(link)](https://www.climatechange.ai/papers/neurips2019/31/paper.pdf)