# “Dead or Alive, we can deny it”. A Differentially Private Approach to Survival Analysis.

This repository contains the code and data for the paper "Dead or Alive, we can deny it”. A Differentially Private Approach to Survival Analysis" accepted at the SEBD 2024: 32nd Symposium on Advanced Database Systems.

```bibtex
@inproceedings{DeFaveriEtAl2024,
  author       = {Francesco Luigi De Faveri and
                  Guglielmo Faggioli and
                  Nicola Ferro and
                  Riccardo Spizzo},
  editor       = {Maurizio Atzori and
                  Paolo Ciaccia and
                  Michelangelo Ceci and
                  Federica Mandreoli and
                  Donato Malerba and
                  Manuela Sanguinetti and
                  Antonio Pellicani and
                  Federico Motta},
  title        = {"Dead or Alive, we can deny it". {A} Differentially Private Approach
                  to Survival Analysis},
  booktitle    = {Proceedings of the 32nd Symposium of Advanced Database Systems, Villasimius,
                  Italy, June 23rd to 26th, 2024},
  series       = {{CEUR} Workshop Proceedings},
  volume       = {3741},
  pages        = {401--411},
  publisher    = {CEUR-WS.org},
  year         = {2024},
  url          = {https://ceur-ws.org/Vol-3741/paper69.pdf},
  timestamp    = {Wed, 21 Aug 2024 22:46:00 +0200},
  biburl       = {https://dblp.org/rec/conf/sebd/FaveriF0S24.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```

## Authors
- Francesco Luigi De Faveri, Guglielmo Faggioli, Nicola Ferro: Department of Information Engineering, University of Padua, Padua, Italy.
- Riccardo Spizzo, National Cancer Center CRO Aviano, Aviano, Italy.

### Corresponding Authors
- francescoluigi.defaveri@phd.unipd.it (F. L. De Faveri)
- faggioli@dei.unipd.it (G. Faggioli)

© 2024 Copyright for this paper by its authors. Use permitted under Creative Commons License Attribution 4.0 International (CC BY 4.0).


## Abstract

Survival Analyses (SAs), a key statistical tool used to predict event occurrence over time, often involve sensitive information, necessitating robust privacy safeguards. This work demonstrates how the Revised Randomized Response (RRR) can be adapted to ensure Differential Privacy (DP) while performing SAs. This methodology seeks to safeguard the privacy of individuals’ data without significantly changing the utility, represented by the statistical properties of the survival rates computed. Our findings show that integrating DP through RRR into SAs is both practical and effective, providing a significant step forward in the privacy-preserving analysis of sensitive time-to-event data. This study contributes to the field by offering a new comparison method to the current state-of-the-art used for SAs in medical research.

### Keywords

Differential Privacy, Privacy-Preserving Mechanisms, Survival Analysis, Information Security

## Code

The code is written in Python and implemented using two Jupyter Notebooks. The first notebook relates to the original scenario, while the second notebook relates to the DP scenario. The code is available in the `src` folder. All the notebooks are commented to explain the code and the results.

## Results

The results are available in the `results` folder. The results are presented in the form of tables and plots.
