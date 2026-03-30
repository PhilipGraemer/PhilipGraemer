# Philip Graemer

PhD student in deep learning for biomedical microscopy at the [University of Strathclyde](https://www.strath.ac.uk/) and at [CeMi](https://glasgow.thecemi.org) jointly with the [University of Glasgow](https://www.gla.ac.uk), supervised by [Dr Giuseppe Di Caprio](https://dicaprio.bioe.strath.ac.uk).

I study how vision architectures learn, transfer, and fail when moved from natural images into biomedical microscopy. My current work shows that previously reported CNN superiority over Vision Transformers on single-cell classification can be an artefact of uncontrolled pretraining, and that standard optimisation recipes can unexpectedly hurt under domain shift. I also found that ViTs such as EVA-02 make excellent distillation teachers for small deployable models such as EN-B0, imparting better dark knowledge than CNNs.

On the other side of my research I am interested in the optics of microscopy, especially phase contrast and QPI, as well as in the differentiation and morphology of a variety of human cell types.

Future/current work includes work on time series prediction of human Mesenchymal Stem Cell differentiation and in-domain vs cross-domain SSL Dino for classification.


### Current projects

- **Controlled CNN–ViT benchmark on LIVECell**: Systematic comparison of eleven architectures (CNNs, ViTs, hierarchical transformers) with matched pretraining conditions. Manuscript in preparation.
- **PhaseDINO**: Domain-adaptive self-supervised learning for phase contrast microscopy via DINO-style pretraining.
- **Cross-architecture knowledge distillation**: Investigating why weaker teachers (EVA-02) can outperform stronger ones (EfficientNet-B5) when distilling across architecture families.

### Tech

`PyTorch` · `timm` · `PyTorch Lightning` · `NVIDIA A100 / RTX Pro 6000` · `Mixed precision` · `AdamW` · `WandB`

### Links

- 📧 [philip.graemer@strath.ac.uk](mailto:philip.graemer@strath.ac.uk)
- 🔬 [Di Caprio Lab](https://dicaprio.bioe.strath.ac.uk)
- 🌐 [Personal site](https://philipgraemer.github.io)
  

<!--
**PhilipGraemer/PhilipGraemer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
