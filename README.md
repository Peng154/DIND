# DIND
Code and datasets for paper "Kullback-Leibler divergence of multivariate distribution reveals the critical states of complex biological systems"

## Kullback-Leibler divergence of multivariate distribution reveals the critical states of complex biological systems
- The dynamics of complex biological systems are not always smooth; they are occasionally abrupt, i.e., there is a critical state transition or tipping point at which complex systems undergo a sudden qualitative shift. There are generally few significant differences at the critical state in terms of static measurements, such as differential expression, which may lead to the failure of traditional biomarkers to identify such a tipping point. In this study, we propose a computational method to detect the critical state of complex biological systems by exploiting the dynamic changes in multivariable distributions inferred from observable samples and local biomolecular direct interaction networks (DINs). Such a method is model-free and applicable to both bulk and single-cell expression data. Our approach was validated by successfully identifying the tipping point just before the occurrence of a critical transition for both a simulated dataset and seven real datasets, including some from The Cancer Genome Atlas (TCGA) and two single-cell RNA sequencing datasets of embryonic differentiation. Both functional and pathway enrichment analyses also validated the computational results from the perspectives of both molecules and networks.

## Data avalability
- We put all the datsets on Google Drive, you can download them from [here](https://drive.google.com/file/d/1eL6I393qSStDocIPgEEL2tC65WguD-Ql/view?usp=sharing).
- Before run the code, you should unzip the data files into the folder [./data_files](./data_files).

## Demo
After putting the data folder "data_files/simulation" from the zipped [file](https://drive.google.com/file/d/1eL6I393qSStDocIPgEEL2tC65WguD-Ql/view?usp=sharing) into the folder [./data_files](./data_files), the noebook "dind_main.ipynb" in repository can demonstrate the effectiveness of our method on numerical simulation data.