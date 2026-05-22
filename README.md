# # Spatial Clustering of Ecological Niches using K-Means

An unsupervised spatial machine learning pipeline engineered to segment wildlife habitat suitability and identify ecological niches using geographical (GPS) coordinates and macro-climatic features (Rainfall, Elevation). 

## 🔬 Ecological Context
Understanding species distribution and mapping critical habitats is essential for conservation planning and reserve design. Traditional niche modeling requires extensive presence/absence labels, which are often incomplete or heavily biased in wild surveys. This pipeline utilizes unsupervised machine learning to group observation sites based purely on shared bioclimatic and spatial characteristics, successfully drawing habitat maps without human-assigned training labels.

## 💡 The Computational Approach
* **Spatial Feature Matrix:** Integrates raw latitude and longitude datasets directly with micro-climate inputs, allowing the coordinates to retain their geometric meaning.
* **Unsupervised Segmentation:** Utilizes **K-Means Clustering** to find natural cluster boundaries within multi-dimensional environmental gradients.
* **Geographical Mapping:** Directly maps the mathematically derived clusters back onto true coordinate space (Latitude vs. Longitude), bypassing abstract feature reductions like PCA and keeping the final output immediately interpretable for field ecologists. Spatial-Ecology-Species-Distribution-Modeling
