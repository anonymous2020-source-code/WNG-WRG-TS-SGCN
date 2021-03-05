# WNG-WRG-TS-SGCN
This repository holds the source code of Weighted Neighborhood Graph (WNG) and Weighted random Graph (WRG) method. The code consists of three parts: Data, Complex_network, and Classification_model.


Data

Due to the size limitation of upload file, we provide source code for batch processing of data. The Bonn dataset can be obtained from：http://epileptologie-bonn.de/cms/front_content.php?idcat=193&lang=3&changelang=3.


Complex_network

This part contains method file. All of the complex network methods are in this file.


Classification_model

This part contains five code files, TS-MLP.py, TS-CNN.py, TS-GNN.py, TS-SGCN.py and main.py. The main file is main.py. To use these classifier, please keep all three files in a sinlge folder, and make sure that you have pytorch, Python 3 and all the packages we have used installed.

Next, please take the following two steps.

Step 1. Change the path in line 20 and 21 of training.py to the train and test folder's path.

Step 2. Run the command in your command council.
