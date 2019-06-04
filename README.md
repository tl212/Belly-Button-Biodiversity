# Belly-Button-Biodiversity

On this project I'll be building an interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/).

Using Plotly.js the following charts was built into the dashboard. 
* PIE chart that uses data from the samples route (`/samples/<sample>`) to display the top 10 samples.

  * `sample_values` as the values for the PIE chart

  * `otu_ids` as the labels for the pie chart

  * `otu_labels` as the hovertext for the chart
  
* Bubble Chart that uses data from your samples route (`/samples/<sample>`) to display each sample.

  * `otu_ids` for the x values

  * `sample_values` for the y values

  * `sample_values` for the marker size

  * `otu_ids` for the marker colors

  * `otu_labels` for the text values
  
* Display the sample metadata from the route `/metadata/<sample>`.

  * Display each key/value pair from the metadata JSON object somewhere on the page

* Update all of the plots any time that a new sample is selected.

## Heroku 

The developed app was deployed to heroku. [Click here](https://edhw.herokuapp.com) to interect with it. 

##### Copyright

© 2019 realGenius, Inc.
