# project_1_recalls

## Team Members for Team 3
- Natalia Galvan
- Manuel Galvan
- Ziheng Song
- Joe Almendarez

## Synopsis

### Description
Recalls are an appropriate alternative method for removing or correcting marketed consumer products, their labeling, and/or promotional literature that violate the laws administered by the Food and Drug Administration (FDA). Recalls afford equal consumer protection but generally are more efficient and timely than formal administrative or civil actions, especially when the product has been widely distributed.

Analysis will be on:

    Which firms have the most recalls? - Natalia

    Time it takes to close a recall - Manuel

    Which States are impacted by recalls - Joe

    Classification Analysis - Ziheng

## Context of `FDARecall.ipynb`
The `FDARecall.ipynb` notebook is designed to fetch and analyze FDA food enforcement recall data. Below is a brief overview of the initial steps taken in the notebook:

### Import Libraries
The notebook begins by importing necessary libraries such as `requests`, `pandas`, `matplotlib.pyplot`, `plotly.graph_objects`, `plotly.subplots`, and `seaborn`.

### Define API and Parameters
The API for FDA food enforcement data is defined with a search parameter for report dates ranging from January 1, 2020, to August 4, 2024, and a limit of 500 records.

### Send GET Request
A GET request is sent to the FDA API endpoint to fetch the recall data.

### Check Request Success
The response status code is checked to ensure the request was successful.

### Parse JSON Data
If the request is successful, the JSON data is parsed to extract the list of recall results.

### Create DataFrame
A DataFrame is created from the list of recall records.

### Save DataFrame to CSV
The DataFrame is saved to a CSV file named `fda_food_enforcement_data.csv` in the `output_data` directory.

This initial setup allows the team to work with a structured dataset of FDA food enforcement recalls, enabling further analysis on various aspects such as the firms with the most recalls, the time taken to close recalls, the states impacted by recalls, and the volume of recalls per product or state.

![Alt text](https://mcintyrelaw.com/wp-content/uploads/2020/01/drug-recall-classes.png)

## References
    
## How to change format of data to '%Y%m%d' in Pandas?
        https://stackoverflow.com/questions/51310072/how-to-change-format-of-data-to-ymd-in-pandas
## 4 Ways to Add Images to GitHub README + 1 Bonus Method
        https://cloudinary.com/guides/web-performance/4-ways-to-add-images-to-github-readme-1-bonus-method
## Rotating Axis Labels in Matplotlib
        https://www.pythoncharts.com/matplotlib/rotating-axis-labels/
## Code Writing Help with ChatGPT
        https://chatgpt.com/

    
