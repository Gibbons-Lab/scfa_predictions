# Prediction of Short-Chain Fatty Acid Production from the Human Gut Microbiome
In this respository, find all analyses for the manuscript "Microbial community-scale metabolic modeling predicts personalized short-chain-fatty-acid production profiles in the human gut", Quinn-Bohmann et al., 2023. 

__Notebooks__

In the notebooks directory, all Jupyter notebooks for all analyses can be found. invitro.ipynb details the construction and simulation of in vitro samples from Clark et al., 2021, as shown in Fig. 2A.

studyA.ipynb, studyB.ipynb, studyC.ipynb and studyD.ipynb contain analysis of ex vivo studies A, B, C and D. summarized_exvivos.ipynb contains combined z-scored predictions for all studies, as shown in Fig. 2B and Fig 3.

fiber_study.ipynb contains analysis for modeling of samples in the longitudinal fiber study from Wastyk et al., 2021.

Analysis of blood chemistry association and interventions are not included, as Arivale data is not publically available. 

__Data__

Abundance matricies and measured SCFAs for each study are available in the _Data_ directory. 

Original data collected from experiments or publications is in the _raw_data_ subdirectory within the _Data_ directory

__Media__

All media used in the growth simulations are available in the _Media_ directory
