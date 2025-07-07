# Dynamic-Pricing-Parking-Lots   
# 🚗 Dynamic Pricing for Urban Parking Lots

## 📌 Overview

This project was built as part of the Summer Analytics 2025 program.  
It focuses on implementing dynamic pricing for urban parking spaces based on demand and location data.

## 💻 Tech Stack Used

- Python
- Google Colab
- Pathway (Real-time dataflow engine)
- Pandas, NumPy, Bokeh
- Jupyter/Colab Notebooks

## 🛠️ Architecture Diagram

```mermaid
flowchart TD
    A[User uploads CSVs] --> B[Pathway Ingestion]
    B --> C[Dynamic Pricing Logic]
    C --> D[Bokeh Visualizations]
    D --> E[Colab Output]
