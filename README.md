# Addressing the Spatio-Temporal Blurring Effect on Fluorescence Lifetime Imaging Microscopy

## MSSR-FLIM

This repository contains the code and data associated with the research article:

**Addressing the Spatio-Temporal Blurring Effect on Fluorescence Lifetime Imaging Microscopy**  
by Mario González-Gutiérrez, et. al.
---

## Summary

Fluorescence Lifetime Imaging Microscopy (FLIM) enables high-specificity, quantitative mapping of biochemical environments in live systems. However, spatial resolution improvements through intensity-based processing often come at the cost of **temporal blurring** — the distortion of lifetime information due to overlapping point spread functions (PSFs).

In this study, we present a framework that applies **Mean-Shift Super-Resolution (MSSR)** as a probabilistic spatial filter to raw intensity images *before* lifetime extraction. MSSR improves spatial resolution significantly **without compromising fluorescence lifetime accuracy**, as verified by **phasor analysis**.

Key contributions:
- MSSR reduces the spread of lifetime clusters without shifting their phasor centroid, preserving temporal fidelity.
- Temporal blurring persists even at 4σ emitter separation and worsens at the Sparrow limit (2σ).
- MSSR's percentile-based masking isolates high-confidence pixels and corrects fluorophore mislocalization.

This work establishes MSSR as a robust and efficient approach for enhancing spatial resolution in FLIM while preserving lifetime accuracy.

---

## Authors & Affiliations

**Authors:**  
Mario González-Gutiérrez¹, Nicolás Mateos², Wonsang Hwang³, Diana M. Vázquez-Enciso¹, Esley Torres-García⁴, Jenu V. Chacko⁵, Iván Coto Hernández⁶, Pablo Álvarez-Loza², Christopher Wood¹, Adan Guerrero¹

**Affiliations:**  
1. Laboratorio Nacional de Microscopía Avanzada, Instituto de Biotecnología, UNAM, Mexico  
2. Institut de Ciencies Fotoniques, Catalunya, Spain  
3. Wellman Center for Photomedicine, Harvard Medical School, MGH, USA  
4. Facultad de Ingeniería, Universidad de la República, Uruguay  
5. Laboratory for Optical and Computational Instrumentation, University of Wisconsin–Madison, USA  
6. Institute for Innovation in Imaging, MGH and Harvard Medical School, USA

---

## Repository Structure

├── README.md
├── requirements.txt (to be filled)
│
├── /code/ # All Jupyter Notebooks
│
└── /data/ # Input/sample datasets
