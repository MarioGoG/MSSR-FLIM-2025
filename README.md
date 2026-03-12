# Addressing the Spatio-Temporal Blurring Effect on Fluorescence Lifetime Imaging Microscopy

## MSSR-FLIM

This repository contains the code and data associated with the research article:

**PSF-Driven Spatio-Temporal Blending in Fluorescence Lifetime Imaging Microscopy and Its Mitigation via Mean-Shift Super-Resolution–Based Masking**, by Mario González-Gutiérrez, et. al.

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
Mario González-Gutiérrez¹, Diana M. Vázquez-Enciso¹, Nicolás Mateos², Wonsang Hwang³, Esley Torres-García⁴, Haydee O. Hernández⁵, Jenu V. Chacko⁶, Iván Coto Hernández⁷, Pablo Álvarez-Loza², Christopher Wood¹, Adan Guerrero¹<sup>,</sup>⁸<sup>,</sup>*

**Affiliations:**  
1. Laboratorio Nacional de Microscopía Avanzada, Instituto de Biotecnología, Universidad Nacional Autónoma de México, Cuernavaca, Morelos, Mexico.
2. Institut de Ciencies Fotoniques, Castelldefels, Catalunya, Spain.
3. Wellman Center for Photomedicine, Harvard Medical School, Massachusetts General Hospital, CNY149, 13th St, Charlestown, 02129, MA, USA.
4. Facultad de Ingeniería, Universidad de la República, Montevideo, Uruguay. 
5. Centro de Investigación en Ciencias, Universidad Autónoma del Estado de Morelos, Cuernavaca, Morelos, Mexico.
6. Laboratory for Optical and Computational Instrumentation, University of Wisconsin at Madison, 1675 Observatory Dr., Madison, WI 53706, USA.
7. Center for Interdisciplinary Innovation in Imaging, Massachusetts General Hospital and Harvard Medical School, 149 13th St, Charlestown, 02129, MA, USA.
8. Centro Internacional de Ciencias AC. Cuernavaca, Morelos, Mexico.


---

## Repository Structure

├── README.md
├── requirements.txt (to be filled)
│
├── /code/ # All Jupyter Notebooks
