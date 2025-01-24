# Urban-Sprawl
Java script can be used to assess the urban sprawl in any part of the world. Just change your ROI (Region of Interest)
This project visualizes Pakistan's built-up surface area between 1975 and 2020 using the Global Human Settlement Layer (GHSL) dataset. The visualization highlights urban growth over time by displaying only the built-up areas in distinct colors, while non-built-up regions remain transparent. This approach enables clear identification of urban expansion trends within Pakistan.

Key Objectives
To analyze and compare the built-up surface area in Pakistan for 1975 and 2020.
To visualize urban growth trends with a focus on built-up regions only.
To provide an interactive map with a clear legend for easy interpretation.
Features
Built-Up Area Masking:
Non-built-up areas are masked (made transparent), ensuring only urban areas are displayed.
Distinct Color Palettes:
1975: Blue shades (0000FF to 00FFFF) represent the built-up areas.
2020: Red-to-yellow shades (FF0000 to FFFF00) highlight the built-up areas.
Clipping to Pakistan Boundary:
The built-up surface data is clipped to a custom shapefile of Pakistan for precise regional analysis.
Dynamic Legend:
A legend is included to describe the color-coding for each year.
Dataset Used
GHSL Built-Up Surface Dataset:
Dataset ID: JRC/GHSL/P2023A/GHS_BUILT_S
Provides global built-up surface data at 10m resolution for multiple years.
Pakistan Boundary Shapefile:
Custom shapefile uploaded to Google Earth Engine: users/shahidiqbal/Pak.
How It Works
Defining the Area of Interest (AOI):
The shapefile for Pakistan is used to define the AOI.
This ensures the data is clipped to display built-up areas only within Pakistan.
Built-Up Area Masking:
Using the updateMask() function, non-built-up regions are masked, leaving only urbanized areas visible.
Year-Specific Visualization:
Built-up areas for 1975 and 2020 are visualized in distinct color palettes.
Interactive Map with Legend:
The map is centered on Pakistan and includes a legend explaining the color codes for each year.
Applications
Urban Planning:
Analyze historical urbanization trends for informed urban development.
Climate Change Studies:
Assess urban expansion impacts on the environment and climate.
Educational Use:
Serve as a learning tool for students and researchers studying urbanization and geospatial analysis.
Policy Making:
Provide data-driven insights for sustainable development policies.
Local Features
Blue Shades for 1975:
Highlight historical built-up areas.
Red-to-Yellow Shades for 2020:
Display modern urban expansion.
Transparency for Non-Built-Up Areas:
Keeps non-built regions clear for focused analysis.
How to Use
Open in Google Earth Engine:
Access the project using the Earth Engine Code Editor.
Run the Script:
View the built-up areas for 1975 and 2020 clipped to Pakistan's boundary.
Analyze the Map:
Compare urban areas for each year using the distinct color-coded layers.
Expected Output
Built-Up Areas for 1975:
Displayed in blue shades.
Built-Up Areas for 2020:
Displayed in red-to-yellow shades.
Transparent Background:
Only urban areas are visible, while the rest of the region remains clear.
Interactive Legend:
A legend with colors and descriptions for both years.
Why This Project Matters
This project provides a clear and visually engaging analysis of urban growth in Pakistan over time. By focusing exclusively on built-up areas and masking non-built regions, the map offers an intuitive way to understand urban expansion. It serves as a valuable resource for urban planners, researchers, policymakers, and students.
