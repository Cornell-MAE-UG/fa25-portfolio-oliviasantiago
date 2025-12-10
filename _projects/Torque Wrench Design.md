---
layout: project
title: Torque Wrench Design
description: MAE 3270 Mecahnics of Materials Final Project
technologies: [ANSYS]
image: /assets/images/newdesign_maximumprincipalstress.png
---

## Overview
The task was to design a non-ratcheting, 3/8 inch drive instrumented torque wrench rated for 600 in-lbf. Torque will be transduced using strain gauges bonded to the outer surfaces of the wrench at high strain locations. The basic analyses needed for the design were performed using hand calculations done on a MATLAB script and performing FEA of the final design.

#### Requirements
- Attain at least 1.0 mV/V output at the rated torque of 600 in-lbf
- Safety factor of X_0 = 4 for yield failure
- Safety factor of X_K = 2 for crack growth from an assumed crack of depth of 0.04 inches (1 mm)
- Fatigue stress safety factor of X_S = 1.5
- Material must be a steel, aluminum or titanium alloy

### Design 
- Length: 16 inches
- Width: 0.57 inches
- Thickness: 0.36 inches
- Distance from center of drive to center of strain gauge: 1.0 inch
- Material: High Alloy Steel, AerMet 100, solution treated and aged
   - Young's modulus: 28*10^(6) psi
   - Poisson's ratio: 0.3
   - Yield strength: 280*10^(3) psi
   - Fracture toughness: 125*10^(3) psi-sqrt(in)
   - Fatigue strength (10^6 cycles): 50 ksi

### Hand Calculations/MATLAB Computations
Hand calcs yielded:
- Load point deflection: 0.329 inches
- Max Normal Stress: 30.78 ksi
- Factor of Safety for Strength: 9.1
- Factor of Safety for Crack Growth: 10.23
- Factor of Safety for Fatigue: 1.62
- Strain at gauge: 1030.5 microstrain

### ANSYS Analysis

![Total Deflection]({{ "/assets/images/newdesign_totaldeformation.png" | relative_url }}){: .project-image"}

### CAD Renderings

![Photo of old radio]({{ "/assets/images/CAD_Renderings.png" | relative_url }}){: .project-image-l}



