# ufpr-map

![Points on Google Earth | VRI4WD UFPR-MAP Dataset](https://github.com/VRI-UFPR/ufpr-map/blob/main/points_googleEarth_vri4wd_ufpr-map_2023.png)

VRI4WD UFPR-MAP DATASET

This work contributed to creating a dataset with coordinates of points obtained by geodetic and topographic methods for using this data to validate the positioning obtained through autonomous wheeled mobile robots.

## dataset

Indoor A to B | [dataset\_vri4wd\_ufpr-map\_20230830s001ab.bag](https://ufprbr0-my.sharepoint.com/:u:/g/personal/vrilab_ufpr_br/Eco5U3yqVSRHg_J4jI-OL-UBGIADWMPkpIpNDOUW4X2cpw?e=CTX3q3) - Aug 30, 2023 

Outdoor B to C | [dataset\_vri4wd\_ufpr-map\_20230830s001bc.bag](https://ufprbr0-my.sharepoint.com/:u:/g/personal/vrilab_ufpr_br/EXn7qFX1JyBBlVAaHKwaCEoBcPRdI8_j8kTimWN9dbMCig?e=mZO755) - Aug 30, 2023

Outdoor C to D | [dataset\_vri4wd\_ufpr-map\_20230830s001cd.bag](https://ufprbr0-my.sharepoint.com/:u:/g/personal/vrilab_ufpr_br/EWZhqdd_r41DrgeEhgc9Gm0B88y1-ZFZZL6WmTzRL4I0Iw?e=7VSWUA) - Aug 30, 2023

Outdoor D to E | [dataset\_vri4wd\_ufpr-map\_20230901s001de.bag](https://ufprbr0-my.sharepoint.com/:u:/g/personal/vrilab_ufpr_br/EWwJ5soqGD5GqtEfcwoxpn4B0mTjUq6mFP2YslzecmvGbw?e=z8s6hp) - Sept 1, 2023

Outdoor E to B | [dataset\_vri4wd\_ufpr-map\_20230901s001eb.bag](https://ufprbr0-my.sharepoint.com/:u:/g/personal/vrilab_ufpr_br/EbdVK5aFBkRDlAV13PaHYh8B2FqlQUKcA1_MtO0k7U9t3g?e=WfzqFL) - Sept 1, 2023

Indoor B to F | [dataset\_vri4wd\_ufpr-map\_20230901s001bf.bag](https://ufprbr0-my.sharepoint.com/:u:/g/personal/vrilab_ufpr_br/Ea-mkrKv9n9ArJNv9D_LylABK1ibMV2kU4BnKKEH7Ns4bw?e=QuHQRf) - Sept 1, 2023

![Paths on Google Earth | VRI4WD UFPR-MAP Dataset](https://github.com/VRI-UFPR/ufpr-map/blob/main/path_googleEarth_vri4wd_ufpr-map_2023.png)

## sensors

ROS TOPICS

Encoder | _publisher_ **/left\_encoder**, **/right\_encoder** (std_msgs/Int16)  
Accelerometer (IMU) | _publisher_ **/imu/data** (sensor_msgs/Imu)  
Digital Compass (IMU) | _publisher_ **/imu/data** (sensor_msgs/Imu)  
GPS | _publisher_ **/gps\_neo8m** (sensor_msgs/NavSatFix)  
Gyroscope (IMU) | _publisher_ **/imu/data** (sensor_msgs/Imu)  
Infrared | _publisher_ **/ir1\_sharp**, **/ir2\_sharp**, **/ir3\_sharp** (sensor_msgs/Range)    
Ultrasound | _publisher_ **/us1\_urm**, **/us3\_urm**, **/us5\_urm** (sensor_msgs/Range)  
Vision | _publisher_ **/camera/depth/image**, **/camera/rgb/image\_color**, **/camera/rgb/image\_mono** (sensor_msgs/Image)  
Laser Scanner | _publisher_ **/scan** (sensor_msgs/LaserScan)  
RF Sensor (WLAN) | _publisher_ **/rssi1\_wlan**, **/rssi2\_wlan**, **/rssi3\_wlan**, **/rssi4\_wlan**, **/rssi5\_wlan**, **/rssi6\_wlan**, **/rssi7\_wlan**, **/rssi8\_wlan**, **/rssi9\_wlan**, **/rssi10\_wlan**, **/rssi11\_wlan**, **/rssi12\_wlan**, **/rssi13\_wlan**, **/rssi14\_wlan**, **/rssi15\_wlan**, **/rssi16\_wlan**, **/rssi17\_wlan**, **/rssi18\_wlan**, **/rssi19\_wlan** (std_msgs/Int8)
  

## rosbag

ROSbag is a set of tools for recording from and playing back to ROS topics.

$ rosbag play dataset_vri4wd_ufpr-map_20230830s001ab.bag 

## vri4wd

VRI4WD MOBILE ROBOT PLATFORM

The [VRI4WD mobile robot](https://github.com/VRI-UFPR/vri4wd) was developed to apply multi-sensors and locomotion in indoor and outdoor environments.
