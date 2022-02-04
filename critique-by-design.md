# Critique by Design
2/3/2022

## Step one: Find a data visualization

### _Visualizing NYC Bike Trips_
The Citi Bike System data has information about bike rides in NYC. It allows to answer questions like: where do bikers ride? When do they ride? And how far do they go?. The dataset contains start and end station names, along with timestamps and geolocation (latitude and longitude). The data is provided for analysis, development, and visualization.

In a [Medium post](https://medium.com/towards-data-science/visualizing-nyc-bike-share-trips-with-a-chord-diagram-eb4c8e14366), the author used September 2020's records to show how a chord diagram could be used to represent the Citi Bike data. A chord diagram provides a way to visualize flows between entities. 

The final visualization looks like this:

![ChordDiagram](https://miro.medium.com/proxy/1*HYJXUPqcLVafFgURyJETkw.png)

**Note**: this wasn't intended to be a visualization for the general audience but was designed as part of a Python tutorial. That's why you don't see any labeling.

Sure, chord diagrams are very eye-catching, but more often than not, audiences will find themselves confused about the main takeaway of the visualization. Additionally, depending on the number of categories displayed and whether you'd expect them to have a natural order, it's hard for the naked eye to identify at a glance meaningful differences between flows. Consider for a moment the visualization above and ask: *what can I conclude from this visualization?* You'll find yourself turning your head a couple of times to read the labels and following those long lines that connect with each other. In the end, you're just too distracted by all the colors and unusual shapes that it'll be too hard to have an aha moment (not to mention that it can be exhausting decoding all these data without additional visual aids).

> In case you were wondering, the intent of the visualization was to analyze the Citi Bike usage among the most popular boroughs. It's worth noting too that these visualizations are more useful when you incorporate interactive capabilities to further explore the data.
