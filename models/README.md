# Models

This folder is reserved for the serialized final scikit-learn Pipeline for the PTB-XL ECG risk classification project.

The final model pipeline is created in the notebook and saved with the following file name:

`final_ptbxl_pipeline.pkl`

The saved pipeline includes preprocessing, feature engineering, and the final trained classifier. This supports reproducibility because the same transformation and prediction workflow can be reused without manually rebuilding each step.

If the `.pkl` file is not included in this repository, the final Jupyter Notebook in the `notebooks/` folder can be rerun from top to bottom to recreate the final trained pipeline.
