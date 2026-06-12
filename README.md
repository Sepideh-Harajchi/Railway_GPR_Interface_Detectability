# Railway_GPR_Interface_Detectability

This repository contains the analytical calculations, numerical simulations, experimental ground-penetrating radar (GPR) measurements, and extracted signal attributes used in the study of ballast–sand interface detectability under varying moisture conditions and antenna elevations.

The repository provides a reproducible dataset supporting the evaluation of ballast–sand interface identification, attenuation behaviour, detectability, and spatial consistency through complementary analytical, numerical, and experimental investigations.

---

# Associated publication

This repository accompanies the manuscript:

**Influence of antenna elevation and moisture conditions on GPR-based ballast–sand interface detectability in railway substructures**

Submitted to *NDT & E International*.

---

# Author

**Sepideh Harajchi**  
Department of Geoscience and Engineering  
Delft University of Technology, The Netherlands

---

# Contact

- s.harajchi@tudelft.nl
- sepideh.harajchi@gmail.com

---

# Repository structure

## 01_analytical_results

Contains analytical travel-time calculations used to predict the arrival times of the ballast–B15 interface reflection and other major reflection events discussed in the manuscript.

Contents include:

- Analytical arrival-time calculations
- Travel-time prediction tables
- Supporting calculation spreadsheets

---

## 02_numerical_results

Contains the numerical simulation models developed using gprMax.

The data are organized according to the four investigated moisture scenarios:

- Dry
- Wet1
- Wet2
- Wet3

Each scenario contains simulations for five antenna elevations:

| Model | Antenna height |
|---------|---------|
| 1 | 10 cm |
| 2 | 20 cm |
| 3 | 30 cm |
| 4 | 40 cm |
| 5 | 50 cm |

Included files comprise:

- gprMax input files (*.in)
- Simulation output files (*.out)

---

## 03_experimental_results

Contains laboratory GPR measurements acquired from the controlled railway substructure model.

The data are organized according to the four investigated moisture scenarios:

- Dry
- Wet1
- Wet2
- Wet3

Each folder contains the corresponding A-scan measurements acquired at five antenna elevations (10–50 cm), together with exported data files and visualizations.

Included files comprise:

- Experimental A-scan data (*.txt)
- A-scan visualizations (*.png)

---

## 04_attributes_extraction

Contains the extracted reflection attributes and derived metrics used in the quantitative analysis.

The provided data support the results presented in the manuscript, including:

### Reflection-strength metrics

- RMS amplitude
- Envelope RMS amplitude
- Peak amplitude
- Reflection energy

### Detectability metrics

- Signal-to-background ratio (SBR)

### Spatial-consistency metrics

- Adjacent-trace correlation
- Amplitude coefficient of variation (CV)

### Quality-control metrics

- Arrival-time stability
- Lateral coherence

This folder also contains the figures and data used to generate the attribute-based analyses presented in the manuscript.

---

# Study overview

The study investigates three primary research questions:

1. Whether the ballast–sand interface can be reliably identified under varying moisture conditions and antenna elevations using analytical, numerical, and experimental observations.

2. How antenna elevation and moisture content influence the strength and attenuation behaviour of the ballast–sand reflection.

3. How antenna elevation and moisture conditions affect the reliability and spatial consistency of interface detection.

The results demonstrate that the ballast–sand interface remains detectable across all investigated conditions, while increasing antenna elevation and moisture content progressively reduce reflection strength and detection reliability.

---

# Data availability

All data required to reproduce the analyses presented in the associated manuscript are provided within this repository, including analytical calculations, numerical simulation files, experimental measurements, extracted signal attributes, and supporting figures.
