---
title: "Mapping of parks and high stars restaurant in the city"
date: 2022-12-23
published: true
tags: [dataviz, folium]
excerpt: "Using folium to set a base for the project and visualize parks and restaurant density in Boston"
folium-loader:
  folium-chart-1: ["charts/folium park with restaurant density.html", "600"] # second argument is the height
  folium-chart-2: ["charts/folium high star restaurant disto park.html", "600"] # second argument is the height
toc: true
toc_sticky: true
---



## Mapping of parks and restaurant density

In this part, I visualize the parks and restaurants in the city through folium chart to show the density of restaurants.

<div id="folium-chart-1"></div>

## Mapping of high-star restaurant in or out of 75 m buffer from parks

In this section, I chose a buffer of 75m and screened out restaurants with a score of 4.5 or more. Then I classify them according to whether they are within 75 meters of the park, and plot them.

<div id="folium-chart-2"></div>
