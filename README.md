# U24ClinicalImaging
This dataset includes baseline and post-treatment diffusion-weighted MRI (DW-MRI) and dynamic contrast-enhanced MRI (DCE-MRI) from a pancreatic cancer patient enrolled in clinical trial entitled “A Randomized Pilot Study of Perioperative Nivolumab and Paricalcitol to Target the Microenvironment in Resectable Epithelial Subtype Pancreatic Cancer” (NCT03519308). 

MRI data were obtained on a Siemens 1.5T system.

Imaging parameters for DW-MRI:
* Sequence: Single-shot EPI (free-breathing)
* FOV = 380x380 mm2
* Reconstructed matrix size = 192x192
* Slice thickness = 9 mm, with 1 mm between slices
* Number of slices = 16
* Echo spacing = 0.69 ms
* 8 b-values: 0, 50, 100, 200, 500, 800, 1200, 2000
* Bandwidth = 1735 Hz/pixel
* Flip angle = 90 degrees
* TR = 2400 ms
* TE = 79 ms

Imaging parameters for DCE-MRI:
* Sequence: 3D hybrid golden-angle stack-of-stars spoiled gradient echo acquisition with KWIC processing (free-breathing)
* FOV = 380x380 mm2
* Reconstructed matrix size = 256x256
* Slice thickness = 5 mm
* Number of slices = 32
* Total number of view angles = 3520
* Bandwidth = 100 Hz/pixel
* Flip angle = 25 degrees
* TR = 3.66 ms
* TE = 1.74 ms
* Injection begins ~1 min 30 sec after scan begins
* Effective temporal resolution = 5.234 s
* Total number of temporal frames = 64
* Contrast agent = Dotarem (at 0.2 mL/kg, assumed relaxivity = 3.6 mL/mM/ms)


