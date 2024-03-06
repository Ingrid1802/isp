---
title: "CloudSEN12"
type: data/generic_dataset
subtitle: "A Benchmark Dataset for Cloud Semantic Understanding"
logo: /isp/images/data/cloudsen12/logo.gif
banner: /images/banner.png
github: https://github.com/cloudsen12
huggingface: https://huggingface.co/isp-uv-es/cloudsen12
tags:
    - Sentinel-2
    - UNet
    - Cloud Detection
    - Multi-Modal
    - Remote Sensing
---

## Introduction

CloudSEN12 is a LARGE dataset (~1 TB) for cloud semantic understanding that consists of 49,400 image patches (IP) that are evenly spread throughout all continents except Antarctica. Each IP covers 5090 x 5090 meters and contains data from Sentinel-2 levels 1C and 2A, hand-crafted annotations of thick and thin clouds and cloud shadows, Sentinel-1 Synthetic Aperture Radar (SAR), digital elevation model, surface water occurrence, land cover classes, and cloud mask results from six cutting-edge cloud detection algorithms.

CloudSEN12 is designed to support both weakly and self-/semi-supervised learning strategies by including three distinct forms of hand-crafted labeling data: high-quality, scribble and no-annotation. For more details on how we created the dataset see our paper: [CloudSEN12 - a global dataset for semantic understanding of cloud and cloud shadow in Sentinel-2](https://www.nature.com/articles/s41597-022-01878-2).


## Authors

- [Herrera Fernando](/isp/images/data/cloudsen12/authors/fernando.png)
- [Loja Jhomira](/isp/images/data/cloudsen12/authors/jhomira.jpeg)
- [Ysuhuaylas Luis](/isp/images/data/cloudsen12/authors/luis.jpeg)
- [Gonzales Karen](/isp/images/data/cloudsen12/authors/andrea.jpeg)
- [LLactayo Valeria](/isp/images/data/cloudsen12/authors/valeria.jpg)
- [Bautista Lesly](/isp/images/data/cloudsen12/authors/lesly.jpg)
- [Diaz Lissette](/isp/images/data/cloudsen12/authors/lissette.png)
- [Flores Angie](/isp/images/data/cloudsen12/authors/angie.jpg)
- [Cuenca Nicole](/isp/images/data/cloudsen12/authors/nicole.jpg)
- [Inga Joselyn](/isp/images/data/cloudsen12/authors/inga.jpg)
- [Espinoza Wendy](/isp/images/data/cloudsen12/authors/wendy.jpg)
- [Fernando Prudencio](/isp/images/data/cloudsen12/authors/fernando.png)
- [Yali Roy](/isp/images/data/cloudsen12/authors/roy.jpg)
- [Aybar Cesar](/isp/images/data/cloudsen12/authors/cesar.jpg)
- [Mateo-García Gonzalo](/isp/images/data/cloudsen12/authors/gonzalo.png)
- [Gomez-Chova Luis](/isp/images/data/cloudsen12/authors/gomez.png)
- [Tiede Dirk](/isp/images/data/cloudsen12/authors/dirk.jpg)
- [Sudmanns Martin](/isp/images/data/cloudsen12/authors/martin.png)
- [David Montero](/isp/images/data/cloudsen12/authors/david.jpg)




## Examples

- [Download CloudSEN12 using easystac](https://colab.research.google.com/github/cloudsen12/examples/blob/master/example01.ipynb)

- [Make a prediction using UnetMobV2 (CloudSEN12)](https://colab.research.google.com/github/cloudsen12/examples/blob/master/example02.ipynb)

- [CloudSEN12 and PyTorch Lightning](https://colab.research.google.com/github/cloudsen12/examples/blob/master/example03.ipynb)

- [Visualize CloudSEN12 using geemap](https://colab.research.google.com/github/cloudsen12/examples/blob/master/example04.ipynb)

- [Compare cloud masking models](https://colab.research.google.com/github/cloudsen12/examples/blob/master/example05.ipynb)

- [Visualize CloudSEN12 in GEE code editor](https://github.com/cloudsen12/examples/tree/main/js)


## Citation

@article{aybar2022cloudsen12,
  title={CloudSEN12, a global dataset for semantic understanding of cloud and cloud shadow in Sentinel-2},
  author={Aybar, Cesar and Ysuhuaylas, Luis and Loja, Jhomira and Gonzales, Karen and Herrera, Fernando and Bautista, Lesly and Yali, Roy and Flores, Angie and Diaz, Lissette and Cuenca, Nicole and others},
  journal={Scientific data},
  volume={9},
  number={1},
  pages={782},
  year={2022},
  publisher={Nature Publishing Group UK London}
}
