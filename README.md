# belly-button-challenge

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

# Instructions
Complete the following steps:

1.) Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

2.) Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

* Use sample_values as the values for the bar chart.

* Use otu_ids as the labels for the bar chart.

* Use otu_labels as the hovertext for the chart.

![Screenshot 2023-05-16 at 7 38 00 PM](https://github.com/DunieCarrasco/belly-button-challenge/assets/117786548/537639df-1717-4f58-a65d-a519561b9f0a)

3.) Create a bubble chart that displays each sample.

* Use otu_ids for the x values.

* Use sample_values for the y values.

* Use sample_values for the marker size.

* Use otu_ids for the marker colors.

* Use otu_labels for the text values.

![Screenshot 2023-05-16 at 7 42 41 PM](https://github.com/DunieCarrasco/belly-button-challenge/assets/117786548/f703ff30-1fd9-4c4a-9b3a-797f4bfd35d5)

4.) Display the sample metadata, i.e., an individual's demographic information.

5.) Display each key-value pair from the metadata JSON object somewhere on the page.

![Screenshot 2023-05-16 at 7 44 36 PM](https://github.com/DunieCarrasco/belly-button-challenge/assets/117786548/5d9f9c34-f142-41ba-98bc-0aaa6bd02730)

6.) Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

![Screenshot 2023-05-16 at 7 45 01 PM](https://github.com/DunieCarrasco/belly-button-challenge/assets/117786548/43293c44-a2de-4c54-8f05-d96756930b69)

7.) Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file

# Advanced Challenge Assignment
The following task is advanced and therefore optional.

* Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.

* You will need to modify the example gauge code to account for values ranging from 0 through 9.

* Update the chart whenever a new sample is selected.

![Screenshot 2023-05-16 at 7 47 09 PM](https://github.com/DunieCarrasco/belly-button-challenge/assets/117786548/cb315866-54cd-4b53-8b75-b59555543dc5)

# References
Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.
