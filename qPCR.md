# QPCR Protocol
The qPCR machine is located in the Bowen Lab. Please coordinate with their lab before using the machine.

## What you need before you start
* Kit: KAPA Library Quantification Kit (Universal) (Cat #: KK4923)
* Specific strip tubes & caps: Agilent AriaMx 96 Tube Strips (Cat #: ) & Agilent Optical Cap, 8x Strip (Cat #: )
* Make a stock of 10 mM Tris-HCl + 0.05% Tween-20 (optional but recommended for the dilution of library DNA, as it leads to improved accuracy by reducing the adherence of DNA to plastic surfaces)
* Copy of KAPA Protocol [Found here](https://rochesequencingstore.com/wp-content/uploads/2017/10/KAPA-Lib-Quant-ILMN_9.17-IfU_1.pdf)
* Ensure qPCR reagents are thawed and properly mixed. If the kit is new, the 2X KAPA SYBR-FAST qPCR Master Mix (5mL) should be combined with 1 mL 10X Illumina Primer Premix and then aliquoted out. These should be labeled with the date it was mixed because once mixed the reagent is only good for (*60 days double check that timeframe*). 
* 1.5 mL microcentrifuge tube per library
* Previously quantified libraries and their concentrations

## Step 1: Make library dilutions
* Libraries need to be diluted to be read on the QPCR machine. All dilutions should be done in 10 mM Tris-HCl + 0.05% Tween-20. First dilute sample to a 1:1000 concentration in a 1.5mL microcentrifuge tube (Table 1). 

### Table 1:
|---------------|---------------------------|
| 10 mM Tris-HCl + 0.05% Tween-20 | 999 uL  |
| Library DNA                     | 1 uL    |
| Total                           | 1000 uL |

* Next dilute your sample libraries to ensure they fall within the range of the standards provided by the KAPA kit (Table 2). Typically for a library in the range of 1-200 ng/uL you need a 1:18000 dilution to be read on the QPCR machine. However, you can use the calculation below to determine what you need to dilute your undiluted library down to:

### Calculation 1 - determining library concentration in pM: 

* Calc 1: (Undiluted Library Conc. (ng/uL)/ (617.9 g/mol * fragment size of library)) * 10^6 = undiluted library in nM
 
* Calc 2: undiluted library in nM * 1000 = undiluted library in pM

* Calc 3: dilute final library to be in the range of the standards in Table 2

### Table 2:
| Standard Name | dsDNA concentration (pM) |
|---------------|--------------------------|
| Standard 1    | 20                       |
| Standard 2    | 2                        |
| Standard 3    | 0.2                      |
| Standard 4    | 0.02                     |
| Standard 5    | 0.002                    |
| Standard 6    | 0.0002                   |


## Step 2: qPCR setup
* qPCR reactiions for the six standards and each liibrary dilutiioin must be set up in triplicate. Load each well of the qPCR plate as indicated below in Table 3, for a total reaction volume of 20 uL. 

### Table 3:
| KAPA SYBR FAST qPCR Master Mix containing Primers | 12 uL |
| PCR-grade water                                   | 4 uL  |
| Diluted dsDNA library dsDNA Standard (1-6)        | 4 uL  |
| Total                                             | 20 uL |

* Ensure that the qPCR plate is sealed. 
* Collect all components in the bottom of the well by brief centrifucation. 