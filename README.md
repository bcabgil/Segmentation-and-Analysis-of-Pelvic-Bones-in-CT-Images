# Segmentation and Analysis of Pelvic Bones in CT_Images

Authors: Federica Aresu & Blanca Cabrera Gil

## Description

The procedure to perform multi-atlas-based segmentation to obtain the segmentation of hip bones as well as image classification are presented. Affine linear registration and b-splines Free Form Deformation are used as registration methods. K-Nearest Neighbor is selected as classifier to detect the location of pubic symphysis.
This project has been developed in the scope of the subject HL2027 3D Image Reconstruction and Analysis in Medicine from KTH.

## Sections

1. Segmentation: Performed with MiaLab tool following the segrmentation workflow. The executer file can be found in the MiaLab.zip.
2. Registration: Multi-method registration using SimpleElastix library. To download refere to this site (https://simpleelastix.readthedocs.io/GettingStarted.html). The procedure performs firstly a linear affine registration, secondly a non-linear b-splines Free Form Deformation is applied. The metric used during the registration is Mutual Information.
3. Atlas-Based Segmentation: Majority voting is used to perform the multi-atlas-based segmentation.
4. Image Analysis: SimpleITK is used to build a K-Nearest Neighbor Classifier to detect the slices which contain the pubic symphysis.


The document report and results can be found in Group12-Report.pdf file.