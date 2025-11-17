# HSTNet: Hybrid Supervision-Driven Two-Stream Collaborative Network for Hyperspectral Wheat Variety Classification
This repository contains the code (in Pylorch)
# Introduction
WITH the rapid advancement of breeding technologies,
the number of wheat hybrid varieties has grown substantially,
showing notable differences in growth traits and
disease resistance. Accurate classification of wheat varieties is
therefore essential not only for precise field management but
also for improving yield and optimizing quality. However, the
coexistence of mixed varieties, the large number of categories,
and the high similarity of phenotypic features pose new
challenges for modern smart agriculture [1, 2]. Hyperspectral
imaging has been widely adopted in agricultural management
because of its ability to capture fine spectral details of crops at
the nanoscale [3, 4]. Compared with the traditional chemical
composition analysis method, deep learning technology combined
with hyperspectral images can be more comprehensively
and accurately applied to the classification and identification
of different varieties of crops in agriculture [5–7], which
provides a solid theoretical foundation and technical support
for crop planting optimization and yield augmentation and
injects a new impetus for the sustainable development and
modernization transformation of smart agriculture.
In the data augmentation, existing studies have proved that
the diversity and richness of generated samples can improve
the effectiveness and robustness of deep learning methods for
different visual tasks [8–12]. Currently, researchers mainly focus
on data augmentation and network optimization to improve
the accuracy of deep learning for wheat variety classification.
In terms of data augmentation, traditional methods mainly
include random cropping and flipping, channel swapping, and
interpolation [13, 14], while deep learning mainly includes
generative adversarial network (GAN) [15, 16] and variational
autoencoder (VAE) [17]. Although traditional methods are
straightforward and easy to apply, they have inherent limitations.
For instance, they fail to fully exploit the spatial
and spectral features of hyperspectral images and struggle
to accurately model the distribution of natural interference
factors and real-world data. To address the above challenges,
VAE utilizes the latent probability distribution of the learning
