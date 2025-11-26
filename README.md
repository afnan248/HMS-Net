<h1 align="center">HMS-Net: Hybrid Multi Directional Mamba Segmentation Network with Boundary Enhancement for Medical Image Segmentation</h1>
<p align="center">
  Authors:
  <a href="https://scholar.google.com/citations?user=UngixbEAAAAJ&hl=en">Afnan Ghafoor</a>,
  <a href="https://scholar.google.com/citations?user=maY0q9IAAAAJ&hl=en">Bumshik Lee</a>
</p>

## Abstract

Accurate medical image segmentation demands models that simultaneously capture long-range anatomical context and preserve precise boundaries under real clinical conditions such as artifacts, low contrast, and cluttered backgrounds, yet no existing architecture achieves this balance effectively. CNNs remain inherently limited by local receptive fields, transformers incur prohibitive quadratic complexity and often degrade fine structure, and recent Mamba-based networks still rely on a single-direction state-space formulation that fails to model anisotropic anatomical variability or maintain boundary fidelity. To overcome these fundamental limitations, we present a Hybrid Multi-Directional Mamba Segmentation Network embedded in the nnU-Net framework, introducing a multi-directional state-space modeling module for efficient and comprehensive spatial dependency learning, a dedicated boundary enhancement pathway for highly precise contour recovery, and a hybrid fusion strategy that seamlessly unifies global semantics with local structural detail. On ISIC 2018 and ISIC 2017, our model achieves new state-of-the-art results of 0.8207 / 0.9115 and 0.8326 / 0.9133 in JI/Dice, and on the highly challenging EndoVis 2017 benchmark, it markedly surpasses strong baselines with 0.7628 DSC and 0.7121 NSD while delivering substantially improved stability across sequences. Ablation analyses confirm that each proposed innovation is indispensable, clearly demonstrating that our architecture addresses core weaknesses of CNN-, Transformer-, and existing Mamba-based models, setting a new standard for high-accuracy, boundary-aware segmentation in both diagnostic and surgical environments.


## Paper submitted. Repository prepared for release after acceptance
