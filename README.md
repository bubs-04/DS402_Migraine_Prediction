# DS402_Migraine_Prediction
DS402 final project on migraine headaches prediction.
# Project: Migraine Attack Prediction Using Patient-Reported Data
# Course: DS402 - Machine Learning for Healthcare
# Team Members:
#   1. Prabhat Mattaparthi (pkm5487@psu.edu)
#   2. Rohan Samuel Sampath (rss5845@psu.edu)

-------------------------------------------------------------------------
FILES INCLUDED IN THIS ARCHIVE:
-------------------------------------------------------------------------
1. Project_Report.pdf        - The final project report (5 pages).
2. Migraine_Prediction.ipynb - The source code (Jupyter Notebook).
3. migraine_data.csv         - The synthetic dataset used for training.
4. README.txt                - This file.

-------------------------------------------------------------------------
HOW TO RUN THE CODE
-------------------------------------------------------------------------
Note: This notebook was developed using Google Colab. It utilizes the
`google.colab` library for file uploading. It is highly recommended to 
run this in Google Colab to avoid environment issues.

OPTION 1: RUNNING ON GOOGLE COLAB (RECOMMENDED)
1. Open Google Colab (https://colab.research.google.com/).
2. Go to File > Upload Notebook and upload the 'Migraine_Prediction.ipynb' file.
3. In the notebook, go to Runtime > Run all.
4. **CRITICAL STEP**: When the first code cell runs, a "Choose Files" button 
   will appear in the output area. Click it and upload the included 
   'migraine_data.csv' file.
5. The rest of the notebook will execute automatically, training the LSTM 
   model and generating the results/plots.

OPTION 2: RUNNING LOCALLY (JUPYTER NOTEBOOK)
1. Ensure you have the following libraries installed:
   pip install pandas numpy scikit-learn tensorflow matplotlib seaborn
2. Place 'Migraine_Prediction.ipynb' and 'migraine_data.csv' in the same folder.
3. Open the notebook.
4. You may need to comment out the `google.colab` import and manually load 
   the CSV using `df = pd.read_csv('migraine_data.csv')` in the first cell.
5. Run all cells.

-------------------------------------------------------------------------
DEPENDENCIES
-------------------------------------------------------------------------
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn
