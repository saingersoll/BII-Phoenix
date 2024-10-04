# Determining the Effects of Urban Development on Biodiversity Intactness Index in Phoenix, AZ
## Changes in Biodiversity Intactness Index (BII) Within Phoenix, AZ Between 2017 and 2020.
![image](https://github.com/saingersoll/BII-Phoenix/assets/141206781/b4690f6d-2aa8-4a0d-8879-d7568233b62b)


### Objective

Our goal with this project is to access the variations in biodiversity in Phoenix, Arizona between 2017 and 2020 to determine the affects of urban development. The metropolitan area of Phoenix, more specifically, Maricopa County, was dubbed the most developed land since 2001, in 2021 [1]. As the sprawl of the urban landscape continues to grow, new pressures are introduced to natural areas, creating stress on local biodiversity. Monitoring the changes that evolve as a result of these developments is important for understanding the depth in which anthropogenic activity impacts the natural environment. The assessments made using BII data may be applied strategically to spatial planning and management of remaining habitats.

### Method Highlights

- Accessing MPC STAC catalog collection for a specific bounding box
- Creating a map to demonstrate Phoenix subdivision
- Calculating pct_area within Phoenix subdivision for 2017 & 2020
- Visualizing devestated BII areas (>= 75% lost) between 2017 and 2020

### About the Data

Two data sources are utilized in this document:

Microsoft Planetary Computer (MPC): Biodiversity Intactness
io-biodiversity

https://planetarycomputer.microsoft.com/dataset/io-biodiversity

TIGER Shapefiles Census County Subdivision shapefile for Arizona, specifically the Phoenix subdivision polygon.
https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions

```
Citations:
1. https://www.washingtonpost.com/nation/interactive/2021/land-development-urban-growth-maps/
2. Microsoft Planetary Computer. Planetary Computer. (n.d.-a). https://planetarycomputer.microsoft.com/dataset/io-biodiversity
3. 2022 Tiger/Line® shapefiles: County+subdivisions. United States Census Bureau. (n.d.). https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County%2BSubdivisions
``` 

