# Airbnb Amentity Detection Project

## Purpose

Create a predictive model that, when given an image, will identify the amenities in that room.

## Motivation

Airbnb published a Medium article outlining how they built an amenity detection model; however, they did not publish the code pertaining to this. My goal is to reconstruct their model from scratch using the article as a guide.

Airbnb Amentity Detection Article: https://medium.com/airbnb-engineering/amenity-detection-and-beyond-new-frontiers-of-computer-vision-at-airbnb-144a4441b72e

## Project Outline

The project will follow the below outline:
  - Week 1: Build web scraping application. This will scrape all the approriate images to use for training. Once this is done, build the approriate preprocessing script to process these images for model ingestion.
  - Week 2: Explore the dataset. This includes class creation, tagging (if applicable), data mugging, feature engineering, etc.
  - Week 3: Begin model building. Learn Detectron2 and play around with weights and biasis using PyTorch and understand what methods are working and what aren't.
  - Week 4: Finish model building. Finish model building and train on entire dataset with GPU (pending CBA approval).
  - Week 5: Deploy model. Deploy model in cloud environment so that anyone can access. Deploy in Docker container on Heroku using Amazon S3 as storage. Build application using Flutter.
  
 ### Model Contruction and Deployment Pipeline Flowchart Diagram

![](Airbnb%20Amenity%20Detection%20Model%20Pipeline.png?raw=true)

## Project Success Criteria

- Be accessable via web url on any device and any browser or operating system.
- Be within 5 percentage points of Airbnb's Minimum Viable Product (MVP): Mean Average Percision (mAP) of 50%.
- Publish Jupyter Notebooks containing code, via Github, for demoncranization of model.
