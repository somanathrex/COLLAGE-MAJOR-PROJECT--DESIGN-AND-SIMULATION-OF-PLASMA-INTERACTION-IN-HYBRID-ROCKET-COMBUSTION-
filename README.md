# Plasma-Assisted Hybrid Rocket Thrust Chamber

## 🚀 Project Overview

This project presents the **design, analytical investigation, and CFD validation of a plasma-assisted hybrid rocket thrust chamber**. The work investigates the application of **nanosecond pulsed high-voltage plasma discharge** as a technique for improving ignition and combustion characteristics in a chemical hybrid rocket propulsion system.

The fundamental thrust-generation mechanism remains based on **conventional chemical rocket combustion and classical compressible-flow gas dynamics**. Plasma is considered as an enabling technology for ignition and combustion enhancement rather than as the primary source of thrust.

The project combines theoretical propulsion analysis, thermochemical calculations, CAD-based geometry development, and computational fluid dynamics to develop and evaluate the proposed thrust chamber configuration.

---

## 🎯 Project Objectives

The major objectives of this project are:

* To develop the preliminary design of a hybrid rocket thrust chamber.
* To perform analytical calculations for the major propulsion parameters.
* To evaluate thermochemical performance using **RPA-4**.
* To develop the thrust chamber and nozzle geometry using **SolidWorks**.
* To investigate the internal flow and combustion behaviour using **ANSYS CFD**.
* To study the potential role of nanosecond pulsed plasma in ignition and combustion enhancement.
* To analyse the flow behaviour through the combustion chamber and nozzle.
* To compare analytical predictions with numerical CFD results.
* To establish a technically consistent methodology for the design and validation of a plasma-assisted hybrid rocket configuration.

---

## 🔬 Engineering Approach

The project follows a sequential engineering methodology:

**Propulsion Requirements → Analytical Design → Thermochemical Analysis → CAD Modelling → CFD Setup → Numerical Simulation → Results Analysis → Validation**

Each stage is used to progressively develop and evaluate the thrust chamber design.

### 1. Analytical Design

Initial design calculations are performed using classical rocket propulsion and hybrid rocket theory.

The analytical stage establishes the primary design parameters required for subsequent CAD modelling and CFD analysis, including relevant chamber, nozzle, flow, and performance parameters.

The analytical calculations provide a baseline against which the numerical results can be evaluated.

---

### 2. Thermochemical Analysis

**RPA-4** is used for thermochemical analysis of the propulsion system.

The thermochemical analysis provides important combustion and performance parameters required for evaluating the proposed rocket configuration.

These results serve as a reference for the preliminary analytical design and subsequent CFD investigation.

---

### 3. Thrust Chamber and Nozzle Design

The thrust chamber geometry is developed based on the analytical design parameters.

The CAD model includes the relevant combustion chamber and nozzle regions required for numerical investigation.

**SolidWorks** is used for:

* Thrust chamber geometry development
* Nozzle geometry development
* Dimensional modelling
* Geometry preparation for CFD
* Design visualization

The resulting geometry is subsequently prepared for numerical analysis in ANSYS.

---

## ⚡ Plasma-Assisted Combustion

The distinguishing feature of the project is the integration of **nanosecond pulsed high-voltage plasma discharge** with the hybrid rocket combustion process.

The plasma system is investigated primarily for:

* Ignition assistance
* Improvement of ignition characteristics
* Enhancement of combustion processes
* Supporting more effective chemical reaction initiation

The plasma does **not** replace the chemical propulsion system or directly provide the primary thrust mechanism.

The thrust is generated through the conventional process of chemical energy release, high-temperature gas production, chamber pressure generation, and nozzle expansion.

This distinction is important because the project is fundamentally a **chemical hybrid rocket propulsion system with plasma-assisted combustion**.

---

## 💻 CFD Analysis

Computational Fluid Dynamics is used to investigate the flow behaviour within the proposed thrust chamber and nozzle.

**ANSYS CFD** is used for numerical modelling and analysis.

The CFD stage focuses on understanding parameters such as:

* Pressure distribution
* Temperature distribution
* Velocity distribution
* Flow development
* Combustion-region behaviour
* Nozzle flow characteristics
* Expansion of combustion gases
* Overall internal flow field

The numerical model provides spatially resolved information that cannot be obtained directly from the zero-dimensional or one-dimensional analytical calculations.

---

## 🧮 Analytical vs CFD Analysis

A key part of the project is the distinction between analytical prediction and numerical validation.

### Analytical Analysis

Analytical calculations provide:

* Preliminary design parameters
* Thermodynamic estimates
* Performance predictions
* Reference operating conditions
* Initial chamber and nozzle design information

### CFD Analysis

CFD provides:

* Detailed flow-field information
* Pressure and temperature distributions
* Velocity fields
* Local flow behaviour
* Numerical investigation of chamber and nozzle performance

The two approaches are therefore complementary rather than interchangeable.

The analytical calculations establish the design basis, while CFD provides a higher-resolution numerical investigation of the resulting geometry.

---

## 🛠️ Software and Tools

| Tool                                  | Application                                    |
| ------------------------------------- | ---------------------------------------------- |
| **RPA-4**                             | Thermochemical and rocket performance analysis |
| **SolidWorks**                        | CAD modelling and geometry development         |
| **ANSYS CFD**                         | Computational fluid dynamics and flow analysis |
| **MATLAB / Engineering Calculations** | Analytical calculations and data processing    |
| **GitHub**                            | Project documentation and version control      |

---

## 📊 Project Workflow

```text
                    PROJECT REQUIREMENTS
                           │
                           ▼
                 HYBRID ROCKET DESIGN
                           │
                           ▼
                 ANALYTICAL CALCULATIONS
                           │
                           ▼
                  RPA-4 THERMOCHEMISTRY
                           │
                           ▼
                  THRUST CHAMBER DESIGN
                           │
                           ▼
                   SOLIDWORKS CAD MODEL
                           │
                           ▼
                     CFD GEOMETRY
                           │
                           ▼
                     ANSYS CFD
                           │
                           ▼
                 FLOW-FIELD ANALYSIS
                           │
                           ▼
                ANALYTICAL–CFD COMPARISON
                           │
                           ▼
                    DESIGN VALIDATION
```

---

## 📁 Repository Structure

A suggested repository structure is:

```text
plasma-assisted-hybrid-rocket/
│
├── README.md
│
├── Analytical_Calculations/
│   ├── chamber_calculations
│   ├── nozzle_calculations
│   └── performance_analysis
│
├── RPA_Analysis/
│   └── thermochemical_results
│
├── CAD/
│   ├── SolidWorks/
│   └── geometry/
│
├── CFD/
│   ├── geometry/
│   ├── mesh/
│   ├── setup/
│   ├── results/
│   └── post_processing/
│
├── Results/
│   ├── pressure/
│   ├── temperature/
│   ├── velocity/
│   └── nozzle_results/
│
├── References/
│
└── Documentation/
```

---

## 📈 Results and Validation

The project uses analytical calculations and CFD results together to evaluate the proposed thrust chamber.

The analytical results provide the expected design and operating parameters, while CFD is used to examine the corresponding internal flow behaviour.

Important quantities for comparison include:

* Chamber pressure
* Temperature
* Gas velocity
* Nozzle flow behaviour
* Pressure distribution
* Temperature distribution
* Velocity distribution
* Predicted propulsion performance

The comparison helps identify differences between idealized analytical assumptions and the more detailed numerical flow solution.

---

## 🔍 Significance of the Study

Hybrid rocket propulsion offers a combination of features associated with solid and liquid propulsion systems. However, ignition and combustion behaviour can present important design challenges.

Plasma-assisted combustion provides a potential method for influencing the ignition and combustion process without fundamentally changing the chemical rocket propulsion mechanism.

This project therefore investigates the integration of **plasma-assisted combustion enhancement with conventional hybrid rocket propulsion**, combining propulsion analysis with CFD-based flow investigation.

---

## 📚 Research Basis

The project is supported by research literature concerning:

* Hybrid rocket propulsion
* Plasma-assisted ignition
* Plasma-assisted combustion
* Flame stabilization
* Plasma–combustion interaction
* Rocket combustion and nozzle flow
* Computational modelling of reacting flows

The literature review provides the theoretical basis for investigating plasma-assisted combustion and helps establish the engineering methodology adopted in the project.

---

## ⚠️ Scope and Limitations

The present work focuses on the **design and numerical investigation** of a plasma-assisted hybrid rocket thrust chamber.

The plasma system is treated as an ignition and combustion-enhancement mechanism. The project does not treat plasma as an independent electromagnetic propulsion system.

The CFD results are dependent on the selected physical models, boundary conditions, mesh quality, thermochemical assumptions, and numerical setup.

Therefore, CFD results are interpreted as a numerical investigation and are compared with analytical predictions wherever applicable.

Experimental validation would provide an additional level of validation beyond the scope of the present numerical study.

---

## 🔭 Future Work

Potential extensions of the project include:

* Experimental fabrication and testing of the thrust chamber
* Experimental investigation of plasma-assisted ignition
* High-speed visualization of ignition and combustion
* Investigation of different plasma pulse parameters
* Parametric CFD studies
* Mesh-independence studies
* Detailed reacting-flow modelling
* Investigation of different fuel and oxidizer combinations
* Optimization of chamber and nozzle geometry
* Comparison of numerical results with experimental measurements

---

## 👨‍🔬 Project Focus

The overall project integrates multiple areas of mechanical and aerospace engineering:

**Rocket Propulsion + Hybrid Combustion + Plasma-Assisted Combustion + Thermochemistry + CAD + CFD**

The objective is to develop a technically consistent computational framework for investigating a plasma-assisted hybrid rocket thrust chamber and to evaluate its performance using established propulsion analysis and CFD methodologies.

---

## 📌 Project Status

**Status:** Academic Major Project / Research and Development

**Primary Domains:**

* Aerospace Propulsion
* Hybrid Rocket Propulsion
* Plasma-Assisted Combustion
* Computational Fluid Dynamics
* Thermochemical Analysis
* CAD Design

---

## 📖 References

Relevant research papers, technical literature, analytical calculations, and project documentation are included in the repository where applicable.

---

## 👥 Project

This repository documents the design methodology, engineering calculations, CAD development, CFD investigation, and results associated with the **Plasma-Assisted Hybrid Rocket Thrust Chamber** major project.
