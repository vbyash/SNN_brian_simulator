***README***

The given ZIP file contains 4 files: 
  - Hand_snn_CP302_with_bias.ipynb and Hand_snn_CP302_without_bias.ipynb: Can be opened with Google Colab/Jupyter Notebook/VS Code. Contains the main code for SNN.
  - weight.csv: Contains weights used in SNN
  - bias.csv: Contains bias values used in SNN
  - try.txt: Contains 1797 (i.e. a set of 1797 input vectors) lines with each line having 65 integers separated by ','. In each line, first 64 integers represent 64 inputs and 65th integer represents the output label for that input. Use this file to give all the digits (0-9) as input to the model.
  - test.txt: Contains 80 (i.e. a set of 80 input vectors) lines with each line having 65 integers separated by ','. In each line, first 64 integers represent 64 inputs and 65th integer represents the output label for that input. Use this file for giving ( 20 samples of each of 0,1,2,7) as input to the model.

Insert the complete path of bias file, weights file test.txt/try.txt file in the code if the files are moved to some other location from after extracting them to a folder.
If all the files and python code are kept in the same folder after extracting, then no need to make any changes in the paths already written in the code.

The user needs to run each cell one by one in the given sequence in the code file except the second cell. 
IMPORTANT Run the 2nd cell to clear cache only if the first cell shows an error and then begin with the first cell again.

The given code runs the SNN model for the test cases in 'try.txt' (or 'test.txt') files and displays the predicted output v/s actual digit, accuracy of the model and plots showing spiking patterns for each of the input and output neurons.
