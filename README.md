# DIND
Code and datasets for paper "Identifying the critical states of complex diseases by the dynamic change of multivariate distribution"

## Identifying the critical states of complex diseases by the dynamic change of multivariate distribution
  > The dynamics of complex diseases are not always smooth; they are occasionally abrupt, i.e., there is a critical state transition or tipping point at which the disease undergoes a sudden qualitative shift. There are generally few significant differences in the critical state in terms of gene expressions or other static measurements, which may lead to the failure of traditional differential expression-based biomarkers to identify such a tipping point. In this study, we propose a computational method, the direct-interaction-network-based divergence (DIND), to detect the critical state of complex diseases by exploiting the dynamic changes in multivariable distributions inferred from observable samples and local biomolecular direct interaction networks (DINs). Such a method is model-free and applicable to both bulk and single-cell expression data. Our approach was validated by successfully identifying the tipping point just before the occurrence of a critical transition for both a simulated dataset and seven real datasets, including those from The Cancer Genome Atlas (TCGA) and two single-cell RNA sequencing datasets of cell differentiation. Functional and pathway enrichment analyses also validated the computational results from the perspectives of both molecules and networks.

## Data avalability
- We put all the datsets on Google Drive, you can download them from [here](https://drive.google.com/file/d/1eL6I393qSStDocIPgEEL2tC65WguD-Ql/view?usp=sharing).
- Before run the code, you should unzip the data files into the folder [./data_files](./data_files).

## Demo
After putting the data folder "data_files/simulation" from the zipped [file](https://drive.google.com/file/d/1eL6I393qSStDocIPgEEL2tC65WguD-Ql/view?usp=sharing) into the folder [./data_files](./data_files), the noebook "dind_main.ipynb" in repository can demonstrate the effectiveness of our method on numerical simulation data.

## Citation
Please cite this paper if you find the repository helpful:

    @article{peng2022identifying,  
        title={Identifying the critical states of complex diseases by the dynamic change of multivariate distribution},  
        author={Peng, Hao and Zhong, Jiayuan and Chen, Pei and Liu, Rui},  
        journal={Briefings in Bioinformatics},
        year={2022}
    }