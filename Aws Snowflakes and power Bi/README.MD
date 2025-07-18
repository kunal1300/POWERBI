# Rainfall, Humidity, Temperature, and Yields Analysis

This repository contains data and scripts for analyzing rainfall, humidity, temperature, and crop yields across various years, seasons, crops, and locations. The data is sourced from an AWS S3 bucket and processed using Snowflake for data integration.

## Overview

- **Rainfall Analysis**: Average rainfall data by year, season, crops, and locations.
- **Humidity Analysis**: Average humidity data by year, season, crops, and locations.
- **Temperature Analysis**: Average temperature data by year, season, crops, and locations.
- **Yields Analysis**: Average yields data by year, season, crops, and locations.

## Data Source

The raw data is stored in an AWS S3 bucket (`powerbi.project13`) and includes a CSV file (`data_season.csv`) uploaded on July 1, 2025. The data is integrated into a Snowflake database for further analysis.

## Structure

- **Data Files**: `data_season.csv` (contains seasonal data for rainfall, humidity, temperature, and yields).
- **Scripts**: SQL scripts for data integration and analysis are available in the Snowflake workspace.

## Usage

1. **Access Data**: Download `data_season.csv` from the S3 bucket or use the Snowflake database.
2. **Run Queries**: Execute the provided SQL scripts in Snowflake to generate analysis.
3. **Visualize**: Use the data to create visualizations (e.g., bar charts as shown in the images).

## Analysis Highlights

- **Rainfall**: Highest average in 2007 (100.44% of GT Average), with Khari season at 3097 units.
- **Humidity**: Consistent at 56-66% across years, seasons, crops, and locations.
- **Temperature**: Ranges from 33°C (Chikmagaluru) to 186°C (Bangalore), with Khari at 72°C.
- **Yields**: Highest for Cotton (51K) and Coconut (34K), with Kodagu at 28.7K.

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests. Ensure to update the documentation accordingly.

## for more detail
[Click on link](https://g.co/gemini/share/824716bb5bc7)

## Insights preview
### Dashboard 
![Dashboard Screenshot 1](https://github.com/kunal1300/POWERBI/blob/main/Aws%20Snowflakes%20and%20power%20Bi/Screenshot%201.png)

![Dashboard Screenshot 2](https://github.com/kunal1300/POWERBI/blob/main/Aws%20Snowflakes%20and%20power%20Bi/Screenshot%202.png)

![Dashboard Screenshot 3](https://github.com/kunal1300/POWERBI/blob/main/Aws%20Snowflakes%20and%20power%20Bi/Screenshot%203.png)

![Dashboard Screenshot 4](https://github.com/kunal1300/POWERBI/blob/main/Aws%20Snowflakes%20and%20power%20Bi/Screenshot%204.png)

## Aws(S3)

![ Screenshot 5](https://github.com/kunal1300/POWERBI/blob/3675d25444e41e441b621672a7e039ca3698a9b9/Aws%20Snowflakes%20and%20power%20Bi/AWS%20S3.png)

## Snowflakes Dashboard
![ Screenshot 6](https://github.com/kunal1300/POWERBI/blob/3675d25444e41e441b621672a7e039ca3698a9b9/Aws%20Snowflakes%20and%20power%20Bi/snowflakes.png)



