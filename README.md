Classification of Heart Sound Signal Using Multiple Features

Data and code for heart sound signal classification using multiple features (MFCC + DWT).

Dataset

1000 audio files (.wav format)

5 classes (200 samples each):

AS (Aortic Stenosis)

MR (Mitral Regurgitation)

MS (Mitral Stenosis)

MVP (Mitral Valve Prolapse)

N (Normal)

Feature Extraction

Use the provided MATLAB scripts:

MFCC features
Matlab code heart sound signal processing mfcc features

DWT features
Matlab code heart sound signal processing dwt features

MFCC + DWT features
Matlab code heart sound signal processing mfcc plus dwt features

Model Training

Extracted features are stored in the "Features" folder

Use the provided Python script for DNN training

You can also use CNN or other deep learning models

How to Use

Download code.rar

Extract it into your MATLAB directory

Run the following MATLAB files:

Matlab code heart sound signal processing dwt features.docx
For extracting and saving DWT features

Matlab code heart sound signal processing MFCC features.docx
For extracting and saving MFCC features

Matlab code heart sound signal processing dwt + MFCC features.docx
For extracting and saving combined features

run_Example_Schmidit_script.m
For heart sound signal segmentation

Important Notes

Do not move the "shmidit-Segmentation" folder (it contains dependencies)

Some MATLAB functions may be deprecated; update them if needed

Reference

Further details are available in the published paper:
https://www.mdpi.com/2076-3417/8/12/2344

Citation

If you use this dataset or code, please cite:

@article{yaseen2018classification,
title={Classification of heart sound signal using multiple features},
author={Yaseen and Son, Gui-Young and Kwon, Soonil},
journal={Applied Sciences},
volume={8},
number={12},
pages={2344},
year={2018},
publisher={MDPI}
}

@inproceedings{jamil2025facegest,
title={FaceGest: A Comprehensive Facial Gesture Dataset for Human-Computer Interaction},
author={Jamil, Sonain and others},
booktitle={Proceedings of the Computer Vision and Pattern Recognition Conference},
pages={337--347},
year={2025}
}
