---
layout: project
title: Nonlinear Modeling of Rudder-Steered Autonomous Boat
description: MAE 3260 Final Design Project
technologies: [MATLAB]
image: /assets/images/Yaw_Angle.png
---

## Overview 
Sailboats are inherently nonlinear dynamic systems in which aerodynamic forces acting on the sail and hydrodynamic forces on the hull and rudder interact with control inputs to determine stability and maneuvering behavior. Accurately modeling these coupled effects is critical for understanding and designing effective control strategies.

In this project, a two-dimensional planar dynamics model is developed to capture the boat’s horizontal motion and heading. The model includes the surge, sway, and yaw degrees of freedom, while heave, roll, and pitch are neglected under the assumption of steady sailing conditions. The core objectives of the project are to derive the nonlinear equations of motion governing planar motion and yaw rotation, and then linearize these dynamics using Jacobian matrices about an operating point.

The resulting linearized equations are expressed in state-space form to support control system design. Multiple feedback controllers are then developed to stabilize the yaw dynamics and regulate heading. Finally, the controllers are evaluated through MATLAB simulations of the original nonlinear model, allowing comparison between linear predictions and nonlinear system response.

## Final Report

📄 [View Full Project Report (PDF)](assets/Final_Groupwork_Report.pdf)
