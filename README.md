# Forest Loss and Protected Area Effectiveness for Pollinators (Order: Hymenoptera) in Java-Bali (2000-2024)

## Project Overview
This study analyzed forest habitat loss and protected area effectiveness for pollinators, to answer whether pollinator occurences are associated with forest areas, whether remaining forests support higher pollinator richness compared to forest-loss areas, and whether protected areas support higher pollinator richness compared to surrounding areas.

## Data Sources
1. Hymenoptera occurrence records obtained from Global Biodiversity Information Facility (GBIF)
2. Forest cover (2000), forest loss (2001-2024) were obtained from Global Forest Watch (GFW)
3. Protected areas were obtained from World Database on Protected Areas (WDPA)

## Methods
1. Data acquisition from GBIF
2. Taxonomic cleaning and quality filtering
3. Spatial preprocessing
4. Forest cover extraction
5. Classification:
   - Forest
   - Non-forest
   - Remaining forest
   - Forest-loss
   - Protected Areas (PA)
   - Non-Protected Areas (OPA; Outside Protected Areas)
6. Species/taxonomic richness calculation
7. Rarefaction analysis to correct unequal sampling effort
8. Negative binomial Generalized Linear Model (GLM) Analysis

## Main Findings
### Forest Association
- Most occurrence records were located in non-forest landscapes.
- This pattern likely reflects sampling bias and the ability of pollinators to utilize modified habitats.
- Occurrence records alone do not indicate habitat preference.
### Forest Loss
- Remaining forest areas contained higher observed pollinator richness compared to forest-loss areas.
- Forest retention appears important for maintaining pollinator diversity
### Protected Areas
- Protected areas were associated with higher expected pollinator richness after accounting for tree cover.
- Protected landscapes may provide more stable habitat conditions and resources for Hymenoptera communities.

## Tools Used
- RStudio
- GIS/spatial analysis
- GBIF biodiversity data
- WDPA protected areas database
- Google Earth Engine

## Repositories included
1. R files (RData)
2. Final report (pdf)
3. Forest loss cover, pollinator distribution in forest vs non forest area, remaining forest vs forest-loss area, protected areas vs outside protected areas (png)
4. Pollinator richness in protected areas, unique pollinator taxa in protected areas (csv)

## Status
Independent study
