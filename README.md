# Logistic Growth Model of Phytoplankton Based on Lighting Duration

This project models the effect of **lighting duration** on the **population density of phytoplankton** using a logistic growth function.  
It simulates and compares population changes under different light exposure scenarios using an interactive Python notebook.

## 📊 Features
- Logistic growth prediction based on user-defined lighting durations (6–24 hours)
- Interactive slider for dynamic simulation in Jupyter/Colab
- Comparison with actual observed data for 6h, 12h, and 24h exposures
- Error analysis using MAPE (Mean Absolute Percentage Error)
- Automated interpretation: identifies which actual condition the prediction most closely resembles

## 🧪 Context
This model was developed during an undergraduate research project to analyze the impact of light exposure on phytoplankton population growth.  
It utilizes logistic regression and real-world experimental data.

## ⚙️ How to Use
1. Open the notebook in [Google Colab](https://colab.research.google.com/github/yoga-andri/phytoplankton-logistic-growth/blob/main/phytoplankton_logistic_growth_model.ipynb)
2. Use the slider to select a light exposure duration (between 6 and 24 hours)
3. The notebook will:
   - Generate a logistic growth curve
   - Display MAPE error compared to actual 6h, 12h, and 24h data
   - Interpret which real scenario your input most closely aligns with

## 🔧 Dependencies
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `ipywidgets`

> These will be automatically installed if using Google Colab.

## 👨‍💻 Author
**Yoga Andriyanto**  
Mathematics Graduate – Passionate in data, analysis, and modeling  
📬 Open for data-driven projects and collaboration opportunities.
