# ADS-599-Capstone
University of San Diego MS ADS 599: Capstone Project for Jeremiah Fa'atiliga, Ravita Kartawinata, and Sowmiya Kanmani Maruthavanan (Fall 2024)

## Project Title
Damage Assessment from Catastrophic Natural Events Using Satellite Imagery

## Project Status
Complete

## Installation
To use, install, run, or edit this project on your machine, follow these steps:

git init  
git clone https://github.com/jeremiahf24/ADS-Capstone.git

## Project Intro/Objective
In order for key partners and government agencies to effectively implement a humanitarian response in regards to the aftermath of natural disasters, they would require accurate damage assessments. This project seeks to leverage the application of advanced machine learning techniques in order to utilize high-resolution satellite images in order to identify proper impact reports. Automating the analysis of satellite data, one aims to enhance and provide situational awareness for first responders. This definitively allows for proper resource allocation to the areas most impacted. Integration of these techniques with satellite imagery can optimize disaster response operations, ultimately accelerating recovery efforts and saving lives.

## Partner(s)/Contributor(s)  
*	Jeremiah Fa'atiliga
*	Ravita Kartawinata 
*	Sowmiya Kanmani Maruthavanan

## Methods Used
*	Programming
*	Data Engineering
*	Data Mining 
*	Data Visualization
*	Exploratory Data Analysis
*	Predictive Modeling 
*	Machine Learning
*	Image Segmentation
*	Image Analysis
*	Neural Networks


## Technologies
A few examples are:
*	Python
*	Pre and Post Satellite Imagery
*	Keras Library


## Project Description
This project is utilizing the xView2 dataset, which is specifically designed for natural disaster damage assessments. Currently, this dataset comprises of 2,438 JSON files. Each image is either a pre or post damage visual for the affected areas. Additionally, an important thing to note is that all the images, JSON files, and models are unable to be uploaded to GitHub due to size limitation. However, JSON and Images data currently were temporary downloaded to an S3 bucket. The modeling section of the code includes comments to guide users in training their own models. This project applies image segmentation and classification techniques to identify building locations and assess damage levels, leveraging the Keras library to develop models that predict the severity of damage for each building. The main question, however, for this image driven initiative is which type of damages are most prevelant in the impacted areas? What is the severity of the damage correlated with the type of disaster and or categorical level of hurricanes?


## License
This project is licensed under the MIT License. Please refer to the LICENSE file in the project folder for more details.

## Acknowledgments
We would like to express our sincere appreciation to our instructors and fellow cohort members in the ADS-599 course for their consistent guidance and support. Special thanks to the previously mentioned partners and data providers for their invaluable resources, which ultimately brought this project to fruition.
