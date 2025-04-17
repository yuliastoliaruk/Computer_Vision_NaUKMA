# Intel Image Classification
_Author: Yuliia Stoliaruk_

This project focuses on classifying natural scenes from dataset `Intel Image Classification` using PyTorch andt computer vision techniques. It walks through a complete pipeline — from building a basic CNN to fine-tuning pretrained models using transfer learning.

---

## Project Structure

- **`intel_image_classification.ipynb`**  
  Main notebook containing four progressive practices:

  ### Practice 1: Data Preparation
  - Data Augmentation  
  - Splitting into Training & Validation Sets  
  - Denormalization  

  ### Practice 2: Basic Neural Network
  - Simple CNN built from scratch using PyTorch

  ### Practice 3: Hyperparameter Optimization
  - Manual Tuning  
  - Automated Optimization  

  ### Practice 4: Transfer Learning
  - Pretrained ResNet50



- **`cnn_finnal_v0.pth`**  
  Model weights of the best custom CNN after training and optimization.

- **`model_best.pth`**  
  Best-performing model using transfer learning (ResNet50).

- **`requirements.txt`**  
  List of all Python dependencies used in the project.

---

## Dataset

The model is trained on the [Intel Image Classification dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification), consisting of images from six natural scene classes:
- `buildings`, `forest`, `glacier`, `mountain`, `sea`, `street`


## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yuliastoliaruk/Computer_Vision_NaUKMA.git

2. Install the requirements:
    ```bash
   pip install -r requirements.txt

3. Run the notebook: Open `intel_image_classification.ipynb` and follow the steps cell by cell.
