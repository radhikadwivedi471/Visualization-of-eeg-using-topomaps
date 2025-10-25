#  EEG Psychiatric Disorders – Brainwave Topomap Visualization

This repository visualizes **EEG (Electroencephalogram)** data of individuals diagnosed with various **psychiatric and behavioral disorders**.  
Each disorder’s EEG brainwave patterns are represented using **topographic maps (topomaps)** that highlight frequency-band activity (Delta, Theta, Alpha, Beta, Gamma).

---

##  Dataset Overview

- **Dataset:** [Psychiatric Disorders EEG Dataset](https://www.kaggle.com/datasets/hatouta/psychiatric-disorders-eeg-dataset)  
- **File:** `EEG.machinelearing_data_BRMH.csv`  
- **EEG Bands:** Delta, Theta, Alpha, Beta, Gamma  
- **Electrodes:** 59 (10–20 system layout)  
- **Environment:** Google Colab + Python 3  

---

##  Visualization Objective

This project explores **EEG signal differences across psychiatric disorders** through scalp-level visualization.  
It includes:
- Mean band power comparisons
- Topographic brain maps
- Visual separation between **main disorder groups** and **specific subtypes**

---

###  Electrode Placement Map
The standard **10-20 electrode placement** system was used to plot scalp topographies.

[View Electrode Placement](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/image/electrode_placement.png)

---
##  Visualization Results

##  Main Psychiatric Disorders – EEG Topomaps

| Disorder | Alpha Band Topomap |
|-----------|--------------------|
| Addictive Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/main__Addictive_disorder__alpha.png) |
| Anxiety Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/main__Anxiety_disorder__alpha.png) |
| Health Control | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/main__Health_control__alpha.png) |
| Mood Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/main__Mood_disorder__alpha.png) |
| Obsessive-Compulsive Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/main__Obsessive_Compulsive_disorder__alpha.png) |
| Somatoform Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/main__Somatoform_disorder__alpha.png) |
| Trauma and Stress-Related Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/main__Trauma_and_stress_related_disorder__alpha.png) |

---

## 🎯 Specific Psychiatric Disorders – EEG Topomaps

| Specific Disorder | Alpha Band Topomap |
|-------------------|--------------------|
| Acute Stress Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/specific__Acute_stress_disorder__alpha.png) |
| Adjustment Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/specific__Adjustment_disorder__alpha.png) |
| Alcohol Use Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/specific__Alcohol_use_disorder__alpha.png) |
| Behavioral Addiction Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/specific__Behavioral_addiction_disorder__alpha.png) |
| Bipolar Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/specific__Bipolar_disorder__alpha.png) |
| Depressive Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/specific__Depressive_disorder__alpha.png) |
| Health Control | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/specific__Health_control__alpha.png) |
| Obsessive-Compulsive Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/specific__Obsessive_Compulsive_disorder__alpha.png) |
| Panic Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/specific__Panic_disorder__alpha.png) |
| Post-Traumatic Stress Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/specific__Post_traumatic_stress_disorder__alpha.png) |
| Schizophrenia Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/specific__Schizophrenia_disorder__alpha.png) |
| Social Anxiety Disorder | [View](https://github.com/radhikadwivedi471/Visualization-of-eeg-using-topomaps/blob/main/images/specific__Social_anxiety_disorder__alpha.png) |




##  How to Run the Notebook

1. **Mount Drive and load dataset**
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
