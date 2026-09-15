# 🌱 AI Footprint

AI Footprint is a web-based AI footprint calculator that estimates the environmental impact of everyday AI usage. Users can enter the number of text and image prompts they use daily, and the system estimates energy consumption, carbon emissions, and water usage.

## Problem Statement

The increasing use of Generative AI involves computational resources that consume energy and contribute to environmental impact. However, users often have little awareness of how their everyday AI usage can translate into resource consumption.

AI Footprint aims to provide a simple and accessible way for users to estimate the environmental impact associated with their AI activity and understand the potential footprint of their digital usage.

## Objective

The main objectives of AI Footprint are:

- Allow users to enter their daily AI activity.
- Estimate energy consumption from text and image prompts.
- Calculate estimated carbon emissions.
- Calculate estimated water usage.
- Provide an easy-to-understand impact analysis.
- Maintain a history of previous calculations.
- Provide a user profile and dashboard.
- Present environmental metrics through a simple and user-friendly interface.

## Tools and Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript

### UI and Styling

- Tailwind CSS
- Google Fonts
- Material Symbols

### Data Storage

- Browser LocalStorage

### Deployment

- Firebase Hosting

### Version Control

- Git
- GitHub

## System Architecture

The system follows a simple input, calculation, and analysis workflow:

1. User enters the number of daily text prompts.
2. User enters the number of daily image prompts.
3. The system calculates estimated energy consumption.
4. Carbon emissions and water usage are derived from the estimated energy consumption.
5. The calculated results are stored locally in the browser.
6. The user is redirected to the results page.
7. The results page displays energy, carbon, and water metrics.
8. The impact analysis page interprets the estimated energy usage.
9. Previous calculations can be viewed through the user dashboard.

## Calculation Methodology

AI Footprint uses a simplified project-level estimation model to demonstrate the environmental impact of AI usage.

### Energy Estimation

The estimated energy consumption is calculated using:

```text
Energy =
(Text Prompts × 0.002)
+
(Image Prompts × 0.02)
```

### Carbon Emissions

```text
Carbon Emissions = Energy × 0.5
```

### Water Usage

```text
Water Usage = Energy × 1.8
```

These values are used as simplified estimation factors for the project and are intended to provide an approximate representation rather than exact real-world measurements.

## Major Functions

### AI Footprint Calculator

Users can enter their daily number of text and image prompts to calculate their estimated AI footprint.

### Energy Consumption Estimation

The system estimates energy consumption based on the type and number of AI prompts.

### Carbon Emissions Estimation

Estimated carbon emissions are calculated from the energy consumption value.

### Water Usage Estimation

The system estimates associated water usage based on the calculated energy consumption.

### Impact Analysis

The application categorizes the estimated energy impact into:

- Low
- Medium
- High

The impact page also provides contextual information to help users understand their estimated footprint.

### User Profile

Users can create a local profile and access their personal dashboard.

### Activity History

Previous footprint calculations are stored locally and displayed in the dashboard, allowing users to review their past activity.

### Dashboard

The dashboard provides an overview of the user's previous calculations and activity history.

### Local Data Storage

User information, calculation results, and activity history are stored using browser LocalStorage.

## Output

The system provides:

- Estimated energy consumption
- Estimated carbon emissions
- Estimated water usage
- Impact classification
- Previous calculation history
- User dashboard
- Easy-to-understand environmental insights

## Live Demo

[https://ai-foot-print-calculator.web.app/](https://ai-foot-print-calculator.web.app/)

## Project Structure

```text
AI-FootPrint/
│
├── index.html
├── login.html
├── dashboard.html
├── result.html
├── impact.html
│
├── firebase.json
├── .firebaserc
├── .gitignore
│
├── Team_48_SIP_2323.pdf
└── README.md
```

## Data Handling

AI Footprint uses browser-based LocalStorage for storing:

- User profile information
- Current calculation results
- Calculation history

Firebase is used for hosting and deployment of the web application.

No external database is currently used for storing user calculation data.

## Future Improvements

Possible future improvements include:

- Integration with real-time AI usage data.
- More detailed environmental impact calculations.
- Support for additional AI activities such as video generation and audio generation.
- User accounts with cloud-based data storage.
- Historical charts and analytics.
- More detailed sustainability recommendations.
- Improved estimation models based on updated research and infrastructure data.

## Project Goal

The goal of AI Footprint is to increase awareness of the environmental impact of everyday AI usage by converting AI activity into simple and understandable environmental metrics.

## Live Application

🌐 **AI Footprint:**  
https://ai-foot-print-calculator.web.app/

## Author

**Sukriti Gupta**

GitHub: [@sukriti-8](https://github.com/sukriti-8)

---

### Semester 2 Project

AI Footprint was developed as a Semester 2 academic project focused on combining web development, AI awareness, and environmental sustainability.
