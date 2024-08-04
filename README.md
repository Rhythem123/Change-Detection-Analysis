Forest Cover Change Detection and Analysis in Möllergrab Marteloscope (2019-2023)

Project Overview

This project aims to detect, analyze, and report changes in forest cover in the Möllergrab Marteloscope area over the years 2019 and 2023. The Change Detection Analysis involves calculating the Canopy Height Model (CHM), statistical measures of CHM, and comparing these metrics between 2019 and 2023.

Table of Contents

Introduction
Data Description
Methodology
Results and Analysis
Conclusion
Usage
License
Contributors
Acknowledgements

Introduction

Forest cover change detection is crucial for understanding and managing forest ecosystems. This study focuses on the Möllergrab Marteloscope area, analyzing changes from 2019 to 2023 using the Canopy Height Model (CHM). CHM represents the height from the ground to the top of the tree canopy, derived from Digital Surface Model (DSM) and Digital Terrain Model (DTM).
Data Description
Canopy Height Model (CHM): Raster dataset representing the vertical distance from the ground surface to the canopy.
Digital Surface Model (DSM): Provides elevation information of both natural and artificial features.
Digital Terrain Model (DTM): Provides elevation information of the bare earth's surface, including natural terrain features like rivers and ridges.

Methodology

Data Acquisition:
Collect DSM and DTM data for the years 2019 and 2023.
CHM Calculation:
Compute CHM by subtracting DTM from DSM.
Statistical Analysis:
Calculate mean, range, standard deviation, and maximum value of CHM for both years.
Change Detection:
Compare CHM and its statistical measures between 2019 and 2023.

Results and Analysis

The analysis revealed significant changes in the forest cover from 2019 to 2023:

Increase in mean, range, standard deviation, and maximum value of CHM: Indicates regeneration of forest canopy, increased variability, and diversity in the forest ecosystem.
Decrease in sum and minimum value of CHM: Suggests possible deforestation or disturbances like wind damage.

Conclusion

Despite being a windthrow area, the Möllergrab Marteloscope showed a positive change in 2023. The observed increase in CHM values suggests forest regeneration and sustainable forest management. However, the decrease in the sum and minimum values of CHM indicates areas affected by deforestation or natural disturbances.

Repository Content

/docs: Documentation and supplementary materials related to the project.
README.md: This readme file providing an overview of the project.
