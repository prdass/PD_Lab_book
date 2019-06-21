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

### RPMI1640 media (Thermofisher) with no supplements

Store at 4°C.

Warm to 37°C before use.

### Sulphorhodamine B (SRB)

| Additive | Final concentration |
|------------|-------|
|SRB   |  0.4% |
|Acetic acid   |1%   |


### 10% tricholoroacetic acetic acid (TCA)

### Tris/HCl

### 40mM Crizotinib (in DMSO)


### 1% acetic acid

### TRIS/HCl buffer
Adjust pH to 10.5 (?)

###### BioRad Microplate Spectrophotometer


------------------------------------------------------------------
## Methods

### Day 1

#### Cell seeding

Remove cells from the flask according to [Steps 1-9 of the cell splitting protocol](../Protocols/Splitting_cells.md) - resulting in 10mL of cells resuspended in fresh media

###### Cell counting
1. Clean haemocytomer and coverslips with ethanol and place coverslip on top
2. Pipette 20uL of resuspended cells into onto the haemocytomer, under the coverslip
3. Using a microscope, count the numbers of cells in 3 of the 9 larger squares (1 square highlighted in red below)

![](Figure_cache/Haemocytometer.png?raw=true)

4. Take the average cell count of the three squares and multiply by 10,000 to get cells per mL
5. Calculate the desired number of cells for all wells (including extra to account for pipetting error) and the total volume of media required for all wells (including extra)
6. Divide the desired number of cells by the total cells per ml to get the volume of cells needed to get desired dilution
7. Subtract that number from the total media volume required to get the volume of media needed for the dilution

**Example:**

>3 cell counts: **115,110, 180**
>
>Average cell count = **135**
>**135 x 10,000 = 1,350,000 cells per mL** in the resuspended cells
>
>To get 7000 cells/well in a 96 well plate: round up to 110 and multiply
>**7000 x 110 = 770,000 cells** in 110 wells
>
>Total media volume for 110 wells **150uL x 110 = 16.5mL**
>
>Volume of cells required in 16.5mL **770,000/1,350,000 = 0.5704mL**
>
>**16.5mL - 0.5704mL = 15.93mL** of fresh media
>
>Final dilution = **15.93mL fresh media + 0.57mL resuspended cells**

8. Pipette 150uL of the diluted cells each well in a 96 well plate. Gently tap the place 10 times on each side to bring the cells towards the centre of each well.
9. Place lid on plate and incubate plate for 24hrs to allow cells to adhere

### Day 2

#### Setting up drug treatments

1. Using the 40mM crizotinib, make four 1 in 10 serial dilutions of crizotinib in DMSO to get concentrations of 4mM, 0.4mM. 0.04mM and 0.004mN.
2. Using the crizotinib serial dilutions, dilute them further to make 10 crizotinib concentrations. Add the amount of each crizotinib dilution specified below into a new eppendorf and add DMSO if required to ensure all wells get the same amount of DMSO.
3. Make up the 10 crizotinib dilutions to 100uL using serum free RPMI1640 media, pipetting up and down to mix solution

| Final conc uM | 11x Conc uM | 4mM | 0.4mM | 0.04mM | 0.004mM | DMSO |
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

4. Pipette 15uL of each crizotinib dilution into the wells seeded yesterday. One column per concentration and technical replicates for each concentration are in B/C/D for each column. <br>

![](Figure_cache/96wellplate.jpg?raw=true)<br>
5. Gently tap the plate 10 times on each side and incubate at 37°C for 72 hours.

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
