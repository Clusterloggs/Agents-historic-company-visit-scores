
# Agents Historic Company Visit Scores Analysis

**Author**: Azeez Akintonde  
**Date**: April 15, 2024  

This repository contains an analysis of historic company visit scores collected by the Bank of England's Agents from 2009-2020. The analysis explores sectoral investment and employment trends over time.

## Table of Contents
- [Introduction](#introduction)
- [Tasks Overview](#tasks-overview)
  - [Task 1: Data Loading](#task-1-data-loading)
  - [Task 2: Data Filtering](#task-2-data-filtering)
  - [Task 3: SIC Code Mapping](#task-3-sic-code-mapping)
  - [Task 4: Data Visualization](#task-4-data-visualization)
- [Results](#results)
  - [Investment Score Analysis](#investment-score-analysis)
  - [Employment Score Analysis](#employment-score-analysis)
- [Conclusion](#conclusion)
- [Limitations](#limitations)

## Introduction

The aim of this project is to analyze historic visit scores related to company investment and employment, categorized by sectors over time. The dataset includes data from the **Bank of England's Agents** collected between **2009 and 2020**. This README provides an overview of the analysis process, from data loading to visualization.

## Tasks Overview

### Task 1: Data Loading
This section loads required libraries and imports the dataset. The data is explored to obtain basic information such as the number of observations and columns.

### Task 2: Data Filtering
Companies with both positive **Investment Score** and **Employment Score** were filtered, and the resulting dataset was reviewed for structure and content.

### Task 3: SIC Code Mapping
Using the SIC column, categories were mapped to specific SIC codes. A new column `Potential_SICs` was created to store these mappings.

### Task 4: Data Visualization
Two heatmaps were generated to visualize average **Investment Score** and **Employment Score** across years and sectors.

## Results

### Investment Score Analysis

This analysis covers sector-wise trends for **Investment Scores** from **2008 to 2020**. Key findings include:
- **Transportation, Storage, and Communications** consistently had the highest scores, peaking in 2008.
- **Distribution, Hospitality, Arts, and Entertainment** sectors displayed lower scores but saw a slight increase in recent years.

### Employment Score Analysis

Employment scores varied more significantly across sectors:
- **Transportation, Storage, and Communications** maintained a high average, suggesting employment stability.
- **Distribution, Hospitality, Arts, and Entertainment** sectors showed rising employment scores from 2018 onward.

## Conclusion

The analysis offers insights into the **investment and employment dynamics** across sectors over a decade. Transportation, storage, and communication sectors stood out in both investment and employment stability, while others experienced varied fluctuations.

## Limitations

This analysis has limitations:
1. **Data Coverage**: Limited by the scope of data from Bank of England’s Agents.
2. **Sector Classification**: The broad categorization may mask nuances within each sector.
3. **Economic Factors**: External economic impacts are not explicitly considered, which may influence the observed trends.
