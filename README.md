**Mapping Vegetation & Swimming Pools in Los Angeles: A Remote Sensing & GIS Analysis**

**_Project Overview_**

This project demonstrates advanced remote sensing analysis and GIS spatial modeling using high-resolution 4‑band NAIP aerial imagery of Los Angeles’ Westside. The primary objective is to extract meaningful insights about urban vegetation patterns and swimming pool distribution through raster analysis, spectral indices, and vector‑based zonal statistics.

By completing this analysis, I showcase proficiency in industry‑standard geospatial technologies and analytical methods directly applicable to careers in urban planning, environmental consulting, precision agriculture, and geospatial intelligence.

**_Learning Objectives Achieved_**

Multi-band raster visualization and interpretation (true color, color‑infrared)

Calculation of Normalized Difference Vegetation Index (NDVI) – a foundational remote sensing metric

Raster calculator operations and threshold‑based classification

Zonal statistics aggregation using rectangular and hexagonal grids

Advanced map layout design with vector/raster integration

Critical evaluation of spectral anomalies and false positives in classification

**_Technical Skills Demonstrated_**

Skill Category

Specific Techniques	Relevance to Industry

Remote Sensing	Multi‑band image processing, NDVI calculation, spectral signature interpretation	Essential for environmental monitoring, agriculture, forestry
Raster Analysis	Reclassification, binary masking, raster calculator	Core competency for any GIS analyst
Vector Analysis	Grid generation, spatial overlay, polygon labeling	Urban planning, real estate analysis
Spatial Statistics	Zonal statistics, density aggregation, pattern analysis	Data‑driven decision making, policy research
Cartography	Print layout design, color theory, blending modes	Professional map production for reports and presentations

Critical Thinking

Identifying false positives, interpreting land use patterns	Problem‑solving in real‑world consulting scenarios

**_Data Sources_**

NAIP (National Agricultural Imagery Program) Aerial Imagery – 2020, 4‑band (Red, Green, Blue, Near‑Infrared), 1‑meter resolution

Los Angeles Neighborhood Boundaries – Polygon layer of Westside communities (e.g., Santa Monica, Venice, Mar Vista)

**_Methodology_**

Image Visualization

True Color Map (RGB): Standard natural color representation using bands 1, 2, 3

Color‑Infrared (CIR) Map: False‑color composite (NIR, Red, Green) to highlight vegetation health

Spectral Index Calculation
NDVI = (NIR - Red) / (NIR + Red)

Values range from -1 to 1

Vegetation threshold: > 0.3 (moderate to healthy vegetation)

Swimming pool threshold: < -0.45 (water bodies)

Density Analysis Using Grids
Rectangular grid (200m cells): Vegetation density via zonal statistics on NDVI > 0.3 mask

Hexagonal grid (200m cells): Swimming pool density via zonal statistics on NDVI < -0.45 mask

Hexagonal grids are preferred for reduced bias and more natural visualization

Advanced Visualization
Grayscale base imagery with green overlay (vegetation) and blue overlay (pools) using blending modes

Side‑by‑side comparison of high‑density vs. low‑density areas

**_Map Products_**

Below are the five maps produced in this analysis. Each map integrates the NAIP imagery with Los Angeles neighborhood boundaries and labels.

Map 1: True Color
Natural color composite using red, green, and blue bands.
https://images/TRUE%2520COLOR.png

Map 2: Color‑Infrared (CIR)
False‑color composite (NIR, red, green) highlighting vegetation in shades of red.
https://images/CIR.png

Map 3: Vegetation Density (Rectangular Grid)
Rectangular grid cells shaded by the fraction of pixels with NDVI > 0.3 (vegetation density).
https://images/Vegetation%2520Density.png

Map 4: Swimming Pool Density (Hexagonal Grid)
*Hexagonal grid cells shaded by the fraction of pixels with NDVI < -0.45 (swimming pool density).*
https://images/Swimming%2520Pool%2520Density.png

Map 5: False‑Color with Highlighted Features
*Grayscale NAIP imagery with green overlay (NDVI > 0.3) and blue overlay (NDVI < -0.45) using blending modes. Top frame: high‑density area; bottom frame: low‑density area.*
https://images/Map5.png

Key Findings & Insights
Vegetation Distribution
Highest density: Santa Monica residential areas, parklands (e.g., Palisades Park)

Lowest density: Dense commercial corridors, industrial zones near Venice Boulevard

Land use patterns: Single‑family neighborhoods with mature trees dominate high‑vegetation zones; impervious surfaces dominate low‑vegetation areas

False Positives & Anomalies
Some dark rooftop materials registered NDVI < -0.45, mimicking swimming pools

Deep shadows in urban canyons occasionally classified as water bodies

Lush green lawns correctly identified, but artificial turf sometimes produced unexpected NDVI values

**_Methodological Insight_**

Grid‑based density mapping proved far more effective for pattern recognition than pixel‑level classification, enabling neighborhood‑scale comparisons essential for urban planning applications.

**_Real‑World Applications_**

The techniques demonstrated here are directly transferable to numerous professional domains:

Urban Planning: Quantify green space access, identify heat island mitigation opportunities, track urban tree canopy changes over time

Public Health: Correlate vegetation density with health outcomes (asthma rates, mental health, physical activity levels)

Environmental Consulting: Monitor wetland health, assess drought impacts, conduct environmental impact assessments

Agriculture: Precision agriculture, crop yield prediction, irrigation optimization

Insurance & Risk Assessment: Map wildfire fuel loads, assess floodplain vegetation, identify high‑value assets (e.g., swimming pools) for property valuation

Real Estate Development: Identify neighborhood amenities (greenspace, water features) for site selection and marketing

**_Software & Tools_**

QGIS 3.x – Primary GIS platform (open source)

Raster Calculator – NDVI derivation and masking

Zonal Statistics Tool – Grid‑based aggregation

Print Layout Manager – Professional map composition
