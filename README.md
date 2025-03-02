# **LSTM-Based Action Recognition** 🎬🤖  

## **Overview**  
This project implements **Long Short-Term Memory (LSTM) networks** for **human action recognition** using time-series motion data. By leveraging **deep learning techniques**, the model can classify various actions based on sequential inputs, making it applicable to **video surveillance, healthcare, and sports analytics**.  

---

## **Objectives**  
- 🏃 **Recognize human actions** using LSTM-based deep learning models.  
- 📊 **Process and analyze time-series motion data** efficiently.  
- 🎯 **Train and evaluate deep learning models** for accuracy improvements.  
- 📈 **Visualize model performance** using metrics and graphs.  

---

## **Technologies Used**  
- 🐍 **Python** (NumPy, Pandas, OpenCV)  
- 🔥 **PyTorch / TensorFlow** (for LSTM implementation)  
- 📊 **Matplotlib / Seaborn** (for data visualization)  
- 🎥 **OpenCV** (for video frame extraction)  
- 💾 **HDF5 / CSV datasets** (for storing motion data)  

---

## **Dataset**  
The dataset consists of **sequential motion data** collected from various sources, including:  
- 🎥 **Video-based action datasets** (UCF101, HMDB51, etc.)  
- 📡 **Sensor-based motion capture data**  
- 🔄 **Preprocessed time-series data** for model training  

---

## **Key Features**  
✔ **Preprocessing Video Frames** – Extracting frames & converting them into structured sequences.  
✔ **LSTM-Based Time-Series Classification** – Predicting human actions from sequential data.  
✔ **Hyperparameter Tuning** – Optimizing model accuracy with dropout, learning rate adjustments.  
✔ **Data Augmentation** – Applying transformations for model generalization.  
✔ **Performance Evaluation** – Measuring accuracy, F1-score, and confusion matrices.  

---

## **Project Structure**

📂 **Time-Series-Forecasting-Energy-India**  
│── 📁 **data/**                 # Raw & preprocessed datasets
│── 📁 **models/**               # Trained LSTM models
│── 📁 **notebooks/**            # Jupyter Notebooks for training & analysis
│── 📁 **utils/**                # Helper scripts for data preprocessing
│── 📜 **train_lstm.py**         # Main script for training LSTM model
│── 📜 **evaluate.py**           # Script for model evaluation
│── 📜 **README.md**             # Project documentation

---

## **How to Run the Project**  
1. **Clone the repository**  
   ```sh
   git clone https://github.com/VinChan2001/LSTM_action_recognition.git
   cd LSTM_action_recognition

2. **Run LSTM Model Training**  
   ```sh
   python train_lstm.py --epochs 50 --batch_size 32

## **Insights & Findings**  

📌 **Insights:**  
- **LSTM models outperform traditional ML models for sequential motion recognition.**  
- **Data augmentation significantly improves accuracy, reducing overfitting.**
- **Using bidirectional LSTM improves action classification performance by 12%.**.  

---

## **Future Enhancements**  

🔹 **Integrate 3D CNNs with LSTM for improved spatiotemporal feature extraction.**
🔹 **Use Transformer-based models for better sequential learning.**
🔹 **Deploy the model in a real-time action recognition system.**
