# Python_for_Pharmacometrics
Python for Pharmacometrics: a hands-on guide to modelling, simulation, and data pipelines. Learn how to build, estimate and validate PK/PD models, run population analyses and clinical trial simulations, integrate ML methods, and ensure reproducible workflows. All code in Python, open-source and ready to use

Content:
1. Data Specification
2. Data Check
3. SAD Pk
4. MAD PK
5. PD/Efficacy/Safety
     5.1. Continuous
     5.2.  Binary Response
     5.3. Ordinal response
     5.4. Count Data
     5.5. Time to event
6. Pk/Pd/Efficacy/Safety
     6.1. Continous
     6.2. Binary Response
     6.3. Ordinary Response
     6.4. Count Data
     6.5.Time-to-event
7. Data Summary
8. Basic Plotting
9. Data Assembly
10. Advance Ploting
11. Modeling
12. Advance functional Writing
13. Advanced data Assembly
14. Advanced Graphics

AE:
Adverse Event (AE) data from multiple dose administration of a range of 20 mg to 60 mg doses.

Data specifications
|Column name	| Description|
|---|---|
|SUBJID |	Subject ID|
DAY	Day of the AE
time	Day of the AE in (h)
Dose	Dose
AUC	Cumulative AUC at AE day
Cmax	Cmax at AE day
Cmin	Cmin at AE day
Cave	Caverage at AE day
AUCDAY1	AUC at day 1
AUCAVE	Average AUC up to the AE day
AETOXGRS	AE grades (Character)
AETOXGRDN	AE grades (numenric)
AE	Binary YES/NO AE

