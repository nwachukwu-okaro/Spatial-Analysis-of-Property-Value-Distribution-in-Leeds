# Spatial-Analysis-of-Property-Value-Distribution-in-Leeds
Tools Used: ArcGIS Pro, Excel (Data Cleaning), REPD/Land Registry Dataset Integration.

# 1. Project Overview
This project examines the economic landscape of Leeds and surrounding areas by visualizing aggregated mean property prices. By processing raw transaction data from April 2024, I created a spatial distribution map that identifies high-value real estate corridors and price variations across the metropolitan region.

# 2. Key Objectives

Price Aggregation: Synthesize individual property transactions into meaningful regional averages.


Geographic Correlation: Analyze the relationship between property values and proximity to major infrastructure like the M62, A6120, and A660.


Market Density: Visualize the volume of transactions alongside price data using multi-variable symbology.

# 3. Step-by-Step Technical Approach
**Phase I:** Data Engineering

Data Sourcing: Cleaned and filtered a dataset focused on Leeds property transactions for the period of April 2024.


Aggregation: Performed a spatial join/aggregation to calculate the Mean Price for specific clusters, ensuring the data was statistically representative of local neighborhoods.

**Phase II:** Cartographic Design

Base Mapping: Utilized a World Hillshade layer to provide topographic context without cluttering the thematic data.

Symbolic Hierarchy: Developed a dual-symbology approach:


Color Ramp: Transitioned from orange to deep red to represent price points ranging from £210,000 to £1,210,000.


Proportional Size: Scaled circle sizes (from 5 to 25 units) to indicate the density or volume of data points within each cluster.

**Phase III:** Spatial Layout & Standards

Professional Layout: Included essential cartographic elements: a north arrow, a dual-unit scale bar (miles and kilometers), and accurate data sourcing.


Map Projection: Set a scale of 1:249,173 to capture the regional context from Bradford in the west to Knottingley in the east.

# 4. Key Spatial Insights

High-Value Clusters: Noticeable concentration of high-value properties (dark red circles) near Wetherby Road and the northern A6120 corridor.


Connectivity Impact: Property values show distinct patterns along the M62 motorway and major "A" roads, highlighting the influence of transport links on regional pricing.


Urban vs. Suburban: The map clearly differentiates the price density of central Leeds from outlying towns like Pudsey, Morley, and Kippax.
