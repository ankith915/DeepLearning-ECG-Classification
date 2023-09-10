The Whole project is done at google colab with the GPU P100 , The modeles used in the project are : LSTM,BILSTM,GRU,ALEXNET,DEEP RESIDUAL MODEL(RESNET).

The Final Simulated Result's:
![Screenshot (118)](https://github.com/ankith915/DeepLearning-ECG-Classification/assets/76102192/c757c0be-0c66-4b91-83ab-53f48a115117)

Description about dataset : 

The MIT-BIH Arrhythmia Database contains 48 half-hour excerpts of two-channel ambulatory ECG recordings, obtained from 47 subjects studied by the BIH Arrhythmia Laboratory between 1975 and 1979. Twenty-three recordings were chosen at random from a set of 4000 24-hour ambulatory ECG recordings collected from a mixed population of inpatients (about 60%) and outpatients (about 40%) at Boston's Beth Israel Hospital; the remaining 25 recordings were selected from the same set to include less common but clinically significant arrhythmias that would not be well-represented in a small random sample.

The recordings were digitized at 360 samples per second per channel with 11-bit resolution over a 10 mV range. Two or more cardiologists independently annotated each record; disagreements were resolved to obtain the computer-readable reference annotations for each beat (approximately 110,000 annotations in all) included with the database.
 
This directory contains the entire MIT-BIH Arrhythmia Database. About half (25 of 48 complete records, and reference annotation files for all 48 records) of this database has been freely available here since PhysioNet's inception in September 1999. The 23 remaining signal files, which had been available only on the MIT-BIH Arrhythmia Database CD-ROM, were posted here in February 2005.

Contents
•	Number of Samples: 109446
•	Number of Categories: 5
•	Sampling Frequency: 125Hz
•	Data Source: Physionet's MIT-BIH Arrhythmia Dataset
•	Classes: ['N': 0, 'S': 1, 'V': 2, 'F': 3, 'Q': 4]
