---
layout: project
title: Torque Wrench Analysis
description: Mechanics of Engineering Materials Final Project
technologies: [Autodesk Fusion, ANSYS Workbench]
image: /assets/images/FEM, Displacement Top View.jpg
---

## Project Overview

As the final project for Mechanics of Engineering Materials, we designed a torque wrench by selecting an appropriate material and adjusting the dimensions to meet specified performance and safety requirements.  
A quenched and tempered high-strength low-alloy steel (AISI 4340 QT 409) was selected due to its durability and ability to deliver sufficient torque output while maintaining acceptable safety margins.

---

## Material Properties (AISI 4340 QT 409)

- **Young’s modulus:** E = 30 × 10⁶ psi  
- **Poisson’s ratio:** ν = 0.29  
- **Ultimate tensile strength:** σᵤ = 210 ksi  
- **Fracture toughness:** Kᴵᶜ = 77 ksi·√in  
- **Fatigue strength (10⁶ cycles):** σ_fatigue = 95 × 10³ psi  

---

## CAD Model

<div style="display: flex; gap: 24px; flex-wrap: wrap; justify-content: center;">
  <figure style="text-align: center;">
    <img src="{{ '/assets/images/Render_Torque_Wrench_CustomizedView18042193490_jpg.jpg.jpeg' | relative_url }}"
         alt="Torque Wrench Render"
         style="width: 380px; max-width: 100%;">
    <figcaption><em>Rendered torque wrench model</em></figcaption>
  </figure>

  <figure style="text-align: center;">
    <img src="{{ '/assets/images/TW CAD DIM.jpg' | relative_url }}"
         alt="Torque Wrench CAD Dimensions"
         style="width: 380px; max-width: 100%;">
    <figcaption><em>Dimensioned CAD model</em></figcaption>
  </figure>
</div>

---

## Finite Element Model (FEM)

### Load and Boundary Conditions

<div style="display: flex; justify-content: center;">
  <figure style="text-align: center;">
    <img src="{{ '/assets/images/FEM, Force and Constraint set up.jpg' | relative_url }}"
         alt="FEM Force and Constraint Setup"
         style="width: 480px; max-width: 100%;">
    <figcaption><em>Applied loads and boundary conditions in ANSYS</em></figcaption>
  </figure>
</div>

---

### Displacement Contours

<div style="display: flex; gap: 24px; flex-wrap: wrap; justify-content: center;">
  <img src="{{ '/assets/images/FEM, Displacement Side View.jpg' | relative_url }}"
       alt="FEM Displacement Side View"
       style="width: 420px; max-width: 100%;">

  <img src="{{ '/assets/images/FEM, Displacement Top View.jpg' | relative_url }}"
       alt="FEM Displacement Top View"
       style="width: 420px; max-width: 100%;">
</div>

---

### Strain in the Gauge Direction

<div style="display: flex; gap: 24px; flex-wrap: wrap; justify-content: center;">
  <img src="{{ '/assets/images/FEM, Strain Side View.jpg' | relative_url }}"
       alt="FEM Strain Side View"
       style="width: 420px; max-width: 100%;">

  <img src="{{ '/assets/images/FEM, Strain Top View.jpg' | relative_url }}"
       alt="FEM Strain Top View"
       style="width: 420px; max-width: 100%;">
</div>

---

### Maximum Principal Stress

<div style="display: flex; gap: 24px; flex-wrap: wrap; justify-content: center;">
  <img src="{{ '/assets/images/FEM, Stress Side View.jpg' | relative_url }}"
       alt="FEM Stress Side View"
       style="width: 420px; max-width: 100%;">

  <img src="{{ '/assets/images/FEM, Stress Top View.jpg' | relative_url }}"
       alt="FEM Stress Top View"
       style="width: 420px; max-width: 100%;">
</div>

---

## FEM Results Summary

| Quantity | Value |
| --- | --- |
| Maximum normal stress | **40.972 ksi** (between strain gauge and wrench knob) |
| Strain at strain gauge location | **1060 µε** |
| Load-point deflection | **0.36641 in** |
| Torque wrench sensitivity (from FEM strain) | **1.06 mV/V** |

The FEM results demonstrate acceptable stress levels, measurable strain at the gauge location, and predictable deflection behavior. The resulting electrical sensitivity provides a clear and reliable calibration pathway for torque measurement.

