# Digital-Forestry-Toolbox
A collection of digital forestry tools for Matlab.


## Scripts

#### Input/Output

| Function        | Description                                                       | 
| --------------- | ----------------------------------------------------------------- | 
| *LASread.m*     | Read 3D point cloud from ASPRS LAS (1.0-1.4) file (.las)          | 
| *LASwrite.m*    | Write 3D point cloud to ASPRS LAS (1.0-1.4) file (.las)           | 
| *HDRread.m*     | Read ENVI header file (.hdr)                                      | 
| *SBETread.m*    | Read Applanix SBET trajectory file (.sbet)                        | 
| *TRJread.m*     | Read Terrascan TRJ trajectory file (.trj)                         | 

#### Basic

| Function         | Description                                                       | 
| ---------------- | ----------------------------------------------------------------- | 
| *LASclip.m*      | Clip 3D point cloud (LAS file) with a polygon               | 
| *LASextent.m*    | Extract spatial extent of 3D point clouds (LAS files) and write result to ESRI shapefile (.shp)| 
| *crossSection.m* | Extract a 2D cross-section from a 3D point cloud| 

#### Grids

| Function        | Description                                                       | 
| --------------- | ----------------------------------------------------------------- | 
| *rasterize.m*   | Convert a 3D point cloud to a 2D/3D raster                        | 


## Data

#### Airborne Laser Scanning

| File                      | Location                                                          | Sensor       |
| ------------------------- | ----------------------------------------------------------------- | ------------ |
| *zh_6995_2710.las*        |  Zürich, Switzerland (47.58384 N, 8.76594 E), [see map][1]        | Trimble AX60 |


[1]: https://map.geo.admin.ch/?topic=ech&lang=fr&bgLayer=ch.swisstopo.swissimage&layers=ch.swisstopo.zeitreihen,ch.bfs.gebaeude_wohnungs_register,ch.bafu.wrz-wildruhezonen_portal,ch.swisstopo.swisstlm3d-wanderwege&layers_visibility=false,false,false,false&layers_timestamp=18641231,,,&X=271212&Y=699817&zoom=10&crosshair=marker                                           
