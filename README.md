# LENet
LENet(Localizability Estimation) is a method that estimates localizability using deep learning model. Specifically, the method estimates localization error from 3DLiDAR point cloud data and Map point cloud. In this method, firstly obtaining localization error and 3DLiDAR point cloud data and Map point cloud are conducted. AWSIM(the autonomous vehicle simulator) was used. After that, feature of point cloud data was captured by MinkLoc3D-SI and MinkLoc3D. This time we have already made a dataset and you can download it. Lastly deep learning model estimates the localizability from extracted feature vector. 

[slide](https://docs.google.com/presentation/d/1vMgdlAEvBwDfVt9v45OYaq9gnzyPmK90/edit?usp=sharing&ouid=116487337898901321934&rtpof=true&sd=true)

[paper](https://drive.google.com/file/d/108T9ID0mWuxmlshyQW3xdMoeSP7xW9p8/view?usp=sharing)

## Dataset
You can download dataset from this [link](https://drive.google.com/file/d/17B2oQuUgeu1w3CNZS-dBDrT7RX5kGYmv/view?usp=sharing)

## Methods
There are three .ipynb file.
- DLmodel.ipynb
  - Estimate localizability from 3DLiDAR point cloud data.
- DLmodel_map.ipynb
  - Estimate localizability from Map point cloud 
- DLmodel_map_lidar.ipynb
  - Estimate localizability from both 3DLiDAR point cloud data and Map point cloud

## Model
For DLmodel_map_lidar.ipynb there is a learned model. 

## RUN
Run the .ipynb file using google colab.
Please do not forget to set the path of the dataset.

