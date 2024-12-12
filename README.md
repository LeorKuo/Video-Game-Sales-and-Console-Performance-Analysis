# Video-Game-Sales-and-Console-Performance-Analysis

## Introduction
This project explores the relationship between video game releases and the performance of gaming consoles/platforms. By analyzing historical sales data of video games and consoles, we aim to determine whether flagship games have a measurable impact on console sales.

## Objectives
The main objectives of this project are:
1. To investigate the correlation between flagship game releases and console sales.
2. To assess the influence of the frequency of game releases on console sales performance.
3. To identify other factors that may drive console sales.

## Dataset
We used three main data sources:
1. **Video Game Sales Data**: Information on 64,016 video game titles (1971–2024) from [Maven Analytics Data Playground](https://www.mavenanalytics.io/data-playground).
2. **Weekly Console Sales Data**: Data (2004–2024) scraped from [vgchartz.com](https://www.vgchartz.com/).
3. **Platform Information**: Cross-referenced public data for platform names and release years, manually verified.

## Methodology
1. **Data Preparation**:
   - Filtered data to focus on relevant time frames (2004–2024).
   - Addressed missing data and normalized date formats for time series analysis.
   - Merged datasets to align video game release dates with console sales data.

2. **Analysis**:
   - Identified top-selling games per console and evaluated their impact on console sales.
   - Used heatmaps to visualize missing data and assess data quality.
   - Conducted time series analysis to evaluate sales patterns around flagship game launches.
   - Built a Random Forest Regression model to predict console sales based on game release frequency and sales data.

3. **Visualization**:
   - Created bar charts and line charts to highlight trends.
   - Utilized correlation matrices and autocorrelation plots to uncover patterns in sales data.

## Key Findings
1. The release of flagship games has limited and short-term effects on console sales.
2. Platforms with higher numbers of game releases show a long-term positive trend in sales.
3. Sales data exhibits a cyclical pattern, likely influenced by seasonal events like holiday promotions.
4. The Random Forest Regression model achieved limited accuracy (R² = 0.308), indicating that other factors may drive sales beyond game releases.

## Results
- The highest-selling games per console included titles like *Grand Theft Auto V*, *Dragon Quest XI*, and *Minecraft*.
- A strong correlation exists between the number of game releases and console sales.
- Sales fluctuations align with yearly cycles, highlighting the importance of external events.
