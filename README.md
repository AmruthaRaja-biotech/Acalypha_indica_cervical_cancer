# Bioactive Compounds in *Acalypha indica* for Cervical Cancer Inhibition

> 🔬 **Status: Active Research** — Ongoing at Hindustan Institute of 
> Technology and Science, Chennai  
> 📄 **[View Full Project Report](report/acalypha_indica_full_project_report.pdf)**

---

## Overview

Cervical cancer remains one of the leading causes of cancer-related
mortality among women globally, particularly in developing countries,
with HPV-associated protein targets presenting viable candidates for
phytochemical-based drug discovery. This project investigates the
anticancer potential of bioactive compounds isolated from *Acalypha
indica* (Indian Nettle, Family: Euphorbiaceae) — a medicinally
significant plant in traditional Ayurvedic and Siddha systems —
through an integrated computational and experimental approach
targeting Bcl-2 and HPV E6 proteins associated with cervical cancer
progression.

---

## Objectives

- Perform qualitative phytochemical screening of *Acalypha indica* extract
- Identify bioactive compounds using GC–MS analysis
- Evaluate molecular interactions of selected compounds with cancer-related
  proteins (HPV E6, Bcl-2) using SwissDock and AutoDock Vina
- Assess pharmacokinetic properties through ADME analysis
- Determine cytotoxic effects on HeLa cells using MTT assay
- Evaluate apoptosis through DNA fragmentation analysis

---

## Methodology

| Step | Tool / Technique |
|------|-----------------|
| Plant extraction | Aqueous & ethanolic extraction |
| Phytochemical screening | Qualitative chemical tests (Wagner's, Salkowski, Keller-Killiani) |
| Compound identification | GC–MS (DB-5 column, Helium carrier gas) |
| Protein structure retrieval | RCSB Protein Data Bank (PDB) |
| Ligand preparation | PubChem database |
| Molecular docking | SwissDock / AutoDock Vina |
| ADME profiling | SwissADME |
| Cytotoxicity | MTT assay (HeLa cells, 96-well plate) |
| Apoptosis confirmation | DNA fragmentation — Agarose gel electrophoresis |
| Data analysis | Microsoft Excel |

---

## Phytochemical Screening Results

Qualitative phytochemical screening of *Acalypha indica* extract
confirmed the presence of the following secondary metabolites:

| S.No | Phytochemical | Result |
|------|--------------|--------|
| 1 | Alkaloids | +++ (Strong) |
| 2 | Saponins | – (Absent) |
| 3 | Flavonoids | +++ (Strong) |
| 4 | Tannins | +++ (Strong) |
| 5 | Terpenoids | ++ (Moderate) |
| 6 | Quinones | +++ (Strong) |
| 7 | Cardiac Glycosides | ++ (Moderate) |

> Note: (–) Not detected | (+) Mild | (++) Moderate | (+++) Strong

---

## GC–MS Analysis — Key Compounds Identified

GC–MS analysis identified multiple phytoconstituents. Three compounds
were selected for computational studies based on biological relevance:

| S.No | Retention Time (min) | Compound | Molecular Formula | MW | Peak Area (%) |
|------|---------------------|----------|------------------|----|---------------|
| 1 | 5.298 | Phenol | C₆H₆O | 94.11 | 50.19 |
| 2 | 6.967 | Acetic acid, 2-ethylhexyl ester | C₁₀H₂₀O₂ | 172.26 | 5.22 |
| 3 | 10.378 | **2,4-di-tert-butylphenol** ⭐ | C₁₄H₂₂O | 206.32 | 0.49 |
| 4 | 11.877 | Hexadecane, 2,6,10,14-tetramethyl | C₂₀H₄₂ | 282.55 | 3.98 |
| 5 | 12.100 | Pyridine-3-carboxamide, oxime | C₆H₇N₃O | 137.14 | 0.31 |
| 6 | 12.207 | Hexadecane, 2-methyl | C₁₇H₃₆ | 240.47 | 2.77 |
| 7 | 12.759 | **Tetradecanal** ⭐ | C₁₄H₂₈O | 212.37 | 1.00 |
| 8 | 13.078 | 1,2-Benzenedicarboxylic acid | C₈H₆O₄ | 166.13 | 0.34 |

⭐ Selected for molecular docking studies

---

## Molecular Docking Results

Docking performed against **Bcl-2** and **HPV E6** — two key proteins
in cervical cancer progression:

| S.No | Ligand | Target Protein | Binding Affinity (kcal/mol) |
|------|--------|---------------|-----------------------------|
| 1 | 2,4-di-tert-butylphenol | HPV E6 | -5.423 |
| 2 | **2,4-di-tert-butylphenol** | **Bcl-2** | **-6.010** 🏆 |
| 3 | Tetradecanal | HPV E6 | -4.187 |
| 4 | Tetradecanal | Bcl-2 | -4.772 |
| 5 | Pyridine-3-carboxamide | HPV E6 | -4.236 |
| 6 | Pyridine-3-carboxamide | Bcl-2 | -4.711 |

🏆 **Lead compound:** 2,4-di-tert-butylphenol showed the highest
binding affinity with Bcl-2 (−6.01 kcal/mol), indicating a stable
interaction with this key anti-apoptotic regulator in cervical cancer.

---

## ADME Analysis

Pharmacokinetic properties evaluated using SwissADME:

| Property | 2,4-di-tert-butylphenol | Tetradecanal | Pyridine-3-carboxamide |
|----------|------------------------|--------------|------------------------|
| Lipinski Rule | ✅ Yes; 0 violations | ✅ Yes; 0 violations | ✅ Yes; 0 violations |
| GI Absorption | High | High | High |
| Bioavailability Score | 0.55 | 0.55 | 0.55 |
| Drug-likeness | High | Moderate | Moderate |

**2,4-di-tert-butylphenol** demonstrated the most favourable
drug-likeness profile among all three compounds.

---

## Cytotoxicity — MTT Assay Results

Effect of *Acalypha indica* extract on HeLa cervical cancer cell viability:

| Concentration (µg/mL) | Cell Viability (%) | OD |
|-----------------------|-------------------|-----|
| Control | 100 | 0.093 |
| 15.62 | 89.2 | 0.083 |
| 31.25 | 74.1 | 0.069 |
| 62.5 | 59.8 | 0.056 |
| 125 | 50.1 | 0.047 |
| 150 | 32.95 | 0.031 |

> **IC₅₀ observed at ~125 µg/mL** — significant dose-dependent
> cytotoxic activity against HeLa cells confirmed.

---

## DNA Fragmentation Analysis

DNA fragmentation analysis of HeLa cells treated with *Acalypha indica*
extract at IC₅₀ concentration demonstrated a **distinct ladder-like
pattern**, confirming induction of **apoptosis** (programmed cell
death) rather than necrosis. Untreated control cells showed intact
genomic DNA.

---

## Repository Structure
