# Chifaa Saghrouni

## Maritime Engineer | Hydrodynamics & Offshore Structures

---

![Profile](https://img.shields.io/badge/Location-Marseille,_France-blue)
![Profile](https://img.shields.io/badge/Status-Available_Immediately-green)
![Profile](https://img.shields.io/badge/School-Centrale_Méditerranée-orange)

---

### About Me

Maritime engineer graduated from **École Centrale Méditerranée** (Naval & Maritime Engineering) and **ENIM** (Mechanical Engineering), specialised in **hydrodynamics**, **mooring analysis** and **numerical modelling** for offshore floating structures.

Hands-on experience in coupled hydrodynamic analysis, fatigue assessment of mooring systems, and wave climate data processing at **DORIS Group / Océanide** (France Énergie Marine R&D project).

**Core Skills:** OrcaFlex | OrcaWave | OpenFAST | Python | Abaqus

📧 [chifaasagh@gmail.com](mailto:chifaasagh@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/chifaa-saghrouni-82967b236/)  
📄 [Download my CV](./CV_Chifaa_SAGHROUNI_.pdf)

---

## Projects

### 🌊 Project 1 — Mooring Fatigue Analysis (FOWT 15 MW)

**Parametric study of mooring line fatigue for a semi-submersible floating wind turbine**

- Ran 7 parametric load cases varying Hs, Tp and wave direction
- Applied **Rainflow counting** (ASTM E1049) + **Miner's rule** (DNV S-N curves) via Python
- **Key result:** Wave height (Hs) is the dominant parameter → +23% fatigue damage when Hs increases from 4m to 6m
- The windward mooring line carries **~20× more fatigue damage** than leeward lines

**Tools:** OrcaFlex, OrcaWave, Python (rainflow, pandas, matplotlib)

| Parameter | Family A (Hs) | Family B (Tp) | Family C (Dir) |
|-----------|---------------|---------------|----------------|
| Damage variation | **+23%** | -8% | -7% |
| Impact level | Dominant | Moderate | Limited |

![Fatigue Results](./images/fatigue_damage_relative.png)
![Time Histories](./images/time_histories.png)

📌 [Read the full LinkedIn post](https://lnkd.in/p/eMndyx_a)

---

### 🌊 Project 2 — Offshore Wave Climate Analysis (Gulf of Lion)

**Scatter diagram and operability analysis using real ERA5 wave data**

- Processed **40,908 data points** from ERA5 Reanalysis (Copernicus) for 2020-2023
- Built **scatter diagram** (Hs vs Tp), **wave rose** and **operability statistics**
- Identified optimal installation windows and maintenance access periods

**Key Statistics (Gulf of Lion, 2020-2023):**

| Parameter | Value |
|-----------|-------|
| Mean Hs | 0.94 m |
| P90 Hs | 2.02 m |
| Max Hs | 6.38 m |
| Crew transfer operability (Hs<2m) | ~90% |
| Heavy lift operability (Hs<1.5m) | ~75% |
| Best installation window | June-August |

**Tools:** Python (netCDF4, matplotlib, numpy), ERA5/Copernicus data

![Scatter Diagram](./images/scatter_diagram.png)
![Wave Rose](./images/wave_rose.png)
![Operability](./images/operability.png)

📌 [Read the full LinkedIn post](https://lnkd.in/p/eDVNSsvs)

---

### 🌊 Project 3 — 3D Animation of FOWT Dynamic Response (OpenFAST)

**Real-time visualisation of a semi-submersible platform under wave loading using OpenFAST simulation data**

- Performed a **1-hour coupled simulation** (3600s, 36,000 time steps) of the OC4 DeepCwind semi-submersible 5MW using **OpenFAST v3.5.5**
- Modules: **HydroDyn** (hydrodynamic loads + QTFs) + **MoorDyn** (3 catenary mooring lines) + **ElastoDyn** (structural dynamics) + **AeroDyn** (aerodynamic loads)
- Created a **3D animation** showing real-time platform motions under irregular waves (JONSWAP, Hs=4m, Tp=12s)
- Visualised: wave surface, semi-submersible platform, mooring lines, rotating turbine blades, with camera rotation

**Platform Response (OpenFAST results):**

| DOF | Min | Max | Description |
|-----|-----|-----|-------------|
| Surge | 4.3 m | 13.7 m | Mean drift under wind loading |
| Heave | -1.5 m | +1.5 m | Excellent vertical stability |
| Pitch | 0.3 deg | 4.0 deg | Moderate rotational response |

**Mooring Line Tensions:**

| Line | T_min (kN) | T_max (kN) | T_mean (kN) |
|------|-----------|-----------|-------------|
| Line 1 | 826 | 1,113 | 987 |
| Line 2 (critical) | 957 | 2,574 | 1,626 |
| Line 3 | 775 | 1,054 | 894 |

**Tools:** OpenFAST v3.5.5, Python (matplotlib 3D animation), MoorDyn, HydroDyn

![Platform Motions](./images/openfast_platform_motions.png)
![Mooring Tensions](./images/openfast_mooring_tensions.png)

📌 [Watch the animation on LinkedIn](https://lnkd.in/p/eggVNP2e)

---

## Professional Experience

### DORIS Group / Océanide, Toulon — End-of-studies Internship
**April 2025 – September 2025** | France Énergie Marine R&D Project

- Performed hydrodynamic calculations (diffraction/radiation) for floating offshore structures
- Compared 6 calculation methods (frequency/time domain, coupled/uncoupled, with/without 2nd order effects)
- Defined load cases and operability criteria for maintenance operations
- Implemented dynamic positioning system via Python scripting
- **Tools:** OrcaFlex, OrcaWave, Python

### LMA (CNRS), Marseille — Internship
**June 2024 – July 2024**

- Finite element modelling of complex structures (Specfem2D, Gmsh)
- Numerical data processing and analysis
- **Tools:** Specfem2D, Gmsh, Python

---

## Professional Development
**October 2025 – Present** | Active job search & continuous skills development

- Self-taught **OpenFAST** (NREL): coupled dynamic simulation of a 5MW semi-submersible FOWT (OC4 DeepCwind) with HydroDyn + MoorDyn
- Performed **complete mooring fatigue analysis** using Rainflow counting + Miner's rule (DNV S-N curves)
- Processed **real wave data** (ERA5/Copernicus) for offshore climate analysis
- Created **3D animations** of platform dynamic response using Python
- Regular **technical publications** on LinkedIn with international engagement
- Built this **technical portfolio** on GitHub Pages

---

## Education

| Degree | School | Year |
|--------|--------|------|
| MSc Naval & Maritime Engineering | École Centrale Méditerranée | 2023-2025 |
| MSc Mechanical Engineering | ENIM, Tunisia | 2021-2023 |
| Preparatory Cycle (Physics) | IPEI Bizerte, Tunisia | 2019-2021 |

---

## Technical Skills

| Domain | Skills |
|--------|--------|
| **Hydrodynamics** | Diffraction/radiation, RAOs, QTFs, mooring dynamics, fatigue, operability |
| **Offshore Software** | OrcaFlex, OrcaWave, DeepLines, **OpenFAST** |
| **FEA/CAD** | Abaqus, SolidWorks, Specfem2D, Gmsh |
| **Programming** | Python (rainflow, pandas, matplotlib, numpy, netCDF4, 3D animation) |
| **Data** | Wave climate analysis, ERA5/Copernicus, scatter diagrams |
| **Standards** | DNV-OS-E301, DNV-RP-C203, DNVGL-ST-N001, ASTM E1049 |

---

## Languages

| Language | Level |
|----------|-------|
| Arabic | Native |
| French | Bilingual |
| English | B2 (Professional) |

---

## Contact

📧 **Email:** [chifaasagh@gmail.com](mailto:chifaasagh@gmail.com)  
🔗 **LinkedIn:** [Chifaa Saghrouni](https://www.linkedin.com/in/chifaa-saghrouni-82967b236/)  
📍 **Location:** Marseille, France  
✅ **Status:** Available immediately

---

*Last updated: July 2026*
