# Steam Lightweight-GAN

![Examples of generated Steam banners][cover-illustration]

The goal of this [Colab][colab-website] notebook is to capture the distribution of Steam banners and sample with a "lightweight GAN".

## Usage

-   Acquire a dataset, e.g. one of the versions proposed with [`Steam-OneFace`][steam-oneface-section],
-   Run [`Steam_Lightweight_GAN.ipynb`][Lightweight_GAN_training] to train a "lightweight GAN" from scratch,
[![Open In Colab][colab-badge]][Lightweight_GAN_training]

## Data

The dataset consists of `Steam-OneFace-small`, which is a small version of [`Steam-OneFace`][steam-oneface-section].
It features 993 Steam banners, with RGB channels and resized from 300x450 to 256x256 resolution.
The banners were selected to contain exactly one face, based on the two face detection modules `face_alignment` and `retinaface`.

## Training parameters

TODO

## Results

### Training time

TODO

### Model checkpoints

TODO

### Generated Steam banners

TODO

## References

-   DCGAN:
    -   [Radford, Alec, et al. *Unsupervised Representation learning with Deep Convolutional GAN*. ICLR 2016.][dcgan-paper]
    -   [Official implementation][dcgan-official-repository]
    -   [Application to Steam banners][dcgan-applied-to-steam-banners]
-   StyleGAN:
    -   [Karras, Tero, et al. *A Style-Based Generator Architecture for Generative Adversarial Networks*. CVPR 2019.][stylegan1-paper]
    -   [Official implementation][stylegan1-official-repository]
    -   [Application to Steam banners][stylegan1-applied-to-steam-banners]
-   StyleGAN2:
    - [Karras, Tero, et al. *Analyzing and Improving the Image Quality of StyleGAN*. CVPR 2020.][stylegan2-paper]
    -   [Official implementation][stylegan2-official-repository]
    -   [Application to Steam banners][stylegan2-applied-to-steam-banners]
-   StyleGAN2-ADA:
    -   [Karras, Tero, et al. *Training generative adversarial networks with limited data*. NeurIPS 2020.][stylegan2-ada-paper]
    -   [Official implementation][stylegan2-ada-official-repository]
    -   [Application to Steam banners][stylegan2-ada-applied-to-steam-banners]
-   "Lightweight-GAN":
    -   [Anonymous. *Towards Faster and Stabilized GAN Training for High-fidelity Few-shot Image Synthesis*. ICLR 2021.][lightweight-gan-paper]
    -   [Unofficial implementation][lightweight-gan-unofficial-repository]
    -   [Application to Steam banners][lightweight-gan-applied-to-steam-banners]    
    
<!-- Definitions -->

[cover-illustration]: <https://raw.githubusercontent.com/wiki/woctezuma/steam-lightweight-gan/img/generated_banners.jpg>

[steam-oneface-section]: <https://github.com/woctezuma/steam-filtered-image-data#steam-oneface-dataset>

[colab-website]: <https://colab.research.google.com/>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>
[Lightweight_GAN_training]: <https://colab.research.google.com/github/woctezuma/steam-lightweight-gan/blob/main/Steam_Lightweight_GAN.ipynb>

[dcgan-paper]: <https://arxiv.org/abs/1511.06434>
[stylegan1-paper]: <https://arxiv.org/abs/1812.04948>
[stylegan2-paper]: <https://arxiv.org/abs/1912.04958>
[stylegan2-ada-paper]: <https://arxiv.org/abs/2006.06676>
[lightweight-gan-paper]: <https://openreview.net/forum?id=1Fqg133qRaI>

[dcgan-official-repository]: <https://github.com/Newmu/dcgan_code>
[stylegan1-official-repository]: <https://github.com/NVlabs/stylegan>
[stylegan2-official-repository]: <https://github.com/NVlabs/stylegan2>
[stylegan2-ada-official-repository]: <https://github.com/NVlabs/stylegan2-ada>
[lightweight-gan-unofficial-repository]: <https://github.com/lucidrains/lightweight-gan>

[dcgan-applied-to-steam-banners]: <https://github.com/woctezuma/google-colab>
[stylegan1-applied-to-steam-banners]: <https://github.com/woctezuma/steam-stylegan>
[stylegan2-applied-to-steam-banners]: <https://github.com/woctezuma/steam-stylegan2>
[stylegan2-ada-applied-to-steam-banners]: <https://github.com/woctezuma/steam-stylegan2-ada>
[lightweight-gan-applied-to-steam-banners]: <https://github.com/woctezuma/steam-lightweight-gan>
