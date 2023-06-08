# Python Visualization (Bokeh)

**Note:** I am going to focus on Bokeh as I am familiar with this library.

**Summary:**       
Bokeh is an interactive python visualization tool/library which can be used to create a wide range of plots, charts and graphs from a simple line, bar and scatter plot to more advanced choropleth maps, jitter plots etc.

**Data formats in:**  .csv, Pandas DataFrame, .json          
**Data formats out:**  .html, .png, .jpg, .svg

**Three tips:**  
1.  ColumnDataSource is a useful way to transform a DataFrame into an accessible way of structuring data as input into the Bokeh visualization, you can reference column names with simply a string 'column_name'
2.  Google maps can be imported as gmap and GMapOptions, you can use longitude and latitude coordinates to plot points on the familiar map
3.  There are a variety of tool tips, my favourite being the HoverTool(), it allows you to hover over a data point and display information about you can manipulate using HTML code

**Examples of use:**              
This [Jupyter Notebook](notebooks/python-bokeh.ipynb) is full of examples of different plots

**Contribution to data analytics pipeline:**                 
Bokeh can be used in *Analyzing* (exploratory plots) and *Presenting* (explanatory plots)

**Comment on your skill level:**  4 / 10                     
I have acquired the skills to design and code a few basic and advanced plots, however I really have only scratched the surface, of those I have created, there is much to improve on.
