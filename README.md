Mapping Vegetation & Swimming Pools in Los Angeles
Remote Sensing & Urban Spatial Intelligence Analysis
Executive Summary

This project applies advanced remote sensing and GIS spatial modeling techniques to high-resolution 4-band NAIP aerial imagery of Los Angeles’ Westside.

The objective was to extract actionable intelligence on:

Urban vegetation distribution

Residential swimming pool density

Neighborhood-scale spatial patterns

Classification limitations and spectral anomalies

The workflow integrates raster analysis, spectral index modeling, grid-based aggregation, and professional cartographic design — reflecting real-world geospatial consulting applications.

Project Context

Urban planners, environmental analysts, and infrastructure strategists require neighborhood-scale metrics to evaluate:

Green space accessibility

Heat island mitigation capacity

Land use patterns

High-value property features

This project demonstrates an operational methodology for transforming raw multispectral imagery into decision-grade spatial intelligence.

Data Sources

NAIP Aerial Imagery (2020)

4-band imagery (Red, Green, Blue, Near-Infrared)

1-meter spatial resolution

Los Angeles Neighborhood Boundaries

Polygon dataset of Westside communities

Includes Santa Monica, Venice, Mar Vista, and adjacent zones

Analytical Workflow
1️⃣ Multi-Band Visualization

True Color Composite (RGB)

Color-Infrared Composite (NIR, Red, Green)

Spectral interpretation of vegetation vigor

2️⃣ NDVI Computation
𝑁
𝐷
𝑉
𝐼
=
(
𝑁
𝐼
𝑅
−
𝑅
𝑒
𝑑
)
/
(
𝑁
𝐼
𝑅
+
𝑅
𝑒
𝑑
)
NDVI=(NIR−Red)/(NIR+Red)

Value Range: -1 to 1

Vegetation Threshold: > 0.3

Water/Pool Threshold: < -0.45

3️⃣ Raster Classification

Binary vegetation mask

Binary swimming pool mask

False positive evaluation

4️⃣ Density Modeling (Grid-Based Aggregation)
Grid Type	Purpose	Justification
Rectangular (200m)	Vegetation Density	Simple spatial aggregation
Hexagonal (200m)	Pool Density	Reduced directional bias

Grid-based density mapping enabled neighborhood-level comparisons rather than noisy pixel-level classification.

5️⃣ Cartographic Production

Blending modes for feature emphasis

Vector overlay integration

Neighborhood labeling

Comparative layout design

Map Portfolio
Map 1: True Color Composite

Natural RGB representation of NAIP imagery.

Map 2: Color-Infrared (CIR)

Vegetation displayed in shades of red to emphasize biomass and canopy density.

Map 3: Vegetation Density (Rectangular Grid)

Fraction of pixels with NDVI > 0.3 aggregated per 200m grid cell.

Map 4: Swimming Pool Density (Hexagonal Grid)

Fraction of pixels with NDVI < -0.45 aggregated using hexagonal tessellation.

Map 5: Spectral Classification Visualization

Grayscale imagery with:

Green overlay → Vegetation mask

Blue overlay → Water/pool mask

Comparative high-density vs low-density frames

Key Findings
Vegetation Distribution

Highest density: Santa Monica residential zones and parklands

Lowest density: Commercial corridors and industrial districts

Clear dominance of tree canopy in single-family neighborhoods

Swimming Pool Patterns

Concentration in affluent low-density housing clusters

Strong correlation with parcel size and urban morphology

Classification Challenges Identified

Dark rooftops falsely classified as water

Deep building shadows misidentified as pools

Artificial turf producing unexpected NDVI values

This demonstrates critical evaluation beyond algorithmic output — a core competency in applied geospatial consulting.

Strategic Insight

Pixel-level classification is insufficient for policy and planning decisions.

Grid-based spatial aggregation:

Enhances interpretability

Reduces noise

Enables neighborhood benchmarking

Supports data-driven planning

Professional Applications

This methodology scales directly to:

Urban Planning

Tree canopy assessment

Heat island mitigation strategy

Green equity analysis

Environmental Consulting

Wetland mapping

Drought monitoring

Vegetation health tracking

Insurance & Risk Modeling

Wildfire fuel mapping

Asset valuation (pool identification)

Property feature intelligence

Public Health

Vegetation density vs health outcome correlation

Real Estate Analytics

Amenity mapping

High-value feature extraction

Technical Stack

QGIS 3.x

Raster Calculator

Zonal Statistics

Grid Generation Tools

Advanced Print Layout Design

Competencies Demonstrated
Domain	Skills
Remote Sensing	Multispectral interpretation, NDVI
Raster Analysis	Reclassification, masking
Vector Analysis	Grid creation, spatial overlay
Spatial Statistics	Zonal aggregation
Cartography	Professional layout & symbology
Analytical Reasoning	False positive evaluation
Repository Structure
project-root/
│
├── README.md
└── images/
    ├── TRUE COLOR.png
    ├── CIR.png
    ├── Vegetation Density.png
    ├── Swimming Pool Density.png
    └── Map5.png
Closing Statement

This project demonstrates the transformation of raw aerial imagery into structured spatial intelligence suitable for policy design, environmental analysis, and urban investment strategy.

It reflects a scalable, industry-aligned workflow bridging remote sensing science with applied GIS decision support.
