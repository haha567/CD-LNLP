# CD-LNLP
 
## Introduction

- `data/association.csv` is the circRNA-disease association matrix.

-  `LNLP_methd` contains our method, that is `linear_neighbor_predict`.

- `semisupervise.py` contains the method we calculate metrics.

- `input_and_output.py` contains methods for input and output.

- `evaluation_result/loocv` contains our method's metrics.
    - `0.1_0.9_1.0_loo.csv` contains the values of 6 metrics.
    - `0.1_0.9_1.0_loo_pr_x.csv` contains the values of **recall**.
    - `0.1_0.9_1.0_loo_pr_y.csv` contains the values of **precision**.
    - `0.1_0.9_1.0_loo_roc_x.csv` contains the values of **False Positive Rate**.
    - `0.1_0.9_1.0_loo_roc_y.csv` contains the values of **True Positive Rate**

## Run LOOCV evaluation

### Prerequisites
 - python 3.6
   
 - In addition, you may need to install some basic python packages.
 
### Run LNLP_evaluation.py

You will get the output at `evaluation_result/loocv` folder. We have produced the result in the folder.