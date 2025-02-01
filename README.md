# 🏥 Pneumonia Detection Using Deep Learning

## 📌 Overview
Pneumonia is a serious lung disease caused by bacteria, fungi, or viruses, leading to lung inflammation. Traditional diagnosis relies on X-ray interpretation by medical professionals, but this project automates the detection process using **deep learning**.

## 🔬 Dataset
- **Total Images**: ~6,000 lung X-ray images
- **Labels**:
  - `0` – Normal
  - `1` – Pneumonia
- **Preprocessing**:
  - Converted images to **128×128 2D numpy arrays**
  - Applied data augmentation techniques
  - Normalized pixel values

## 🚀 Model Architecture
- **Pre-trained Model**: **InceptionV3** (Transfer Learning)
- **Layers Added**:
  - Convolutional layers for feature extraction
  - Fully connected layers for classification
  - Dropout layers to prevent overfitting
- **Optimization & Fine-tuning**:
  - Used **Adam optimizer**
  - Loss function: **Binary Crossentropy**
  - Tuned hyperparameters for better accuracy

## 🎯 Results
✅ Achieved an **impressive accuracy of 95%** on test data.

## 🛠️ Technologies Used
- **Python**
- **TensorFlow & Keras**
- **OpenCV**
- **NumPy & Pandas**
- **Matplotlib (for visualization)**

## 🔧 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pneumonia-detection.git
   cd pneumonia-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model for prediction:
   ```python
   python predict.py --image sample_xray.jpg
   ```

## 📌 Contribution
Feel free to fork this repository, improve the model, and submit a pull request!

## 📄 License
This project is open-source under the **MIT License**.
