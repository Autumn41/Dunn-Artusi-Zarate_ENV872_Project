
## Summary 

The data contains gage height data from the USGS streamflow gage sites 02111000 (Yadkin River at Patterson, NC), 03446000 (Mills River Near Mills River, NC), and 03447687 (French Broad River Near Fletcher, NC). 

## Data information

Data were collected from the U.S. Geological Survey's Water Data website. More information can be found here: https://waterdata.usgs.gov/nwis

The steps to collect the data were the following: 
* From the homepage (https://waterdata.usgs.gov/nwis) select Surface Water
* Historical Observations (select the box)
* State/Territory (check box) and submit
* Select North Carolina from the State/Territory options box 
* Select gage height from Water Level/Flow Parameters (check boxes)
* Select Choose Site on a Map from Choose Output Format
* Begin date: 2000-01-01 (begin date)
* End date: 2020-12-01 (end date)
* Tab separated (radio button)

Refer to the following link where all the selections have been made:
https://maps.waterdata.usgs.gov/mapper/nwisquery.html?URL=https://waterdata.usgs.gov/nc/nwis/current?type=qw&group_key=huc_cd&format=sitefile_output&sitefile_output_format=xml&column_name=agency_cd&column_name=site_no&column_name=station_nm&column_name=site_tp_cd&column_name=dec_lat_va&column_name=dec_long_va&column_name=agency_use_cd

Data were saved in two formats: .rds and .csv.
rds file was saved as `Yadkin.rds`.
rds file was saved as `Mills.rds`.
rds file was saved as `FrenchBroad.rds`.
csv file was saved as `Yadkin.csv`. 
csv file was saved as `Mills.csv`. 
csv file was saved as `FrenchBroad.csv`. 

Data were accessed 2021-04-26. 

## Data Content Information

agency_cd: the name of the institution that collected the data. 
site_no: the number of the site where the data was collected. 
GH: gage height (feet). 

## Additional information

File-format description:  https://help.waterdata.usgs.gov/faq/about-tab-delimited-output

