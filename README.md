# Probabilistic Models with Deep Neural Networks 

This repository refers to the following manuscript:

- Title: Probabilistic Models with Deep Neural Networks 
- Authors: Andrés R. Masegosa, Rafael Cabañas, Helge Langseth, Thomas D. Nielsen, Antonio Salmerón 
- PDF: [https://arxiv.org/pdf/1908.03442.pdf](https://arxiv.org/pdf/1908.03442.pdf)

Here we provide the code for running the examples in the aforementioned manuscript using
[TensorFlow Probability](https://www.tensorflow.org/probability). These are provided in Jupyter notebook format and can be executed in cloud services:

- [Example 1 - PCA](https://github.com/PGM-Lab/ProbModelingDNNs/blob/master/notebooks/Example1-PCA.ipynb)
- [Example 6 - Non-linear PCA](https://github.com/PGM-Lab/ProbModelingDNNs/blob/master/notebooks/Example6-NLPCA.ipynb)
- [Example 10 - VAE](https://github.com/PGM-Lab/ProbModelingDNNs/blob/master/notebooks/Example10-VAE.ipynb)

Another two well known probabilistic models including artificial neural newtorks, not detailed in the manuscript, can be found here:
- [Bayesian Neural Networks](https://github.com/PGM-Lab/ProbModelingDNNs/blob/master/notebooks/BayesianNeuralNetworks-Edward2.ipynb)
- [Mixture Density Networks](https://github.com/PGM-Lab/ProbModelingDNNs/blob/master/notebooks/mixture_density_networks-Edward2.ipynb)

The same notebooks are also coded using [InferPy](https://inferpy.readthedocs.io), which is a high-level API for probabilistic modeling with deep neural networks. InferPy has a strong focus on ease of use. 
- [Example 1 - PCA](https://github.com/PGM-Lab/InferPy/blob/master/notebooks/ProbModelingDNNs/Example1-PCA.ipynb)
- [Example 6 - Non-linear PCA](https://github.com/PGM-Lab/InferPy/blob/master/notebooks/ProbModelingDNNs/Example6-NLPCA.ipynb)
- [Example 10 - VAE](https://github.com/PGM-Lab/InferPy/blob/master/notebooks/ProbModelingDNNs/Example10-VAE.ipynb)
- [Bayesian Neural Networks](https://github.com/PGM-Lab/InferPy/blob/master/notebooks/BayesianNeuralNetworks.ipynb)
- [Mixture Density Networks](https://github.com/PGM-Lab/InferPy/blob/master/notebooks/mixture_density_networks.ipynb)

A comparison of the evolution of the ELBO (i.e., objective function) is shown in the following notebook:

- [ELBO Evolution](https://github.com/PGM-Lab/ProbModelingDNNs/blob/master/notebooks/res/ELBO-Evolution.ipynb)


Citation:

```
@article{masegosa2019probabilistic,
  author = {Masegosa, A.R. and Caba\~{n}as, R. and Langseth, H. and Nielsen, T.D. and Salmer\'{o}n, A. },
    title = {Probabilistic Models with Deep Neural Networks},
  journal = {arXiv preprint arXiv:1908.03442},
  year = {2019}
}
``` 


The analogous code examples using InferPy can be found [here](https://github.com/PGM-Lab/InferPy/tree/develop/notebooks/ProbModelingDNNs).
For further information about this package go to [https://inferpy.readthedocs.io/](https://inferpy.readthedocs.io/en/latest/).
