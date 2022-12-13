# ML7267ProjectCodes
Option 1: Grade part 01 as presented. 

01: 
01a:  01_a_MLP_Bandwaves.ipynb
	⁃	Loaded Mat files and created CSV’s. Csvs will be saved into the same directory. 
	⁃	Read the saved Csv’s and did spectral analysis and created new dataset. 
	⁃	MLP model

01b: 01_b_Classifiers_FromCSV_XGBoost_RF_SVM_DT.ipynb
In this part, the CSV’s generated per channel are imported from part 1a. Then, it is normalized and loaded into different classifiers like SVM, Random Forest, XGBoost, MLP and DT using sklearn library.

02: Optional:
This is the first notebook where I did before part 01. This is independent from part 01. Submitted in case you like to review it.
1. Normalization on Raw data
2. PCA pre-processing.
3. Created new dataset using tensor flow.
4. Coded MLP model.

Part 3 submission: Independent
03-08: Optional:
Further to the presentation, as we discussed, I did Data pre-processing, and ICA and improved the accuracy to 90%+.

These notebooks 03-08 are very slow as the data takes too much time to load and process. There are almost 20 million records. It takes an hour or more to complete the steps 03-08 but it performed well thank god. This part was coded this week and so there is no more time. For future, I have ideas to re-code it for faster runs. 

And, 03-08 is one single program divided into section due to data overload. It is explained in video part II. 
In case you notice, Theta waveband is not extracted as by the time I found it, my system was crashing. Regardless, it is producing an accuracy of 95% almost by KNN.

The notebook takes one hour to run 150 epochs. It is not mentioned in paper; just added for your review in case.

Thank you!
