# FeatureSelection-KarstSpringLSTM
This is the repository containing all the data and code used in the investigation of feature selection on modeling Wakulla Spring, an eogenetic karst spring, using and LSTM neural network. 

This repository contains folders for Code, Data, Plots, Models, Results  and Additional Figures.

Some raw data was collected manually frm the Northwest Florida Water Management District online portal (https://nwfwmd.aquaticinformatics.net/) and the Florida Climate Center (https://climatecenter.fsu.edu/climate-data-access-tools/downloadable-data), and this has been noted in the code when appropriate. USGS data of Wakulla Spring was downloaded within the notebook. Both raw and processed data can be found in the data folder.


Code is organized in 4 Jupyter Notebooks
1. Data processing
2. Hyperparameter tuning for each of the neural networks
3. Training the neural networks under the tuned parameters and saving the network weights and simulation results
4. Generating figures used in the reports

Due to the computational demands of hyperparameter tuning, it is recommended to not run this code again unless you have a good amount of storage and time.

Model weights for each of the models are saved in the Models folder from Notebook 3, and loaded from here in Notebook 4.

Plots generated with code are saved in the Plots folder from Notebook 4.

Some additional figures for this study were generated in ArcGIS Pro and Adobe Illustrator, and these files can be found in the AdditionalFigures folder.

