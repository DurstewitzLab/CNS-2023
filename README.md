# CNS-2023
A Guide to Reconstructing Dynamical Systems from Neural Measurements Using Recurrent Neural Networks

Dynamical system reconstruction (DSR) is a powerful framework for analyzing neural data and understanding the brain’s computational processes [1]. DSR is a deep learning methodology, mostly based on recurrent neural networks (RNNs), where we infer a generative model from neural and/ or behavioral recordings that behaves in every dynamically relevant aspect like the system underlying the data observed. Thus, after training on neural data, an RNN should be able to generate new data with the same temporal and geometrical signatures and attractor states as the underlying neural substrate (Fig. 1).

It thereby becomes a formally accessible surrogate model for the real system which can be analyzed, simulated, and probed further.

After a brief overview over various machine learning approaches for DSR, we will introduce a general framework for training a class of mathematically tractable RNN models specifically tailored to DSR. We will also discuss multimodal extensions that allow to integrate various simultaneously observed data modalities, like single-unit recordings, Ca2+ imaging, and behavioral data, into the same DSR model [3].

Practical examples will cover multiple single-unit recordings,  fMRI, EEG and behavioral/ smartphone-based data [4].
Example fMRI, EEG and MSU reconstructions. Taken from [1].

Besides training RNNs for DSR on such data, we will also discuss their post-training analysis, including procedures for model validation, and for analyzing state spaces, attractor objects like fixed points, cycles, and chaos,  and basins of attraction, or Lyapunov spectra.

We will provide Jupyter Notebooks and example data sets on which the methods can be tested, but encourage participants to also bring their own data!

Software tools:

- https://github.com/DurstewitzLab/dendPLRNN
- https://github.com/DurstewitzLab/GTF-shPLRNN

A Jupyter notebook with code examples will be made available here before the workshop begins.

Background reading:

[1] Daniel Durstewitz, Georgia Koppe, and Max Ingo Thurm. Reconstructing computational dynamics from neural measurements with recurrent neural networks, 2022. https://www.biorxiv.org/content/10.1101/2022.10.31.514408v

[2] Brenner, Hess, et al. (2022). Tractable Dendritic RNNs for Reconstructing Nonlinear Dynamical Systems. In International Conference on Machine Learning (pp. 2292-2320). PMLR

[3] Manuel Brenner, Georgia Koppe and Daniel Durstewitz, Multimodal Teacher Forcing for Reconstructing Nonlinear Dynamical Systems, AAAI 2023 workshop paper.
https://arxiv.org/abs/2212.07892

[4] Koppe et al. (2019). Koppe G, Toutounji H, Kirsch P, Lis S, Durstewitz D (2019) Identifying nonlinear dynamical systems via generative recurrent neural networks with applications to fMRI. PLOS Computational Biology 15(8): e1007263.

[5] Hess, F., Monfared, Z., Brenner, M., & Durstewitz, D. (2023). Generalized Teacher Forcing for Learning Chaotic Dynamics. arXiv preprint arXiv:2306.04406. https://arxiv.org/abs/2306.04406

