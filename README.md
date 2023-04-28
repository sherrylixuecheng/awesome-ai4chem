# Awesome AI for Chemistry

*[AI4Sci Edu](https://github.com/AI4SciEdu) related repo* 

*Still under construction*🚧👷🏻‍♂️

A list of awesome AI for chemistry papers. Inspired by the "Awesome" branded repositories in Computer Science. Please feel free to contribute and help to improve the quality of this page.

- Note 1: To highlight the paper, we switch the order of authors and paper title in the citation. Please cite the authors correctly instead of directly copying from our page.

- Note 2: If your work is not listed, but you feel it is influncial/inspiring/novel, please feel free to provide comments via Discussion or create an issue. 


## Table of Contents
- [Organic/Inorganic chemsitry: Retrosynthesis planning](#retrosynthesis)
    - [Molecular/Material design](#molecular/material_design)
    - [Reaction design/Reactivity](#reaction_design)
    - ...
- [Theoretical/Computational chemistry: Electronic structure](#electronic_structure)
    - [DFT parmetrization](#dft_parmetrization)
    - [DFT ansatz learning](#dft_ansatz_learning)
    - [Wavefunction learning](#wavefunction_learning)
    - [Wavefunction theory learning](#wavefunction_theory_learning)
    - [Active/embedding space learning](#active_embedding_space_learning)
    - [Property learning](#property_learning)
- [Theoretical/Computational chemistry: Molecular Dynamics](#molecular_dynamics)
    - [Enhanced sampling](#enhanced_sampling)
    - [Force field design](#force_field_design) 
- [Generalized model/Datasets](#generalized_model/datasets)
- [Experimental physical chemistry](#experimental_physical_chemistry)
- [Biochemistry: Biomolecule (protein/nucleic acid/lipid) design/structure](#biomolecule_design)
- [Analytical chemistry](#analytical_chemistry)
- [Robotic chemist/Automation](#automated_experiments)
- [Reviews](#reviews)


## Retrosynthesis
### Molecular/Material_Design
1. [Planning chemical syntheses with deep neural networks and symbolic AI.](https://www.nature.com/articles/nature25978)
    Marwin H. S. Segler, Mike Preuss, & Mark P. Waller, Nature **555**, 604–610 (2018) [Reinforcement learning]
2. [Learning retrosynthetic planning through simulated experience.](https://pubs.acs.org/doi/full/10.1021/acscentsci.9b00055)
    John S. Schreck, Connor W. Coley, & Kyle J. M. Bishop, ACS Central Science **5**(6), 970-981 (2019) [Reinforcement learning]
3. ...

### Reaction_Design
1. [Prediction of organic reaction outcomes using machine learning](https://pubs.acs.org/doi/full/10.1021/acscentsci.7b00064)
    Connor W. Coley, Regina Barzilay, Tommi S. Jaakkola, William H. Green, & Klavs F. Jensen, ACS Central Science **3**(5), 434–443 (2017)
2. 

## Electronic_Structure
1. ...

## Molecular_Dynamics

### Force_field_design
1. [SchNet - A deep learning architecture for molecules and materials](https://pubs.aip.org/aip/jcp/article/148/24/241722/962591/SchNet-A-deep-learning-architecture-for-molecules) 
    K. T. Schütt, H. E. Sauceda, P.-J. Kindermans, A. Tkatchenko, K.-R. Müller, The Journal of Chemical Physics **148**, 241722 (2018)
2. [ANI-1: An extensible neural network potential with DFT accuracy at force field computational cost](https://pubs.rsc.org/en/content/articlelanding/2017/sc/c6sc05720a)
    J. S. Smith,   O. Isayev, & A. E. Roitberg, Chemical Sciences **8**, 3192-3203 (2017)

## Generalized_Model/Datasets
1. [The Open Reaction Database](https://pubs.acs.org/doi/10.1021/jacs.1c09820)
    S. M. Kearnes, M. R. Maser, M. Wleklinski, A. Kast, A. G. Doyle, S. D. Dreher, J. M. Hawkins, K.s F. Jensen, & C. W. Coley, Journal of the American Chemical Society **143**(45), 18820–18826 (2021). [Dataset](https://docs.open-reaction-database.org/en/latest/)
2. QM series (Please also see [quantum-machine](http://quantum-machine.org/datasets/) page)
- QM9 Dataset:
    - [Quantum chemistry structures and properties of 134 kilo molecules](https://www.nature.com/articles/sdata201422)
        R. Ramakrishnan, P. O. Dral, M. Rupp, & O. A. von Lilienfeld, Scientific Data **1**, 140022 (2014) 
    - [Orginial version. Theory: B3LYP/6-31G(2df,p)](https://doi.org/10.6084/m9.figshare.978904)
    - [Wavefunction theory verison. Theory: MP2/cc-pVTZ](https://doi.org/10.22002/D1.20142) Only has dipole moments and molecular energies
    - [Kaggle page](https://www.kaggle.com/code/zaharch/quantum-machine-9-qm9)
- QM7 & QM7b Dataset:
    - [Fast and Accurate Modeling of Molecular Atomization Energies with Machine Learning.](http://dx.doi.org/10.1103/PhysRevLett.108.058301) (QM7)
        M. Rupp, A. Tkatchenko, K.-R. Müller, O. A. von Lilienfeld, Physical Review Letters **108**(5),058301 (2012)
    - [Machine Learning of Molecular Electronic Properties in Chemical Compound Space.](https://iopscience.iop.org/article/10.1088/1367-2630/15/9/095003)
        G. Montavon, M. Rupp, V. Gobre, A. Vazquez-Mayagoitia, K. Hansen, A. Tkatchenko, K.-R. Müller, O.A. von Lilienfeld, New Journal of Physics **15**, 095003(2013)
    - [QM7 original dataset](http://quantum-machine.org/data/qm7.mat)
    - [QM7b original dataset](http://quantum-machine.org/data/qm7b.mat)
    - [Wavefunction theory verison. Theory: MP2/cc-pVTZ](https://doi.org/10.22002/D1.1177) Improved features & addtional datasets are available [here](https://doi.org/10.22002/D1.1792)

- QMSpin Dataset:

- tmQM Dataset: 

3. GDB series:
- GDB 17:
- GDB 13:

4. [ISO17 dataset]()


5. [DESMILES Models & Training datasets](https://www.deshawresearch.com/downloads/download_desmiles.cgi/)
- [A Deep-Learning View of Chemical Space Designed to Facilitate Drug Discovery](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00321)
    P. Maragakis, H. Nisonoff, B. Cole, & D. E. Shaw, Journal of Chemical Information and Modeling **60**(10), 4487–4496 (2020)

6. 

## Experimental_Physical_Chemistry
1. ...

## Biomolecule_Design
1. ...

## Analytical chemistry
1. ...

## Automated_Experiments
1. [A mobile robotic chemist.](https://www.nature.com/articles/s41586-020-2442-2)
    B. Burger, P. M. Maffettone, V. V. Gusev, C. M. Aitchison, Y. Bai, X. Wang, X. Li, B. M. Alston, B. Li, R. Clowes, N. Rankin, B. Harris, R. S. Sprick, & A. I. Cooper, Nature **583**, 237–241 (2020) [Robtics + Bayesian learning]
2. [A robotic platform for flow synthesis of organic compounds informed by AI planning.](https://www.science.org/doi/full/10.1126/science.aax1566) 
    C. W. Coley, D. A. Thomas III, J. A.M. Lummiss, J. N. Jaworski, C. P. Breen, V. Schultz, T. Hart, J. S. Fishman, L. Rogers, H. Gao, R. W. Hicklin, P. P. Plehiers, J. Byington, J. S. Piotti, W. H. Green, A. J. Hart, T. F. Jamison, & K. F. Jensen, Science **365**(6453), eaax1566 (2019) [Software + Experiments]

## Reviews
Note: We will try to provide both the most influncial/comprehensive reviews and the most recent/updated reviews. The list will be updated timely manner. 

1. [Roadmap on Machine learning in electronic structure.](https://iopscience.iop.org/article/10.1088/2516-1075/ac572f)
    H. J. Kulik, T. Hammerschmidt, J. Schmidt, S. Botti, M. A. L. Marques, M. Boley, M. Scheffler, M. Todorović, P. Rinke, C. Oses, A. Smolyanyuk, S. Curtarolo, A. Tkatchenko, A. P. Bartók, S. Manzhos, M. Ihara, T. Carrington, J. Behler, O. Isayev, M. Veit, A. Grisafi, J. Nigam, M. Ceriotti, K. T. Schütt, J. Westermayr, M. Gastegger, R. J. Maurer, B. Kalita, K. Burke, R. Nagai, R. Akashi, O. Sugino, J. Hermann, F. Noé, S. Pilati, C. Draxl, M. Kuban, S. Rigamonti, M. Scheidgen, M. Esters, D. Hicks, C. Toher, P. V. Balachandran, I. Tamblyn, S. Whitelam, C. Bellinger, & L. M. Ghiringhelli, Electronic Structure **4**, 023004 (2022)
2. [Machine learning for molecular and materials science.](https://www.nature.com/articles/s41586-018-0337-2)
    K. T. Butler, D. W. Davies, H. Cartwright, O. Isayev, & A. Walsh, Nature **559**, 547–555 (2018)
3. [Four generations of high-dimensional neural network potentials](https://pubs.acs.org/doi/10.1021/acs.chemrev.0c00868)
    J. Behler, Chemical Reviews **121**(16), 10037–10072 (2021)
4. [Inverse molecular design using machine learning: Generative models for matter engineering.](https://www.science.org/doi/10.1126/science.aat2663)
    B. Sanchez-Lengeling,& A. Aspuru-Guzik, Science **361**(6400), 360-365 (2018) 
5. [Data-driven strategies for accelerated materials design](https://pubs.acs.org/doi/10.1021/acs.accounts.0c00785)
    R. Pollice, G. dos Passos Gomes, M. Aldeghi, R. J. Hickman, M. Krenn, C. Lavigne, M. Lindner-D’Addario, A. Nigam, C. T. Ser, Z. Yao, & A. Aspuru-Guzik, Accounts of Chemical Research **54**(4), 849–860 (2021)
6. [Molecular excited states through a machine learning lens](https://www.nature.com/articles/s41570-021-00278-1)
    P. O. Dral & M. Barbatti, Nature Reviews Chemistry **5**, 388–405 (2021)
7. [Combining machine learning and computational chemistry for predictive insights into chemical systems](https://pubs.acs.org/doi/10.1021/acs.chemrev.1c00107)
    J. A. Keith, V. Vassilev-Galindo, B. Cheng, S. Chmiela, M. Gastegger, K.-R. Müller, & A. Tkatchenko, Chemical Reviews **121**(16), 9816–9872 (2021)
8. [Machine learning force fields](https://pubs.acs.org/doi/10.1021/acs.chemrev.0c01111)
    O. T. Unke, S. Chmiela, H. E. Sauceda, M. Gastegger, I. Poltavsky, K. T. Schütt, A. Tkatchenko, & K.-R. Müller, Chemical Reviews **121**(16), 10142–10186 (2021)
9. [Physics-inspired structural tepresentations for molecules and materials](https://pubs.acs.org/doi/10.1021/acs.chemrev.1c00021)
    F. Musil, A. Grisafi, A. P. Bartók, C. Ortner, G. Csányi, & M. Ceriotti, Chemical Reviews **121**(16), 9759–9815 (2021)
10. [Machine Learning for Chemical Reactions](https://pubs.acs.org/doi/10.1021/acs.chemrev.1c00033)
    M. Meuwly, Chemical Reviews **121**(16), 10218–10239 (2021)
11. [Artificial intelligence applied to battery research: Hype or reality?](https://pubs.acs.org/doi/10.1021/acs.chemrev.1c00108)
    T. Lombardo, M. Duquesnoy, H. El-Bouysidy, F. Årén, A. Gallo-Bueno, P. B. Jørgensen, A. Bhowmik, A. Demortière, E. Ayerbe, F. Alcaide, M. Reynaud, J. Carrasco, A. Grimaud, C. Zhang, T. Vegge, P. Johansson, & A. A. Franco, Chemical Reviews **122**(12), 9759–9815 (2022)
12. [Autonomous Discovery in the Chemical Sciences Part I: Progress.](https://onlinelibrary.wiley.com/doi/10.1002/anie.201909987) and [Autonomous Discovery in the Chemical Sciences Part II: Outlook.](https://onlinelibrary.wiley.com/doi/10.1002/anie.201909989)
    C. W. Coley, N. S. Eyke, & K. F. Jensen, Angewandte Chemie International Edition, **59**, Part I: 22858 and Part II: 23414 (2020) 
13. [Taking the leap between analytical chemistry and artificial intelligence: A tutorial review.](https://www.sciencedirect.com/science/article/abs/pii/S0003267021002294)
    L. B. Ayres, F. J.V. Gomez, J. R. Linton, M. F. Silva, & C. D. Garcia, Analytica Chimica Acta **1161**, 338403 (2021)
14. [Recent advances and applications of deep learning methods in materials science.](https://www.nature.com/articles/s41524-022-00734-6)
    K. Choudhary, B. DeCost, C. Chen, A. Jain, F. Tavazza, R. Cohn, C. W. Park, A. Choudhary, A. Agrawal, S. J. L. Billinge, E. Holm, S. P. Ong, & C. Wolverton, npj Computational Materials **8**, 59 (2022)
15. [Perspective on integrating machine learning into computational chemistry and materials science](https://pubs.aip.org/aip/jcp/article/154/23/230903/200193/Perspective-on-integrating-machine-learning-into)
    J. Westermayr, M. Gastegger, K. T. Schütt, & R. J. Maurer, The Journal of Chemical Physics **154**, 230903 (2021)

16. [Machine learning in scanning transmission electron microscopy](https://www.nature.com/articles/s43586-022-00095-w)
    S. V. Kalinin, C. Ophus, P. M. Voyles, R. Erni, D. Kepaptsoglou, V. Grillo, A. R. Lupini, M. P. Oxley, E. Schwenker, M. K. Y. Chan, J. Etheridge, X. Li, G. G. D. Han, M. Ziatdinov, N. Shibata, & S. J. Pennycook, Nature Reviews Methods Primers **2**, 11 (2022) 
