# ufpr-map

![Points on Google Earth | VRI4WD UFPR-MAP Dataset](https://github.com/VRI-UFPR/ufpr-map/blob/main/points_googleEarth_vri4wd_ufpr-map_2023.png)

VRI4WD UFPR-MAP DATASET

This work contributed to creating a dataset with coordinates of points obtained by geodetic and topographic methods for using this data to validate the positioning obtained through autonomous wheeled mobile robots.

## dataset

Indoor A to B | [dataset\_vri4wd\_ufpr-map\_20230830s001ab.bag](https://ufprbr0-my.sharepoint.com/:u:/r/personal/vrilab_ufpr_br/Documents/dataset_vri4wd_ufpr-map/dataset_vri4wd_ufpr-map_20230830s001ab.bag) - Aug 30, 2023 

Outdoor B to C | [dataset\_vri4wd\_ufpr-map\_20230830s001bc.bag](https://ufprbr0-my.sharepoint.com/:u:/r/personal/vrilab_ufpr_br/Documents/dataset_vri4wd_ufpr-map/dataset_vri4wd_ufpr-map_20230830s001bc.bag) - Aug 30, 2023

Outdoor C to D | [dataset\_vri4wd\_ufpr-map\_20230830s001cd.bag](https://ufprbr0-my.sharepoint.com/:u:/r/personal/vrilab_ufpr_br/Documents/dataset_vri4wd_ufpr-map/dataset_vri4wd_ufpr-map_20230830s001cd.bag) - Aug 30, 2023

Outdoor D to E | [dataset\_vri4wd\_ufpr-map\_20230901s001de.bag](https://ufprbr0-my.sharepoint.com/:u:/r/personal/vrilab_ufpr_br/Documents/dataset_vri4wd_ufpr-map/dataset_vri4wd_ufpr-map_20230901s001de.bag) - Sept 1, 2023

Outdoor E to B | [dataset\_vri4wd\_ufpr-map\_20230901s001eb.bag](https://ufprbr0-my.sharepoint.com/:u:/r/personal/vrilab_ufpr_br/Documents/dataset_vri4wd_ufpr-map/dataset_vri4wd_ufpr-map_20230901s001eb.bag) - Sept 1, 2023

Indoor B to F | [dataset\_vri4wd\_ufpr-map\_20230901s001bf.bag](https://ufprbr0-my.sharepoint.com/:u:/r/personal/vrilab_ufpr_br/Documents/dataset_vri4wd_ufpr-map/dataset_vri4wd_ufpr-map_20230901s001bf.bag) - Sept 1, 2023

![Paths on Google Earth | VRI4WD UFPR-MAP Dataset](https://github.com/VRI-UFPR/ufpr-map/blob/main/path_googleEarth_vri4wd_ufpr-map_2023.png)

## sensors

ROS TOPICS

Encoder | _publisher_ **/left\_encoder**, **/right\_encoder**  
Accelerometer (IMU) | _publisher_ **/imu/data**  
Digital Compass (IMU) | _publisher_ **/imu/data**  
GPS | _publisher_ **/gps\_neo8m**  
Gyroscope (IMU) | _publisher_ **/imu/data**  
Infrared | _publisher_ **/ir1\_sharp**, **/ir2\_sharp**, **/ir3\_sharp**    
Ultrasound | _publisher_ **/us1\_urm**, **/us3\_urm**, **/us5\_urm**  
Vision | _publisher_ **/camera/depth/image**, **/camera/rgb/image\_color**, **/camera/rgb/image\_mono**  
Laser Scanner | _publisher_ **/scan**  
RF Sensor (WLAN) | _publisher_ **/rssi1\_wlan**, **/rssi2\_wlan**, **/rssi3\_wlan**, **/rssi4\_wlan**, **/rssi5\_wlan**, **/rssi6\_wlan**, **/rssi7\_wlan**, **/rssi8\_wlan**, **/rssi9\_wlan**, **/rssi10\_wlan**, **/rssi11\_wlan**, **/rssi12\_wlan**, **/rssi13\_wlan**, **/rssi14\_wlan**, **/rssi15\_wlan**, **/rssi16\_wlan**, **/rssi17\_wlan**, **/rssi18\_wlan**, **/rssi19\_wlan**  

## vri4wd

VRI4WD MOBILE ROBOT PLATFORM

The [VRI4WD mobile robot](https://github.com/VRI-UFPR/vri4wd) was developed to apply multi-sensors and locomotion in indoor and outdoor environments.
