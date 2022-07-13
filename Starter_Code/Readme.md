### Step 1: Tune the training algorithm by adjusting the size of the training dataset. 

To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your `README.md` file. 

Answer the following question: What impact resulted from increasing or decreasing the training window?

Increasing the training window to 6 months (doubling) created better fit in the later period while decreasing it worsened the model output. Increasing to 12 months was optimal.   



Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?

Increasing and decreasing either the long or short SMAs did nothing to improve the model output.  The opitimal result is the default setting.  