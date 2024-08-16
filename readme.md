# Belly Button Challenge

## Overview
 For the Module 14 Challenge, we build Belly Button Biodiversity Dashboard, an interactive web application that allows users to explore the Belly Button Biodiversity dataset. This dataset catalogs the microbes that colonize human navels, and shows that a small handful of microbial species are present in more than 70% of people, while the rest are relatively rare. The dashboard provides visualizations of the top 10 Operational Taxonomic Units (OTUs) for each sample, along with demographic information for each test subject.

## Files
- 'belly-button-challenge'(https://github.com/jackthomas1430/belly-button-challenge.git) :The main repo for this challenge. 
- 'index.html': The main HTML file for the dashboard.
- 'sample.json': Conatains the Belly Button Biodiversity dataset.
- 'static': Directory containing 'app.js'
    -app.js: Contains the JavaScript code for the dashboard
- 'results': Contains images of the visualizations created for the project
- https://jackthomas1430.github.io/belly-button-challenge/: Github pages link to view dashboard

## Technologies Used

1. HTML:structures the dashboard
2. CSS: Dashboard styling
3. JavaScript: contains code for the dashboard
4. D3.js: Collects and Cleans data
5. Plotly.js: provides the interactive charts
       
## Instructions
1. Clone the repository to your local device using git clone (https://github.com/jackthomas1430/belly-button-challenge.git)
2. Open the Project: Copy path for 'index.html' and open in your web browser to view dashboard
3. Use the following link to access the dashboard: https://jackthomas1430.github.io/belly-button-challenge/

## Usage

1. Explore OTU Data:
    -Use the dropdown menu to select a sample ID.
    -Bar chart to shows the top 10 OTUs found in that individual.
    -Bubble chart shows the abundance of OTUs for the selected sample.

2. View Demographic Information:
    The demographic panel shows the metadata for the selected sample, including age, gender, ethnicity, and more.

##Results/Analysis: 
1. Interactive Bar Chart: Displays the top 10 OTUs for each selected sample.
![bar_chart]()
2. Bubble Chart: Visualizes the abundance of OTUs for each sample with hover functionality.
![bubble_chart]()
3. Demographic Information: Displays metadata such as age, gender, and ethnicity for the selected
 sample.
 ![demographic_info]()
4. Dropdown Menu: Allows users to select different samples and updates the visualizations accordingly.
![dropdown_menu]()

     
##Acknowledgements
    Xpert Learning Assistant was used to answer detailed questions, and assist in debugging.For more information about the Xpert Learning Assistant, visit [EdX Xpert Learning Assistant](https://www.edx.org/). 
    
##References
Plotly.js Function Reference - Plotly.newPlot
Plotly.js Reference - Layout.xaxis.autotickangles
JavaScript Array sort() Method - W3Schools
D3.js Documentation - DevDocs
D3.js Selection - d3-selection
D3.js Selection - d3.select - DevDocs
D3.js Selection Events - d3-selection
Standard Events - MDN Web Docs
D3.js Documentation - DevDocs
JavaScript this Keyword - W3Schools
JavaScript Init Function - How It Works - ITSourceCode
Plotly.js Documentation
JavaScript Array forEach() Method - W3Schools
Array.prototype.forEach() - MDN Web Docs
JavaScript Array Sort Implementation - Stack Overflow
Array.prototype.sort() - MDN Web Docs
Array.prototype.slice() - MDN Web Docs
Array.prototype.forEach() - MDN Web Docs


