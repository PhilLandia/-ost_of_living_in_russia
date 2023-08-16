# Collection of maps "Cost of living in the subjects of the Russian Federation"
This project is a collection of thematic maps that show statistics on the cost of goods, services and housing in various regions of the Russian Federation.
## **Example**
'layouts\2022.png'
## **Objective**

The goal of this project is to provide a visual representation of the cost of living in different regions of Russia. Using collected data and interactive maps, users can analyze the dynamics of price changes and compare the economic conditions between different regions.

## **Key Features**

- Utilization of a tiled map of the Russian Federation for easy data visualization.
- Data about the cost of goods, services, and housing is sourced from the Unified Interdepartmental Information and Statistical System (UIISS).
- Analysis is based on the cost of a fixed set of consumer goods and services per month, as well as the average price per square meter of total area for apartments in the housing market.
- The project enables tracking price dynamics and analyzing cost of living variations among Russian subjects.

## **Project Structure**

- **`data/`** - directory containing data on the cost of goods, services, and housing.
- **`layouts/`** - directory with maps for each subject of the Russian Federation.
- **`README.md`** - this file providing project description.

## **Usage**

1. Clone the repository to your computer.
2. Familiarize yourself with the data in the **`data/`** directory.
3. Study the generated maps in the **`layouts/`** directory for cost of living analysis.

## **Data and Methodology**
The analysis in this project is based on two primary sets of data: the cost of a fixed set of consumer goods and services per month, and the average price per square meter of residential properties in the housing market. The list of consumer goods and services was derived from the decree of Rosstat (Russian Federal State Statistics Service) dated December 22, 2021, No. 944.

To calculate the monthly cost of living, several criteria were taken into account, including the monthly rental cost, and the cost of goods and services. Rental cost data was calculated based on the average price per square meter of residential properties in each specific region of the Russian Federation. During data processing, it was determined that the average price per square meter of housing exceeds the monthly rental cost of apartments by a factor of 5.75 on average. This insight allowed us to compute rental cost data for all subjects of the Russian Federation.

By integrating these datasets and applying a comprehensive methodology, we aimed to provide accurate and informative insights into the cost of living variation across regions.

Please note that this information provides a deeper understanding of the data sources and analysis methods employed in the project, enhancing transparency and credibility.

## **License**

The project is distributed under the **[MIT License](https://github.com/PhilLandia/Cost_of_living_in_Russia/blob/main/LICENSE)**, allowing free use and modification of the code with attribution.
