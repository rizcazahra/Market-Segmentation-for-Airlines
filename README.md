# Market-Segmentation-for-Airlines

One of the business keys is to be able to classify customers, based on their value. So that different marketing strategies can be carried out, can focus on high-value customers, and increase the profit of a company. The purpose of this case is to identify customer value. By using the LRFMC model technique. 

The workflow of this project will be:

1. Data Preprocessing
2. Visual Exploratory Data Analysis
3. Encoding Categorical values
4. Reduce Dimensionality
5. Find the Clusters
6. Visualize and Interpret the Clusters

As for this case, columns that will be used in the clustering process are:

     L: "MEMBER_DURATION" The number of months from the membership time to the end of the observation window
     R: "LAST_TO_END" The number of months from the end of the observation window when the customer last took a company plane Last consumption interval
     F: "FLIGHT_COUNT" The number of times customers take company aircraft in the observation window
     M: "SEG_KM_SUM" The flight mileage accumulated by the customer in the observation window
     C: "avg_discount" The average value of the discount coefficient corresponding to the customer's position in the observation window


This clustering will use PCA for dimension reduction
 ![alt text](http://www.nlpca.org/fig_pca_principal_component_analysis.png)
By performing this operation, we acttually look at the data from different point of view, means that new attributes can be extracted.


After ![image](https://user-images.githubusercontent.com/84758353/179644144-a22a117a-4fc4-40b3-a571-d4a9f7361275.png)

