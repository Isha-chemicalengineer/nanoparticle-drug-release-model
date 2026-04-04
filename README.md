Diffusion-Based Drug Release from Nanoparticles

Overview
This project models drug release from a spherical nanoparticle under diffusion-controlled conditions. The aim is to understand how transport phenomena influence drug release and how external triggers such as ultrasound can enhance release rates.
This was implemented as a small computational exercise to connect core chemical engineering concepts with drug delivery systems.

Objective
- To model diffusion-controlled drug release from nanoparticles
- To study the effect of diffusion coefficient on release kinetics
- To simulate externally triggered release by increasing diffusion

Model Description
The system is modeled assuming a spherical nanoparticle where drug release is governed by diffusion.

A simplified exponential model is used:

Mt/M∞ = 1 - exp(-kt)

where k is proportional to D/R².

- D = diffusion coefficient  
- R = particle radius  

An increase in D is used to simulate external triggering (e.g., ultrasound), which enhances drug release.

Results
The model shows that increasing the diffusion coefficient significantly increases the rate of drug release.

This demonstrates how external stimuli such as ultrasound can accelerate transport and improve controlled drug delivery performance.

Tools Used
- Python  
- NumPy  
- Matplotlib  

Files
- drug-release-model.py → simulation code  
- drug-release-model.ipynb → notebook version  
- results.png → output graph  

 Future Scope
- Solve full diffusion equation (Fick’s second law)  
- Include degradation and multi-layer nanoparticle effects  
- Extend model to biological barriers and realistic drug delivery systems  
