---
name: Project 3
tools: [Python, HTML, vega-lite, Altair]
image: assets/pngs/chicago.png
description: This group project seeks to help understand energy usage in Chicago, based on building type. 
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Who is Using all the Energy in Chicago in 2010? 
*by Liz Tran, Samantha Sy, Kevin Cervantes, Shawn Huang*

In 2010, there was a total of 124,888,607 kWh (kilowatt) of electrical energy and 16,811,616 thermal energy used in Chicago. This was a **collective 141,700,223 total** in units of energy combined, with kilowatts being *more than triple the amount of thermal energy*! The data was collected between commercial and residential buildings within Chicago across different community areas. Below is an interactive visualization to help understand what buildings used collectively throughout the year in both thermal energy and electricity, as well as a look into our analysis for it. 

*Use the dropdown to compare the different building types. Hovering specific points give more information about that point.* 

<vegachart schema-url="{{ site.baseurl }}/assets/json/proj3interact.json" style="width: 100%"></vegachart>

<!-- the data & methods -->
<div class="right">
{% include elements/button.html link="https://github.com/trane07/trane07.github.io/blob/main/python_notebooks/project3interact_UPDATED.ipynb" text="Vis Analysis" %}
</div>

<br>

<!-- ## **Contextual Visualizations** -->

To fully understand energy usage, both community areas and building types were considered, as commercial buildings tended to have higher energy usage than a majority of the residential buildings. At the same time, there are more residential buildings than commercial ones. But where exactly were these buildings located? Thus, another question at large is... 

#### How are buildings distributed in Chicago? 
![Geographical Distribution of Buildings in Chicago by Sector](/assets/pngs/proj3map.png)


<!-- the data & methods -->
<div class="right">
{% include elements/button.html link="https://github.com/trane07/trane07.github.io/blob/main/python_notebooks/IS_445_3_1_Project.ipynb" text="Vis Analysis" %}
</div>
**Behind the Visualization:** 
*Using a color-coded dot map, this visualization displays the geographical distribution of buildings in Chicago by sector. Each dot represents a building, and the colors distinguish different sectors: blue for residential, red for commercial, green for municipal, and light blue for other types. The map is based on a geographic layout of Chicago, with the Lake Michigan shoreline visible on the right side. This distribution shows a high concentration of residential buildings (blue dots) across the city. In contrast, commercial (red dots) and municipal buildings (green dots) are more clustered in specific areas, likely reflecting commercial hubs and government facilities.* 
<br>

According to the visualization, residential areas tended to be sprawled across the city, in higher numbers than commercial buildings by far, which were usually together in clusters. Now that we have a greater understanding of the geographical distribution of buildings, we must now know which areas of Chicago contributed the most to the high energy usage. So... 

#### What are some communities involved? 

In 2010, the top communities with energy usage differed depending on thermal energy and kilowatt. 

##### **For kWh:**
![Top Communities by Total KWH Usage](/assets/pngs/proj3kwh.png)


##### **For Thermal Energy:**
![Top Communities by Total THERMAL Usage](/assets/pngs/proj3therms.png)


<!-- the data & methods -->
<div class="right">
{% include elements/button.html link="https://github.com/trane07/trane07.github.io/blob/main/python_notebooks/context2.ipynb" text="Vis Analysis" %}
</div>

The data presented shows that top communities differed in usage in 2010. For electrical energy (kWh), **Near North Side** by far had the highest counts of compared to other areas in Chicago, followed by **Lakeview** . On the other hand, **Lakeview** had the highest thermal energy usage, followed by **Uptown**. In both cases, ***Lakeview was among the top communities with energy usage***. One thing that remained consistent with both graphs is that a large portion of energy usage pertained to multi-story buildings, with 7 or more floors, followed by commercial buildings, except for Uptown with no commercial buildings. 

Overall, the findings show that in 2010, energy usage in Chicago mostly consisted of electrical energy, measured in kilowatts, by both commercial and residential buildings. Though residential buildings were higher in count, commercial buildings tended to be higher in energy usage overall. This was moreso true in regions such as Lakeview, where both commercial and multi-story buildings of over 7 floors had the highest total energy usage compared to other building types.  
<br>

## **References**
* [The Main Data: Chicago's Energy Usage 2010](https://data.cityofchicago.org/Environment-Sustainable-Development/Energy-Usage-2010/8yq3-m6wp/about_data)
* [The Contextual Data: Chicago Energy Benchmark](https://data.cityofchicago.org/Environment-Sustainable-Development/Chicago-Energy-Benchmarking-Covered-Buildings/g5i5-yz37/about_data)
<br>


