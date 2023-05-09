This repository is the final project for the Machine Learning in Geosciences course at KAUST. The aim of the project is to classify rocks based on their mantle-source signature using only major and minor elemental composition; however, as per the current state of the project, the aim was not totally fullfilled. For future work the labeling of the input data needs to be improved, as well as the imbalace of the data per class. Project is under development 💜 all suggestions are more than welcome (by email or PR). 


*Software requirements*
* Python 3.8.16
* Pytorch 2.0.0
* Pandas 2.0.1

*Content description*

**scripts folder**
* Data_labeling: This file needs to be run in order to create the input file required for the [model](../Porject_ML_Mantle_Source/scripts/Model.ipynb). 

* Model: Script of the model used for this excercise. 

**DataFP folder**
* [dataOK](../Porject_ML_Mantle_Source/DataFP/dataOK.csv) is the input file for the [data_labeling](../Porject_ML_Mantle_Source/scripts/Data_labeling.ipynb). [dataOK](../Porject_ML_Mantle_Source/DataFP/dataOK.csv) was obtained after filtrating the data published in [Ueki et al., 2022](https://github.com/hideitsu/geoSMR/blob/4ce024f5f7e9dc76b1be6f8a5a49b198059a5f2e/Uekietal_SMR_input.csv), [Ueki et al., 2018](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2017GC007401) and [Gard et al., 2019](https://doi.org/10.5194/essd-11-1553-2019
). For the filtration were considered only mafic rocks, both intrusive and extrusive, meaning basalts but also mantle xenoliths. 
* [final_data](../Porject_ML_Mantle_Source/DataFP/final_data.csv) is the input file for the [model](../Porject_ML_Mantle_Source/scripts/Model.ipynb). This data file contain the labels for each rock sample and the different features, meaning the isotopic values and the major and minor composition for each rock. 

* All the other files in this folder are explained in the [data_labeling script](../Porject_ML_Mantle_Source/scripts/Data_labeling.ipynb) or [model script](../Porject_ML_Mantle_Source/scripts/Model.ipynb)

**Results**

It contains the classification resports and the confusion matrix of the testing. 


