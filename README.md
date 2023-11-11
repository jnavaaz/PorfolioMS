# PorfolioMS
This is an collection of a few of the examples of coding projects that I can share publicly.

1. Coords2UTM&CrossReference
   
  Both files labeled with (1.) belong to the same code. The complete .py code can be found in: 1.Coords2UTM&CrossReference and the reference Excel document 1. 0.WGS84 standard. The only other file required to run this code can be found in: https://stridata-si.opendata.arcgis.com/datasets/panama-corregimientos-boundaries-2022/explore?location=9.099774%2C-79.677617%2C8.30. I did try to upload it but it was too large.
  
   LIBRARIES:
    pandas as pd
    os
    utm
    numpy as np
    json
    from shapely.geometry import shape, Point

   INSTRUCTIONS: 
     1) REQUISITES: RUN ON MACBOOK, PYTHON 3 AND BOTH FILES: XLSX & JSON.
     2) AFTER DOWNLOADING BOTH REFERENCE FILES THEY SHOULD BE IN THE SAME DIRECTORY AS THE .PY FILE.
