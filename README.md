# HSTNet: Hybrid Supervision-Driven Two-Stream Collaborative Network for Hyperspectral Wheat Variety Classification
This repository contains the code (in Pylorch)
# Introduction
Hyperspectral remote sensing technology is widely
utilized in agriculture. Fine classification of wheat varieties using
hyperspectral images is essential for smart agriculture. Unfortunately,
the limited availability of spectral data and the difficulty
in collecting it have long hindered progress in wheat classification.
To cope with these issues, we design a hybrid supervised-driven
two-stream collaborative network (HSTNet), which consists of
a semi-supervised conditional generative adversarial network
for data augmentation (SCGAN) and a supervised two-stream
discriminative network (STDNet) for wheat classification. In SCGAN,
the generator constructs a mapping relationship between
input noise and real wheat hyperspectral samples to generate
fake wheat hyperspectral samples that are highly matched with
the distribution of the real sample, and the discriminator with
multilayer perceptions utilizes discriminative learning to identify
real and fake samples. In STDNet, it collaboratively extracts the
spectral, spatial and texture features of wheat hyperspectral images
employing the dual-stream branch structure of 3DCNN and
2DCNN. Subsequently, it utilizes the Fast Fourier Transform and
the cross-attention mechanism to refine and fuse these features to
improve their capability of feature expression. Noteworthy, the
individual design effectively improves the classification results of
wheat varieties via collaborative optimization among modules.
Besides, we built a mixed wheat hyperspectral dataset (MWHD)
with 4800 samples of 20 wheat varieties. Extensive experiments on
our constructed MWHD dataset demonstrate that the proposed

<img width="1806" height="270" alt="image" src="https://github.com/user-attachments/assets/502b0ac3-1eee-43ae-9931-905cc566c476" />
<img width="1798" height="316" alt="image" src="https://github.com/user-attachments/assets/edbd6a5e-57c8-4397-866d-584b065fe004" />
<img width="1802" height="638" alt="image" src="https://github.com/user-attachments/assets/99ef6597-21f2-4d0e-aaab-9e625eb08d10" />

# Dependencies
-- Python == 3.12.7
-- PyTorch == 1.10.1
-- mmde應趾ection == 2,22.0
-- mmcv == 1.4.0
-- numpy == 1.21.2
