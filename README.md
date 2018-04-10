### CIL_Public_Data_JSON
This repository contains all CIL public annotation metadata in the JSON format.

##### The JSON Mapping file
https://github.com/slash-segmentation/CIL_Public_Data_JSON/blob/master/Version8_6/MAPPING/mapping.json

##### The CIL annotation metadata
https://github.com/slash-segmentation/CIL_Public_Data_JSON/tree/master/Version8_6/DATA/CIL_PUBLIC_DATA

##### How to download our data
Let's take CIL_10725 as an example.

If $json->CIL_CCDB->Data_type->Video is set to be TRUE, then you can download the following files:
```
https://cildata.crbs.ucsd.edu/media/videos/10725/10725.jpg
https://cildata.crbs.ucsd.edu/media/videos/10725/10725.flv
https://cildata.crbs.ucsd.edu/media/videos/10725/10725.zip
```

Otherwise, download the following files instead:
```
https://cildata.crbs.ucsd.edu/media/images/13007/13007.jpg
https://cildata.crbs.ucsd.edu/media/images/13007/13007.tif
https://cildata.crbs.ucsd.edu/media/images/13007/13007.zip
```

There are alternative or supplemental files. You should check whether
 $json->CIL_CCDB->CIL->Alternative_image_files object exists. If so,
 You should take value from $json->CIL_CCDB->CIL->Alternative_image_files->URL_postfix
 and add "https://cildata.crbs.ucsd.edu" as the prefix.
 
Take CIL_45701 as an example,
 
 https://cildata.crbs.ucsd.edu/broad_data/plate_20585/BBBC022_v1_images_20585w1.zip






