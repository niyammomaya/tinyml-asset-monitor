# TinyML Asset Health Monitoring System

## Overview

An end-to-end Edge AI platform that simulates IoT sensor telemetry, detects anomalies using machine learning, and explores TinyML deployment for resource-constrained devices.

This project demonstrates the complete lifecycle of an intelligent monitoring system, from data generation and ingestion to anomaly detection, visualization, and edge deployment.

---

## Motivation

Industrial assets, warehouse equipment, and logistics systems continuously generate sensor data such as:

* Temperature
* Humidity
* Vibration
* Battery Health

Unexpected deviations in these signals may indicate equipment failures, tampering, or maintenance issues.

This project aims to proactively detect such anomalies using machine learning before failures occur.

---

## Features

* Synthetic IoT sensor telemetry generation
* Realistic anomaly injection
* Data storage and management
* Machine learning-based anomaly detection
* Asset health scoring
* Monitoring dashboard
* TinyML model optimization and deployment workflow

---

## Tech Stack

### Machine Learning

* PyTorch
* Scikit-Learn
* ONNX
* TensorFlow Lite

### Backend

* FastAPI
* PostgreSQL

### Data Processing

* Pandas
* NumPy

### Deployment

* Docker

### Visualization

* Streamlit

---

## System Architecture

Sensor Simulator
↓
FastAPI Backend
↓
PostgreSQL
↓
ML Anomaly Detection
↓
Dashboard & Alerts
↓
TinyML Deployment

---

## Project Roadmap

### Phase 1

* Sensor telemetry simulation
* Synthetic anomaly generation

### Phase 2

* FastAPI backend
* PostgreSQL integration

### Phase 3

* Dashboard and visualization

### Phase 4

* Anomaly detection models

### Phase 5

* TinyML optimization
* ONNX/TFLite deployment

---

## Learning Goals

* Build a production-style ML system
* Understand anomaly detection workflows
* Explore edge AI deployment
* Learn TinyML optimization techniques
* Combine embedded systems, machine learning, and software engineering

---

## Status

🚧 In Development
