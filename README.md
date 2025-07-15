# Logistic Growth Model of Phytoplankton Based on Lighting Duration

This project models the effect of **lighting duration** on the **population density of phytoplankton** using a logistic growth function.  
It is based on real experimental data collected during academic research and is designed to simulate and compare population changes under different light conditions.

## 📊 Features
- Logistic growth prediction based on user-defined lighting durations (6–24 hours)
- Interactive visualization (slider) in Jupyter/Colab Notebook
- Comparison with actual data from 6h, 12h, and 24h exposure
- Error analysis using MAPE and automated interpretation to assess closeness to actual observations

## 📁 Files Included
- `phytoplankton_logistic_growth_model.ipynb` – Interactive Python notebook (Jupyter/Colab)
- `README.md` – This documentation file

## ⚙️ How to Use
1. Open the notebook in [Google Colab](https://colab.research.google.com/github/yoga-andri/phytoplankton-logistic-growth/blob/main/phytoplankton_logistic_growth_model.ipynb)
2. Use the slider to select light exposure duration (6 to 24 hours)
3. The notebook will:
   - Display the logistic growth curve
   - Calculate prediction error (MAPE) for 6h, 12h, and 24h
   - Automatically interpret which actual exposure the result is closest to

## 🔧 Dependencies
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `ipywidgets`

> These will be automatically installed if using Google Colab.

## 🧪 Context
This project was originally developed as part of my undergraduate thesis (skripsi) in Mathematics at Institut Teknologi Sumatera (ITERA).  
The core modeling and analysis were completed in **December 2024**, using real experimental data related to phytoplankton population growth under varying light durations.

In **July 2025**, the project was enhanced and published as an interactive, open-source Python notebook, with added features:
- Slider-based input
- Logistic prediction chart
- Error analysis and interpretation

This makes the project easier to use and share, especially for educational and analytical purposes.

## 👨‍💻 Author
**Yoga Andriyanto**  
Mathematics Graduate – Interested in data, analysis, and modeling  
📬 Open to data-related roles and collaboration opportunities.
