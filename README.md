# BME 3053C Final Project: Sleep Stage Classification
## Group 12

### Project Overview
This project develops a neural network to classify sleep stages (Wake, N1, N2, N3, REM) using EEG data from the Sleep-EDF Database. The goal is to improve insomnia diagnosis by identifying abnormal sleep patterns.

### Dataset
- **Source**: Sleep-EDF Database (https://www.physionet.org/content/sleep-edfx/1.0.0/)
- **Subset**: `BestGroup_Data.zip` contains EEG recordings and hypnograms for 5 subjects (SC4001E0 to SC4005E0).
- **Description**: EEG channels (Fpz-Cz, Pz-Oz) sampled at 100 Hz, with 30-second epochs labeled by sleep stage.

### Requirements
```bash
pip install mne numpy pandas scikit-learn tensorflow matplotlib
