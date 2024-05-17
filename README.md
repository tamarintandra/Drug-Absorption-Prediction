# Drug-Absorption-Prediction
In the field of pharmaceutical research and development, the first step in the journey to identifying a novel therapeutic or enhancing an existing one is exploring unknown drug candidate molecules. However, understanding the pharmacokinetic and pharmacodynamic properties of the drug candidate remain challenging. 

This code uses a Random Forest model to predict drug permeability across the cellular membrane. A dataset comprising 2035 drug molecules was acquired from the publication "**Validating ADME QSAR models using marketed drugs**" (2021) by Siramshetty *et al*. The dataset was used to train and validate the machine learning model. Features were generated using the RDKit module. The model was first trained on the training set (70% split) and validated on the validation set (10% split), after which it was evaluated on the testing set (20% split). A five-fold cross-validation was also performed.

## Citation
[1] Siramshetty V, Williams J, Nguyễn ÐT, Neyra J, Southall N, Mathé E, Xu X, Shah P. Validating ADME QSAR Models Using Marketed Drugs. SLAS Discov. 2021 Dec;26(10):1326-1336. doi: 10.1177/24725552211017520. Epub 2021 Jun 26. PMID: 34176369.
[2] Landrum, G. 2010. “RDKit.” Q2. https://www.rdkit.org/.
