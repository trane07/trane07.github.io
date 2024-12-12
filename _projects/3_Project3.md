---
name: Project 3
tools: [Python, HTML, vega-lite, Altair]
image: assets/pngs/proj3.png
description: This group project seeks to help understand energy usage in Chicago, based on building type. 
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Understanding Chicago Energy Usage, by Buildings
##### ***Group: Liz Tran, Samantha Sy, Kevin Cervantes, Shawn Huang***

<vegachart schema-url="{{ site.baseurl }}/assets/json/proj3inter.json" style="width: 100%"></vegachart>

<!-- the data & methods -->
<div class="right">
{% include elements/button.html link="https://github.com/trane07/trane07.github.io/blob/main/python_notebooks/project3interact.ipynb" text="The Analysis" %}
</div>

<br>

## **Contextual Visualizations**

#### Top Communities by Total KWH Usage
![Top Communities by Total KWH Usage](/assets/pngs/proj3kwh.png)

<!-- the data & methods -->
<div class="right">
{% include elements/button.html link="https://github.com/trane07/trane07.github.io/blob/main/python_notebooks/context2.ipynb" text="The Analysis" %}
</div>

<br>

#### Geographical Distribution of Buildings in Chicago by Sector 
![Geographical Distribution of Buildings in Chicago by Sector](/assets/pngs/proj3map.png)


<!-- the data & methods -->
<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>

## The Main Dataset 

<!-- these are written in a combo of html and liquid --> 

<div class="center">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="Main Data" %}
</div>


