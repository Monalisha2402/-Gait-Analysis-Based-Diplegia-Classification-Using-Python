# -Gait-Analysis-Based-Diplegia-Classification-Using-Python

## Introduction

This dataset is derived from the research work "Signal Processing and Machine Learning for Diplegia Classification" and "Gait-Based Diplegia Classification Using LSMT Networks". Diplegia, a prevalent form of cerebral palsy (CP), affects the voluntary muscular system. Various classification criteria have been proposed to aid in diagnosing and managing CP.

## Data

Access the dataset [LINK](https://drive.google.com/drive/folders/1evTPpJcG0CqtR8F0_sHUo5z_yUlZOLRR).

The dataset encompasses 1139 trials obtained from 178 patients at distinct diplegia stages. 

Each .npy file encompasses a varying number of frames. For each frame, 19 markers are documented with 3D coordinates (first 3 elements) and a validation flag. If you require additional markers or medical indicators, kindly reach out via email.

The file path structure is as follows:
```
base_folder/class_label/subject_label/.npy 
```
## Utilities

The repository includes a script for .npy file extraction and a simple visualizer based on [Open3D](http://www.open3d.org/). See examples below:

<table style="width:100%">
    <tr>
        <th>
            <p align="center">
            <img src="./img/5_3.gif" alt="Example" width="75%" height="75%">
            <br>Class 0 example.
            </p>
        </th>
        <th>
            <p align="center">
            <img src="./img/34_1.gif" alt="Example" width="75%" height="75%">
            <br>Class 1 example.
            </p>
        </th>
     </tr>
 </table>

 <table style="width:100%">
    <tr>
        <th>
            <p align="center">
            <img src="./img/70_3.gif" alt="Example" width="75%" height="75%">
            <br>Class 2 example.
            </p>
        </th>
        <th>
            <p align="center">
            <img src="./img/114_1.gif" alt="Example" width="75%" height="75%">
            <br>Class 3 example.
            </p>
        </th>
     </tr>
 </table>

