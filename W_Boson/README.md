# W Boson Production via the W → μ ν Decay Channel

### Overview
This project tests the Standard Model prediction for W-boson production using the 13 TeV ATLAS Open Data.  
Muon–neutrino final-state events were isolated, and the W mass distribution was reconstructed using a Breit–Wigner fit.

### Key Results
- **Measured W transverse mass:** 78.07 ± 0.006 GeV  
- **Standard Model value:** 80.379 ± 0.012 GeV  
- Agreement between data and MC ≈ 5 %.

### Data and Methods
- **Dataset:** ATLAS 13 TeV Open Data  
- **Tools:** Python 3 · CERN ROOT · NumPy · Matplotlib  
- **Workflow:**
  1. Event selection using muon triggers and isolation cuts  
  2. MC weighting and normalization (luminosity × cross-section / Σweights)  
  3. Statistical comparison of data vs MC using χ² tests  
  4. Breit–Wigner fit for W mass extraction  

### Files
- `Wlv Final Report.pdf`  
- `Final Code.ipynb`  
- `Finale Code NO lepistightID.ipynb`

### Skills Demonstrated
Statistical inference • Simulation weighting • Curve fitting • Uncertainty analysis • High-energy data processing • Scientific visualization

### References
ATLAS Open Data 13 TeV (2020): https://atlas-opendata.web.cern.ch  
Aaboud & Aad et al., *Eur. Phys. J. C (2018)* – Measurement of the W-boson mass in pp collisions at √s = 7 TeV.
