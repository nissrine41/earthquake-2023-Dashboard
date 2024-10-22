# earthquake-2023-Dashboard

## Description
This project involves the creation of an Earthquake Dashboard that visualizes earthquake events data. The dashboard provides insights into the characteristics of seismic events using a star schema design for data modeling.

## Data Overview
The dataset includes the following fields:

- **Time:** Timestamp of the earthquake event.
- **Latitude:** Geographic coordinate specifying the north-south position.
- **Longitude:** Geographic coordinate specifying the east-west position.
- **Depth:** Depth of the earthquake in kilometers.
- **Mag:** Magnitude of the earthquake.
- **MagType:** Type of magnitude measurement.
- **Nst:** Number of seismic stations that reported the earthquake.
- **Gap:** The gap between different seismic stations' coverage.
- **Dmin:** Minimum distance to the earthquake epicenter for the nearest station.
- **Rms:** Root Mean Square of the earthquake's amplitude spectrum.
- **Net:** Network reporting the earthquake.
- **Id:** Unique identifier for the earthquake event.
- **Updated:** Timestamp indicating when the earthquake information was last updated.
- **Place:** Location description of the earthquake.
- **Type:** Type of seismic event (e.g., earthquake).
- **HorizontalError:** Horizontal error in location determination.
- **DepthError:** Error in depth determination.
- **MagError:** Error in magnitude determination.
- **MagNst:** Number of seismic stations used to calculate the magnitude.
- **Status:** Status of the earthquake event (e.g., reviewed).
- **LocationSource:** Source reporting the earthquake location.
- **MagSource:** Source reporting the earthquake magnitude.

## Data Modeling
To effectively analyze and visualize the earthquake data, a star schema was created using **Talend**. This involved:

- **Fact Table:** Containing metrics related to the earthquake events, such as magnitude, depth, and number of seismic stations.
- **Dimension Tables:** Including details like the time of occurrence, geographical location, and magnitude types.

## Tools and Technologies Used
- **Talend:** For data extraction, transformation, and loading (ETL) to create the star schema.
- **Power BI:** For visualizing the earthquake data through interactive dashboards.

## Key Contributions
- Designed a star schema for organizing earthquake data, enabling efficient querying and analysis.
- Developed interactive dashboards in Power BI to visualize key metrics related to seismic events.
- Analyzed earthquake trends and patterns to provide insights into seismic activity in different regions.

