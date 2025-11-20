# Traffic_Engineering_Ex2
The code for two models under three scenarios
- **CTM (Cell Transmission Model)**: Discrete LWR model based on Godunov scheme, using piecewise linear fundamental diagram
- **METANET Model**: Advanced macroscopic traffic flow model with velocity dynamics, better capturing traffic wave propagation and congestion formation
- **Scenario A**: Normal demand (Mainline: 4000 veh/h, On-ramp: 2000 veh/h)
- **Scenario B**: High ramp demand (Mainline: 4000 veh/h, On-ramp: 2500 veh/h)  
- **Scenario C**: Lane drop scenario (Mainline: 1500 veh/h, On-ramp: 1500 veh/h, Lane reduction from 3 to 1 at cell 5)

# Prerequisites
Python 3.7+
Jupyter Notebook/Lab (recommended) or Python environment


# How to run
Copy this entire code block into a Jupyter notebook cell
Run the cell
The simulation will automatically execute all three scenarios and generate plots


