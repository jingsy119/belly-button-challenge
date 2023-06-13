# belly-button-challenge
## Background
#### In this challenge, an interactive dashboard was created to explore the Belly Button Biodiversity dataset. The dataset catalogs the microbes that colonize human navels, featuring a small handful of microbial species called operational taxonomic units (OTU). 

## Technical Information
#### The D3 libaray in javascript was utilized to read the JSON file from a provided URL. 
### Horizontal Bar Chart
#### A horizontal bar chart was created with a dropdown menu to display the top 10 OTUs found in an individual. 
- sample_values was used as the values for the bar chart
- otu_ids was used as labels for the bar chart
- otu_labels was used as the hovertext for the chart
### Bubble Chart
#### A bubble chart was created to display each sample.
- otu_ids was used for the x values
- sample_values was used for the y values
- otu_ids was used for the marker colors
- otu_labels was used for the text values
### Demographic Information
#### An individual's demographic information was displayed using the sample metadata by displaying each key-value pair from the metadata JSON object on the page.
