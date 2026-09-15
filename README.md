# 🌱 AI Footprint

> A web-based AI footprint calculator that estimates the environmental impact of everyday AI usage.

🌐 **Live Demo:** https://ai-foot-print-calculator.web.app/



##  Overview

AI Footprint is a lightweight web application designed to help users understand the potential environmental impact associated with their AI usage.

Users enter the number of **text and image prompts** they use, and the application provides estimates for:

- ⚡ Energy consumption
- 🌍 Carbon emissions
- 💧 Water usage
- 📊 Estimated impact level
- 📈 Previous calculation history

The project turns an abstract concept — the environmental cost of AI usage — into simple and understandable metrics.

---

## Problem Statement

The increasing use of Generative AI involves computational resources that consume energy and contribute to environmental impact.

However, users often have little awareness of how their everyday AI usage can translate into resource consumption.

AI Footprint aims to provide a simple and accessible way for users to estimate the potential environmental impact associated with their AI activity.

---

## Objective

The main objectives of AI Footprint are:

- Allow users to enter their daily AI activity.
- Estimate energy consumption from text and image prompts.
- Calculate estimated carbon emissions.
- Calculate estimated water usage.
- Provide an easy-to-understand impact analysis.
- Maintain a history of previous calculations.
- Provide a local user profile and dashboard.
- Present environmental metrics through a simple and user-friendly interface.

---

##  Key Features

### ⚡ AI Footprint Calculator

Users can enter their daily number of text and image prompts to calculate their estimated environmental footprint.

### 🌱 Environmental Metrics

The application estimates:

- Energy consumption
- Carbon emissions
- Water usage

### 📊 Impact Analysis

The estimated energy usage is categorized into:

- Low
- Medium
- High

These categories use project-defined thresholds to provide an easy-to-understand interpretation of the estimated usage.

### 👤 Local User Profile

Users can create a local profile using their name.

The profile is stored in the browser using `LocalStorage`.

### 📈 Calculation History

Previous footprint calculations are stored locally and displayed through the dashboard.

### 📊 Dashboard

The dashboard provides an overview of previous calculations and activity history.

### 🔥 Live Deployment

The application is deployed using Firebase Hosting and is accessible online.

---
## Calculation Methodology

AI Footprint uses a simplified project-level estimation model to demonstrate the potential environmental impact of AI usage.

Energy Estimation
Energy = (Text Prompts × 0.002) + (Image Prompts × 0.02)

Carbon Emissions
Carbon Emissions = Energy × 0.5

Water Usage
Water Usage = Energy × 1.8

These values are used as simplified estimation factors for this project and are intended to provide an approximate representation rather than exact real-world measurements.

## Actual AI environmental impact can vary depending on factors such as:

AI model architecture
Hardware used
Data-center efficiency
Location
Electricity sources
Workload and usage patterns

## Data Handling

AI Footprint uses browser LocalStorage for storing:
                                                    User profile information
                                                    Current calculation results
                                                    Calculation history

No external database is currently used for storing user calculation data.

Firebase is used for hosting and deployment of the web application.

This keeps the application lightweight and demonstrates client-side data persistence without requiring a backend database.

##What I Learned

##Building AI Footprint helped me strengthen my understanding of:

Frontend development using HTML, CSS, and JavaScript
Client-side state and data persistence using LocalStorage
Designing a multi-page web application
Implementing calculation logic from defined assumptions
Building responsive and user-friendly interfaces
Deploying a web application using Firebase Hosting
Using Git and GitHub for version control
Testing and debugging a deployed web application
Understanding how AI usage can be represented through environmental metrics
Clearly communicating technical assumptions and project limitations

## How It Works

```text
User Input
    ↓
Text & Image Prompt Counts
    ↓
Energy Estimation
    ↓
Carbon & Water Estimation
    ↓
Results Dashboard
    ↓
Impact Analysis
    ↓
Local Calculation History


