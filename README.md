# 🚦 Real-Time Accident Detection and Prediction 🚗💥

This repository contains the implementation of **Real-Time Accident Detection and Prediction** using **YOLOv10** with transfer learning. The project leverages object detection techniques to identify potential accident scenarios, providing real-time predictions with high accuracy. 🚀

---

## 📌 Features  
- **YOLOv10 Transfer Learning:** Trained on a custom dataset for accurate predictions.  
- **Visualization Tools:** Includes confusion matrices, performance curves, and more for detailed analysis.  
- **Real-Time Performance:** Capable of detecting accident scenarios in live video feeds.  

---

## 🎯 Goals  
The primary goal of this project is to:  
- Enhance road safety by detecting potential accidents in real time.  
- Leverage state-of-the-art deep learning techniques for object detection.  

---

## 📊 Results  

### 1️⃣ Confusion Matrix  
![Confusion Matrix](confusion_matrix.png)  

<br><br>

### 2️⃣ Normalized Confusion Matrix  
![Normalized Confusion Matrix](confusion_matrix_normalize.png)  

<br><br>

### 3️⃣ Performance Curves  

- **F1-Score Curve**  
  ![F1 Curve](f1_curve.png)  

  <br>

- **Precision Curve**  
  ![Precision Curve](p_curve.png)  

  <br>

- **Recall Curve**  
  ![Recall Curve](r_curve.png)  

  <br>

- **Precision-Recall Curve**  
  ![PR Curve](pr_curve.png)  

---

## 📷 Visualizations  

### Validation Labels  

- **Batch 0**  
  ![Val Batch 0 Labels](val_batch0_labels.jpg)  

  <br>

- **Batch 1**  
  ![Val Batch 1 Labels](val_batch1_labels.jpg)  

  <br>

- **Batch 2**  
  ![Val Batch 2 Labels](val_batch2_labels.jpg)  

  <br><br>

### Validation Predictions  

- **Batch 0**  
  ![Val Batch 0 Predictions](val_batch0_pred.jpg)  

  <br>

- **Batch 1**  
  ![Val Batch 1 Predictions](val_batch1_pred.jpg)  

  <br>

- **Batch 2**  
  ![Val Batch 2 Predictions](val_batch2_pred.jpg)  

  <br><br>

### Label Correlogram  
![Label Correlogram](label_correlogram.jpg)  

---

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/Real-Time-Accident-Detection-and-Prediction.git
   ```  
2. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run the model:  
   ```bash
   python detect.py --source <input_source>
   ```  
---

## 💡 Future Scope  
- Extend the model to detect other traffic violations.  
- Enhance the dataset for better performance.  
- Integrate with IoT devices for real-time monitoring.  

---
