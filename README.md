# Data-Driven System Level Synthesis

This repository hosts the code needed to reproduce the examples in the published work:

1. A. Xue, and N. Matni. Data-Driven System Level Synthesis. In _Proceedings of Machine Learning Research_, Vol. 144:1–12, 2021. Preprint (extended version) available at https://arxiv.org/abs/2011.10674.

2. C. Amo Alonso*, F. Yang*, and N. Matni. Data-Driven Distributed and Localized Model Predictive Control via System Level Synthesis. Submitted to _IEEE Open Journal of Control Systems_, 2022. Preprint available at https://arxiv.org/abs/2112.12229.

*denotes equal contribution

## 2021_L4DC_DataDriven-SLS

This folder hosts the code needed to reproduce the examples in article [1] and its extended version available at https://arxiv.org/abs/2011.10674. Extended versions of the paper can be found in this folder in both the L4DC (abridged format with proofs in the appendix) and arXiv (no appendices, self-contained document) formats.

A README file can be found in the "experiments" folder, where a detailed explanation of how the files should be run is available. 

## 2022_OJCS_DataDriven-DLMPC

This folder hosts the code needed to reproduce the examples in article [2] and its preprint https://arxiv.org/abs/2112.12229.

The names of the subfolders correspond to the figure's number that they generate. Users must first run the script named `script_[corresponging figure].m`, which will save the data in folder named `results` as a .mat file. Once this is done, users must run the script named `plot_[corresponging figure].m`, located in the same folder where the first script was run. This will produce the desired figure. 

*Note*: To run the script, users must change the current directory to the one the script is in.

*Warning*: some of the scripts, in particular the ones concerning runtime measures, might take several hours to run.
