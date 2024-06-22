# Hospital Readmissions Prediction
Prediction of hospital readmissions of diabetic patients

This repo contains the Applied AI coursework to predict hospital readmissions for diabetic patients, regardless of the time after which they were readmitted (>30 or <30 days after the first recorded visit). I used a linear Support Vector Machine (SVM) as a baseline, and compared this with an SVM with a Radial Basis Function (RBF Kernel), a RandomForest, and XGBoost. The RandomForest achieved the best performance across two experiments. For the first experiment, the coursework tasked us with using a cross-validation pipeline and single held-out test set; for the second, a nested cross-validation pipeline was required for more robust results.  

The dataset used includes ten years (1999-2008) of clinical care records of patients diagnosed with diabetes, compiled from 130 US hospitals and integrated delivery networks. This is publicly available in the [UCI Machine Learning repository](https://doi.org/10.24432/C5230J).  

The code can be found in the Jupyter notebook (`.ipynb`).  The report and appendix pdfs are also provided.
