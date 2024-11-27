# this-and-that
this-and-that has stuff worth sharing.
  
  1-basic-use-xgboost gives a quick introduction on how to use xgboost with CPU or GPU. It uses the diamond dataset in seaborn. It is assumed that you have your environment setup for the XGBoost. I suggest checking these sites for the setup: [the official XGBoost website](https://xgboost.readthedocs.io/en/stable/), [this article](https://medium.com/rapids-ai/rapids-23-10-release-075aa5a50570#0ebc). Especially, the latter one I followed for the GPU setup.

  2-ordinal-or-not continues from 1, but focusing on some hypothesis testing regarding the 'cut' variable. It demonstrates how you can represent a variable as nominal or ordinal.

  3-reconstruction-with-xgboost introduces a reconstruction module for feature engineering before a predictive model training with xgboost. The latent features from the reconstructor's encoder, which has smaller dimension than the original/physical features, can be used instead. This notebook demonstrates the workflow.
