Assignment 1 - Fremont Bridge Bicycle Counts
===

Overview
---
1) First Part is 
 A small canvas demonstrating four required graphics primitives (rectangle, circle, line, polygon) with distinct colors. 

2) Second part I uses D3.js to visualize bicycle traffic on the Fremont Bridge.
  A data-driven chart showing the last 30 days of daily total riders, with bars, a trend line, points, and a peak-day highlight.

Tips:Please do not direct open index.html , run local server first(`python -m http.server`).


Technical 
-  data was summed up by day(raw date is hour) using d3.rollup, as it transformed the high-frequency data into a readable daily trend.
-  using d3.scaleBand() and d3.scaleLinear().nice() to sacle the X,y axis.


Design 
---
- .slice(-30) only takes the data of the last 30 days to prevent the chart from being too crowded.
- primitives on top, analytical chart below.
- Color palette separates primitives from data marks.
- Peak-day annotation.


Screenshots
---

- `ScreenShot.png`
---

`https://RIleyyu1.github.io/01-ghd3/index.html`




Data source from :https://data.seattle.gov/Transportation/Fremont-Bridge-Bicycle-Counter/65db-xm6k/about_data