# BME_3053C_Final_Project
Bane, Denning, Filippone, Lafayette, Ramanand, Wagner

## Dataset

We started with the Figshare dataset “Brain Tumor Dataset” found at:

> https://figshare.com/articles/dataset/brain_tumor_dataset/1512427


The original uploader split the full collection (3064 slices) into four chunks of 766 files each. I only uploaded 2/4 zip files for a total of 1532 test files. 

## Running Code

1. Install dependencies by copy pasting the pip install line in cell 1 in your terminal

2. Click Restart 

3. Configure sample size (optional):

- Find the MAX_SAMPLES line near the top.

- To test quickly, set MAX_SAMPLES = # (whatever amount of files you'd like to test, it has been preset to 200)

- To train on the full set, comment out the MAX_SAMPLES = # line and uncomment the 
MAX_SAMPLES = None line found shortly below

4. Click run or CTRL+Enter in cell 2! 