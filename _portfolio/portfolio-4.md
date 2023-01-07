---
title: "Urban2Vec"
excerpt: "Understanding intrinsic patterns and predicting spatiotemporal characteristics of cities require a comprehensive representation of urban neighborhoods. Existing works relied on either inter- or intra-region connectivities to generate neighborhood representations but failed to fully utilize the informative yet heterogeneous data within neighborhoods. In
this work, we propose Urban2Vec, an unsupervised multimodal framework which incorporates both street view imagery and point-of-interest (POI) data to learn neighborhood embeddings. Specifically, we use a convolutional neural network to extract visual features from street view images while preserving geospatial similarity. Furthermore, we model each POI as a bag-of-words containing its category, rating, and review information. Analog to document embedding in natural language processing, we establish the semantic similarity between neighborhood (“document”) and the words from its surrounding POIs in the vector space. By jointly encoding visual, textual, and geospatial information into the neighborhood representation, Urban2Vec can achieve performances better than baseline models and comparable to fully-supervised methods in downstream prediction tasks. Extensive experiments on three U.S. metropolitan areas also demonstrate the model interpretability, generalization capability, and its value in neighborhood similarity analysis.
<br/>
<br/><img src='/images/urban2vec.png'>"
collection: portfolio
---

Urban neighborhoods are complicated systems containing local environments, local businesses, and people living there. There are multiple modalities of data in a neighborhood like street view images which reflect local environments, and the textual data describing local points-of-interest (POI), like the ratings, categories, and customer reviews of restaurants and stores. 
The characterisitcs of urban neighborhoods are important information to support people-centric decision making. However, the common approach to collect such information (e.g., census) are very expensive and not timely. In this project, we proposed an unsupervised learning model, called Urban2Vec, to capture neighborhood characteristics from open multi-modal data including street view images and textual data of POIs. The model can project each neighborhood into a high-dimensional vector space. Such vectorized representations can be used in many applications. 
For example, they can be used as input features to predict neighborhood-level characteristics like demographic variables, real estate sale price, and solar adoption rates. It can also be used to search for neighborhoods similar to a query neighborhood, like a search engine, based on the similarity between vectors. For example, given a neighborhood in Chicago, we can retrieve the most and the least similar neighborhoods to it in New York.

**Publication**:

* **Zhecheng Wang**\*, Haoyuan Li\*, and Ram Rajagopal (2020). 
Urban2Vec: Incorporating Street View Imagery and POIs for Multi-Modal Urban Neighborhood Embedding''. 
**AAAI Conference on Artificial Intelligence**. (\* equal contribution)
[(link)](https://doi.org/10.1609/aaai.v34i01.5450)

* Tianyuan Huang\*, **Zhecheng Wang**\*, Hao Sheng\*, Andrew Ng, and Ram Rajagopal (2021). 
M3G: Learning Urban Neighborhood Representation from Multi-Modal Multi-Graph. 
**ACM SIGKDD Workshop on Deep Learning for Spatiotemporal Data**. (\* equal contribution). 
[(link)](http://cs.emory.edu/~lzhao41/venues/DeepSpatial2021/papers/M3G__Deepspatial_2021.pdf)
