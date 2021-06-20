# Plotly-
# Belly-button-biodiversity-Dashboard
In this project, we will build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

# Step 1: Plotly


1- Use the D3 library to read in samples.json.


2- Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.




Use sample_values as the values for the bar chart.


Use otu_ids as the labels for the bar chart.


Use otu_labels as the hovertext for the chart.

![image](https://user-images.githubusercontent.com/75787486/122659711-8be7b200-d148-11eb-9503-c1ab27e2e7a0.png)

3 -Create a bubble chart that displays each sample.



Use otu_ids for the x values.


Use sample_values for the y values.


Use sample_values for the marker size.


Use otu_ids for the marker colors.


Use otu_labels for the text values.

![image](https://user-images.githubusercontent.com/75787486/122659723-ac177100-d148-11eb-8359-7f61dde47b60.png)

4- Display the sample metadata, i.e., an individual's demographic information.


5- Display each key-value pair from the metadata JSON object somewhere on the page.

![image](https://user-images.githubusercontent.com/75787486/122659736-c6514f00-d148-11eb-9a4b-425adb7cea7d.png)


6- Update all of the plots any time that a new sample is selected and create any desired layout for the dashboard.An example of dashboard below
![image](https://user-images.githubusercontent.com/75787486/122659766-129c8f00-d149-11eb-9955-72f53684a684.png)


