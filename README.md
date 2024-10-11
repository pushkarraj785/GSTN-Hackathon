# GSTN-Hackathon
# Team ID: GSTN_222

**Instructions for Running Scripts in the `gstn` Directory:**

1. **Train the Model:**
   - Run `Model.py` to train the machine learning model and save it as `final_model.pkl`.
   - Command: 
     ```bash
     python Model.py
     ```

2. **Validate the Model:**
   - **With Target Labels:** Run `validation_with_target.py` to generate predictions and calculate metrics.
     - Command:
       ```bash
       python validation_with_target.py
       ```
     - Output: `val_submission_2.csv` with metrics.

   - **Without Target Labels:** Run `validation.py` to generate predictions only.
     - Command:
       ```bash
       python validation.py
       ```
     - Output: `val_submission.csv`. 
