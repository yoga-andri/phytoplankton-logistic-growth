# Logistic Growth Model of Phytoplankton Based on Lighting Duration

This project models the effect of **lighting duration** on the **population density of phytoplankton** using a logistic growth function.  
It is based on real experimental data collected during academic research and is designed to simulate and compare population changes under different light conditions.

## 📊 Features
- Logistic growth prediction based on user-defined lighting durations (6–24 hours)
- Interactive visualization (slider) in Jupyter/Colab Notebook
- Comparison with actual data from 6h, 12h, and 24h exposure
- Error analysis using MAPE and automated interpretation to assess closeness to actual observations
- Fully functional **without needing external Excel files** (inline data is used)
- Excel version still available for manual input and logic testing

## 📁 Files Included
- `phytoplankton_logistic_growth_model.ipynb` – Interactive Python notebook (Jupyter/Colab)
- `logistic-growth-model-fitoplankton.xlsm` – Optional Excel-based model
- `README.md` – This documentation file

## 🧾 Excel File (Optional)
An optional Excel version of the model is included for spreadsheet simulation.

To try it:
- Open the file `logistic-growth-model-fitoplankton.xlsm`
- Go to the sheet:

### ➤ `Modified Logistic Model`

- Find the input labeled:
###    "Enter Lighting Duration Value"
- Enter a value (in hours) to simulate the model
- The spreadsheet uses built-in formulas to calculate population prediction

> Only this sheet is intended for user input. Other sheets contain raw/reference data.

## ⚙️ How to Use (Python Version)

✅ This notebook **does not require any external data upload**. Just open and run.

### ▶️ Steps:
1. Open the notebook in [Google Colab](https://colab.research.google.com/github/yoga-andri/phytoplankton-logistic-growth/blob/main/phytoplankton_logistic_growth_model.ipynb)
2. Use the slider to select light exposure duration (6 to 24 hours)
3. The notebook will:
   - Display the logistic growth curve
   - Show error values (MAPE) between prediction and actual data
   - Provide interpretation of which exposure duration your prediction is closest to

---

## 🔧 Dependencies
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `ipywidgets`

> Automatically installed in Google Colab.

---

## 🧪 Context
This modeling project was inspired by a study on the **influence of light duration on phytoplankton growth**, using logistic regression techniques.  
It was developed during an undergraduate research project in Mathematics, with data sourced from a real experimental environment.

## 👨‍💻 Author
**Yoga Andriyanto**  
Mathematics Graduate – Interested in data, analysis, and modeling  
📬 Open to data-related roles and collaboration opportunities.
