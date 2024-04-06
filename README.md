# Belly Button Biodiversity Dashboard

Welcome to the Belly Button Biodiversity Dashboard! This interactive dashboard allows users to explore the microbial diversity of human navels based on the Belly Button Biodiversity dataset.

## Introduction

The Belly Button Biodiversity dataset catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs) are present in more than 70% of people, while the rest are relatively rare.

This dashboard provides visualizations and insights into the microbial diversity of individual subjects' navels. Users can select a test subject ID from the dropdown menu to view demographic information, a horizontal bar chart displaying the top 10 OTUs found in that individual, and a bubble chart displaying each sample.

## How to Use

1. **Select Test Subject ID:** Use the dropdown menu to select a test subject ID to explore.

2. **View Demographic Information:** Demographic information about the selected test subject will be displayed in the "Demographic Info" section.

3. **Explore Microbial Diversity:**
   - **Horizontal Bar Chart:** Displays the top 10 OTUs found in the selected individual.
   - **Bubble Chart:** Displays each sample, with OTU IDs on the x-axis, sample values on the y-axis, marker size representing sample values, marker colors representing OTU IDs, and text values representing OTU labels.

4. **Update Charts:** All charts will be updated dynamically based on the selected test subject ID.

## Deployment

The Belly Button Biodiversity Dashboard is deployed using GitHub Pages. You can access it [here](https://kasheshjaiin.github.io/belly-button-challenge/).

## Technologies Used

- D3.js: Used for data visualization and DOM manipulation.
- Plotly: Used for creating interactive charts.
- HTML/CSS: Used for structuring the dashboard layout and styling.

## Getting Started

To run this dashboard locally or contribute to the project, follow these steps:

1. Clone this repository to your local machine.

2. Open the `index.html` file in your web browser to view the dashboard.
