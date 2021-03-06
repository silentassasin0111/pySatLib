# Satellite Data Handling Library
### Sentinel2 Data 
https://theia.cnes.fr/atdistrib/rocket/
### Landsat Data   
https://earthexplorer.usgs.gov/
# Bangladesh Shapefile
https://gadm.org/download_country_v3.html
# python - 3.6.7 
## Dependancy Check -- 
    Install --GDAL,basemap,termcolor
#### For BaseMap
    Install -pyproj==1.9.3
# Useage -- Data Extraction -- extractor.py
    usage: extractor.py [-h] source target satellite

    Data Extraction from compressed data files.

    positional arguments:  
    source      /path/to/compressed/data
    target      /desired/path/for/uncommpressing/the/data
    satellite       Satellite Name: Landsat / Sentinel2

    optional arguments:
    -h, --help  show this help message and exit

# Useage --Area Mask Creation -- genAreaMask.py  

    usage: genAreaMask.py [-h] shp_path ref_tif_path mask_path identifier  

    Mask Creation from shape file and Geotiff  

    positional arguments:  
    shp_path      /path/to/shape/file.shp  
    ref_tif_path  /path/to/geotiff/file.tif  
    mask_path     /path/to/save/mask.tif  
    identifier    location identifier  

    optional arguments:  
    -h, --help    show this help message and exit  

# Useage --Forest Mask Creation -- genForestMask.py 
    usage: genForestMask.py [-h] water_mask_path area_mask_path mask_path identifier  

    Forest Mask Creation from WaterMask And Area Mask  

    positional arguments:  
    water_mask_path  /path/to/water_mask/file.tif  
    area_mask_path   /path/to/area_mask/file.tif  
    mask_path        /path/to/save/mask.tif  
    identifier       location identifier  

    optional arguments:  
    -h, --help       show this help message and exit  
# Sentinel2 Specific Scripts
    Sentinel2_genAnalytics.py  
    Sentinel2_genIndexData.py  
    Sentinel2_genWatermask.py
# SATLIB
![](/src_img/cnes.ico?raw=true)
![](/src_img/esa.ico?raw=true )
![](/src_img/cop.ico?raw=true )
![](/src_img/sen.ico?raw=true )
![](/src_img/usgs.ico?raw=true)
![](/src_img/python.ico?raw=true)
![](/src_img/gdal.ico?raw=true)
![](/src_img/buet.ico?raw=true)



