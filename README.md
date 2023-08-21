These codes are made for calculating the asymmetric parameter eta.

Created by zhzhong@nao.cas.cn

Authors:    
Zehao Zhong (zhzhong@nao.cas.cn)    
Gang Zhao
Hans-Walter Rix
Luis C. Ho

This example is used to calculate the asymmetry parameter, and could reproduced the results in our article (Fig. 2, Fig. 3).


You may need these reference:
Our paper (in preparation)    
(Data and tables from SAMI survey Dr3):   
Croom, S. et al. 2021, MNRAS, 505, 991–1016 (SAMI survey Dr3)   
Owers, M. et al. 2017, MNRAS, 468, 1824–1849 (table InputCatClustersDR3)    
D’Eugenio, F. et al. 2021, MNRAS, 504, 5098–5130 (table MGEPhotomUnregDR3)    
Cortese, L. et al. 2016, MNRAS, 463, 170–184 (table VisualMorphologyDR3)    
van de Sande, J. et al. 2017, APJ, 835, 104 (stellar kinematics)    
Bryant, J. et al. 2015, MNRAS, 447, 2857–2879 (table InputCatGAMADR3)
(COBS – Constrained B-splines)
Ng P, Maechler M (2007). “A Fast and Efficient Implementation of Qualitatively Constrained Quantile Smoothing Splines.” Statistical Modelling, 7(4), 315–328. doi:10.1177/1471082X0700700403.
Ng PT, Maechler M (2022). COBS – Constrained B-splines (Sparse matrix based). R package version 1.3-5., https://CRAN.R-project.org/package=cobs.

The details of these codes are showed in the 'Methods' section of our paper.

If you would like to replot the figures in our article, please download the 
corresponding SAMI data and tables, and then run the program. The method 
of calculating eta of TNG DATA is similar, and the code is not repeated here.

Or if you would like to calculate the asymmetric parameter eta of your 
own IFU data. Please look at the core function 'calind2inv3' and 'calchinreMCv14',
you can also refer to function 'asymparaquanall'.

Please note that modify the corresponding path to your own path when running the program.
