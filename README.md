# 2.0 MR-Eye

A repository for all acquisition, reconstruction, and analysis code associated with the registered report submission.

The standard operation procedure is available [here](https://mattechlab.github.io/sops/debi/data-collection/data-collection_DEBI_protocol/).


## 🚀 **Overview**

This repository provides full transparency into every step of the experimental pipeline, as follows:
1.	MR Data Acquisition
    - [Sequence implementations](https://github.com/MattechLab/pulseq4mreye) using Pulseq for control of MR pulse sequences. 
    - [Codes](https://github.com/Evelyn92/MREye_psychopy) for generating eye‑tracking visual stimuli implemented using PsychoPy.
2. MRI Image Reconstruction
    - [ET data processing](https://github.com/Evelyn92/hcph-sops-fork) for ET mask generation.
    - [Reconstruction scripts](https://github.com/Evelyn92/Recon_scripts) leveraging the Monalisa Reconstruction Toolbox to convert raw k-space data into images.
3.	Data Analysis & Conversion
    - [Alignment, preprocessing](https://github.com/Evelyn92/Recon_scripts/tree/master/func/spm_related), statistical analysis, and format conversion (e.g. DICOM to NIfTI/ MAT to BIDs).
