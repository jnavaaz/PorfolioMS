# PorfolioMS
This is an collection of a few of the examples of coding projects that I can share publicly.
GENERAL:
   1 - All files without an extensiona are .py codes.
   2 - All .py codes are complete in one large file.
   3 - To run/test, do follow instructions and download required reference files.
   4 - Each is an example of different skills acquired but do not display the full potential of all the          work that has been achieved throughout these last few years. 
   5 - Lastly, I do hope you find potential and usefulness in these two examples.
____________________________________________________________________________________________________
1. Basic GEOSPATIAL ANALYSIS - Coords2UTM&CrossReference
   
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
_____________________________________________________________________________________________________     
2. Basic EMAIL AUTOMATION - MKTEMAILS

   All files labeled with (2.) belong to the same code. You do have to add your email, password and reference directory where the .pdf files will be in your computer. Also, in the "CONTACTOS.xlsx" you will need to add emails so the code will send them to those that you choose. The code asumes the email address or service you use is gmail and the body and data contained are just examples at this point.
   
 LIBRARIES:
   smtplib
   time
   pandas as pd
   os
   from email.mime.text import MIMEText
   from email.mime.image import MIMEImage
   from email.mime.multipart import MIMEMultipart
   from email.mime.application import MIMEApplication

   INSTRUCTIONS: 
     1) REQUISITES: RUN ON MACBOOK, PYTHON 3 AND ALL FILES.
     2) AFTER DOWNLOADING ALL REFERENCE FILES, DO MAKE THE NECCESARY CHANGES FOR IT TO RUN.
   
   
