# 🧠 EEG Psychiatric Disorders – Brainwave Topomap Visualization

This repository visualizes **EEG (Electroencephalogram)** data of individuals diagnosed with various **psychiatric and behavioral disorders**.  
Each disorder’s EEG brainwave patterns are represented using **topographic maps (topomaps)** that highlight frequency-band activity (Delta, Theta, Alpha, Beta, Gamma).

---

## 📊 Dataset Overview

- **Dataset:** [Psychiatric Disorders EEG Dataset](https://www.kaggle.com/datasets/hatouta/psychiatric-disorders-eeg-dataset)  
- **File:** `EEG.machinelearing_data_BRMH.csv`  
- **EEG Bands:** Delta, Theta, Alpha, Beta, Gamma  
- **Electrodes:** 59 (10–20 system layout)  
- **Environment:** Google Colab + Python 3  

---

## 🧩 Visualization Objective

This project explores **EEG signal differences across psychiatric disorders** through scalp-level visualization.  
It includes:
- Mean band power comparisons
- Topographic brain maps
- Visual separation between **main disorder groups** and **specific subtypes**

---

###  Electrode Placement Map
The standard **10-20 electrode placement** system was used to plot scalp topographies.

>  Click below to view electrode layout

[View Electrode Placement](./EEG_Visualizations/electrode_positions.png)

> 🔧 Replace this path with the actual file or link where you upload your **electrode_positions.png**  
> (you can export or capture it from your plotting cell if not yet saved).
---
##  Visualization Results
## 📁 Folder Structure

###  Main Psychiatric Disorders – EEG Topomaps
Each map shows average scalp activity per frequency band for major disorder groups.

>  Click below to open the topomap images

| Disorder | Topomap |
|-----------|----------|
| Addictive Disorder | [View Image](./EEG_Visualizations/topomap_images/main__Addictive_disorder__alpha.png) |
| Anxiety Disorder | [View Image](./EEG_Visualizations/topomap_images/main__Anxiety_disorder__alpha.png) |
| Personality Disorder | [View Image](./EEG_Visualizations/topomap_images/main__Personality_disorder__alpha.png) |
| Depression | [View Image](./EEG_Visualizations/topomap_images/main__Depression__alpha.png) |


###  Specific Disorders – EEG Topomaps
Fine-grained visualization for specific clinical subtypes.

| Disorder | Topomap |
|-----------|----------|
| OCD | [View Image](./EEG_Visualizations/topomap_images/specific__OCD__alpha.png) |
| PTSD | [View Image](./EEG_Visualizations/topomap_images/specific__PTSD__alpha.png) |
| Schizophrenia | [View Image](./EEG_Visualizations/topomap_images/specific__Schizophrenia__alpha.png) |
| Eating Disorder | [View Image](./EEG_Visualizations/topomap_images/specific__Eating_Disorder__alpha.png) |

---

##  How to Run the Notebook

1. **Mount Drive and load dataset**
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
