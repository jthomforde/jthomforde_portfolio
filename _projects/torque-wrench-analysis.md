---
layout: project
title: Torque Wrench Analysis
description: Mechanics of Engineering Materials Final Project
technologies: [Autodesk Fusion, ANSYS Workbench]
image: /assets/images/FEM, Displacement Top View.jpg
---

## Project Overview

As the final project for Mechanics of Engineering Materials, we designed a torque wrench by selecting an appropriate material and adjusting the dimensions to meet specified performance and safety requirements.  
We chose a quenched and tempered high-strength low-alloy steel (AISI 4340 QT 409) for its durability and ability to deliver a high enough output torque.

## Material Properties (AISI 4340 QT 409)

- Young's modulus: **E = 30 × 10⁶ psi**
- Poisson's ratio: **ν = 0.29**
- Tensile strength: **σ<sub>u</sub> = 210 ksi**
- Fracture toughness: **K<sub>IC</sub> = 77 ksi·√in**
- Fatigue stress for 10⁶ cycles: **σ<sub>fatigue</sub> = 95 × 10³ psi**

---

## CAD Model

| | |
|:--:|:--:|
| ![Torque Wrench Render]({{ "/assets/images/Render_Torque_Wrench_CustomizedView18042193490_jpg.jpg.jpeg" | relative_url }}) | ![Torque Wrench CAD DIM]({{ "/assets/images/TW CAD DIM.jpg" | relative_url }}) |
| *Rendered torque wrench* | *Dimensioned CAD model* |

---

## Finite Element Model (FEM)

**Load and boundary conditions**

| |
|:--:|
| ![FEM Force and Constraint Setup]({{ "/assets/images/FEM, Force and Constraint set up.jpg" | relative_url }}) |
| *Setup of loads and constraints in ANSYS* |

**Displacement contours**

| Side View | Top View |
|:--:|:--:|
| ![FEM Displacement Side View]({{ "/assets/images/FEM, Displacement Side View.jpg" | relative_url }}) | ![FEM Displacement Top View]({{ "/assets/images/FEM, Displacement Top View.jpg" | relative_url }}) |

**Strain in the gauge direction**

| Side View | Top View |
|:--:|:--:|
| ![FEM Strain Side View]({{ "/assets/images/FEM, Strain Side View.jpg" | relative_url }}) | ![FEM Strain Top View]({{ "/assets/images/FEM, Strain Top View.jpg" | relative_url }}) |

**Maximum principal stress**

| Side View | Top View |
|:--:|:--:|
| ![FEM Stress Side View]({{ "/assets/images/FEM, Stress Side View.jpg" | relative_url }}) | ![FEM Stress Top View]({{ "/assets/images/FEM, Stress Top View.jpg" | relative_url }}) |

---

## FEM Results Summary

| Quantity | Value |
| --- | --- |
| Maximum normal stress | **40.972 ksi** (between strain gauge and wrench knob) |
| Strain at strain gauge location | **1060 µε** |
| Load-point deflection | **0.36641 in** |
| Torque wrench sensitivity (from FEM strain) | **1.06 mV/V** |

The FEM analysis confirms that the wrench geometry and material selection provide acceptable stress levels, measurable strain at the gauge location, and a clear electrical sensitivity for calibration.
