---
name: Homework 6
tools: [Python, HTML, vega-lite, Altair]
image: assets/pngs/bflocation.png
description: This is my homework 6 visualizations.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# **Bigfoot Visualizations**
<br>

### Visual 1: *Bigfoot Sightings & Seasonal Precipitation*
<br>

**Explanation:**
For this, I'm comparing the precipitation probability of precipitation types in different seasons at Bigfoot sightings. In other words, the visualization shows the audience precipitation probabilities, rain or snow, sorted by seasons. 

**Transformation tools:** 
Specifically, I used the cleaned data to ensure there were no null values within the data chosen, as it would deeply affect how the data was presented. No other data transformation tools were used besides this. 

**Encoding:**
I used the ```x, y``` encoding type for this as it allowed for easy perspective of how precipitation type and probability were related. The *precip probabilities* are quantitative data types, while the *precipitation type* is a nominal data type. They are paired with the *seasons* category, which is also a nominal data type, for a more specified perspective. Nominal was chosen because it's unordered data. The addition of seasons allows the audience to see what precipitation is more likely during what season. 

**Colors:** The only color used are the different seasons, to distinguish between different points within the rain or snow categories. 

**Overlap from HW5:**
There should be no overlap from homework 5 for this visualization. 

**The visualization:** 

<vegachart schema-url="{{ site.baseurl }}/assets/json/bigfoot_precip.json" style="width: 100%"></vegachart>

<br>

### Visual 2: *Bigfoot Sighting Locations & Classifications*
<br>

**Explanation:** This visualization shows a map of all Bigfoot Sightings, where they're located, and the classification they fall under within the United States. 

**Transformation tools:** For this, I used the original Bigfoot data as there were no null values within the categories used. No data transformations were required because of the ccolumns chosen, which focused on longitude, latitude, and classification. 

**Encoding:** The encoding type used is ```longitude and latitude``` because of the location data. Thus, the columns paired with them are *longitude* and *latitude*, which are both quantitative data types. 

**Colors:** I also used the colors blue and red, with red being highlighted values from the dropdown menu. These two colors were used, particularly the red, to highlight and allow for interaction. No further data transformation was used for this. 

**Interactivity:** 
I previously stated that I incorporated a drop down menu that let the audience select what classification they wanted to view. In selecting it, the point would highlight red. This helps make my visualization be more interesting, as it allows for specification of values chosen and lets the viewer see if there's any concentrated areas for specific classifications within the United States. 

**Overlap from HW5:**
There should be no overlap from homework 5 for this visualization. 

**The visualization:** 

<vegachart schema-url="{{ site.baseurl }}/assets/json/bigfoot_location.json" style="width: 100%"></vegachart>


## Search The Data & Methods

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/bfro_reports_fall2022.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/trane07/trane07.github.io/blob/b4d48f357738bdbc16caf0694718dc117259b569/python_notebooks/Workbook.ipynb" text="The Analysis" %}
</div>

