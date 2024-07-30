# CSP_immunotherapy_model
XGBoost anti-PD1/PD-L1 immunotherapy model based on cGAS-STING-centric pathways
## Step 1: Configure  the  working  environment.
We recommend the use of conda for managing R version and R package versions.
        R 4.2.2  
        xgboost 1.6.0.1 
        Tip: If you are unable to ensure that the version of R is 4.2.2 within the conda environment, the version 4.2.0 is also acceptable.
## Step 2: Establish a new working directory including following files.
        /new working directory  
          |_ CSP_immunotherapy_model.R  
          |_ Input_File.csv  
          |_ Trained_XGBoost.model   
       Tip: The "Input_File.csv" document is fundamentally a gene expression matrix (TPM format);     
            when using it, please replace the provided file with your own.  
## Step 3: Directly execute the Python script.
        Rscript CSP_immunotherapy_model.R  
## Step 4: Inspect the output file.
After executing the aforementioned R script, you will obtain a file named "Output_file.csv"; "response_probability" denotes the anti-PD1/PD-L1 response probability of patients with hepatocellular carcinoma, with higher response probability indicating better prognosis. Our model might also be applicable in the immunotherapy of urothelial  carcinoma and melanoma with using anti-PD1/PD-L1.







  

## Tip: our code and data are only for academic researches.


