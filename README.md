# Ultrasonic Distance Meter
**Codtech IT Solutions Internship Project - Project 4 (Final Milestone)**

A conceptual embedded system design that measures the distance of an obstacle accurately using ultrasonic sound reflections and displays the data dynamically on a digital readout panel.

## 📁 Project Submission Files
This repository contains the complete conceptual implementation details:
1. `Project_Report.txt`: Theoretical framework, mathematical distance derivations, and sensor mechanics.
2. `Distance_Log_Dataset.csv`: Calibrated log dataset mapping sound travel time values to real physical distances.
3. `Hardware_and_UI_Concepts.txt`: Structural layout definitions for the physical device enclosure and display parameters.

## ⚡ Core Concept & Calculation Model
The module replaces manual tape measurements with a non-contact acoustic scanning cycle:
- **Trigger Phase:** The sensor projects a high-frequency sound wave burst into the surrounding environment.
- **Echo Phase:** The wave travels, strikes a target surface, rebounds, and triggers the reception node.
- **Math Engine:** The controller logs the elapsed time and derives the absolute distance using the speed of sound.
