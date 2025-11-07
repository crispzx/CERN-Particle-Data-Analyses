# Measurement of Higgs Boson Production via the Diphoton Decay Channel

### Overview
This project reproduces the discovery of the Higgs boson using open 13 TeV ATLAS data from CERN.  
It isolates Higgs → γγ (diphoton) decay events, reconstructs the Higgs mass from invariant-mass distributions, and compares the results with Standard Model Monte Carlo (MC) predictions.

### Key Results
- **Measured Higgs mass:** 124.76 ± 0.86 GeV  
- **Expected value (PDG 2020):** 125.09 ± 0.24 GeV  
- **χ² = 1.92**, **p = 0.983**, confirming strong agreement between data and MC simulation.

### Data and Methods
- **Dataset:** ATLAS 13 TeV Open Data (≈ 270 million collisions)
- **Tools:** Python 3 · CERN ROOT · NumPy · Matplotlib
- **Workflow:**
  1. Applied diphoton trigger + photon-isolation cuts  
  2. Reconstructed invariant mass of photon pairs  
  3. Fit a 3rd-order polynomial + Gaussian (signal + background)  
  4. Evaluated χ² probability vs null hypothesis  

### Files
- `Final Research Paper Hyy.pdf` — Full report  
- `finalcodeLOOSEcut.ipynb`  
- `finalcodeTIGHTcut.ipynb`  
- `Final code (1).ipynb`

### Skills Demonstrated
Data wrangling • Statistical modeling • Monte Carlo validation • Hypothesis testing • Visualization • Scientific computing

### References
ATLAS Open Data 13 TeV (2020): https://atlas-opendata.web.cern.ch  
Aad et al., *Phys. Lett. B 716 (2012)* – Observation of a new particle in the search for the Standard Model Higgs Boson.
