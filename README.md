# [Unsupervised Learning : Discovering Global Patterns in Cancer Mortality Across Countries Via Clustering Analysis](https://johnpaulinepineda.github.io/Portfolio_Project_43/)

[![](https://img.shields.io/badge/Python-black?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-black?logo=Jupyter)](#)

Age-standardized cancer mortality rates refer to the number of deaths attributed to cancer within a specific population over a given period, usually expressed as the number of deaths per 100,000 people adjusted for differences in age distribution. Monitoring cancer mortality rates allows public health authorities to track the burden of cancer, understand the prevalence of different cancer types and identify variations in different populations. Studying these metrics is essential for making accurate cross-country comparisons, identifying high-risk communities, informing public health policies, and supporting international efforts to address the global burden of cancer. This [case study](https://johnpaulinepineda.github.io/Portfolio_Project_43/) aims to develop a clustering model with an optimal number of clusters that could recognize patterns and relationships among cancer mortality rates across countries, allowing for a deeper understanding of the inherent and underlying data structure when evaluated against supplementary information on lifestyle factors and geolocation. Data quality assessment was conducted on the initial dataset to identify and remove cases noted with irregularities, in addition to the subsequent preprocessing operations most suitable for the downstream analysis. Multiple clustering modelling algorithms with various cluster counts were formulated using K-Means, Bisecting K-Means, Gaussian Mixture Model, Agglomerative and Ward Hierarchical methods. The best model with optimized hyperparameters from each algorithm was determined through internal resampling validation applying 5-Fold Cross Validation with the Silhouette Score used as the primary performance metric. Due to the unsupervised learning nature of the analysis, all candidate models were compared based on internal validation and apparent performance. Post-hoc exploration of the model results involved clustering visualization methods using Pair Plots, Heat Maps and Geographic Maps - providing an intuitive method to investigate and understand the characteristics of the discovered cancer clusters. These findings aided in the formulation of insights on the relationship and association of the various descriptors for the clusters identified.

<img src="docs/CaseStudy4_Summary_0.png?raw=true"/>

<img src="docs/CaseStudy4_Summary_1.png?raw=true"/>

<img src="docs/CaseStudy4_Summary_2.png?raw=true"/>

<img src="docs/CaseStudy4_Summary_3.png?raw=true"/>

<img src="docs/CaseStudy4_Summary_4.png?raw=true"/>

<img src="docs/CaseStudy4_Summary_5.png?raw=true"/>

<img src="docs/CaseStudy4_Summary_6.png?raw=true"/>
