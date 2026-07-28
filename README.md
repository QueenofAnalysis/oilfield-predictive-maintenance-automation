# Oilfield Predictive Maintenance Automation

## Overview

This project is an end-to-end predictive maintenance workflow built using n8n to simulate an intelligent oilfield monitoring system.

The workflow reads equipment sensor data, evaluates equipment health using engineering thresholds, filters critical equipment, generates AI-powered maintenance recommendations using Google Gemini, logs incidents into Google Sheets, and automatically sends maintenance alert emails.

---

## Business Problem

Unexpected equipment failures in oil and gas operations can lead to:

- Production downtime
- High maintenance costs
- Equipment damage
- Safety risks
- Reduced operational efficiency

This workflow automates early detection and notification to support faster maintenance response.

---

## Workflow Architecture

```
Oilfield Sensor Data
        │
        ▼
Google Sheets
        │
        ▼
Equipment Health Analysis (JavaScript)
        │
        ▼
Critical Risk Detection
        │
        ▼
Google Gemini AI
        │
        ▼
Incident Log
        │
        ▼
Gmail Alert Notification
```

---

## Features

- Reads equipment sensor data automatically
- Calculates equipment health using JavaScript
- Detects abnormal operating conditions
- Generates AI-powered maintenance recommendations
- Logs maintenance incidents automatically
- Sends email alerts to maintenance personnel
- Simulates an industrial predictive maintenance workflow

---

## Technologies Used

- n8n
- JavaScript
- Google Sheets
- Gmail API
- Google Gemini AI
- Workflow Automation
- Business Process Automation

---

## Engineering Rules

Equipment is classified as Critical when any of the following conditions are met:

- Temperature > 85°C
- Vibration > 5 mm/s
- Flow Rate < 400 bpd

Otherwise, equipment is classified as Normal.

---

## Sample Alert

```
🚨 CRITICAL MAINTENANCE ALERT

Well ID: WELL-001

Equipment:
ESP Pump

Temperature:
91°C

Pressure:
2600 psi

Vibration:
7.5 mm/s

Flow Rate:
320 bpd

Recommendation:
Immediate inspection required.
```

---

## Project Structure

```
workflow/
dataset/
assets/
documentation/
```

---

## Future Improvements

- Replace Google Sheets with live IoT sensors
- Integrate MQTT
- Connect to Azure IoT Hub
- Connect to AWS IoT Core
- Build Power BI Dashboard
- Deploy using Docker
- Connect Microsoft Teams or Slack

---

## Skills Demonstrated

- Workflow Automation
- Predictive Maintenance
- Industrial Automation
- JavaScript
- AI Integration
- Conditional Logic
- Google Workspace Automation
- Incident Management
- Email Automation

---

## Author

**Esther Obasi**

Automation Engineer | Workflow Automation | AI Solutions | Business Process Automation
