# Roundabout-simulation
🔄 Impact of CAVs on Roundabout Capacity using IDM in SUMO
This repository provides the simulation scripts, configuration files, and analysis code used in our study on evaluating the impact of Connected and Automated Vehicles (CAVs) on the capacity of a single-lane roundabout. The simulation is conducted using SUMO (Simulation of Urban MObility) and employs the Intelligent Driver Model (IDM) to model car-following behavior. Capacity is estimated using two speed-density models (Papageorgiou and Underwood) and the Macroscopic Fundamental Diagram (MFD).

📌 Key Features:

Microscopic simulation using SUMO with IDM-based car-following behavior

Editable CAV/AV penetration rate via the route file (default file reflects a single scenario)

Capacity estimation using both Papageorgiou and Underwood speed-density models

One-minute aggregated output analysis to evaluate flow and critical density

⚙️ Customizability:

The provided files simulate one predefined scenario.

You can adjust the CAV/AV penetration rate by modifying the vehicle distribution in the *.rou.xml route file.

📊 Findings: CAVs improve both link-level and network-level capacity, with diminishing returns at high penetration rates (>80%).

📄 Reference:
This repository is based on the following publication:
Karbasi, A. H., & Saffarzadeh, M. (2020). Impact of Connected and Automated Vehicles on Capacity of Roundabout using IDM Car-Following Model.
ResearchGate Link

📢:
If you use this repository or build upon this work in your research, please cite the above paper to acknowledge the original contributio
