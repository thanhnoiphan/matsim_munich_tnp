## MATSim Munich Simulation Results

This repository demonstrates a successful MATSim simulation run for the Munich scenario with 30 iterations.
> The model reaches convergence and produces stable travel behavior patterns across all major indicators.
## Key results

### Mode Share

<img src='https://github.com/thanhnoiphan/matsim_munich_tnp/blob/main/Output_Viz/figure_01_mode_share.png' width='750'> 

**Figure 1. Mode share of simulated trips.**  
The bar chart shows the proportion of trips by transport mode in the MATSim Munich scenario. 
Each trip recorded in `output_trips.csv.gz` is classified by its main mode. 
The resulting distribution provides an overview of the modal split of the simulated travel demand, 
including private car, public transport, cycling, and walking.



### Score convergence
<img src="https://github.com/thanhnoiphan/matsim_munich_tnp/blob/main/Figures/munich.scorestats.png" width="500">

The score improves rapidly in early iterations and stabilizes afterwards, indicating convergence.

### Mode share
<img src="https://github.com/thanhnoiphan/matsim_munich_tnp/blob/main/Figures/munich.modestats_stackedbar.png" width="500">

Mode shares remain stable across iterations.

### Passenger kilometers traveled
<img src="https://github.com/thanhnoiphan/matsim_munich_tnp/blob/main/Figures/munich.pkm_modestats.png" width="500">

Passenger-kilometers by mode remain consistent across iterations.

### Passenger hours traveled
<img src="https://github.com/thanhnoiphan/matsim_munich_tnp/blob/main/Figures/munich.ph_modestats.png" width="500">

Passenger-hours by mode indicate stable travel-time patterns.

### Average trip distance
<img src="https://github.com/thanhnoiphan/matsim_munich_tnp/blob/main/Figures/munich.traveldistancestatstrips.png" width="500">

Average trip distance stabilizes quickly, suggesting consistent mobility patterns.

👉 The MATSim Munich simulation completed successfully and reached stable behavioral and system-level patterns within 30 iterations.
