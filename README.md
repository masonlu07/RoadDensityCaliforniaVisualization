### The Geography of Road Density in California
 



This visualization shows the geographic distribution of road density in the state of California. The data was accessed from the California Department of Transportation (Caltrans) All Public Roads Networks. In this visualization, it displays 723,692 road features which forms the network. Each road feature is represented as a line, showing the spatial arrangement of the California’s transportation infrastructure.


To compute the road density, California was divided into 10 km by 10 km grid cells. In each cell, the road density was calculated as the total length of roads divided by the cell’s area (km/km2). 
This visualization was created using Python in Jupyter Notebook, with road density represented by a logarithmic color scale ranging from blue (lower density) to magenta (higher density).


Overall, this visualization showcases the distribution of road infrastructure in California. The high-density regions are concentrated in major metropolitan areas, such as Los Angeles, Sacramento, and San Francisco. The rural areas generally exhibit lower road density. 
 


### Reproducing the Visualization

1.) Download or clone this GitHub repository.

2.) Download the Caltrans All Public Roads Network shapefile from the data source.

3.) Extract the shapefile and keep the associated files together. 

4.) Install the required Python libraries (from Requirements.txt). 

5.) Open NetworkViz_Code.ipynb in Jupyter Notebook.

6.) Update the folder and shp_path to match the location of the downloaded files.

7.) Run the notebook to generate the visualization. 




### AI Disclosure

An AI tool (ChatGPT) was used to assist with Python coding and visualization design. 
