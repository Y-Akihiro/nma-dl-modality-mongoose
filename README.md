# NMA-DL Modality Mongoose Project

This project aims to translate between MRI modality types using deep learning.

The code in this repository is **heavily** inspired by the [Pytorch implementation of vox2vox](https://github.com/enochkan/vox2vox), a 3D volume-to-volume generative adversarial network proposed by [M. Cirillo, D. Abramian and A. Eklund](https://arxiv.org/abs/2003.13653)


## Abstract
### TransModalityGAN: Image-to-Image Modality Translation for Human Brain MRI

Magnetic resonance imaging (MRI) is a relatively cheap and noninvasive medical imaging technology that is heavily used in the clinic and research. With its different submodalities, MRI can capture static anatomical information (T1w and T2w), record neuronal activation (BOLD or fMRI), and map the white-matter tracts inside the brain (diffusion-weighted imaging or DWI). These modalities are related by implicit and complex non-linear relationships. Previous work has yielded generative models that can translate between different structural MRI modalities, but it remains an open question whether diffusion-weighted information can be generated from purely structural images. Here, we adapt a conditional generative adversarial network (cGAN), originally developed for brain image segmentation, to the translation between MRI modalities. Using data from the Human Connectome Project (HCP), we (pretend to) demonstrate that this network is able to translate between structural image modalities, but is unable to generalize to DWI. Furthermore, we show that including related brain tissue properties and connectivity information from resting state fMRI and structural data enables the generation of realistic synthetic DWI. Our modality generation method can serve as an auxiliary MRI method where multiple modality acquisition is prohibitive. It may also guide future research relating structural and functional connectivity. Future work should test if these generative networks can also be applied in clinical populations.

