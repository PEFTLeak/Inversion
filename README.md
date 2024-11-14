Run the file Adapter_attack.ipynb. That will call functions from the following files.
Transformer_Model_neuron.py contains the architecture with inserted adapter module
Design_Model_Adapter.py contains the code for malicious design of the parameters
Processing_v2.py contains the code for creating patch statistics' intervals according to public dataset
Recover_Adapter.py recovers the patches from adapter gradients
Clustering.py groups the recovered patches to create the entire images (motivated by Fowl et. al., 2023)
