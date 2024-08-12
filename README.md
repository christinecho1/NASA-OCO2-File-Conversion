# NASA-OCO2-File-Conversion

NASA's OCO-2 Satellite data is stored in HDF5 files, which aren't readable in QGIS (geographic information system software used by NASA). This function takes the needed data in the HDF5 file and stores it in a CSV. The CSV file then can be inputted into QGIS, and thus, read and analyzed. I wanted to observe carbon dioxide aerosol content in specific locations, so I used the parameters xco2 (column-averaged of carbon dioxide in the atmosphere, represented in parts per million (ppm)), longitude and latittude (for location), and xco2_quality_flag (indicates the quality of the retrieved CO2 data). 
