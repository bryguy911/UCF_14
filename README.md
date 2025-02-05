# UCF_14

Belly Button Biodiversity Dashboard
Background
This project involves building an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs) were present in more than 70% of people, while the rest were relatively rare.

Project Overview
The goal of this project is to create an interactive and visually appealing dashboard to:

Visualize the top 10 OTUs for each individual using a horizontal bar chart.

Display all OTUs for each sample in a bubble chart.

Present the demographic information of each individual using the metadata.

Key Features
Horizontal Bar Chart:

Displays the top 10 OTUs found in an individual.

Uses sample_values as the values.

Uses otu_ids as the labels.

Uses otu_labels as the hovertext.

Bubble Chart:

Visualizes each sample.

Uses otu_ids for the x values.

Uses sample_values for the y values and marker size.

Uses otu_ids for the marker colors.

Uses otu_labels for the text values.

Metadata Display:

Shows demographic information of the individual.

Loops through each key-value pair in the metadata JSON object and creates a text string.

Appends the text to the #sample-metadata panel.

Setup Instructions
Create a New Repository:

Create a new repository named belly-button-challenge.

Clone the repository to your local machine.

Copy Starter Code:

Copy the files from the provided starter code folder into your repository (e.g., index.html, samples.json, and the static folder).

Push Changes to GitHub:

Commit and push your changes to GitHub.

Deploy to GitHub Pages:

Deploy the repository to GitHub Pages to make your dashboard accessible online.

Usage
The interactive dashboard allows users to explore the diversity of microbial species found in human navels.

Users can select different samples to update the visualizations and metadata display dynamically.

Additional Information
The samples.json file is used for reference and is not required to be accessed locally.

Ensure regular commits to your GitHub repository and maintain a detailed README file.

Deployment
Deploy the app to a free static page hosting service such as GitHub Pages.

Provide links to your GitHub repository and the deployed dashboard.

For any further questions or assistance, please feel free to reach out.