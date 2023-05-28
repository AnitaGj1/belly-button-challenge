# Belly Button Biodiversity

## Description

In this assignment, we should build an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

> ### [Link to the web page](https://anitagj1.github.io/belly-button-challenge/).

## Instructions

### Step 1

> Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

### Step 2

> Create a drop down menu to select the Test Subject ID No.

![alt text](https://github.com/AnitaGj1/belly-button-challenge/blob/main/Images/Dropdown%20menu.png)

### Step 3

> Create a horizontal bar chart to display the top 10 OTUs found in that individual which will show the OTU Labels when hovering over the text.

* Use `sample_values` as the values for the bar chart.

* Use `otu_ids` as the labels for the bar chart.

* Use `otu_labels` as the hovertext for the chart.

![alt text](https://github.com/AnitaGj1/belly-button-challenge/blob/main/Images/barChart.png)

### Step 4

> Create a bubble chart that displays each sample.

* Use `otu_ids` for the x values.

* Use `sample_values` for the y values.

* Use `sample_values` for the marker size.

* Use `otu_ids` for the marker colors.

* Use `otu_labels` for the text values.

![alt text](https://github.com/AnitaGj1/belly-button-challenge/blob/main/Images/bubbleChart.png)

### Step 5

> Display the sample metadata, i.e., an individual's demographic information.

![alt text](https://github.com/AnitaGj1/belly-button-challenge/blob/main/Images/demographic.png)

### Step 6

> Update all the plots when a new sample is selected.

![alt-text](https://github.com/AnitaGj1/belly-button-challenge/blob/main/Images/updatePlots.png)

## Methodology

* JavaScript
* d3.js
* HTML

## Contents

* app.js
* index.html
* samples.json
* Images

## Notes and resources
* Dataset to be used : [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/).
* NOTE-I have worked with tutor who guided me to put together the code for the dropdown menu. 
