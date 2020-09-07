# Flood Markup Language (FloodML)

## Introduction
The idea of Flood Markup language (FloodML) materialized to standardize all the streamflow and flood related data and make it easier to share with others. As is stated in the recent reports, predesigned language may help to minimize the human error and improve the flood-related information access, preparedness, and response for both public and decision makers, and modeling studies for researchers.

FloodML data include the metadata such as issued organization, event time and waterbody locations. It also includes water data such as water stage and flow rate from both historical observations and model output predictions. Thus, the FloodML can be used to spread through both researchers and the public. In addition, FloodML includes flood alerts data, which can be issued automatically when the model outputs are higher than the flooding alert levels. Related instructions and follow up media broadcast can be released together with the alert as well. It is supported with multiple formats (xml, sql, json). Here is the schema:
![schema](/schema/schema_database_v1.0.jpg)

This repository provides the flood markup language use cases that is presented in the following publication:
Zhongrun Xiang, Ibrahim Demir. (2020). Flood Markup Language – A Standards-based Language for Flood Data Exchange. TBD.

## Use Cases and Visualization
FloodML can be visualized directly through mobile application, which is more efficient than compressing and transferring an image. The geolocation of station from metadata and affected area from alerts in the FloodML can be visualized on the map as well as shown below.

![vis1](/visualization/multiple_forecasts/vis_multiple_forecasts.jpg)
http://iihr-vl01.iihr.uiowa.edu/dev/zhongrun/vis_forecast_with_map.html

![vis2](/visualization/forecast_with_map/vis_forecast_with_map.jpg)
http://iihr-vl01.iihr.uiowa.edu/dev/zhongrun/vis_multi_forecast.html

## Citation
If you use the specification or flood event inventory please cite the following publication:
Zhongrun Xiang, Ibrahim Demir. (2020). Flood Markup Language – A Standards-based Language for Flood Data Exchange. TBD.

## Feedback
Feedbacks are always welcomed to improve this new markup language.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
This project is developed by the University of Iowa Hydroinformatics Lab (UIHI Lab):
https://hydroinformatics.uiowa.edu/.
