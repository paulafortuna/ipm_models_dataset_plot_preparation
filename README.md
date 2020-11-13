# ipm_models_dataset_plot_preparation

In this repository we have the scripts that support the data preparation for the third experiment of our paper:

The complete experiment pipeline for this paper can be found [here](https://github.com/paulafortuna/IP-M_abusive_models_generalize).

In this experiment we aim at systematically study which model and dataset features lead to a better generalization in abusive language-related models, we run an experiment on the relation between the performance when applying BERT, ALBERT, fastText, and SVM and 16 prominent features of the models and datasets considered in the literature as good generalization predictors (e.g number of instances, dataset class). 

Here we present the code for data prepation for the random forest experiment we conduct [here](https://github.com/paulafortuna/ipm_model-generalization_random_forest). 

The code is organized as follows:

data repository - The data that we achieved by following the code in the Experiment 2 of our pipeline. It contains the data about every SVM, fastText, BERT and ALBERT models we have from our previous experiments; it contains also dataset descriptives.

2020-10-19_cross-dataset-generalization_with_SVM_paper.Rmd  - It is a R script for dataset and plot preparation
