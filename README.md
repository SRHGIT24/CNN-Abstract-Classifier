# CNN‐Abstract‐Classifier

**A TensorFlow/Keras CNN that labels each line of a scientific abstract into one of five sections (BACKGROUND, METHODS, RESULTS, etc.), plus a Leave‐One‐Class‐Out (LOCO) analysis.**

---

## 📂 Files

- **01_Full‐Model_Training.ipynb**  
  Trains a TextVectorization→Embedding→Conv1D CNN to classify abstract lines.  
  - Outputs: training/validation accuracy & loss plots, classification report, confusion matrix, ROC curves.

- **02_LOCO_Analysis.ipynb**  
  Runs a LOCO experiment: for each section label, removes it from training, retrains on the remaining four, and plots the drop in Macro‐F₁ and Macro‐AUC.

---

## 🚀 Quick Start

1. Clone this repo:
   ```bash
   git clone https://github.com/SRHGIT24/CNN-Abstract-Classifier.git
   cd CNN-Abstract-Classifier
