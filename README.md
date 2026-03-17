# AI Urban Planning Decision Support

Data science layer for CAN-SIMPLAN, a prototype system designed to support transparent and explainable municipal planning decisions.

## Overview

This repository contains the data science work developed for a cross-functional sprint project focused on AI-assisted municipal planning decision support.

The objective of the project was to explore how structured data and transparent analytics could support planners when evaluating development proposals.

My contribution focused on the **data and analytics layer** used to simulate proposal evaluation.

---

## My Role

As the data scientist on the project, I was responsible for:

- creating synthetic development proposal datasets
- cleaning and structuring the planning data
- engineering features across urban, financial, and socioeconomic dimensions
- designing evaluation logic for proposal scoring
- conducting exploratory data analysis and visualization

The structured datasets produced here were later used by the software engineering team to support the development of the application’s backend and frontend prototype.

---

## Repository Structure

**Notebooks**

`01_mockdata_generation.ipynb`  
Creates and cleans the synthetic development proposal dataset.

`02_visualization_analysis.ipynb`  
Explores proposal score behavior and system-level risk distributions.

**Datasets**

The datasets simulate development proposal inputs used to prototype the planning evaluation system.

These datasets include indicators related to:

- urban planning impact
- financial feasibility
- socioeconomic displacement risk

---

## Project Context

This project was developed in collaboration with software engineers and a UX designer as part of a product sprint.  

While engineers built the application interface and backend architecture, this repository captures the **data preparation, feature engineering, and analytical exploration** that supported the system.

---

## Note

The datasets used in this project are synthetic and designed to replicate the structure of real municipal planning inputs.

## System Pipeline

The data work in this repository supported a broader application prototype developed with software engineers and a UX designer.

The overall system workflow looked like this:

Development Proposal Data  
↓  
Data Cleaning & Structuring (Python / Pandas)  
↓  
Feature Engineering & Scoring Logic  
↓  
Structured Dataset Outputs  
↓  
Backend API (Software Engineering Team)  
↓  
Planner Review Dashboard (Frontend)

## ## Related Project Repositories

- Frontend prototype: [Industry Sprint Front End](https://github.com/hellsten/Industry-Sprint-Front-End)
- Backend prototype: [Industry Sprinti Back End](https://github.com/hellsten/Industry-Sprint-Back-End/tree/main)
