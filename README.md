# hackathon-shape-my-city

## Problem
The civil engineering office is responsible for sustainable infrastructure management. Whether traffic routes, green spaces, sewerage
or waste disposal - its task is to plan and maintain basic infrastructure in the city of Lucerne. The department is responsible for ensuring that installations comply with the regulations, that they are economically and safely constructed, operated and maintained and that future generations will be able to use the plants in in good condition. The effective and secure construction of new infrastructure requires extensive and detailed knowledge about the underground of the affected area. Fresh and sewage water systems pose a constant challenge for architects and engineers as misinformation regarding size and location of water pipes can lead to immense costs. Currently fresh and sewage water data is available in 2D. In order to minimize the risk of damage and to increase the efficency of the construction process the city of Lucern seeks for a way to transform the data into 3D.

## Goal
**Possibilities are to be shown of how to obtain a 3D model of the subsoil with the given 2D fresh and sewage water system plans.** Which data model adaptations are necessary to perform this transformation? Provide an MVP given the LIDAR surface profile, the geo information about the pipes and the information about the layout of the pipe system. Infrastructure data was provided by the civil engineering office of lucerne.

## Data
The following data from a test perimeter on the Frutt-/Industriestrasse is provided as a basis:
- Point cloud digital terrain model of the 2018 LIDAR flight _(start point for Z-axis_
- Sewage data (sewage node, cover, husbandry, husbandry point) _(y- and x-axis in 2 dimensional space)_
- Water data (fitting, hydrant, pipe, pipe point, pipe section) _(y- and x-axis in 2 dimensional space)_
- Detailed information about the layers of the system _(calculate the pipe position Z from it)_

## Recommended Knowledge 
- GIS Program _(QGIS, ARCGIS, ..)_
- 3 modeling _(Blender, ..)_
- LIDAR Reader _(use http://lidarview.com for preview of data)_

> "The way to get started is to quit talking and begin doing." -Walt Disney
