# Instructions

## Goal
Train and validate a surrogate model for an FSI dataset.

## Reference

The methodology implemented in this workshop is based on: Lomazzi L, Morin D, Cadini F, Manes A, Aune V. Deep learning-based analysis to identify fluid-structure interaction effects during the response of blast-loaded plates. International Journal of Protective Structures. 2024;15(4):722-752. doi:[10.1177/20414196231198259](https://journals.sagepub.com/doi/10.1177/20414196231198259).  

## What to do

1. **Open the notebook in Colab**  
   - [Open in Colab](https://colab.research.google.com/github/lucalomazziPolimi/Pia-Enhance-Course/blob/main/04_workshops/01_workshop_fsi/FSI_DL_session.ipynb)

2. **Enable GPU (recommended)**  
   - In Colab, go to: `Runtime` → `Change runtime type`  
   - Set **Hardware accelerator** to **T4 GPU**  
   - Click **Save**

3. **Run the setup cells**
   - Mount your Google Drive
   - The dataset will be downloaded automatically

4. **Run the notebook step by step**
   - Preprocess the dataset  
   - Train the surrogate model  
   - Evaluate the results  

## Expected outcome

You should obtain:
- A trained surrogate model  
- Basic validation plots showing model performance  

## Notes
  
- If you encounter errors, restart the runtime and run all cells again  
