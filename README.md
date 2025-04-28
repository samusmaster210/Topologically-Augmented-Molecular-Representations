# **Topologically-Augmented-MACCS-Keys-for-Protein-Ligand-Classification**

# **Overview**

  Cheminformatics, aided by machine learning, has become a cornerstone of modern drug discovery. This is due to the developed molecular fingerprints that translate a chemical’s structure into a machine-readable format. Traditional substructure representations, like MACCS Keys, record the appearance of predefined structural fragments; however, they ignore the compound’s overall morphology. 
  Topological data analysis (TDA) is an interdisciplinary field of research that uses persistent homology to evaluate the underlying shape of data, and it can be represented using a persistence diagram, landscape, barcode. When applied as a chemical representation, it reveals unique insights into the structure’s form, represented by the homological features: connected components, rings, and cavities. 
  Integrating topology‐based descriptors into a classic cheminformatic fingerprint produces an enriched description vector, which yields a more holistic representation of the molecule and improves the prediction of the molecule’s protein binding interaction. Our work combines persistence images (PIs) with MACCS Keys into a single topological substructure vector (TSV) fingerprint and individually tests its predictive performance on 19 ChEMBL protein-ligand datasets using the same multi-layered perceptron classifier (MLPC) architecture. 
  Persistence images capture each molecule's intrinsic geometry and connectivity, while MACCS Keys encode chemical substructures. Across all but one dataset, the TSV descriptor outperformed its individual components, achieving the highest average validation Matthews correlation coefficient of 0.7988. In contrast, the MACCS Keys’ score was 0.7075, and the TPI descriptor scored 0.7655. These results show that adding topology-based features to classic fingerprints can boost classification reliability in computer-aided drug design.

  ---

# **Installation**

The code is written in Python using Python 3.9.22










---

# **Installation Help**

The packages and their version numbers are explicitly listed here to aid in troubleshooting any conda environment problems

- Python 3.9.22
- Numpy 1.26.4
- Pandas 2.2.3
- PyTorch 2.6.0
- RDKit 2025.03.1
- SciKit Learn 1.2.2
- Ripser 0.6.12
- Cython 3.0.12
- persim 0.3.0
- imbalanced-learn (SMOTE) 0.10.1
- Jupyter Notebook 7.4.0
  

