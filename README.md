# Pokemon Data Analysis

## Overview

This Python script performs web scraping on the Pokemon Database website (https://pokemondb.net/pokedex/all) to extract information about various Pokemon. The data is then analyzed and visualized to gain insights into the distribution of Pokemon.

## Content

- [Web Scraping](#web-scraping)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Conclusion](#conclusion)

## Web Scraping

The script utilizes the `requests` library to fetch the HTML content of the Pokemon Database and `BeautifulSoup` for HTML parsing. It extracts Pokemon data from the HTML table and creates a Pandas DataFrame for further analysis.

## Data Analysis and Visualization

### Bar Chart: Average Total Stats by Pokemon Type

The average total stats for each Pokemon type are calculated and visualized using a bar chart. The color code for Pokemon types is defined for better visualization.

### Pie Chart: Distribution of Pokemon Types

A pie chart is created to show the distribution of Pokemon types based on the count. The color code is applied to represent each Pokemon type.

## Conclusion

The analysis reveals interesting insights, such as the Pokemon type with the highest total stats and the most and least common Pokemon types.

If you wish to conduct further analysis, the DataFrame can be exported to a CSV file named 'pokemon_data.csv' using the provided code.

