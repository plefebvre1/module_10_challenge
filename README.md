# Module 10 Challenge

This respository contains files relating to an analysis of various cryptocurrencies. The pricing data for the cryptocurrencies is cleaned and then fit to a KMeans model both in raw format and after undergoing a Principal Component Analysis to cluster the cryptocurrencies into distinct groups. Using the elbow method, both approaches were clustered into 4 groups. Both gave similar results but the PCA plot showed a cleared view of the four different groups. 

![ClusterComparison](/Images/Cluster_Plot_Comparison.png)

The four groups in both approaches ended up being two primary groups and two single cryptocurrencies that were outliers.

## Technologies

This project leverages Python 3.7 in Jupyter Lab with the following packages:

* [pandas](https://pandas.pydata.org/) - For financial data analysis tools
* [hvplot](https://hvplot.holoviz.org/) - For interactive data visualizations
* [scikit-learn](https://scikit-learn.org/stable/user_guide.html) - To create models for fitting data and making predictions with tools like KMeans, Standard Scaling and PCA

## Contributors

Starter code for this app was provided by the GWU Fintech Bootcamp program. Updates to that code to fulfill the analysis were done by [Peter Lefebvre](peter.c.lefebvre@gmail.com).

## License

[MIT License](https://github.com/plefebvre1/module_10_challenge/blob/main/LICENSE)
