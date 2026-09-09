# Box Office Analysis Dashboard

## Overview

This Power BI dashboard analyzes daily box office revenue data and provides insights into movie performance, distributor contribution, and revenue trends over time.

## Data Model

The solution follows a simple star schema:

- Fact_Revenue
- dim_Date
- dim_Films
- dim_Distributors

The model supports filtering, ranking, and time intelligence calculations.

## Dashboard Features

### Filters
- Year
- Month
- Film Title
- Distributor Name

### KPIs
- Total Revenue
- YTD Revenue
- YTD Million Earning Days
- Movies

### Visualizations
- YTD Revenue and Million Earning Days Trend
- Movie Performance Ranking
- Custom Tooltip with additional movie and monthly performance details

## Key Measures

- Total Revenue
- YTD Revenue
- YTD Revenue %
- Million Earning Days
- YTD Million Earning Days
- YTD Theaters
- YTD Rank
- MoM Growth %
- Top Movie

## Business Value

The dashboard enables users to:

- Analyze box office performance over time
- Identify top-performing movies
- Compare distributor performance
- Track cumulative revenue growth
- Monitor million-dollar earning days
- Evaluate month-over-month trends

## Technologies

- Power BI
- DAX
- Star Schema Modeling
- Time Intelligence (YTD Calculations)

## Assumptions

- Release Date is defined as the earliest revenue date available for a movie.
- Million Earning Days represent days with revenue greater than $1,000,000.
- Rankings are based on YTD Revenue.
