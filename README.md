# deeplearningbasedfruitassessment 🍎🍌🍊

This repository contains Jupyter Notebooks and documentation for a third-year project focusing on automated fruit quality assessment using deep learning models, specifically comparing **YOLOv8** and **ResNet-34** architectures.

## 📚 Project Overview

The goal of this project is to automate fruit quality assessment based on external appearance (defects, bruises, discolorations) using two deep learning approaches:
- **ResNet-34** for classification of fruits into categories like fresh or defective.
- **YOLOv8** for real-time object detection and defect localization.

Both models were trained and evaluated to determine the most suitable approach for industrial fruit quality control applications.

---

## 📂 Repository Contents

- `ResNet.ipynb` — Jupyter notebook for training and evaluating the ResNet-34 classifier.
- `YOLO.ipynb` — Jupyter notebook for training and evaluating the YOLOv8 object detector.
- `README.md` — Project overview and instructions.

---

## 🚀 Quick Start

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/deeplearningbasedfruitassessment.git
    cd deeplearningbasedfruitassessment
    ```

2. (Optional) Install required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the notebooks using Jupyter or VSCode and run them:
    - For fruit classification → Run `ResNet.ipynb`
    - For real-time fruit detection → Run `YOLO.ipynb`

---

## 📊 Key Findings

| Model     | Task                      | F1-Score | Object Detection | Speed          |
|-----------|----------------------------|----------|------------------|----------------|
| ResNet-34 | Fruit Quality Classification| ~98%     | No               | Fast           |
| YOLOv8    | Detection + Classification  | ~93%     | Yes              | Real-time      |

- **ResNet-34** achieves higher accuracy for classification tasks.
- **YOLOv8** enables real-time detection and localization of multiple fruits and defects.

---

## 📖 Report

For detailed methodology, experiments, hyperparameter tuning, and results, refer to the full project report [here](link-or-attach-pdf).

---

## 🤝 Acknowledgements

- Supervisor: Dr. Zhenhong Li
- University of Manchester
- Special thanks to peers and family for their support.

---

## 📬 Contact

**Ben Reinhard Tanos**  
Email: your.email@example.com
