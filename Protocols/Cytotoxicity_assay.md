# Cytotoxicity assay protocol
- **Paper:**
- **Authors:**
- **Date:**

------------------------------------------------------------------
## Overview

In order to measure the cytotoxic activity of a compound (or several compunds) the H3122 cells are seeded in 96-well plates at a known density and allowed to adhere. They will then be treated with different concentrations of the compound of interest. After 72 hours of incubation with the compound, cells are fixed and stained with SRB to dye to protein content of each well. The dye is solubilised and the absorbance of each well is read to measure the effects of the treatment.

------------------------------------------------------------------
## Materials

### RPMI1640 media (Thermofisher) for ELM4-ALK H3122 cells

| Additive |  Final Concentration   |
| :------  | :-------- |
| FBS | 5% |
| Penicillin/Streptomycin  | 1% |

Store at 4°C.

Warm to 37°C before use.

### Sulphorhodamine B (SRB)

| Additive | Final concentration |
|------------|-------|
|SRB   |  0.4% |
|Acetic acid   |1%   |


### 10% tricholoroacetic acetic acid (TCA)

### Tris/HCl

### Crizotinib (dissolved in 0.1% DMSO)

| Final conc uM | 11x Conc | 4mM | 0.4mM | 0.04mM | 0.004mM | DMSO |
| ------------- |:-------------:|:-------------:|:-------------:|:-------------:|:-------------:| -----:|
|0   |  0 |  - | -  | -  | -  |  2.75 |
|0.005   | 0.055  |  - |  - | -  | 1.375  | 1.375  |
|0.01   | 0.11  | -  |-   |  - | 2.75  |  0 |
|0.05   | 0.55  |  - | -  |1.375   |-   |1.375   |
|0.1   |  1.1 |  - | -  | 2.75  | -  |0   |
|0.25   | 2.75  |  - |  0.69 | -  | -  |  2.06 |
|0.5   |  5.5 | -  |   1.375| -  | -  | 1.375  |
|1   | 11  | -  |  2.75 | -  |  - | 0  |
|5   |  55 | 1.375  | -  | -  |  - |   1.375|
|10   | 110  | 2.75  | -  |  - | -  |  0 |

### 1% acetic acid

### TRIS/HCl buffer
Adjust pH to 10.5 (?)

###### BioRad Microplate Spectrophotometer


------------------------------------------------------------------
## Methods

### Day 1

#### Cell seeding



### Day 2

#### Setting up drug treatments


### Day 5

#### Staining

-  (Wellcome)
1. Use aspirator to remove media from each well
-  (Adams)
2. Add 0.1mL of 10% TCA and incubate on ice or in cold room to fix cells
3. Wash with dH20 remove to remove TCA, using a container to submerge the plate
4. Invert the plate onto a paper towel to dry at room temperature (or for 45 minutes in gel drier)
5. Add 0.1mL of 10mM Tris/HCl and incubate (what temperature?) for solubilise dye


#### Plate reader
1. Read single reading at 510nm plate reader
2. Open 'Microplate manager' -> File -> New Endpoint Protocol -> Enter wavelength (510nm or 490-630nm)
3. Place plate in reader and click Run


#### Data analysis
1. Copy data table into Excel
2. Plot absorbance against cell number to generate growth curve
3. Open data in Graphpad Prism
4. Use growth curve to calculate cell number from absorbance and cell number  as percentage of controls

--------------------------------------------------------
### Notes
1. When using aspirator remove from wall before turning off the handle.
2. When washing with acetic acid (300mL) make sure the whole well is covered to remove excess dye - plate reader will pick it up
