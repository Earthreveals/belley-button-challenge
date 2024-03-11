# belley-button-challenge
## Overview
In this assignment, we built an inteactive dashboard to explore the Belly Button Biodiversity Dataset, which catalogs the microbes that colonize human navels.

## Table of Contents
Readme
belly-button-challenge repository
index.html
samples.json
static folder

## Required Libraries
The project requires the following libraries:
- D3
- samples.json


## Installation
Steps include using D3 library to read in samples.json from the URL and any dependencies.
- **D3.js**: Handles data loading and manipulation for creating the interactive elements.
- **Plotly.js**: Used for rendering the bar and bubble charts based on the fetched data.

## Usage
Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in individual.
Create a bubble chart that displays each sample.
Display sample metadata
Display each key-value pair from the metadata JSON object somewhere on the page. 


## Data
Transferring data from a zip file that includes index.html, samples.json, app.js and screenshots of the bubble chart and dashboard. 

## Analysis
**Top OTUs Bar Chart**: By isolating the top 10 OTUs present in each individual's navel sample, we offer a focused view of the most prevalent bacteria, providing a starting point for further biological or medical studies.
- **Bacteria Cultures Bubble Chart**: The bubble chart extends the analysis by correlating the OTU IDs with their respective sample values, giving a clear visual representation of bacterial diversity and concentration in    each sample.
- The dashboard encourages users to interact with the dataset, selecting different test subjects to observe variations across individuals. These interactions could lead to the following observations:
- Variability in bacterial species from one individual to another, possibly influenced by factors captured in the demographic information.
- Correlation between the demographic factors and the prevalence of certain bacteria, which could suggest a pattern or association worth further investigation.
  

## Results
- **Dropdown Menu**: Users can select a test subject ID from a dropdown menu to retrieve specific data.
- **Demographic Information Panel**: Displays selected test subject's demographic information.
- **Bar Chart**: Visualizes the top 10 OTUs found in the selected individual.
- **Bubble Chart**: Each sample's bacteria cultures are displayed with bubble sizes that represent the magnitude of each OTU.


## Contributing
Individual contributer- Nick Nath
Group Collaboration- Nick Nath, Sharon Romero, Anthony Abushacra, Amanpreet Kaur 


## License
Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. 
Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/
