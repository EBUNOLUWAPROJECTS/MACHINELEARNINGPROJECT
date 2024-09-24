# Lagos Housing Rent Predictor

## Project Overview
This project aims to address housing price predictions in Lagos, Nigeria, by building an accurate, location-specific house rent predictor. Lagos, the most populous city in Africa, faces acute housing shortages, driving rents up astronomically. The challenge is fueled by the Lagos subsidy law, multiple taxes, and high construction costs. A proposed solution involves a mixed-income model, reserving 15% of housing units for low and moderate-income earners.

## Problem Statement
Currently, there is no viable house rent predictor for the various neighborhoods in Lagos. Most rental platforms lack the granularity required for accurate and location-specific predictions. This lack of information limits renters' ability to understand rental prices across different areas, causing financial strain and dissatisfaction in housing choices.

## Proposed Solution
This project will develop a location-specific house rent predictor using advanced data analytics and machine learning techniques. The predictor will analyze historical rental data, current market conditions, and future trends to generate personalized rental predictions. It will consider factors such as:

- Neighborhood amenities
- Infrastructure
- Proximity to essential services
- Overall living conditions

Additionally, the predictor will account for fluctuations in the real estate market, economic trends, and demographic changes to ensure accuracy and relevance.

## Data Source
Data for this project is sourced from the real estate website PropertyPro.NG. The dataset includes the following features:

- **Title of the Home/Listing:** Indicates the property type (duplex, apartment, land, flat, etc.)
- **Location of Home:** Provides information on the city and neighborhood.
- **Price of Home:** Initially recorded as a string, converted to integers for analysis.
- **Newly Built:** Indicates if the property is newly built (True/False).
- **Serviced:** Specifies if the property is serviced (True/False).
- **Furnished:** Shows if the property is furnished (True/False).
- **Number of Bedrooms:** Converted from string to integer.
- **Number of Bathrooms:** Converted from string to integer.
- **Number of Toilets:** Converted from string to integer.

## Project Files
The following Jupyter notebooks are included in this project:

- `Web Scraper.ipynb`: Code for data scraping.
- `Lagos Extracting and Cleaning.ipynb`: Data extraction and cleaning processes.
- `Data Preprocessing.ipynb`: Data preparation and feature engineering.
- `Model Building.ipynb`: Model development and training.
- `Feature Importance.ipynb`: Analysis and visualization of feature importance.

## Getting Started
To get a deeper understanding of this project, look at the notebooks. which details each step from data collection to model evaluation

