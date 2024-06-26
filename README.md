# Drug-Absorption-Prediction
In the field of pharmaceutical research and development, the first step in identifying a novel therapeutic or enhancing an existing one is exploring potential drug candidate molecules. However, understanding the pharmacokinetic and pharmacodynamic properties of these drug candidates remains challenging.

This code uses a Random Forest model to predict drug permeability across the cellular membrane. A dataset comprising 2035 drug molecules was acquired from the publication "[**Validating ADME QSAR models using marketed drugs**](https://journals.sagepub.com/doi/full/10.1177/24725552211017520)" (2021) by Siramshetty *et al*. The ```tdc.single_pred``` library was utilized to import and define SMILES strings and labels in the dataset. Features were generated using the RDKit module. The model was first trained on the training set (70% split) and validated on the validation set (10% split), after which it was evaluated on the testing set (20% split). A five-fold cross-validation was also performed.

## Installation
All relevant packages are installed using pip. Please follow the instructions in [here](https://pip.pypa.io/en/stable/installation/) to install pip.

## Usage
1. Open the ```permeability_prediction.ipynb``` file in Google Colab or Jupyter Notebook.
2. The notebook contains the code to install all packages and requirements. Run all the cells in the notebook to observe.

## Citation
[1] Siramshetty V, Williams J, Nguyễn ÐT, Neyra J, Southall N, Mathé E, Xu X, Shah P. Validating ADME QSAR Models Using Marketed Drugs. SLAS Discov. 2021 Dec;26(10):1326-1336. doi: 10.1177/24725552211017520. Epub 2021 Jun 26. PMID: 34176369.

[2] Landrum, G. 2010. “RDKit.” Q2. https://www.rdkit.org/.
