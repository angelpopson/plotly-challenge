# plotly-challenge

Belly Button Biodiversity
Built an interactive dashboard to explore the Belly Button Biodiversity DataSet. All of the plots are updated any time that a new sample is selected. Used Flask API to serve the data needed for plots.

Technology Used
Html,
JavaScript,
Css,
Python,
Sqlite

Step 1 - Plotly.js
Interactive charts for dashboard were created using Plotly.js.

PIE chart - used data from samples route (/samples/<sample>) to display the top 10 samples.

Used sample_values as the values for the PIE chart.

Used otu_ids as the labels for the pie chart.

Used otu_labels as the hovertext for the chart.

Bubble Chart - used data from samples route (/samples/<sample>) to display each sample.

Used otu_ids for the x values.

Used sample_values for the y values.

Used sample_values for the marker size.

Used otu_ids for the marker colors.

Used otu_labels for the text values.
