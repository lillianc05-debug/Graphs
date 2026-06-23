# Graphs-
In this assignment, you will write a Python program that using an API to collect live data. With the live data, you will provide a brief summary of each data type, as well as basic statistical inference, and then generate three graphs.

Steps
1. Identify an API that is live and does not require authentication. Provide a comment with the API endpoint documentation. The endpoint must provide at least four fields of data for this assignment to work, two of which must be quantitative in nature.
2. Use your identified API from step one to send a request to the endpoint. Verify the server status is okay. Store the endpoint response in a variable.
3. Convert the API endpoint response (which will most likely be CSV or JSON) to a Pandas dataframe.
4. Invoke the describe method on the dataframe. Convert any mismatched datatypes to their proper datatypes.
5. Invoke the describe method again with the corrected datatypes. Use a comment to explain what each column represents. Use another comment to explain the statics for your quantitative variables. 
6. Create a univariate plot for any of your columns. You may use matplotlib, seaborn, plotnine, or any other visualization library. Make sure Python outputs the graph as lastname_univariate.png 
6a. With a comment, explain what the graph represents. 
7. Create a bivariate plot for your two quantitative columns. Output the graph as lastname_bivariant.png 
7a. With a comment, explain what the graph represents. Additionally, provide any obvious details of a linear relationship.
8. Create a multivariate plot using at least two quantitative and at least one qualitative variable. An easy way to achieve this is to reuse your graph from step 7, but colorize each datapoint with a qualitative variable. Output the graph as lastname_multivariate.png.
8a. With a comment, explain what the graph represents. Additionally, explain any obvious groupings you see with the qualitative variable colorizing the graph.
9. Output a text file that uses your comments from your interpretation of the graphs and statistics that summarizes the data for someone unfamiliar with your dataset. Include the describe summary in this file. This file should be named lastname_stats.txt
