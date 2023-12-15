# Supervised Classification of Land Cover Types in Southern Santa Barbara County, CA


## Purpose
The purpose behind this project is to test whether or not LiDAR is a worthy tool of geospatial analysis, especially in terms of the classification of land cover. LiDAR (Light Detection and Ranging)" is a remote sensing method that uses light in the form of a pulsed laser to measure ranges (variable distances to the Earth”(americangeosciences.org). Reclassifying an image to help predict land cover type is a very useful tool to help record whether or not it changes over time.

In order to access the data, please unzip this [folder](https://drive.google.com/drive/folders/1ON8FbDqcTjg2PKHmNGgyN7odTqpOnXla?usp=sharing). 
## File structure
```
C:.
|   .gitignore
|   .Rhistory
|   eds-223-landcover-decision-tree.qmd
|   eds-223-landcover-decision-tree.Rproj
|   eds-223-rmarkdown-landcover.html
|   eds-223-rmarkdown-landcover.Rmd
|   README.md
|
+---data
|   |   SB_county_south.cpg
|   |   SB_county_south.dbf
|   |   SB_county_south.prj
|   |   SB_county_south.sbn
|   |   SB_county_south.sbx
|   |   SB_county_south.shp
|   |   SB_county_south.shx
|   |   SB_validation_points.dbf
|   |   SB_validation_points.prj
|   |   SB_validation_points.qpj
|   |   SB_validation_points.shp
|   |   SB_validation_points.shx
|   |   trainingdata.cpg
|   |   trainingdata.dbf
|   |   trainingdata.prj
|   |   trainingdata.qpj
|   |   trainingdata.shp
|   |   trainingdata.shx
|   |
|   +---landsat-data
|   |       LT05_L2SP_042036_20070925_20200829_02_T1_SR_B1.TIF
|   |       LT05_L2SP_042036_20070925_20200829_02_T1_SR_B2.TIF
|   |       LT05_L2SP_042036_20070925_20200829_02_T1_SR_B3.TIF
|   |       LT05_L2SP_042036_20070925_20200829_02_T1_SR_B4.TIF
|   |       LT05_L2SP_042036_20070925_20200829_02_T1_SR_B5.TIF
|   |       LT05_L2SP_042036_20070925_20200829_02_T1_SR_B7.TIF
|   |
|   \---__MACOSX
|       |   ._SB_county_south.cpg
|       |   ._SB_county_south.dbf
|       |   ._SB_county_south.prj
|       |   ._SB_county_south.sbn
|       |   ._SB_county_south.sbx
|       |   ._SB_county_south.shp
|       |   ._SB_county_south.shx
|       |   ._SB_validation_points.dbf
|       |   ._SB_validation_points.prj
|       |   ._SB_validation_points.qpj
|       |   ._SB_validation_points.shp
|       |   ._SB_validation_points.shx
|       |   ._trainingdata.cpg
|       |   ._trainingdata.dbf
|       |   ._trainingdata.prj
|       |   ._trainingdata.qpj
|       |   ._trainingdata.shp
|       |   ._trainingdata.shx
|       |
|       \---landsat-data
|               ._LT05_L2SP_042036_20070925_20200829_02_T1_SR_B1.TIF
|               ._LT05_L2SP_042036_20070925_20200829_02_T1_SR_B2.TIF
|               ._LT05_L2SP_042036_20070925_20200829_02_T1_SR_B3.TIF
|               ._LT05_L2SP_042036_20070925_20200829_02_T1_SR_B4.TIF
|               ._LT05_L2SP_042036_20070925_20200829_02_T1_SR_B5.TIF
|               ._LT05_L2SP_042036_20070925_20200829_02_T1_SR_B7.TIF
|
\---eds-223-rmarkdown-landcover_files
    +---figure-html
    |       unnamed-chunk-2-1.png
    |       unnamed-chunk-4-1.png
    |       unnamed-chunk-6-1.png
    |       unnamed-chunk-8-1.png
    |
    \---libs
        +---bootstrap
        |       bootstrap-icons.css
        |       bootstrap-icons.woff
        |       bootstrap.min.css
        |       bootstrap.min.js
        |
        +---clipboard
        |       clipboard.min.js
        |
        \---quarto-html
                anchor.min.js
                popper.min.js
                quarto-syntax-highlighting.css
                quarto.js
                tippy.css
                tippy.umd.min.js

```
### Finished product

![image](https://github.com/mariamkg00/eds-223-landcover-decision-tree/assets/105567684/c1995c9d-40b6-4728-9903-5adce0b6419c)
