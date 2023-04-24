# Glacial_Lakes_Outlines_JOB_2016_2021
Glacier Lake Outlines (GLO) for 51 lakes around Jostedalsbreen Ice Cap, Norway were mapped from 2016-2021 in each melting season (July-November) with a frequency of 1 image per month.
Lakes from sorrounding glaciers were also included for the analysis. The lakes included in this product are either directly connected to the glacier outline or are at close proximity to the glacier. 

Semi-automatic Classification method by calculating the Normalized Difference Water Index (NDWI) given in a NVE report (Nagy and Andreassen, 2019) was followed for mapping the lakes outlines.
Imageries from Sentinel 2 were used primarily for calculating NDWI and mapping the lake outlines to create seasonal and annual timeseries data of areal lake extent, but the gaps in the
data series were filled up, as much as possible, by using imageries from PlanetScope to optimize the number of useable images in the timeseries. Thus, the following methods were used for NDWI calculation.

In general:
NDWI: (Green – NIR)/(Green + NIR)

For Sentinel 2:
NDWI = (band3-band8)/(band3+band8)

For Planetscope:
NDWI = (band2-band4)/(band2+band4)

Further, a threshold NDWI value which best represents the area of lakes and reduces the need for digitization was obtained with reference to manually digitized high
resolution ortho-imagery of same lakes in Jostedalsbreen region. However, manual digitization was performed where the selected threshold NDWI value fails to represent the water bodies correctly. 
Often, this happened at lake-water and glacier-ice interface. More detail on data processing is provided in the Master's Thesis entitled "Monitoring glacial lakes and outburst floods around 
Jostedalsbreen ice cap" (Pariyar, 2022).

For the basic purpose of this study, lakes were broadly classified into two categories, (1) connected-to-glacier and (2) not-connected-to-glacier with slight modification
in classification followed in the report by NVE (Nagy & Andreassen, 2019). Simply, the lakes which are connected to the glacier are assigned to lake type connected-to-glacier 
and those which are not in direct contact with the glacier and reside at certain distance but very close to the glacier are assigned to lake type not-connected-to-glacier. There were few lakes in special categories 
which actually fall within lake type connected-to-glacier, viz; glacier-dammed (2), moraine-dammed (clearly identifiable in orthoimagery) (1), artificial-water-level-regulation (2), and supraglacial (1). 
These lakes were analysed as seperate groups, details of which are provided in the Master's Thesis entitled "Monitoring glacial lakes and outburst floods around Jostedalsbreen ice cap" (Pariyar, 2022).

Images acquired for each lake were subjectively explored while processing and assigned to different types. Those lakes which happened to change their type 
(for instant, from lake type connected-to-glacier to not-connected-to-glacier) during 6 years’ time-period were keenly observed and assigned to certain type where they appeared to 
in most of the images.

The preliminary information on glacier lakes and associated glaciers were obtained from the report by NVE (Nagy and Andreassen, 2019).The orthophoto used as background image for thresholding was 
obtained from norgeibilder.no. The false colour composite images of both Sentinel 2 and PlanetScope were used as reference for manual digitization to enhance the water feature for better visibility. 

The lake outlines generated in this study were compared with outlines generated in the inventory by NVE in 2018 (Nagy and Andreassen, 2019) and with its updated version 
in 2019 (Andreassen et al., 2022) to test for data accuracy.

The coordinate system assigned for this product is ETRS_1989_UTM_Zone_32N.


Reference and citation:
-----------------------
Andreassen, L.M., T. Nagy, B. Kjøllmoen and J.R. Leigh. 2022
An inventory of Norway’s glaciers and ice-marginal lakes from 2018–19 Sentinel-2 data.
Journal of Glaciology, 1–22. https://doi.org/10.1017/jog.2022.20

Nagy, T., and L.M. Andreassen. 2019. 
Glacier lake outline mapping with Sentinel-2 imagery in Norway. 
NVE Report 40-2019, 54s.
http://publikasjoner.nve.no/rapport/2019/rapport2019_40.pdf

Pariyar, M. (2022). “Monitoring glacial lakes and outburst floods around Jostedalsbreen ice cap, Norway”


When using the GLO_JOB_2016_2021 data in publications, please cite Pariyar, 2022
When using the GLO_JOB_2016_2021 data in presentations, please cite Data: NVE/Copernicus Glacier Service Norway.
