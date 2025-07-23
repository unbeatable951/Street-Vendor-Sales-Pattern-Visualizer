# Street Vendor Sales Pattern Visualizer

## Overview
The **Street Vendor Sales Pattern Visualizer** is a data visualization project that analyzes sales data from street vendors to uncover temporal and spatial patterns in sales activity. Using interactive and intuitive visualizations, this project highlights sales trends across different hours and locations, helping stakeholders better understand foot traffic and popular items sold by vendors.

This project is implemented in a Google Colab notebook and makes use of Python libraries such as pandas, matplotlib, seaborn, and folium for data cleaning, analysis, and visualization.

## Features
- Cleans and preprocesses street vendor sales data
- Removes duplicate timestamps per location and normalizes item names
- Cleans currency symbols from price data for accurate analysis
- Visualizes footfall trends by hour with line graphs
- Displays stacked bar charts of items sold by location
- Shows footfall intensity on a map via interactive folium visualizations

## Data Sources
The dataset used for this project contains street vendor sales records, including:
- Timestamps of sales
- Vendor locations (with latitude and longitude)
- Items sold
- Sale prices (including currency symbols)

**Note:** Data preprocessing steps such as duplicate removal, normalization of item names, and currency cleaning are documented in the notebook.

## Installation
To reproduce this project locally, ensure you have Python 3 installed along with the following packages:

