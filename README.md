# iNNE

iNNE - Isolation‐based anomaly detection using nearest‐neighbor ensembles.

Based on the paper:

Tharindu R., et al. "[Isolation‐based anomaly detection using nearest‐neighbor ensembles](https://onlinelibrary.wiley.com/doi/abs/10.1111/coin.12156)" Computational Intelligence (2018)

Matlab code of iNNE: https://github.com/zhuye88/iNNE

Introduction to the paper: https://www.jianshu.com/p/379a5898beb6


Abstract of the paper:

The first successful isolation‐based anomaly detector, ie, iForest, uses trees as a means to perform isolation. Although it has been shown to have advantages over existing anomaly detectors, we have identified 4 weaknesses, ie, its inability to detect local anomalies, anomalies with a high percentage of irrelevant attributes, anomalies that are masked by axis‐parallel clusters, and anomalies in multimodal data sets. To overcome these weaknesses, this paper shows that an alternative isolation mechanism is required and thus presents iNNE or isolation using Nearest Neighbor Ensemble. Although relying on nearest neighbors, iNNE runs significantly faster than the existing nearest neighbor–based methods such as the local outlier factor, especially in data sets having thousands of dimensions or millions of instances. This is because the proposed method has linear time complexity and constant space complexity.


Documentation, including tutorials, are available on ReadTheDocs at https://inne.readthedocs.io.

## Features

* TODO

## Installing

PyPI install, presuming you have an up to date pip:
```bash
pip install inne
```

## Running the Tests

```
python test_inne.py
```


## Citing

If you have used this codebase in a scientific publication and wish to cite it, please use the following publication (Bibtex format):

@article{bandaragoda2018isolation,
        title={Isolation-based anomaly detection using nearest-neighbor ensembles},
        author={Bandaragoda, Tharindu R and Ting, Kai Ming and Albrecht, David and Liu, Fei Tony and Zhu, Ye and Wells, Jonathan R},
        journal={Computational Intelligence},
        volume={34},
        number={4},
        pages={968--998},
        year={2018},
        publisher={Wiley Online Library}}

## How to Contribute

We welcome contributions in any form! Assistance with documentation, particularly expanding tutorials, is always welcome. To contribute please fork the project make your changes and submit a pull request. We will do our best to work through any issues with you and get your code merged into the main branch.

### Code
### Documents


## License
BSD license