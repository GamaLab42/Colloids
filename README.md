This notebook aims to calculate the dispersion coefficients between ion-colloid and the Hamaker parameter for two media (media 1 and media 2) across a third media, using the Lifshitz theory. The primary motivation of this notebook is to assist young students in this topic. Even master's or doctorate students sometimes struggle with that calculus. 

It is worth noting that the calculations and parameters used here are established in the literature. The equations came from Jacob N. Israelachvili's book (2011); the primary data is from Tavares et al. (2004).

> [!TIP]
> For the applications, the dispersion coefficients can be used in thermodynamic theories for colloid systems, especially for investigating ionic specificity using a Poisson-Boltzmann Equation for charged interfaces.

# Citation
If you are using this notebook to obtain the dispersion coefficients between ion-colloid and using Tavares et al. (2004) data, please consider citing as:
```
@article{doi:10.1021/jp037809t,
author = {Tavares, F. W. and Bratko, D. and Blanch, H. W. and Prausnitz, J. M.},
title = {Ion-Specific Effects in the Colloid−Colloid or Protein−Protein Potential of Mean Force:  Role of Salt−Macroion van der Waals Interactions},
journal = {The Journal of Physical Chemistry B},
volume = {108},
number = {26},
pages = {9228-9235},
year = {2004},
doi = {10.1021/jp037809t},
URL = {https://doi.org/10.1021/jp037809t},
eprint = {https://doi.org/10.1021/jp037809t}
}
```

# Recommended literature
Are you interested in the applications? We recommend to read the following papers:
* Boström M, Tavares FW, Finet S, Skouri-Panet F, Tardieu A, Ninham BW. Why forces between proteins follow different Hofmeister series for pH above and below pI. Biophys Chem. 2005 Oct 3;117(3):217-24. doi: 10.1016/j.bpc.2005.05.010. PMID: 15963625.
  
* Lima ER, Tavares FW, Biscaia EC Jr. Finite volume solution of the modified Poisson-Boltzmann equation for two colloidal particles. Phys Chem Chem Phys. 2007 Jun 28;9(24):3174-80. doi: 10.1039/b701170a. Epub 2007 May 15. PMID: 17612740.

* Lima ER, Biscaia EC Jr, Boström M, Tavares FW. Ion-specific thermodynamical properties of aqueous proteins. An Acad Bras Cienc. 2010 Mar;82(1):109-26. doi: 10.1590/s0001-37652010000100010. PMID: 20209247.

* Alijó, P.H., Tavares, F.W., & Biscaia, E.C. (2012). Double layer interaction between charged parallel plates using a modified Poisson–Boltzmann equation to include size effects and ion specificity. Colloids and Surfaces A: Physicochemical and Engineering Aspects, 412, 29-35.

* Gama MS, Santos MS, Lima ERA, Tavares FW, Barreto AGB Jr. A modified Poisson-Boltzmann equation applied to protein adsorption. J Chromatogr A. 2018 Jan 5;1531:74-82. doi: 10.1016/j.chroma.2017.11.022. Epub 2017 Nov 13. PMID: 29174569.

![ATOMS](https://static.wixstatic.com/media/52a33c_ad1448942345475193f42b50b6c45804~mv2.png/v1/crop/x_0,y_0,w_289,h_275/fill/w_52,h_49,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/logo%20atoms%20bolinha.png) [ATOMS Group](https://atomsufrj.wixsite.com/home)
