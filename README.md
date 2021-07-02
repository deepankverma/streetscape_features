# Identifying streetscape features from VHR imagery and DL methods

This repository contains scripts and trained DL models for identification of various streetscape features from VHR imagery.

### DL Models used:
* Object Detection with RetinaNet
* Semantic Segmentation with D-LinkNet34

### Streetscape features identified:
* Movement Corridor (Segmentation)
* Roadway (Segmentation)
* Sidewalk (Segmentation)
* On-street parking (Segmentation)
* Bikepath (Segmentation)
* Trees (Object Detection)
* Vehicles (Object Detection)
* Road Markings (Segmentation)

#### Trained weights can be downloaded from [Google Drive](https://drive.google.com/drive/folders/1R7_c6YbYJ_XLjl0N_vgnWnPl-R7IPH_P?usp=sharing).

### Google Colab starter notebook would be added in a short while. Meanwhile these weights can be used with the following projects to identify abovementioned streetscape features:
* [D-LinkNet34](https://github.com/zlckanata/DeepGlobe-Road-Extraction-Challenge)
* [RetinaNet](https://github.com/weecology/DeepForest)
