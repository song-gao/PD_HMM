step 0. First put 'A5Sec_2' folder containing all 28 patients' data into the directory. Run 'import_script.m'. (Actually this step doesn't need to be done again as the results are already saved as 'data_cell.mat' so that just directly run step 1)

step 1. run 'training.m' to run train the model using all the patients' data.

step 2. run run_viterbi.m to decode the hidden states and show sample distribution. And the figures would be saved in the folder as '{patient_number}-{figure-number}.jpg' files and the figures in MATLAB would be closed to prevent program being frozen. The decode results would be saved as '{patient_number}.mat'.

The program to synthesize data and apply that to the training model is 'verify_Baum_Welch_with_synthesized_data.m'.
