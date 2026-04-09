Design and Analysis of a 100 mm f/8 Singlet Lens Using Zemax OpticStudio
Author: Surya Mallick
Software: Ansys Zemax OpticStudio 2025 R2 (Student Edition)

Overview: This project demonstrates the complete optical design workflow for a 100 mm f/8 singlet lens, including system setup, optimization, and image‑quality evaluation using Zemax OpticStudio. The goal is to understand the aberration behavior of a simple singlet and analyze its performance using spot diagrams, MTF, and longitudinal aberration.

System Specification: 
The optical system was defined using the following parameters-
Effective Focal Length:	~ 100mm
f number:	f/8
Aperture Radius:	12.5 mm
Wavelengths	0.486 µm, 0.587 µm, 0.656 µm
Field Angles	0°, +5°, –5°
Image Space:	Afocal
Entrance Pupil Diameter:	25mm

Design Workflow:
- Defined system parameters (EFL, f/#, aperture)
- Built initial singlet model
- Optimized R1, R2, and thickness
- Used Quick Focus to find best image plane - (~107.5 mm)
- Evaluated performance using:
- Spot Diagram
- FFT MTF vs Field
- Longitudinal Aberration
  
Results Summary:
Spot Diagram
- Compact on‑axis spot
- Coma dominates off‑axis
- Astigmatism visible at ±5°
- Chromatic spread across wavelengths
  
MTF:
- Moderate on‑axis contrast at low frequencies
- High‑frequency MTF drops due to spherical + chromatic aberration
- Off‑axis MTF collapses due to coma + astigmatism
  
Longitudinal Aberration:
- Strong chromatic aberration (blue/green/red separation)
- Strong spherical aberration (curved ray focus lines)
- Best focus is a compromise point

 Key Learnings:
- Singlet lenses suffer from significant aberrations
- Chromatic and spherical aberration dominate on‑axis
- Coma and astigmatism dominate off‑axis
- MTF and LA plots explain the image quality limitations

 Future Work:
- Replace singlet with an achromatic doublet
- Add aspheric surfaces
- Optimize for wider field of view
- Build an AI surrogate model to predict MTF or spot size


