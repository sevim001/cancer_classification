# 🧠 Cross-Cancer Classification with Transfer Learning

This project investigates the generalization ability of deep learning models trained on histopathological images from one cancer type and tested on others. We use MobileNetV3 with transfer learning and interpret model decisions using Grad-CAM.

---

## 📌 Project Summary

- **Goal**: Evaluate how well a brain cancer model can classify other cancers such as kidney, oral, and more.
- **Techniques**: Transfer learning, MobileNetV3, Grad-CAM, ROC-AUC.
- **Dataset**: Multi-Cancer Histopathology Dataset ([Kaggle Link](https://www.kaggle.com/datasets/obulisainaren/multi-cancer)).

---

##  Platform Notes

- This project was developed and executed on **Kaggle Notebooks** due to the large size of the dataset, which would not run efficiently on Google Colab.
- The **MobileNetV3 weights** were not directly downloadable via code in the Kaggle environment, so I manually uploaded the pre-trained model files into the Kaggle input directory.
- You can **fork the notebook** on Kaggle and run the project with no extra setup required.

---

##  Requirements

- Python ≥ 3.8  
- TensorFlow ≥ 2.12  
- Keras ≥ 2.12  
- NumPy  
- Matplotlib  
- Scikit-learn  
- PIL  
- OS, glob

Install required libraries via:

```bash
pip install tensorflow keras numpy matplotlib scikit-learn

##  How to Run

- Open the Kaggle notebook: [Kaggle Notebook Link](https://www.kaggle.com/code/sevimshafizadegan/deep-learning)
- Make sure the dataset and MobileNetV3 model weights are attached under the **"Add Data"** section.
- Run all cells in order — the notebook includes training, evaluation, Grad-CAM visualization, and cross-cancer transfer testing.
- Visualizations such as model performance plots and Grad-CAM heatmaps are automatically generated as you run the notebook.

📎 Links
https://www.kaggle.com/code/sevimshafizadegan/deep-learning

https://www.kaggle.com/datasets/obulisainaren/multi-cancer
👩‍💻 Author
Sevim Shafizadegan
Master of Data Science
Toronto Metropolitan University