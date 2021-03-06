# DrowsinessDetection

Real-time Driver Drowsiness detection using AI and ML.

## Introduction

Driver Drowsiness is one of the leading causes of motor vehicle crashes. According to [2020 data from the WHO](https://www.who.int/news-room/fact-sheets/detail/road-traffic-injuries), road injuries resulted in approximately 1.35 million deaths per year worldwide i.e. a crash approximately every 23 seconds. </br>
And I understand the seriousness since my parents have also been a part of one such incident (p.s. they are absolutely fine). Hence, this definition is very close to me. </br>
Our aim is to make the model sustainable and accessible to the lower strata of the society, especially the truck and bus drivers. </br>
Therefore, we are presenting a novel approach towards real-time driver drowsiness detection in this project. 

## Getting started

This repository contains,
1. The **source code** for Real-time Driver Drowsiness detection 
2. **A dataset** - *Shape predictor* - most common and well known dlib's facial landmark predictor used to localize individual facial structures, including the:
      * Eyes.
      * Eyebrows.
      * Nose.
      * Lips/mouth.
      * Jawline.
3. **Waveform audio file** - to play an *alarm* to alert the driver

## Prerequisites

* Install Spyder using Anaconda
* Install the below mentioned libraries
* Basics of Neural Network and Machine Learning
* Intuitive understanding of Linear Algebra and Calculus

## Technologies used

* Language : *Python*
* Technology : *Machine Learning & Computer Vision*
* Libraries : Spyder - *scipy, dlib, imutils, openCV*
              <br/> Colab - *numpy, pandas, openCV, matplotlib, sklearn, keras*
* Model : Convolutional Neural Network based on HOG (Histogram of Oriented Gradients)

## Deployment

Under-process to deploy it live, on an application-based system using Android.

## Challenges

* Making our own dataset
* Designing a model with ~80% accuracy

## Drawbacks

* Consumes a lot of energy to capture real-time video
* The data is not stored on the system for future reference

## Future Scope and Improvements

* Implement it on an independent hardware based system say, Raspberry pie
* Make it accessible to the underpriviledged sectors of the society

## Author

*Ms. Yashvi Parikh*

## Acknowledgement

* Mr. Shyam Parmar, Mentor
* Mr. Khushil Modi, Team-mate

## Note

> This project is under process. The base working model is ready though.
> Earlier, we tried to design the model on Colab from scratch, by [developing a dataset](https://teachablemachine.withgoogle.com/) on our own to train a Sequential model. But due to lack of resources for the dataset and the denial of permission to access our laptop's webcam to capture a real-time video, we switched to working on Spyder by using dlib. 


