# clustering-the-stock-market
Goal: Use 5 years of quarterly stock data across the Dow Jones to establish visual filters and informative clusters.
- Doing so can highlight companies that are in growth phases, decline phases, or just kinda stagnant. 
- Using financial ratios combined with clustering, we can assess patterns between stocks in a convenient way.

Note that the model does not implement time series techniques as I wanted to achieve a generic overview of company characteristics. Here are some plots of the clusters. 

![A visualization of UMAP clustered by DBScan](https://user-images.githubusercontent.com/3197895/112230303-efb61980-8bf1-11eb-90c7-c54af8d6bb68.png)

This is a still of an animation that will follow stocks of interest over time through the UMAP shape. 

![Animation still - UMAP](https://user-images.githubusercontent.com/3197895/112230586-51768380-8bf2-11eb-82e4-19c6d0e4cff3.png)

Finally, here is a snippet of how the clusters are classified by feature in relation to one another.  They are not alway strict boundaries, but there are some discernable themes. 

![What is the cluster made of?](https://user-images.githubusercontent.com/3197895/112230815-c1850980-8bf2-11eb-9653-0a53399f5cde.png)

Feel free to fork and play with the parameters, it is fun to watch the stocks move through the market over time in a more artistic way.  
