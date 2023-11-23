# Tutorial introduction

This tutorial is aimed at empirical ecologists interested in using the theory developed in the paper *"Variability of functional and biodiversity responses to perturbations is predictable and informative"*. Using geometric arguments we can gain novel insights into the functioning of ecosystems and into the perturbations, such as climate change, pollution, or invasions, that impact them. The paper is currently available as a [preprint](https://doi.org/10.1101/2022.06.20.496833) on *BioRxiv*. 

A central element of the theory is the *proportion* of mismatches between community properties in their responses to perturbations. Larger datasets will therefore be morer useful, but data should ideally come from similar systems so that ecosystem functions are reasonably consistent. This theory can complement meta-analytical approaches in community and ecosystem ecology to gain new perspectives and to guide future empirical work. The data we'll use in this tutorial is derived from a [systematic review](https://doi.org/10.1038/s41467-020-16881-7) published in 2020 on the impacts of global change factors on microbial soil communities, which was conducted by Zhenghu Zhou, Chuankuan Wang, and Yiqi Luo. 

The tutorial outlines each step of the process as follows: 

1. [Data preparation](data-preparation.ipynb): here we outline the types of datasets that can be used and we explain how they should be organised. We also prepare a sample dataset of perturbation experiments from grassland ecosystems that we'll use in the rest of the tutorial. 
   
2. [Validation tests](validation.ipynb): here we perform some tests based on geometric arguments to check if our theory can be applied to the grasslands dataset. 

   
3. [Insights into ecosystem functions](ecosystem-functions.ipynb): here we use our theory to gain novel insights into the similarity and species contributions to ecosystem functions. 
   
4. [Insights into perturbations](perturbations.ipynb): finally we use the theory to gain novel insights into characteristics of the species-level effects of the perturbations. 
   
The code chunks in the tutorial contain code written in Python 3.11.5. The code and data used for all of the analyses in the paper are available in this [GitHub repository](https://github.com/jamesaorr/community-properties).  