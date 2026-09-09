# Philip Graemer

PhD researcher in deep learning for biomedical microscopy at the
[University of Strathclyde](https://www.strath.ac.uk/) and
[CeMi](https://glasgow.thecemi.org), jointly with the
[University of Glasgow](https://www.gla.ac.uk/), supervised by
[Dr Giuseppe Di Caprio](https://dicaprio.bioe.strath.ac.uk).

I study how vision architectures learn, transfer, and fail when moved from natural images into biomedical microscopy. 

My current work shows that previously reported CNN superiority over Vision Transformers on single-cell classification tasks can be an artefact of uncontrolled pretraining, and that standard optimisation recipes can unexpectedly hurt under domain shift. I also found that ViTs such as EVA-02 make excellent distillation teachers for small deployable models, seemingly imparting better dark knowledge than either CNNs or mixed councils of ViTs and CNNs. I am also interested in efficient deployment. Teacher-council knowledge
distillation allows a compact EfficientNet-B0 student to outperform every individual
backbone in our benchmark while retaining the inference architecture of the small model.

A second strand of my research concerns microscopy and cell biology more directly, especially phase contrast imaging, quantitative phase imaging (QPI), and the morphology and differentiation of human cell types. The broader aim is to use microscopy and machine learning to overcome bottlenecks in biomedical experiments.

More broadly, I work on self-supervised representation learning for microscopy,
phase-contrast and quantitative phase imaging, and machine-learning approaches to
cellular identity, state, and differentiation.

### Current projects

- **Controlled CNN–ViT benchmark on LIVECell** — matched pretraining, leakage-safe
  evaluation, tokenisation and fine-tuning experiments, and deployment analysis. 📊
- **Cross-architecture knowledge distillation** — single-teacher and council
  distillation into compact deployable models. ⚗️ 🐛>🦋
- **PhaseDINO** — domain-adaptive self-supervised representation learning for
  phase-contrast microscopy. 🦖
- **Robust single-cell datasets** — phase contrast, QPI and DIC data across
  instruments, acquisition settings, days, facilities and cell types. 🧫
- **Differentiation time-series prediction** — label-free prediction of human
  mesenchymal stem-cell state and differentiation trajectories. ​📈​

### Tools

PyTorch · timm · DINO / DINOv3 · Vision Transformers · EfficientNet ·
mixed-precision training · NVIDIA A100 / H100  / RTX Pro 6000 · SLURM

### Links

- 🌐 [Personal site](https://philipgraemer.github.io)
- 💻 [GitHub](https://github.com/PhilipGraemer)
- 🔬 [Di Caprio Lab](https://dicaprio.bioe.strath.ac.uk)
- 📧 [philip.graemer@strath.ac.uk](mailto:philip.graemer@strath.ac.uk)
