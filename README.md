# MELT: A Style-Adaptive Multimodal Folktale Generation Framework for Underrepresented Cultures

MELT is a multimodal framework for culturally adaptive folktale generation across text, image, and audio.  
It is designed to support underrepresented traditions through lightweight, data-efficient adaptation.
This repository provides core components of the text generation, LoRA-based style adaptation, and text-to-image (T2I) pipelines described in our paper.

---

## Repository Structure

### Image/
Core image-generation notebooks:

- `MELT_T2I.ipynb` – Main T2I pipeline used for MELT experiments  
- `SDXL_T2I.ipynb` – Baseline image generation using SDXL 1.0  
- `kohya_LoRA_SDXL.ipynb` – LoRA training pipeline for SDXL-based style adaptation  

These notebooks reflect the primary experimental setup used in the study.

---

### Text/
Text generation and prompt construction notebooks:

- `TextGeneration_Korean.ipynb`  
- `TextGeneration_Bengali.ipynb`  
- `imagePromptGeneration.ipynb`  

These files provide representative implementations of the text generation and prompt formulation process described in the manuscript.

---

### Loras/
This folder contains a subset of the datasets and LoRA structures used during training.

Due to dataset licensing conditions, file size limitations, and project organization decisions, only part of the original materials is included in this public release. The provided files illustrate the training structure and directory format used in our experiments.

---

## Running the Code

All `.ipynb` files can be executed in Google Colab.

Basic workflow:

1. Upload or clone the repository into your Colab environment.  
2. Install required dependencies (e.g., Diffusers, Transformers).  
3. Upload the necessary LoRA weight files.  
4. Adjust file paths inside the notebooks as needed.  
5. Execute the notebooks sequentially.

---

## Reproducibility

This repository contains the core experimental pipelines used in the paper.  
Some auxiliary scripts, intermediate experiment variants, and large-scale assets are not included in this release.

The goal of this repository is to provide sufficient materials to understand and reproduce the main methodology described in the manuscript.

For questions regarding reproducibility, please open an issue.

---

## Citation

If you use this work in your research, please cite:

@article{MELT2026,
  author    = {Hanbi Choi and Yuri Kim and Dohee Kim and Heejae Shin and Minsu Lee},
  title     = {MELT: A Style-Adaptive Multimodal Folktale Generation Framework for Underrepresented Cultures},
  journal   = {Forthcoming / Under Review},
  year      = {2026},
  url       = {https://dori943.github.io/MELT.github.io/}
}

---

## License

This repository is released for academic research purposes.  
For inquiries regarding commercial use or redistribution, please contact the authors.

© 2026 MELT Research Team
