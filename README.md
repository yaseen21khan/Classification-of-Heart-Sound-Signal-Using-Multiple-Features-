

---

# Classification of Heart Sound Signal Using Multiple Features

Data and code for heart sound signal classification using multiple features (**MFCC + DWT**).

---

## 📊 Dataset

* **Total samples:** 1000 audio files (`.wav`)
* **Classes (5):**

  * AS (Aortic Stenosis)
  * MR (Mitral Regurgitation)
  * MS (Mitral Stenosis)
  * MVP (Mitral Valve Prolapse)
  * N (Normal)
* **Samples per class:** 200

---

## ⚙️ Feature Extraction

Use the following MATLAB scripts:

* **MFCC features**
  `Matlab code heart sound signal processing mfcc features`

* **DWT features**
  `Matlab code heart sound signal processing dwt features`

* **MFCC + DWT features**
  `Matlab code heart sound signal processing mfcc plus dwt features`

---

## 🤖 Model Training

* Extracted features are saved in the `Features` folder
* Use the provided **Python script** for DNN training
* You may also use other models (e.g., CNN, custom deep learning pipelines)

---

## 🚀 How to Use

1. Download `code.rar`

2. Extract it into your MATLAB directory

3. Run the following files:

* `Matlab code heart sound signal processing dwt features.docx`
  → Extract and save DWT features

* `Matlab code heart sound signal processing MFCC features.docx`
  → Extract and save MFCC features

* `Matlab code heart sound signal processing dwt + MFCC features.docx`
  → Extract and save combined features

* `run_Example_Schmidit_script.m`
  → Perform heart sound segmentation

---

## ⚠️ Important Notes

* Do **not move** the `shmidit-Segmentation` folder (contains dependencies)
* Some MATLAB functions may be deprecated — update if necessary

---

## 📖 Reference

Further details:
[https://www.mdpi.com/2076-3417/8/12/2344](https://www.mdpi.com/2076-3417/8/12/2344)

---

## 📄 Citation

If you use this dataset or code, please cite:

```bibtex
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
```

---
