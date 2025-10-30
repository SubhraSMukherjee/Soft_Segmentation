## Segmentation and Visualization


This project takes MacroEconomic Data (
[[Data Source]](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data)
) from 167 Countries and tries to group them together based on how similar or dissimilar they are based on the Macro Indicators using [Kohonen Maps (Self Organizing Maps)](https://www.geeksforgeeks.org/python/self-organising-maps-kohonen-maps/)


Kohonen Maps are an Neural Network based unsupervised algorithm that preserves the topological structure of the data. Loosely speaking, it means that we can **'see'** the difference between the types of data elements with the most similar ones clubbed together and the different ones further apart

___

### >Translating the Final Map

1. Nearby nodes on the map tend to represent similar data (low dissimilarity).
2. Far-apart nodes usually represent dissimilar data — but not always strictly linearly
3. Light-colored hex cell areas → Countries in this region is homogeneous / one cluster
4. Dark-colored hex cell areas → Neighboring countries are dissimilar they lie between between cluster boundaries


![Page_1](https://github.com/SubhraSMukherjee/Soft_Segmentation/blob/main/screenshots/image.png)
