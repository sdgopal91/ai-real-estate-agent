# AI Real Estate Agent

An end-to-end real estate analytics and generative AI project using Python, machine learning, Google Gemini, and CrewAI.

This project explores a large real estate listings dataset, builds a traditional price prediction model, integrates generative AI for property analysis, and culminates in a multi-agent AI workflow designed to analyze real estate data and provide market and pricing insights.

## Project Overview

The project was developed in stages, with each stage building on the previous one:

### 1. Data Exploration and Preparation
The first stage focuses on understanding and cleaning the real estate dataset.

Key tasks include:
- Reviewing dataset size, structure, and summary statistics
- Identifying missing values and duplicate records
- Cleaning numeric and categorical fields
- Converting date fields
- Identifying price outliers
- Exploring relationships between property characteristics
- Creating visualizations including histograms, box plots, scatter plots, and correlation heatmaps

Notebook: `notebooks/01-real-estate-data-exploration.ipynb`

### 2. Real Estate Price Modeling
The second stage applies traditional machine learning techniques to examine how property characteristics relate to price.

Key tasks include:
- Feature selection and preparation
- Correlation analysis
- Outlier handling
- Feature scaling
- Linear regression modeling
- Model evaluation
- Property price prediction

Notebook: `notebooks/02-real-estate-price-modeling.ipynb`

### 3. Generative AI Analysis with Gemini
The third stage integrates Google's Gemini model with the real estate dataset.

A sample of active property listings is provided to Gemini to:

- Identify price trends
- Analyze bedroom and bathroom patterns
- Evaluate house size and acreage
- Identify geographic patterns
- Detect missing or unusual values
- Generate estimated property prices
- Compare AI-generated estimates with actual listing prices

Notebook: `notebooks/03-gemini-real-estate-analysis.ipynb`

### 4. Multi-Agent Real Estate AI System
The final stage uses CrewAI to create a coordinated multi-agent workflow.

The system includes specialized AI agents responsible for:

- Real estate data analysis
- Residential property price analysis
- Accessing sampled property data through a custom CrewAI tool
- Coordinating dependent analytical tasks
- Producing structured market and pricing insights

Notebook: `notebooks/04-real-estate-ai-agent.ipynb`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Gemini API
- CrewAI
- Jupyter Notebook

## Repository Structure

```text
ai-real-estate-agent/
│
├── README.md
│
├── notebooks/
│   ├── 01-real-estate-data-exploration.ipynb
│   ├── 02-real-estate-price-modeling.ipynb
│   ├── 03-gemini-real-estate-analysis.ipynb
│   └── 04-real-estate-ai-agent.ipynb
│
├── data/
│   └── README.md
│
└── screenshots/
