# mlpf-truth

This repository is developed in parallel with existing machine-learning–based particle-flow and reconstruction projects, in particular:

- **particleflow** — https://github.com/jpata/particleflow  
- **particlemind** — https://github.com/erwulff/particlemind  

Some code and ideas are shared across these repositories.

The purpose of this repository is to develop **standalone, reusable code for defining and studying ground-truth information** for ML-based reconstruction tasks.

Where relevant, this work interfaces with common event data models such as **EDM4hep**:
- https://github.com/key4hep/EDM4hep

---

## Code setup

```bash
conda env create -f environment.yml
conda activate mlpf-dev
