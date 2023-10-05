# Pneumonia Detection from Chest X-Ray Images: Kaggle Contest

## Overview ##

This Kaggle contest aims to leverage machine learning and artificial intelligence to detect Pneumonia from chest X-ray images. Participants are provided with a dataset containing 5,863 X-Ray images labeled either as Pneumonia or Normal.

## Dataset ##

<p align="center">
  <img src="https://github.com/mahsaShv/Pneumonia-Detection/assets/33680001/d395f199-aec1-4443-96e2-1d0b57d4350b" width="600">
</p>

Illustrative Examples of Chest X-Rays in Patients with Pneumonia: The normal chest X-ray (left panel) depicts clear lungs without any areas of abnormal opacification in the image. Bacterial pneumonia (middle) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows), whereas viral pneumonia (right) manifests with a more diffuse ‘‘interstitial’’ pattern in both lungs. 

## Background ##

The chest X-ray images in this dataset are anterior-posterior views and were sourced from pediatric patients aged one to five years old. The data originates from the Guangzhou Women and Children’s Medical Center in Guangzhou.

As part of the data preparation:

- All chest radiographs underwent a quality control process to weed out low-quality or unreadable scans.
- Each of the images was reviewed and graded by two expert physicians to ensure accuracy in the labeling.
- To further enhance the reliability of the evaluation set, a third expert reviewed any discrepancies between the initial gradings.

## Goal ##

The primary objective of this contest is to develop a machine learning model that can accurately classify X-ray images as either "Pneumonia" or "Normal". An accurate model holds potential real-world applications in assisting healthcare professionals in diagnosing pneumonia, particularly in large-scale screenings.
