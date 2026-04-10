# Flood Prediction and Alert System

## Description

An IoT-based system designed to predict flood conditions using real-time environmental data. The system collects sensor inputs such as humidity, rainfall, water level, air pressure, and temperature, and processes them using a machine learning model to generate flood predictions and alerts.

## System Interface


<img width="1619" height="904" alt="image" src="https://github.com/user-attachments/assets/ef248beb-b684-449c-96ab-8df66a507fd3" />

## Idea Behind the Project

The main idea of this project is to develop an intelligent flood prediction system that can analyze multiple environmental parameters in real time. By combining IoT-based data collection with machine learning, the system helps in early detection of potential flood conditions.

The user interface allows input of key parameters such as humidity, rainfall level, water level, air pressure, and temperature. These inputs are processed by the backend model to predict the likelihood of flooding and support early warning decisions.

This system can be further extended for real-world deployment by integrating live sensor data and automated alert mechanisms.



## Tech Stack

* Python
* IoT Sensors
* Machine Learning

## Features

* Real-time environmental data collection
* Flood prediction using machine learning models
* Early warning alert system

## How It Works

1. Sensors collect environmental data such as water level and rainfall
2. Data is transmitted through an IoT module
3. Machine learning model processes the data
4. System predicts flood conditions and generates alerts

## My Contribution

* Built machine learning model for flood prediction
* Designed data collection and processing pipeline
* Implemented alert generation mechanism

## Project Structure

flood-prediction-iot/
│── src/
│   ├── main.py
│   ├── model.py
│   ├── data_processing.py
│── data/
│── images/
│── README.md

## How to Run

python src/main.py

## Status

Completed (2025)

## Future Improvements

* Improve prediction accuracy with larger datasets
* Add real-time visualization dashboard
* Integrate mobile notification system
