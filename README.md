# 4S2P 18650 Battery Module | Autodesk Fusion 360

A modular EV-style battery pack enclosure designed in **Autodesk Fusion 360**, featuring an 8-cell 18650 arrangement in a 4S2P configuration.

The project focuses on 3D part modelling, assembly design, mechanical clearances, interference analysis, and engineering documentation.

## Project Preview

<!-- Add your final render here -->
![4S2P Battery Module Render](images/render.png)

## Key Specifications

| Parameter | Specification |
|---|---|
| Battery configuration | 4S2P |
| Total cells | 8 × 18650 |
| Nominal voltage | Approximately 14.8 V |
| Cell arrangement | 4 series groups, 2 cells in parallel per group |
| Cell holder dimensions | 87.6 × 46.8 × 10 mm |
| Busbar thickness | 0.3 mm |
| BMS mounting plate | 2 mm |
| Enclosure dimensions | 92 × 51.2 × 24 mm |
| CAD software | Autodesk Fusion 360 |

## Design Features

### 1. Cell Holders
- Two identical cell-holder components.
- Dedicated pockets for 18650 cells.
- Weld-access windows.
- M3 mounting holes.

### 2. Nickel Busbars
- Five nickel-strip components.
- Designed around the 4S2P cell arrangement.
- 6 mm clearance holes around mounting locations.

### 3. BMS Mounting System
- Custom 2 mm mounting plate.
- 5 mm spacers.
- Raised mounting points for a 50 × 45 mm BMS board.

### 4. Enclosure
- Custom vented enclosure with a clear lid.
- 2 mm wall thickness.
- Six cooling slots.
- Designed to provide clearance around internal components.

### 5. Assembly
- 20+ CAD components.
- Component positioning using Fusion 360 joints.
- Section analysis and interference inspection.

## Engineering Challenges & Solutions

| Challenge | Design Solution |
|---|---|
| Cells not sitting correctly inside their pockets | Corrected joint orientation and offsets using section analysis |
| Cell and holder-floor interference | Inspected interference volume and adjusted component positioning |
| M3 fasteners interfering with busbars | Added clearance openings |
| Enclosure lid colliding with internal components | Corrected the shell feature and face selection |

## Battery Configuration

The module uses an 8-cell 4S2P arrangement:

- Four parallel cell groups.
- Two cells connected in parallel per group.
- Four groups connected in series.
- Approximately 14.8 V nominal pack voltage.

**Note:** This is a mechanical CAD design. Electrical connections, BMS compatibility, insulation, thermal behaviour, and protection requirements require separate engineering validation before any physical implementation.

## Project Files

| File | Description |
|---|---|
| [Final Render](images/render.png) | Photorealistic project render |
| [Assembly Drawing](drawing/BatteryModule_4S2P_drawing.pdf) | ISO A3 drawing with parts list |
| [Exploded Animation](video/BatteryModule_exploded.mp4) | Exploded assembly animation |
| [Fusion Archive](cad/BatteryModule_4S2P.f3z) | Editable Fusion 360 project |
| [STEP Model](cad/BatteryModule_4S2P.step) | CAD exchange format |

**Drawing Reference:** PM-BAT-001  
**Revision:** A

## Skills Demonstrated

- Autodesk Fusion 360
- Parametric 3D Modelling
- Mechanical Part Design
- Assembly Design and Joints
- Section Analysis
- Interference Detection
- Mechanical Clearance Design
- 3D Rendering
- Exploded-View Animation
- Engineering Drawings

## Project Roadmap

**Project 1 of 5 — CAD + Robotics Portfolio**

Upcoming projects:

1. 4S2P 18650 Battery Module — Completed CAD design
2. Parallel-Jaw Robotic Gripper
3. 3-DOF Robotic Arm
4. ROS 2 Robot Integration
5. Autonomous Robotics System

---

**Author:** Prithvi Mishra  
**Date:** November 2026  
**Software:** Autodesk Fusion 360