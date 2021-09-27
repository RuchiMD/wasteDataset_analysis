# wasteDataset_analysis
I am trying to compare and analyse the trends in waste generation and management practices throughout the world. In particular, I would like to focus on effect of penalty on waste collection, non-monetary impact, and a potential service/product market.

Following is brief summary of functions used:
1. rectify_data(input_df): Make string entries and categorical data of uniform case and punctuation , convert strings to numbers where necessary
2. fill_num_data(input_df, levels, num_cols): Impute missing values in a group by the mean of that group. Cities can be grouped by income levels and geography. 
3. create_dummy_df(df, cat_cols, dummy_na): Create numerical columns for categorical entries to run through machine learning algorithms
4. get_reportedData_distribution(input_df): Get distribution of cities reporting and not reporting a certain data to know the priorities in governance. 
5. get_stacked_distribution(input_df, levels,cluster_levels): Get bar plots of number of countries reporting certain data, mean population, and mean municipal solid waste collected where countries are grouped by income levels and region ids
6. plot_grouped_df(grouped_df, ax,  x, y, cmap = plt.cm.coolwarm): Get bar plots of reported data values by countries grouped by income levels and region ids

I have ocncluded that tracking waste at at least one of consumer level, institutional level, and government level helps in establishing accountability about waste production and management. So interested parties can find a viable market for waste tracking solutions. I have also written a blog boast about my observations. You can find it here:
https://medium.com/@ruchi.dhamnaskar/what-a-waste-re-analyzed-d65fdb49a6a3?sk=3b2ff0b149303a0b54c17087d325f7bb

If the code or information is helpfull in any way, dont forget to let me know your thoughts.
