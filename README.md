# ECE5831 Final Project (2025)

## Project Title
Traffic Sign Classification with Context-Aware Scene Description using Deep Learning

## Overview
This project addresses the robustness limitations of traffic sign classification systems under challenging conditions such as noise, occlusion, and low-confidence predictions. To enhance classification reliability, we propose a pipeline that integrates image reconstruction with a multi-modal learning framework. The approach combines reconstructed visual information and textual cues to improve recognition performance when conventional classifiers exhibit low confidence.

The project is implemented using Python and Jupyter Notebook, and all experiments are reproducible using the provided notebook.

---

## Repository Structure
ece5831-2025-final-project/
├── outputs/ # Generated figures and results
├── final-project.ipynb # Main notebook (executed, shows how to run the project)
├── train_keras_signs.py # Model training script
├── inspect_mtsd.py # Dataset inspection and visualization
├── infer_one_test_image_blip.py # Single-image inference demo
├── save_crops_csv.py # Cropped image metadata generation and save
├── compare_select_models.py # Model comparison and selection
└── README.md # Project documentation


---

## How to Run the Project
1. Download the dataset using the link provided below.
2. Place the dataset in the `data/` directory.
3. Open and run all in `inspect_mtsd.py, save_crops_csv.py, train_keras_signs.py, compare_select_models.py, infer_one_test_image_blip.py` sequentially.
4. Generated results and figures will be saved in the `outputs/` directory.


---

## Dataset
- **Dataset link:**  
  https://drive.google.com/drive/folders/1QNR2BTyNfMU5F1CXex1QbFkhfv16Lfuq

---

## Demo and Presentation Materials

- **YouTube Demo Video:**  
  https://youtu.be/N2LZOy5PZlY

- **Pre-recorded Presentation Video:**  
  https://drive.google.com/drive/folders/1NtQQG2bSREA-I_ZpN4BpwUIvW6s4Iqes

- **Presentation Slides:**  
  https://drive.google.com/drive/folders/1NtQQG2bSREA-I_ZpN4BpwUIvW6s4Iqes

- **Final Report:**  
  https://drive.google.com/drive/folders/1Fz9DF5bKq44gguRw9g1a2O17HlALvwMz


---

## Course Information
- **Course:** ECE 5831 – Pattern Recognition and Neural Networks  
- **Term:** 2025  
- **Final Project Submission**
