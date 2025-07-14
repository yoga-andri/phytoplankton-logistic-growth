# Logistic Growth Model of Phytoplankton Based on Lighting Duration

This project models the effect of **lighting duration** on the **population density of phytoplankton** using a logistic growth function.  
It is based on real experimental data collected during academic research and is designed to simulate and compare population changes under different light conditions.

## 📊 Features
- Logistic growth prediction based on user-defined lighting durations (6–24 hours)
- Interactive visualization (slider) in Jupyter/Colab Notebook
- Comparison with actual data from 6h, 12h, and 24h exposure
- Error analysis using MAPE and automated interpretation to assess closeness to actual observations
- Excel version of the model with editable input and automated logic

## 📁 Files Included
- `phytoplankton_logistic_growth_model.ipynb` – Interactive Python notebook (Jupyter/Colab)
- `logistic-growth-model-fitoplankton.xlsm` – Source data and Excel-based model
- `README.md` – This documentation file

## 🧾 Excel File Details
The Excel file contains multiple sheets for different purposes.  
To **simulate or run the model directly in Excel**, please go to the sheet:

### ➤ `Modified Logistic Model`

- Inside this sheet, you will find a labeled input area:
# "Enter Lighting Duration Value"
- You can adjust this input (light duration in hours), and the spreadsheet will automatically calculate the result using built-in formulas and logic.

> Only this sheet is intended for user interaction. Other sheets are used for reference or fixed data.

## ⚙️ How to Use (Python Version)
1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload the Excel file when prompted (`logistic-growth-model-fitoplankton.xlsm`)
3. Use the slider to select light exposure duration (6 to 24 hours)
4. The notebook will:
 - Display the logistic growth curve
 - Calculate prediction error (MAPE) for 6h, 12h, and 24h
 - Automatically interpret which actual exposure the result is closest to

## 🔧 Dependencies
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `ipywidgets`
- `openpyxl`

> These will be automatically installed if using Google Colab.

## 🧪 Context
This modeling project was inspired by a study on the **influence of light duration on phytoplankton growth**, using logistic regression techniques.  
It was developed during an undergraduate research project in Mathematics, with data sourced from a real experimental environment.

## 👨‍💻 Author
**Yoga Andriyanto**  
Mathematics Graduate – Interested in data, analysis, and modeling  
📬 Open to data-related roles and collaboration opportunities.

