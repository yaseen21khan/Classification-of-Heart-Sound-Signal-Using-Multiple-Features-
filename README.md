# Classification-of-Heart-Sound-Signal-Using-Multiple-Features-
Data plus code fo Classification of Heart Sound Signal Using Multiple Features 

For MFCCs features extraction use;

Matlab code heart sound signal processing mfcc features
===========================================================

For DWT features extraction use;

Matlab code heart sound signal processing dwt features
===========================================================

For MFCCs plus DWT features extraction use;
Matlab code heart sound signal processing mfcc plus dwt features
===========================================================

For DNN training use features provided in the repository folder named Features;
use the python code for training
===========================================================

database contains 1000 audio files with .wav format, 
there are 5 classes each class has 200 audio fies
===========================================================

AS, MR, MS, MVP and N are five classes 

How to use the code?
First of all  download code.rar
Extract the folder  in your matlab directory.

there are 4 matlab files you have to run

1) Matlab code heart sound signal processing dwt features.docx  "For extracting and saving dwt features"
2) Matlab code heart sound signal processing MFCC features.docx  "For extracting and saving mfcc features"
3) Matlab code heart sound signal processing dwt + MFCC features.docx   "For extracting and saving dwt+mfcc features"
4) This file is for for segmentation of  heart sound signal that is "run_Example_Schmidit_script.m"

Also do not move the folder "shmidit-Segmentation" as it  contains dependencies 

Some functions may be deprecated in the signal processing toolbox. You  have to  look for it.
Once you obtain your features you can use the python script to train your data or you can write your own script  using CNN or some other deep learning based techniques. 

Further discussion and explanation can be found published in;
https://www.mdpi.com/2076-3417/8/12/2344
