# Crop Recommendation Exploratory Data Analysis & Report Generator

This project provides an end-to-end data processing, exploratory analysis, and visual reporting pipeline for the **Crop Recommendation Dataset**. It analyzes soil nutrients (`Nitrogen`, `Phosphorus`, `Potassium`) alongside environmental metrics (`Temperature`, `Humidity`, `pH`, `Rainfall`) across 22 crop classes, generating an executive Word document (`.docx`) report embedded with high-resolution visual charts.

---

## 📌 Features & Visualizations Covered

1. **Correlation Heatmap**: Evaluates relationships across all numerical soil and climatic metrics.
2. **Nutrient High-Demand Rankings**:
   - Top 10 Nitrogen-demanding crops (e.g., Cotton, Coffee, Muskmelon).
   - Top 10 Potassium-demanding crops (e.g., Grapes, Apple).
   - Top 10 Phosphorus-demanding crops (e.g., Apple, Grapes, Legumes).
3. **Climatic Profiling**:
   - Scatter profile of crops based on Rainfall vs. Humidity.
   - Temperature distribution boxplots across extreme temperature-tolerant crops.
   - Soil pH preference range (Acidic vs. Alkaline tolerant crops).
4. **Nutrient Clustering**:
   - Scatter analysis of Phosphorus vs. Potassium demonstrating specialized crop clustering.
5. **Feature Distribution**:
   - Histograms displaying normality and skewness for all features.
6. **Water-Intensive Crops**:
   - Ranking of top rainfall-dependent crops (e.g., Rice, Coconut, Jute).

---

## 📁 Repository Structure

```text
.
├── Crop_recommendation.csv               # Dataset
├── requirements.txt                      # Project dependencies
├── Crop_Recommendation_Analysis_Report.docx  # Output styled Word Document
└── README.md                             # Project Documentation