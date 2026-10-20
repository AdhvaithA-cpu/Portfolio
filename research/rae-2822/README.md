# Transonic RAE 2822 Airfoil Research

**Poster authors:** Adhvaith Ananth, Raad Haque, and Dr. Hamid Sadat  
**Institution:** Texas Academy of Mathematics and Science / University of North Texas  
**Status:** Ongoing research; preliminary results

[Read the original research poster (PDF)](research-poster.pdf)

![Research poster showing the mesh, computational setup, preliminary results, and validation limitations](poster-preview.png)

## Research question

Can a refined structured mesh and the k–omega SST turbulence model reproduce published pressure distributions and shock location for the RAE 2822 airfoil?

## Methods and contribution

Adhvaith prepared geometry and structured meshes in ANSYS ICEM CFD, ran compressible-flow simulations in ANSYS Fluent, and examined pressure coefficients, Mach contours, lift, drag, residuals, and wall y-plus under the mentorship of Raad Haque and Dr. Hamid Sadat.

| Parameter | Setup |
| --- | --- |
| Geometry | Two-dimensional RAE 2822 airfoil |
| Mach number | 0.75 |
| Angle of attack | 3.19 degrees |
| Reynolds number | 6.2 million |
| Turbulence model | k–omega SST |

## Results and limits

The preliminary solution captures acceleration, shock formation, and pressure recovery. **Quantitative benchmark validation has not yet been achieved.** Mesh quality and convergence remain under investigation. Shock-control bumps are planned future work after baseline validation.

This repository contains the poster, not raw simulation data, ANSYS case files, or a reproducible solver package. References and acknowledgments remain in the original PDF.

[Related literature review](../../writing/transonic-airfoil-review/) · [Back to portfolio](../../README.md)
