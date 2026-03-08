# REVIVE 3D: Refinement via Encoded Voluminous Inflated Prior for Volume Enhancement

[![Project Page](https://img.shields.io/badge/Project-Page-blue.svg)](https://guts4.github.io/REVIVE3D/)
[![Conference](https://img.shields.io/badge/CVPR-2026-red.svg)]()
[![Paper](https://img.shields.io/badge/Paper-Coming_Soon-lightgrey.svg)]()

![REVIVE 3D Architecture](https://raw.githubusercontent.com/guts4/REVIVE3D/pages/assets/architecture.png)

## 📖 Overview

Recent generative models still struggle to generate voluminous 3D assets when the input is a flat image that provides limited 3D cues. We introduce **REVIVE 3D**, a two-stage, plug-and-play pipeline for generating voluminous 3D assets from flat images. 

* **Stage 1 (Inflated Prior):** We construct an Inflated Prior by inflating the foreground silhouette to recover global volume and superimposing part-aware details to capture local structure. 
* **Stage 2 (3D Latent Refinement):** We inject Gaussian noise into the Inflated Prior's latent and then denoise it, guided by the prior's geometric cues and the backbone's pretrained 3D knowledge.

Our framework also supports image-conditioned 3D editing by initializing the process with the encoded latent of a source mesh.

## 🚀 Code Release

* [ ] Release **Stage 1** code (Inflated Prior generation)
* [ ] Release **Stage 2** code (3D Latent Refinement)

**Please stay tuned! The code will be available soon.**

---
**Citation**
*Citation information will be updated once the paper is published.*
