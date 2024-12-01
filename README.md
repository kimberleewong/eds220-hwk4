# False Color Imagery and the 2017 Thomas Fire

Kimberlee Wong - November 23, 2024

## About

This repository includes two notebooks. Each notebook has the vital steps that were taken in order to get to the final product of a false color imagery map that includes the perimeter of the 2017 Thomas Fire. The hwk4-task2-fire-perimeter-wong.ipynb notebook includes the code that was used to achieve the Thomas Fire perimeter by filtering a dataset that had information on many California fires. The hwk4-task2-false-color-wong.ipynb notebook has the code that was used to visualize the landsat data and overlay the perimeter on top. There is a data folder that only includes the Thomas Fire boundary that was made, for the landsat data was accessible through the server. 

![image](https://github.com/user-attachments/assets/959812ec-8bf3-4a87-b1f8-e3de545e649b)

An image of the 2017 Thomas Fire, as seen over the Santa Barbara cityscape on Dec. 17, 2017. 

## Repository Structure
```
eds220-hwk4
│
├── README.md                     
├── hwk4-task2-false-color-wong.ipynb
├── hwk4-task2-fire-perimeter-wong.ipynb                       
├── .gitignore                    
│
├── data/                       
│   ├── thomas_fire_boundary.cpg
│   ├── thomas_fire_boundary.dbf
│   ├── thomas_fire_boundary.prj
│   ├── thomas_fire_boundary.shp
│   ├── thomas_fire_boundary.shx
```

## Data
The landsat data comes from Microsoft Planetary Computer Data Catalogue, and it is a simplified collection of colored bands. It was processed to remove data outside land and coarsen the spatial resolution. It is not included in this repo, for it is housed in the server.

The California fire perimeter shapefile  comes from the data catalog owned by the United States government. It is specific to the state of California and public, so it was intended for public access and use. Their metadata states that this data provides a "a reasonable view of the spatial distribution of past large fires but is in no way complete." But, for our uses, it has the adequate amount of information. This is not included in the repository, but it can be accessed in the link in the references section.

The Thomas Fire boundary was created in by filtering a California Fire perimeter file available from the US Government Data Catalogue. This is the only data included in the repository, under the data folder.

## References
Hamm, K. (2017, December 14). Closing schools and moving finals due to Thomas Fire. The Santa Barbara Independent. https://www.independent.com/2017/12/13/closing-schools-and-moving-finals-due-thomas-fire/ 

Microsoft Planetary Computer Data Catalogue, Landsat collection 2 Level-2 [Data file] Available from: https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2. Access date: November 22, 2024.

Data.gov Data Catalogue, California Fire Perimeters (all) [Data file] Available from: https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436. Access date: November 22, 2024.

Assignment came from UCSB Masters of Environmental Data Science class, EDS 220 - Working with Environmental Data Science. Class is taught by Carmen Galaz Garcia. 
