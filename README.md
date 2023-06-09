# Awesome AI for Chemistry

*[AI4Sci Edu](https://github.com/AI4SciEdu) related repo.* *Still under construction*🚧👷🏻‍♂️


<p align="center">
<img src="logo.jpg"  width="250" >
</p>

A list of awesome AI for chemistry papers. Inspired by the "Awesome" branded repositories in Computer Science. Please feel free to contribute and help to improve the quality of this page.

- Note 1: To highlight the paper, we switch the order of authors and paper title in the citation. Please cite the authors correctly instead of directly copying from our page.

- Note 2: If your work is not listed, but you feel it is influncial/inspiring/novel, please feel free to provide comments via Discussion or create an issue. 


## Table of Contents
Press `^` to return to the **`Table of Contents`**.

- [Reviews](#reviews)
- [Books](#books)
    - [Chemistry](#chemistry)
    - [Machine learning](#machine-learning)
- [Organic/Inorganic chemsitry: Retrosynthesis planning](#retrosynthesis)
    - [Molecular/Material design](#molecular/material-design)
    - [Reaction design/Reactivity](#reaction-design)
    - ...
- [Theoretical/Computational chemistry: Electronic structure](#electronic-structure)
    - [DFT parmetrization](#dft=parmetrization)
    - [DFT ansatz learning](#dft-ansatz-learning)
    - [Wavefunction learning](#wavefunction-learning)
    - [Wavefunction theory learning](#wavefunction-theory-learning)
    - [Active/embedding space learning](#active-embedding=space-learning)
- [Theoretical/Computational chemistry: Molecular Dynamics](#molecular-dynamics)
    - [Enhanced sampling](#enhanced-sampling)
    - [Force field design](#force-field-design) 
- [Theoretical/Computational chemistry: Property learning](#property-learning)
- [Generalized model/Datasets](#generalized-model/datasets)
- [Experimental physical chemistry](#experimental-physical-chemistry)
- [Biochemistry: Biomolecule (protein/nucleic acid/lipid) design/structure](#biomolecule-design)
- [Analytical chemistry](#analytical-chemistry)
- [Robotic chemist/Automation](#automated-experiments)


## Reviews [^](#table-of-contents)
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
15. [Perspective on integrating machine learning into computational chemistry and materials science.](https://pubs.aip.org/aip/jcp/article/154/23/230903/200193/Perspective-on-integrating-machine-learning-into)
    J. Westermayr, M. Gastegger, K. T. Schütt, & R. J. Maurer, The Journal of Chemical Physics **154**, 230903 (2021)

16. [Machine learning in scanning transmission electron microscopy.](https://www.nature.com/articles/s43586-022-00095-w)
    S. V. Kalinin, C. Ophus, P. M. Voyles, R. Erni, D. Kepaptsoglou, V. Grillo, A. R. Lupini, M. P. Oxley, E. Schwenker, M. K. Y. Chan, J. Etheridge, X. Li, G. G. D. Han, M. Ziatdinov, N. Shibata, & S. J. Pennycook, Nature Reviews Methods Primers **2**, 11 (2022) 

17. [Deep learning and artificial intelligence methods for Raman and surface-enhanced Raman scattering.](https://www.sciencedirect.com/science/article/pii/S0165993619305783)
    F. Lussier, V. Thibault, B. Charron, G. Q. Wallace, & J.-F. Masson. TrAC Trends in Analytical Chemistry **124**, 115796 (2020) 

18. [Machine Learning-Driven Multiscale Modeling: Bridging the Scales with a Next-Generation Simulation Infrastructure.](https://pubs.acs.org/doi/10.1021/acs.jctc.2c01018)
    H. I. Ingólfsson, H. Bhatia, F. Aydin,..., & F. H. Streitz, Journal of Chemical Theory and Computation **19**(9), 2658-2675 (2023)


## Books [^](#table-of-contents)
Note: We will try to provide both the most influncial/comprehensive books (usually the bible book for a field). We provide the links to the corresponding Amazon page to avoid confusion. The list will be updated timely manner. 

### Chemistry
#### Introductory
Note: Undergrad level readings. More general, cover many subfields.

1. [Chemistry: The central science 14th edition](https://www.amazon.com/Chemistry-Central-Science-Theodore-Brown/dp/0134414233)
    T. Brown, H. LeMay, B, Bursten, C. Murphy, P. Woodward, M. Stoltzfus. Pearson, 2017
2. [Principles of modern chemistry](https://www.amazon.com/Principles-Modern-Chemistry-David-Oxtoby/dp/1305079116)
    D.W. Oxtoby, H.P. Gillis, & A. Campion. Thomson Brooks/Cole, 2008
3. [Organic chemistry seventh edition](https://www.amazon.com/Organic-Chemistry-Marc-Loudon/dp/1319188427)
    M. Loudon & J. Parise. W. H. Freeman, 2021
4. [Quantitative chemical analysis](https://www.amazon.com/Quantitative-Chemical-Analysis-Daniel-Harris/dp/1429218150)
    D. C. Harris. W. H. Freeman, 2010
5. [Lehninger principles of biochemistry](https://www.amazon.com/Lehninger-Principles-Biochemistry-David-Nelson/dp/1464126119)
    D. L. Nelson & M. M. Cox 
6. [Physical chemistry 4th edition](https://www.amazon.com/Physical-Chemistry-Robert-J-Silbey/dp/047121504X)
    R. J. Silbey, R. A. Alberty, & M. G. Bawendi. Wiley, 2004
7. [Atkins' physical chemistry](https://www.amazon.com/Atkins-Physical-Chemistry-11e-Peter/dp/0198769865)
    P. Atkins, J. de Paula, & J. Keeler. Oxford University Press, 2018
8. [Fundamental of polymer science](https://www.amazon.com/Fundamentals-Polymer-Science-Introductory-Text/dp/1566765595)
    M. M. Coleman & P. C. Painter. Routledge, 1998


#### Advanced 
Note: Graduate level readings.

1. [Modern quantum chemistry: introduction to advanced electronic structure theory](https://www.amazon.com/Modern-Quantum-Chemistry-Introduction-Electronic/dp/0486691861)
    A. Szabo & N.S. Ostlund. Courier Corporation, 2012.
2. [Density-functional theory of atoms and molecules](https://www.amazon.com/Density-Functional-Molecules-International-Monographs-Chemistry/dp/0195092767)
    R. G. Parr & W. Yang. Oxford University Press, 1994
3. [Molecular electronic-structure theory](https://www.amazon.com/Molecular-Electronic-Structure-Theory-Trygve-Helgaker/dp/1118531477)
    T. Helgaker, P. Jorgensen, J. Olsen. Wiley, 2013
4. [Statistical mechanics](https://www.amazon.com/Statistical-Mechanics-Donald-McQuarrie/dp/8130918935)
    D. A. McQuarrie. VIVA, 2015
4. [Statistical mechanics: theory and molecular simulation](https://www.amazon.com/Statistical-Mechanics-Molecular-Simulation-Graduate/dp/0198525265)
    M. E. Tuckerman. Oxford University Press, 2010
5. [Theories of molecular reaction dynamics: the microscopic foundation of chemical kinetics](https://www.amazon.com/Theories-Molecular-Reaction-Dynamics-Microscopic/dp/0199652759)
    N. E. Henriksen & F. Y. Hansen. Oxford University Press, 2012
6. [Essentials of Computational Chemistry: Theories and Models](https://www.amazon.com/Essentials-Computational-Chemistry-Theories-Models/dp/0470091827)
    C. J. Cramer. Wiley, 2004
7. [Introduction to spectroscopy](https://www.amazon.com/Introduction-Spectroscopy-Donald-L-Pavia/dp/128546012X)
    D. L. Pavia, G. M. Lampman, G. S. Kriz, & J. A. Vyvyan. Cengage Learning, 2014
8. [First course in electrode processes](https://www.amazon.com/First-Course-Electrode-Processes-ebook/dp/B07QGN1XTV)
    D. Pletcher. Royal Society of Chemistry, 2019
9. [Biological physics: Energy, information, life](https://www.amazon.com/Biological-Physics-Student-Energy-Information/dp/057868702X)
    P. Nelson. Chiliagon Science, 2020
10. [Molecular symmetry and group theory](https://www.amazon.com/Molecular-Symmetry-Group-Theory-Introduction/dp/0471489395)
    A. Vincent. Wiley, 2001
11. [Introduction to atmospheric chemistry](https://www.amazon.com/Introduction-Atmospheric-Chemistry-Daniel-Jacob/dp/0691001855)
    D. J. Jacob. Princeton University Press, 1999
12. [Introduction to Bioorganic Chemistry and Chemical Biology](https://www.amazon.com/Introduction-Bioorganic-Chemistry-Chemical-Biology/dp/0815342144)
    D. Van Vranken & G. A. Weiss. Garland Science, 2012
13. [Solid state chemistry and its applications](https://www.amazon.com/Solid-State-Chemistry-its-Applications/dp/1119942942) 
    A. R. West. Wiley, 2014
14. [Modern physical organic chemistry](https://www.amazon.com/Modern-Physical-Organic-Chemistry-Anslyn/dp/1891389319)
    E. V. Anslyn & D. A. Dougherty. University Science, 2005
15. [Physics and chemistry of interfaces](https://www.amazon.com/Physics-Chemistry-Interfaces-Hans-J%C3%BCrgen-Butt/dp/3527414053)
    H. Butt, K. Graf, & M. Kappl. Wiley-VCH, 2023


### Machine Learning
Note: General reading materials. For indepth reading, could check out other awesome series repo, for example, [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)

1. [Machine learning: A probabilistic perspective](https://www.amazon.com/Machine-Learning-Probabilistic-Perspective-Computation/dp/0262018020)
    K. P. Murphy. The MIT Press, 2012
2. [Deep Learning](https://www.amazon.com/Deep-Learning-Adaptive-Computation-Machine/dp/0262035618)
    I. Goodfellow, Y. Bengio & A. Courville. The MIT Press, 2016
3. [Pattern recognition and machine learning](https://www.amazon.com/dp/0387310738)
    C. M. Bishop. Springer, 2006
4. [The elements of statistical learning: Data mining, inference, and prediction](https://www.amazon.com/Elements-Statistical-Learning-Prediction-Statistics/dp/0387848576)
    T. Hastie, R. Tibshirani & J. Friedman. Springer, 2016


## Retrosynthesis [^](#table-of-contents)
### Molecular/Material Design
1. [Planning chemical syntheses with deep neural networks and symbolic AI.](https://www.nature.com/articles/nature25978)
    Marwin H. S. Segler, Mike Preuss, & Mark P. Waller, Nature **555**, 604–610 (2018) [Reinforcement learning]
2. [Learning retrosynthetic planning through simulated experience.](https://pubs.acs.org/doi/full/10.1021/acscentsci.9b00055)
    John S. Schreck, Connor W. Coley, & Kyle J. M. Bishop, ACS Central Science **5**(6), 970-981 (2019) [Reinforcement learning]
3. ...

### Reaction Design
1. [Prediction of organic reaction outcomes using machine learning](https://pubs.acs.org/doi/full/10.1021/acscentsci.7b00064)
    Connor W. Coley, Regina Barzilay, Tommi S. Jaakkola, William H. Green, & Klavs F. Jensen, ACS Central Science **3**(5), 434–443 (2017)
2. 

## Electronic Structure [^](#table-of-contents)
 

## Molecular Dynamics [^](#table-of-contents)

### Force Field Design
1. [SchNet - A deep learning architecture for molecules and materials](https://pubs.aip.org/aip/jcp/article/148/24/241722/962591/SchNet-A-deep-learning-architecture-for-molecules) 
    K. T. Schütt, H. E. Sauceda, P.-J. Kindermans, A. Tkatchenko, & K.-R. Müller, The Journal of Chemical Physics **148**, 241722 (2018)
2. [ANI-1: An extensible neural network potential with DFT accuracy at force field computational cost](https://pubs.rsc.org/en/content/articlelanding/2017/sc/c6sc05720a)
    J. S. Smith, O. Isayev, & A. E. Roitberg, Chemical Sciences **8**, 3192-3203 (2017)
3. [Gaussian approximation potentials: The accuracy of quantum mechanics, without the electrons.](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.104.136403)
    A. P. Bartók, M. C. Payne, R. Kondor, & G. Csányi, Physical Review Letters **104**, 136403 (2010)
4. [Machine learning Of accurate energy-conserving molecular force fields.](https://www.science.org/doi/10.1126/sciadv.1603015) 
    S. Chmiela, A. Tkatchenko, H. E. Sauceda, I. Poltavsky, K. T. Schütt, & K.-R. Müller, Science Advances **3**, No. e1603015 (2017)
5. [DeePMD-kit: A deep learning package for many-body potential energy representation and molecular dynamics.](https://www.sciencedirect.com/science/article/pii/S0010465518300882)
    H. Wang, L. Zhang, J. Han, & E. Weinan, Computer Physics Communications **228**, 178−184 (2018)
6. [Generalized neural-network representation of high-dimensional potential-energy surfaces.](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.98.146401)
    J. Behler &  M. Parrinello Physical Review Letters **98**, 146401 (2007)
7. [The TensorMol-0.1 model chemistry: A neural network augmented with long-range physics.](https://pubs.rsc.org/en/content/articlehtml/2018/sc/c7sc04934j)
    K. Yao, J. E. Herr, D. W. Toth, R. Mckintyre, J. Parkhill, Chemical Sciences **9**, 2261−2269 (2018)
8. [Teaching a neural network to attach and detach electrons from molecules.](https://www.nature.com/articles/s41467-021-24904-0)
    R. Zubatyuk, J. S. Smith, B. T. Nebgen, S. Tretiak, & O. Isayev, Nature Communications **12**, 4870 (2021)
9. 
10. 

## Property learning [^](#table-of-contents)
1. [Physnet: A neural network for predicting energies, forces, dipole moments and partial charges.](https://pubs.acs.org/doi/10.1021/acs.jctc.9b00181)
    O. T. Unke & M. Meuwly, Journal of Chemical Theory and Computions **15**, 3678−3693 (2019)
2.

## Generalized Model/Datasets [^](#table-of-contents)
1. [The Open Reaction Database.](https://pubs.acs.org/doi/10.1021/jacs.1c09820)
    S. M. Kearnes, M. R. Maser, M. Wleklinski, A. Kast, A. G. Doyle, S. D. Dreher, J. M. Hawkins, K.s F. Jensen, & C. W. Coley, Journal of the American Chemical Society **143**(45), 18820–18826 (2021). [Dataset](https://docs.open-reaction-database.org/en/latest/)
2. QM series (Please also see [quantum-machine](http://quantum-machine.org/datasets/) page)
- QM9 Dataset:
    - [Quantum chemistry structures and properties of 134 kilo molecules.](https://www.nature.com/articles/sdata201422)
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
    - [Large yet bounded: Spin gap ranges in carbenes.](https://arxiv.org/abs/2004.10600)
    M. Schwilk, D. N. Tahchieva, & O. A. von Lilienfeld, arXiv:2004.10600 (2020)
    - Dataset[Part 1](http://quantum-machine.org/data/qmspin/QMspin_Part1.tar.gz)  \&  [Part 2](http://quantum-machine.org/data/qmspin/QMspin_Part1_wo_outputs.tar.gz)
 
- [tmQM Dataset.](https://chemrxiv.org/engage/chemrxiv/article-details/60c74f55f96a00358e287c11) Dataset: [Geometries](http://quantum-machine.org/data/tmQM/tmQM_X.xyz.gz)   \&  [Properties](http://quantum-machine.org/data/tmQM/tmQM_y.csv.gz)
     D. Balcells, B. B. Skjelstad ChemRxiv. (2020)

3. GDB series:
- GDB 17:
    - [Original paper.](https://pubs.acs.org/doi/full/10.1021/ci300415d)
    L. Ruddigkeit, R. van Deursen, L. C. Blum, & J.-L. Reymond, Journal of Chemical Information and Modelling **52**, 2864–2875 (2012)
- GDB 13:
    - [Original paper.](https://pubs.acs.org/doi/10.1021/ja902302h)
    L. C. Blum & J.-L. Reymond, Journal of the American Chemical Society **131**, 8732 (2009)

4. [MD17 dataset.](https://www.science.org/doi/10.1126/sciadv.1603015) 
    - [Original Dataset.](http://www.sgdml.org/#datasets)
    S. Chmiela, A. Tkatchenko, H. E. Sauceda, I. Poltavsky, K. T. Schütt, & K.-R. Müller, Science Advances **3**,e1603015(2017)
    - [Reviseddataset (rMD17).](https://figshare.com/articles/dataset/Revised_MD17_dataset_rMD17_/12672038)
    A. S. Christensen & O. A. von Lilienfeld, arXiv:2007.09593 (2020)

5. [DESMILES Models & Training datasets.](https://www.deshawresearch.com/downloads/download_desmiles.cgi/)
    P. Maragakis, H. Nisonoff, B. Cole, & D. E. Shaw

6. [Harvard organic photovoltaic dataset(HOPV15).](https://www.nature.com/articles/sdata201686) [Dataset](https://www.nature.com/articles/sdata201686#ref-CR43)
    S. A. Lopez, E. O. Pyzer-Knapp, G. N. Simm, T. Lutzow, K. Li, L. R. Seress, J. Hachmann, & A. Aspuru-Guzik, Scientific Data **3**, 160086 (2016)

7. [The material project.](https://pubs.aip.org/aip/apm/article/1/1/011002/119685/Commentary-The-Materials-Project-A-materials) [Website](https://materialsproject.org/)
    A. Jain, S. P. Ong, G. Hautier, W. Chen, W. D. Richards, S. Dacek, S. Cholia, D. Gunter, D. Skinner, G. Ceder, & K. A. Persson, APL Materials **1**, 011002 (2013)

8. [The Liverpool materials discovery server.](https://chemrxiv.org/engage/chemrxiv/article-details/646612c7a32ceeff2dd7d288) [Website](lmds.liverpool.ac.uk)
    S. Durdy, C. J. Hargreaves, M. Dennison, B. Wagg, M. Moran, J. A. Newnham, M. W. Gaultois, M. J. Rosseinsky, & M. Dyer, ChemRxiv, 10.26434/chemrxiv-2023-wgdm0 (2023)

## Experimental Physical Chemistry [^](#table-of-contents)
1. ...

## Biomolecule Design [^](#table-of-contents)
1. ...

## Analytical chemistry [^](#table-of-contents)
1. ...

## Automated Experiments [^](#table-of-contents)
1. [A mobile robotic chemist.](https://www.nature.com/articles/s41586-020-2442-2)
    B. Burger, P. M. Maffettone, V. V. Gusev, C. M. Aitchison, Y. Bai, X. Wang, X. Li, B. M. Alston, B. Li, R. Clowes, N. Rankin, B. Harris, R. S. Sprick, & A. I. Cooper, Nature **583**, 237–241 (2020) [Robtics + Bayesian learning]
2. [A robotic platform for flow synthesis of organic compounds informed by AI planning.](https://www.science.org/doi/full/10.1126/science.aax1566) 
    C. W. Coley, D. A. Thomas III, J. A.M. Lummiss, J. N. Jaworski, C. P. Breen, V. Schultz, T. Hart, J. S. Fishman, L. Rogers, H. Gao, R. W. Hicklin, P. P. Plehiers, J. Byington, J. S. Piotti, W. H. Green, A. J. Hart, T. F. Jamison, & K. F. Jensen, Science **365**(6453), eaax1566 (2019) [Software + Experiments]
