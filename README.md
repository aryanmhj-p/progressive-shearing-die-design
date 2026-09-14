# Precision Progressive Shearing Die Design & Optimization

[![SolidWorks](https://img.shields.io/badge/CAD-SolidWorks_3D-red.svg)](#)
[![Standards](https://img.shields.io/badge/Standard-FIBRO_%7C_DIN_%7C_ISO-blue.svg)](#)
[![Material](https://img.shields.io/badge/Material-St12_Cold--Rolled_Steel-grey.svg)](#)
[![Institution](https://img.shields.io/badge/Sharif_University-Mechanical_Engineering-black.svg)](#)

A comprehensive engineering project focused on the strip nesting optimization, standard tooling catalog synthesis, and full 3D parametric CAD modeling in SolidWorks for a single-row progressive shearing die.

> 📄 **Project Presentation & Technical Report:**  
> Detailed component callouts, exploded assembly breakdowns, BOM tables, and nesting derivations are available in the project documentation:  
> 🔗 **[Read Detailed Die Design Presentation (PDF)](./docs/Detailed%20Shearing%20Die%20Design.pdf)**

---

## 📌 Project Overview & Specifications

The die is engineered to mass-produce a $2.00\text{ mm}$ thick St12 cold-rolled steel structural component featuring an arrow profile with a precision $\varnothing 5.00\text{ mm}$ functional hole.

| Parameter | Value / Selected Standard | Engineering Significance |
| :--- | :---: | :--- |
| **Raw Material** | **St12 (DC01) Steel Sheet** | $2.00\text{ mm}$ thickness, scale-free surface |
| **Sheet Format** | **$1000 \times 1200\text{ mm}$** | Sheared & roller-slit into $56.79\text{ mm}$ strips |
| **Die Architecture** | **Single Row - One Pass** | Progressive piercing and blanking |
| **Die Set Standard** | **FIBRO 201.31 (DIN 9822 Shape C)** | Rear-pillar guide set for open-front feeding |
| **Nesting Angle ($\theta$)** | **$-50.0^\circ$** | Optimizes scrap bridge and material flow |
| **Progression Pitch ($P$)** | **$25.65\text{ mm}$** | Minimum edge margin & bridge: $1.40\text{ mm}$ |
| **Production Yield** | **798 pieces / sheet** | **$53.4\%$ Material Utilization Ratio** |

---

## ⚙️ Core Engineering & Tooling Design

### 1. Strip Nesting & Material Yield Optimization
- **Nesting Layout:** Orienting the blank at a $-50.0^\circ$ incline allowed dense interleaving across the $56.79\text{ mm}$ slit width.
- **Scrap Minimization:** Reduced the inter-part bridge and strip edge clearances to an optimal $1.40\text{ mm}$, yielding 38 parts per strip and a total of 798 blanks per raw sheet.

### 2. Standardized Tooling Components (FIBRO / DIN / ISO)
- **Die Set:** Rear guide pillar set (DIN 9822 Shape C / FIBRO Series 201.31) provides rigid precision alignment while maintaining unobstructed front passline access.
- **Piercing Punch:** ISO 8020 stepped round punch with an integrated spring-loaded shedder pin to eliminate vacuum-induced slug pulling during high-speed operation.
- **Blanking Punch:** Engineered with an integral solid mounting flange to maximize beam stiffness and absorb lateral cutting loads.
- **Die Matrix:** Sized with calculated shear land and angular relief tapers for jam-free scrap fall-through.

### 3. Progressive Pitch Control & Stock Feeding
- **Pilot Pins:** Bullet-nose parabolic pilots (direct alignment in the $\varnothing 5.00\text{ mm}$ pierced hole and indirect staging) ensure micro-level register repeatability.
- **Primary Registration:** Manual spring-loaded finger stop provides active lateral stock clamping during initial coil feeding.
- **Continuous Operation:** Model No. 2 automatic trigger stop actuated by an upper-shoe adjustable trip screw for reliable progressive progression.
- **Stripping Mechanism:** Fixed, precision-ground stripper plate preventing blank lift and buckling on the punch return stroke.

---

## 🔩 Hardware & Fastener Callouts

- **Alignment:** Hardened ASME B18.8.2 precision dowel pins ($\varnothing 0.3752"$) for absolute subassembly concentricity.
- **Clamping:** High-tensile $3/8"-24\text{ UNF}$ socket head cap screws.
- **Stock Guides:** Front and back passline ground gages designed with thermal and sliding expansion tolerances.

---

## 👥 Designer & Academic Context

* **Designer & CAD Modeler:** **Arian Mahjoubi** – Sharif University of Technology ([LinkedIn](https://www.linkedin.com/in/aryan-mahjoubi-ba66a0261) / [GitHub](https://github.com/aryanmhj-p))
* **Instructor:** Prof. Asempour
* **Department:** Department of Mechanical Engineering, Sharif University of Technology
