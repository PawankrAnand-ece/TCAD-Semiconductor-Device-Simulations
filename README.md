# TCAD-Semiconductor-Device-Simulations
TCAD-Silvaco-Semiconductor-Analysis
Professional Portfolio: MOSFET Characterization &amp; 
CMOS Logic Simulation 
🚀 Project Overview : This repository showcases the design, modeling, and simulation of fundamental semiconductor devices using Silvaco ATLAS. The project focuses on the DC characterization of NMOS and PMOS transistors and the performance analysis of a CMOS Inverter.By utilizing physical modeling and numerical simulation, I have extracted key device parameters including  curves and Voltage Transfer Characteristics (VTC).
🛠 Technical Specifications : Across all simulations, the following physical parameters and models were implemented:Substrate Material: Silicon (Monocrystalline)Gate Oxide:  (20nm) thicknessDoping Concentration: Uniform  (n-type for NMOS/region 1, p-type for PMOS/region 2)
Physics Models: Shockley-Read-Hall (SRH) recombination model for carrier lifetime analysis.Numerical Method: Newton-Raphson iteration for carrier transport equations.
📂 Project Structure
1. NMOS Simulation (/NMOS_Simulation)
   Objective: Analyze the  output characteristics of an N-channel MOSFET.
   Simulation Details: * Gate biased at  to ensure inversion.Drain voltage swept from  to  ( steps).Key Files: nmos_idvd.in (Input deck), nmos_idvd.log (Log data).
2. PMOS Simulation (/PMOS_Simulation)
   Objective: Analyze the  output characteristics of a P-channel MOSFET.
   Simulation Details: * Gate biased at .Drain voltage swept from  to  ( steps).Key Files: pmos_idvd.in, pmos_idvd.log.
3. CMOS Inverter (/CMOS_Inverter)
   Objective: Extract the Voltage Transfer Characteristics (VTC) of a static CMOS Inverter.
   Simulation Details: * Supply Voltage () set to .Input Voltage swept from  to  to visualize logic high-to-low transition.Integrated NMOS and PMOS regions in a single     mesh structure ().Key Files: cmos_Inverter.in, cmos_vtc.log.
