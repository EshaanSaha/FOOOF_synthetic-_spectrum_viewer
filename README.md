# 🧠 FOOOF Synthetic EEG Spectrum Simulator

This project simulates realistic EEG-like power spectra with randomized **aperiodic components** (offset and exponent of 1/f background activity) and **oscillatory peaks** (e.g., alpha rhythms). It uses the [FOOOF](https://github.com/fooof-tools/fooof) model to fit these spectra and extract both periodic and aperiodic features.

## 🔍 What This Project Does

- Simulates synthetic EEG power spectra with known true parameters
- Adds realistic noise to mimic biological signals
- Fits FOOOF models to each spectrum
- Compares true vs. fitted aperiodic and peak parameters
- Saves results to a `.csv` file
- Provides a **Streamlit app** for:
  - Sample selection via slider
  - Dynamic visualization of spectrum and fitted model
  - Peak highlighting
  - Descriptive analysis of aperiodic exponent

This project is ideal for:

- Learning how aperiodic/oscillatory spectral components interact
- Understanding how FOOOF performs under noise
- Teaching EEG signal decomposition
- Prototyping for more complex EEG/TMS pipelines
