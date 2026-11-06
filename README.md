# 4S2P 18650 Battery Module with BMS

An EV-style battery module designed using **Autodesk Fusion 360**. The design features eight 18650 cells in a 4S2P configuration, with custom cell holders, nickel busbars, a BMS mounting system and a vented enclosure.

## Project 1  Preview

![4S2P Battery Module Final Render](https://github.com/Prithvimishra7/fusion-cad-portfolio/blob/main/01-battery-module-4s2p/render.png)

## Key Features

- **Cell Holders:** Two identical holders (87.6 × 46.8 × 10 mm) featuring cell pockets, weld windows and M3 mounting holes.
- **Nickel Busbars:** Five 0.3 mm nickel strips designed for the 4S2P configuration, with Ø6 mm clearance holes.
- **BMS Mount:** 2 mm mounting plate with 5 mm spacers and a 50 × 45 mm BMS board positioned on 4 mm standoffs.
- **Enclosure:** Clear vented lid measuring 92 × 51.2 × 24 mm, with 2 mm walls and six cooling slots.
- **Assembly:** More than 20 components assembled using Fusion 360 joints, with interference checks performed.

## Battery Configuration

| Parameter | Specification |
|---|---|
| Cell type | 18650 Li-ion |
| Total cells | 8 |
| Configuration | 4S2P |
| Series groups | 4 |
| Cells per parallel group | 2 |
| Nominal voltage | Approximately 14.8 V |

The design uses four parallel cell groups connected in a series arrangement. Cell orientation alternates between groups.

## Engineering Challenges & Solutions

| Problem | How It Was Identified | Solution |
|---|---|---|
| Cells resting against the holder face instead of sitting in pockets | Section analysis | Corrected joint orientation and offsets |
| Cells overlapping the holder floor | Interference volume analysis | Adjusted joint offsets to account for the 5 mm floor |
| M3 bolts interfering with nickel busbars | Design review | Added Ø6 mm clearance holes |
| Lid colliding with the battery assembly | Interference check and part inspection | Corrected the shell feature and face selection |

## Project Deliverables

| File | Description |
|---|---|
| [Final Render](https://github.com/Prithvimishra7/fusion-cad-portfolio/blob/main/01-battery-module-4s2p/render.png) | Photorealistic project render |
| [Assembly Drawing](https://github.com/Prithvimishra7/fusion-cad-portfolio/blob/main/01-battery-module-4s2p/BatteryModule_4S2P_drawing.pdf) | ISO A3 assembly drawing with parts list |
| [Exploded View Animation](https://github.com/Prithvimishra7/fusion-cad-portfolio/blob/main/01-battery-module-4s2p/BatteryModule_exploded.mp4) | Exploded assembly animation |
| [Fusion Archive](https://github.com/Prithvimishra7/fusion-cad-portfolio/blob/main/01-battery-module-4s2p/BatteryModule_4S2P.f3z) | Editable Autodesk Fusion project |
| [STEP Model](https://github.com/Prithvimishra7/fusion-cad-portfolio/blob/main/01-battery-module-4s2p/BatteryModule_4S2P.step) | CAD model for use in other CAD software |

**Drawing Reference:** PM-BAT-001  
**Revision:** A

## Skills & Tools Used

- Autodesk Fusion 360
- 3D Part Modelling
- Parametric Design
- Mechanical Assembly Design
- Fusion 360 Joints
- Interference Analysis
- Section Analysis
- Mechanical Clearance Design
- 3D Rendering
- Exploded-View Animation
- Engineering Drawings

## Project Roadmap

**Project 1 of 5 — CAD + Robotics Portfolio**

Upcoming projects:

1. 4S2P 18650 Battery Module with BMS
2. Parallel-Jaw Robotic Gripper
3. 3-DOF Robotic Arm
4. ROS 2 Robotic Arm Integration
5. Autonomous Robotics System

## About

This project is the first in a five-project CAD and Robotics portfolio, focusing on mechanical design, assembly modelling and engineering documentation.

*Note: This is a CAD design. Electrical safety, cell compatibility, BMS selection, insulation, thermal management and enclosure performance require independent engineering validation before any physical implementation.*

---

**Author:** Prithvi Mishra  
**Date:** November 2026  
**Software:** Autodesk Fusion 360  
