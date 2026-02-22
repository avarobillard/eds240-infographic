# EDS 240 Final Project Infographic: Exploring New York City's Trees: an urban forest

Author: Ava Robillard

This repository contains an analysis of NYC OpenData Street Tree Census data and the creation of an infographic to answer questions about the spatial distribution of trees within New York City. This data will be used alongside census data to explore socioeconomic variables and how they correlate to tree placement.

## Repository Structure

```         
eds240-infographic
├── README.md
├── data
├── exploration.qmd
├── drafting-viz.qmd
└── eds240-infographic.Rproj
```

## Data

NYC OpenData provides Street tree data from the TreesCount! 2015 Street Tree Census, conducted by volunteers and staff organized by NYC Parks & Recreation and partner organizations. It contains information about over 600,000 trees across the city, including the species name, health, borough, and census tract.

Note- this data is from the 2015 Tree Census, but could be replaced with the 2025 Tree Census data when it becomes available, likely in 2026 or 2027.

The spatial attributes of the Street Tree Census data allow it to be joined with data from the US Census Bureau, the American Community Survey (ACS) from 2015 to match the Tree Census year.

## References

This assignment was created as a part of EDS 240: Data Visualization & Communication, taught by Sam Shanny-Csik.

New York City Department of Parks & Recreation. (2015). 2015 Street Tree Census - Tree Data [Dataset]. NYC Open Data. <https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh/about_data>

U.S. Census Bureau. (2015). American Community Survey 5-year estimates. U.S. Department of Commerce. <https://www.census.gov/programs-surveys/acs>

U.S. Census Bureau. (2015). TIGER/Line® Shapefiles: Census Tracts (New York). U.S. Department of Commerce. <https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html>
