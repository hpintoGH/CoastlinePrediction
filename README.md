# Solution to MATLAB and Simulink Challenge project 229 Coastline Prediction using Existing Climate Change Models

[Program link](https://github.com/mathworks/MathWorks-Excellence-in-Innovation)

[Project description link](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/tree/main/projects/Coastline%20Prediction%20using%20Existing%20Climate%20Change%20Models)

# Project details
Global temperature rise leads to accelerated glacier melting, causing sea levels to rise. This impacts populations near the coastline, making it important to delineate at-risk areas for planning and decision-making. In this project, an application was developed to visualize changes in coastlines based on projections of sea level rise.

For the development of the Coastline Prediction application, inspiration was drawn from the work done by Wenyu Hu and Stacia Kolodziejski of Boston University [1]. However, both the source code and the user interface were created from scratch.

Several features and capabilities were added to the Coastline Prediction software, including:

- Inclusion of U.S. Geological Survey (USGS) digital elevation models with a resolution of 1/3 arc-second for the U.S. territory [2].
- The ability to visualize any location on the planet thanks to the incorporation of elevation data from the NASA Shuttle Radar Topography Mission Global 1 arc-second V003 [3], provided that the area of interest is within the coverage of the database.
- The addition of sea level projections until the year 2050 obtained from the Copernicus Climate Change Service [4].
- Coastal variation given a sea level rise.
- Manual adjustment of the area of interest at the user's discretion, with some restrictions to prevent excessively large amounts of data that could overwhelm the computer and disrupt the software's operation.

# How to run section
This application was developed in MATLAB 2023b, so it is recommended to use that version or a more recent one. It is also necessary to have the Mapping Toolbox installed.

Due to the large amount of data handled during the application's execution, it is essential for the computer to have at least 16 GB of RAM, preferably 32 GB or more. Sufficient storage space is also required for the download of terrain elevation files. When using the online version of MATLAB, it must be verified that the license allows the loading of large files.

The necessary files to run the application are in the repository and should be stored in the same manner with the same names. The application file “CoastlinePrediction.mlapp”, along with the other files and subfolders, must be in the same folder.


# Demo
Add a video or animated gif/picture to showcase the code in operation.

# Reference
Add reference papers, data, or supporting material that has been used, if any.
