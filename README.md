# Visualization-of-eeg-using-topomaps
#  EEG Psychiatric Disorders – Brainwave Visualization Project

This project analyzes and visualizes EEG (Electroencephalogram) signals for various **psychiatric disorders** such as Depression, Anxiety, Addiction, and Schizophrenia.  
It produces **EEG topomaps** (brainwave scalp maps) and **frequency band summaries** to explore brain activity differences across mental health conditions.

---

##  Project Overview

**Dataset Used:**  
[`EEG Psychiatric Disorders Dataset`](https://www.kaggle.com/datasets/hatouta/psychiatric-disorders-eeg-dataset)  
File: `EEG.machinelearing_data_BRMH.csv`

**Notebook:**  
`visualising-pre-processed-eeg-data.ipynb`

**EEG Frequency Bands:**  
- Delta (0.5–4 Hz)  
- Theta (4–8 Hz)  
- Alpha (8–13 Hz)  
- Beta (13–30 Hz)  
- Gamma (>30 Hz)

---

###  Electrode Placement Map
The standard **10-20 electrode placement** system was used to plot scalp topographies.

>  Click below to view electrode layout

[View Electrode Placement](./EEG_Visualizations/electrode_positions.png)

> 🔧 Replace this path with the actual file or link where you upload your **electrode_positions.png**  
> (you can export or capture it from your plotting cell if not yet saved).
---
##  Visualization Results

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
