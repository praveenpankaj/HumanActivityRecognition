# Human Activity Recognition  

**Authors:**  
Sreejith Sasidharan, Pranav Prabha, Devasena Pasupuleti, Anand M. Das, Chaitanya Kapoor, Gayathri Manikutty, Praveen Pankajakshan, and Bhavani Rao  

This repository hosts the notebooks used to train the models featured in the conference paper:  

**"Handwashing Action Detection System for an Autonomous Social Robot"**  
*Presented at IEEE TENCON 2022*  

---

## 📂 Data  

### 🔹 Original Handwashing Experiment Data  
– Available at: [Realtime Action Recognition Dataset](https://github.com/Realtime-Action-Recognition/Realtime-Action-Recognition)  

### 🔹 Modified Dataset (6-Step Handwashing with Segmentation Maps)  
– Pranav et al., October 13, 2022  
  *"Six steps of hand washing dataset with segmentation maps"*, IEEE Dataport – DOI: [10.21227/ghr9-y726](https://dx.doi.org/10.21227/ghr9-y726)  

---

## 🧠 Model Architecture  

Our model employs **Channel and Spatial Attention mechanisms** for enhanced action recognition.  
![Model Architecture](https://github.com/praveenpankaj/HumanActivityRecognition/blob/main/ModelArchitecture.png))

---

## ⚙️ Installation  

### Option 1: Manual Installation  
```bash
# 1. Clone the repository
git clone https://github.com/praveenpankaj/HumanActivityRecognition.git
cd HumanActivityRecognition

# 2. Create and activate a virtual environment (optional but recommended)
python3 -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

# 3. Install required packages
pip install numpy pandas scikit-learn matplotlib jupyter

# Install deep learning framework
pip install tensorflow

# Install MediaPipe for hand detection (Optional)
pip install mediapipe

# Install visualization library for attention maps
pip install tf-keras-vis
```
---
## 🚀 Usage  

1. Launch Jupyter Notebook:  
   ```bash
   jupyter notebook
2. Open one of the notebooks, such as:
Preprocess_Rescaled VGG16-SCAttention[Jul29_2022][TENCON].ipynb
ResNet50-plain[Jul26_2022][TENCON].ipynb
3. Preprocessing: Follow the notebook cells to load and prepare your dataset (original or 6-step version).
4. Training: Run the training cells to define, compile, and train the models (e.g., with TensorFlow).
5. Evaluation & Inference: Use the evaluation cells to compute metrics (accuracy, confusion matrix, etc.).
6. You can also use tf-keras-vis to visualize feature importance and attention maps.
---
## 📊 Results & Performance
(TBD)
---
## 📖 Citation

If you use this repository in your work, please cite:
Sreejith Sasidharan, Pranav Prabha, Devasena Pasupuleti, Anand M. Das, Chaitanya Kapoor, Gayathri Manikutty, Praveen Pankajakshan, and Bhavani Rao,
"Handwashing Action Detection System for an Autonomous Social Robot," Proc. IEEE TENCON 2022.
arXiv:2210.15804

---
## 📜 License

This project is released under the MIT License.

---
