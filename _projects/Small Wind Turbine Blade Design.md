---
layout: project
title: Small Wind Turbine Blade Design
description: MAE 4272 – Blade Design
technologies: [MATLAB, Autodesk Fusion 360, Wind Tunnel]
image: /assets/images/Blade CAD Model.png
---


As part of MAE 4272: Fluids and Heat Transfer Laboratory at Cornell University, our team designed, fabricated, and experimentally tested a small-scale wind turbine blade. The objective was to maximize power output under fixed wind-tunel operating conditions while ensuring structural safety under overspeed (free-spin) scenarios. This project mirrors real-world engineering challenges where aerodynamic performance must be balanced against material limits and system constraints. 

The blade design was governed by strict constraints: max blade length of 6 inches, 1 inch hub radius, max rotation rate of 2000 rpm, 80 MPa material strength limit, and limitations imposed by the torque brake assembly. These constraints required careful iteration to acieve reliable and safe performance.

Design Process

The design effort began by establishing aerodynamic operating targets based on prior laboratory work and airfoil performance data. We selected a NACA 4412 airfoil, and used its data to establish a target AoA of 6º to operate near a favorable lift-to-drag region. These targets guided the selection of blade twist and chord distributions along the span.

We defined blade geometry at the root and tip, with linear interpolation used to generate intermediate values along the span. Our chord varied from 7 cm at the root to 3 cm at the tip, and the twist angle ranged from 20º at the root to 0º at the tip.

Our group developed a MATLAB-based blade element and structural stress model to estimate our blade's performance given the selected geometry. The model predicted torque and power output, and was used to make variation in the root and tip fixed values.

Testing & Results

We tested our blade in the closed-loop wind tunnel across five fan operating frequences: 8 Hz, 10 Hz, 12 Hz, 14 Hz, and 16 Hz. For each condition, we allowed the turbine to spin freely to establish a baseline free rotation condition. Afterwards, we slowly increased the torque brake voltage until stall, recording RPM, torque, and electrical power output to evaluate the blade's performance. The blade operated safely under all test conditions and satisfied all structural and operational constraints. While peak power and operating rpm were lower than the model predictions (indicating early stall and reduced aerodynamic efficiency), the testing produced data that clearly revealed performance trends and model limitations.

My Contribution

I contributed primarily to the aerodynamic modeling and data analysis for this project. I helped develop and validate the MATLAB performance model, helped process experimental data to generate poewr curves, and compared predicted vs measured performance. Following our model testing, I helped identify design improvements with the team for future iterations.