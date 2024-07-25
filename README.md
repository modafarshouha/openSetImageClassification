# Algorithms for Open Set Classification on Image Datasets

This is the code implementation for ["Creating Algorithms for Open Set Classification on Image Datasets"](https://cyber.bibl.u-szeged.hu/index.php/actcybern/article/download/4324/4082) project. <br>

## Repo summary
Implementation for the proposed solutions - single and combined algorithms - to tackle open set classification task for image datasets, where a K-classifier is expanded to be able to identify K+1 classes. The algorithms do not require any retraining or modification on the K-classifier architecture. They are strong when avoiding type I or type II errors is fundamental. We also present a mathematical representation for the task to estimate the $K+1$ classification accuracy, and an inequality that defines its boundaries. Additionally, a formula is proposed to calculate the exact K+1 classification accuracy.

## Models
Two K-classifiers were trained in addition to a GAN (to use its discriminator). The training notebooks can be found in [models_train](./models_train/) folder.

## DPM
Moreover, this repo contains the DPM python implementation for [DPM](https://doi.org/10.15388/Informatica.2018.171) paper. The notebooks can be found in [DPM](./DPM/) folder.

## Test
The algorithms test notebooks are in [algos_test](./algos_test/) folder, and the formula test notebooks are in [formula_test](./formula_test/) folder.

## Results
The results' notebooks are in [results](./results/) folder.

## Data
Some of the used data are available in [data](./data/) folder, while the rest are not because of their big size. However, they can be generated easily.

## Cite
```
@article{al2024single,
  title={Single and Combined Algorithms for Open Set Classification on Image Datasets},
  author={Al-Shouha, Modafar and Sz{\H{u}}cs, G{\'a}bor},
  journal={Acta Cybernetica},
  year={2024},
  publisher={University of Szeged},
  url={https://cyber.bibl.u-szeged.hu/index.php/actcybern/article/download/4324/4082}
}
```

## License
This work license is: <a href="./LICENSE">GNU Affero General Public License v3.0</a>.
