# Pandas

**Summary:**      
Pandas is a python library which specializes in data analysis and manipulation with Series (vector) and DataFrame (table) as the primary data structures, it is comparable to R with its range of statistical functions and graphs.

**Data formats in**  .csv, .txt, .json, .ods, .html, .sql       
**Data formats out** .csv, .txt, .json, .ods

**Three tips:**   
1.  Several file types ie. .csv or .json can be read into a dataframe, from here data analysis can be performed
2.  Dataframes can be analysed using functions such as groupby, sort_values and apply (applies a given function to a Series or column)
3.  Dataframes can be brought together using functions such as concat, join, append. Each function is similar but have specific features which differ from each other.

**Examples of use:**          
[Data Warehouse Notebook](https://colab.research.google.com/drive/1o9tIgjRVDPyJdwe0dHBWaRBn3CzFBaJk#)  
Here I used a handful of pandas operations to generate a dataset to use for the basis of a data warehouse.

**Contribution to data analytics pipeline:**         
Pandas is used in the *Gathering* (use of DataFrames can be used to collect several data sources), *Processing* (Pandas operations can be used to clean up datasets), *Analysing* (Pandas has an array of impressive analysis tools, even something as simple as describe(), *Presenting* (Pandas has several basic plotting methods), *Preserving* (DataFrames might be a possibility for storing data however there are more effective strategies).

**Comment on your skill level:** 6 / 10.              
I am very comfortable with pandas operations as they are based in python, it is a very accessible library with fantastic documentation, however an area I would like to improve on is the use of more advanced vectorization when working with data.
