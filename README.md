# Market-Segmentation-for-Airlines

One of the business keys is to be able to classify customers, based on their value. So that different marketing strategies can be 
carried out, can focus on high-value customers, and increase the profit of a company.
The purpose of this case is to identify customer value. By using the LRFMC model technique. As for this case:

     L: The number of months from the membership time to the end of the observation window
     R: The number of months from the end of the observation window when the customer last took a company plane Last consumption interval
     F: The number of times customers take company aircraft in the observation window
     M: The flight mileage accumulated by the customer in the observation window
     C: The average value of the discount coefficient corresponding to the customer's position in the observation window
     
Using the LRFMC concept as shown above in performing feature selection:

     L: Loyalty -> column MEMBER_DURATION
     R: Recency -> column LAST_TO_END
     F: Frequency -> column FLIGHT_COUNT 
     M: Monetary -> column SEG_KM_SUM
     C: Cabin -> column avg_discount
These columns will be used in the clustering process.

The workflow of clustering with PCA will be 

 ![alt text](http://www.nlpca.org/fig_pca_principal_component_analysis.png)
 
