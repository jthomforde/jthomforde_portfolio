---
layout: project
title: Torque Wrench Analysis
description: Mechanics of Engineering Materials Final Project
technologies:  [Autodesk Fusion, ANSYS Workbench]
image: /assets/images/FEM, Displacement Top View.jpg
---

As the final project for Mechanics of Engineering Materials, we were asked to design a torque wrench by selecting the material and adjusting the dimensions to meet specified requirements. The material we chose to use is a quenched and tempered high-strength, low-alloy steel, or AISI 4340 QT 409. We chose this material because it is durable and delivers a high enough output to meet the requirements. The relevant information about this material is the Young's modulus, tensile strength, fracture toughness, and fatigue strength. These properties are as follows:

Young's Mondulus --> E = 30 * 10^6 psi
Poisson's Ratio --> nu = 0.29 
Tensile strength --> su = 210 ksi
Fracture toughness --> KIC = 77 (ksi sqrt(in))
Fatigue stress for 10^6 cycles --> sfatigue = 95 *10^3

The design rendering is shown below.

![Torque Wrench Render]({{ "/assets/images/Render_Torque_Wrench_CustomizedView18042193490_jpg.jpg.jpeg" | relative_url }}){: .inline-image-r style="width: 200px"}

![Torque Wrench CAD DIM]({{ "assets/images/TW CAD DIM.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

Diagram communicating how loads and boundary conditions were applied to the FEM model:

![FEM Force and Constraint Setup]({{ "/assets/images/FEM, Force and Constraint set up.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}


Normal strain contours (in the strain gauge direction):

![FEM Strain Side View]({{ "/assets/images/FEM, Strain Side View.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

![FEM Strain Top View]({{ "/assets/images/FEM, Strain Top View.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

Contour plot of maximum principal stress from FEM:

![FEM Stress Side View]({{ "/assets/images/FEM, Stress Side View.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

![FEM Stress Top View]({{ "/assets/images/FEM, Stress Top View.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

The FEM analysis shows a maximum normal stress of 40.972 ksi, occurring between the strain gauge and the wrench knob. The strain at the strain gauge location is 1060 microstrain. The deflection at the load point is 0.36641 in, which is the maximum displacement under the applied load. The torque wrench sensitivity from our strain values in the FEM analysis is 1.06 mV/V








