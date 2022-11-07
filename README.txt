Capstone Notebooks in order

capstone Data Cleaning - environment : Capstone_environment
- This notebook contains summaries of the different Datasets used in this capstone, as well as the steps taken to reduce the size of the Datasets to only include appropriate data

Capstone EDA_feature creation - environment: Capstone_EDA_environment
- This notebook contains my EDA of the data, as well the creation of all the features I used for my modelling. As all columns that were modelled where created features, feature creation takes up the majority of this notebook
- There is a separate Conda environment for the is notebook, due to the huge amount of pre-requisites required to run GeoPandas, which I couldn't use in my main envrionment.

Capstone pre-processing_initial models - environment: Capstone_environment
- This notebook contains pre-processing (scaling, train-test-split and BoxCox transformation), as well as basic models. These models are not ensemble, and were tested here to see which base models the ensemble models should be built on.

Capstone Advanced modelling - environment: Capstone_environment
- This is the final notebook and contains my evaluation of my ensemble (Advanced) models. This notebook also contains an extensive conclusion to the project.

Data - the datasets are explained in the report and can accessed via the "project url" on synapse or here:

ds_utils - This is a python file that contains basic EDA features

Report - A summary of the project goals and objectives - with the final section being copied from the last notebook
