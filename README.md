# 🚦 Real-Time Accident Detection and Prediction 🚗💥

This repository contains the implementation of **Real-Time Accident Detection and Prediction** using **YOLOv10** with transfer learning. The project leverages object detection techniques to identify potential accident scenarios, providing real-time predictions with high accuracy. 🚀

---

### 🚨 Notice to Viewer  

Please carefully review all outputs and ensure to watch the **entire output video** for a comprehensive understanding of the project's results.  

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

![results](https://github.com/user-attachments/assets/4763f5ec-2836-499c-ab92-f7f554767498)
<br><br>

### 1️⃣ Confusion Matrix  
 
![confusion_matrix](https://github.com/user-attachments/assets/79042684-c118-449d-a5cb-879d9fcc7672)
<br><br>

### 2️⃣ Normalized Confusion Matrix  
![confusion_matrix_normalized](https://github.com/user-attachments/assets/eec700fd-96f4-443c-b022-86fa967f9d13)  

<br><br>

### 3️⃣ Performance Curves  

- **F1-Score Curve**  
![F1_curve](https://github.com/user-attachments/assets/b8f63774-7d9f-4969-b745-df41291786cc) 
  <br>

- **Precision Curve**  
  ![P_curve](https://github.com/user-attachments/assets/6a2f5556-88a8-46df-8e21-57555045ed25) 
  <br>

- **Recall Curve**  
  ![R_curve](https://github.com/user-attachments/assets/92e027f1-2867-4329-8859-f8b3087029e9)  
  <br>

- **Precision-Recall Curve**  
  ![PR_curve](https://github.com/user-attachments/assets/e7c2b335-a262-45d3-ae9e-ca4a25c07d90)    

---

## 📷 Visualizations  

### Validation Labels  

- **Batch 0**  
  ![val_batch0_labels](https://github.com/user-attachments/assets/69dfa5f2-a968-4515-bdf6-48c5c57ec19d)  

  <br>

- **Batch 1**  
  ![val_batch1_labels](https://github.com/user-attachments/assets/09c56e8c-9fe2-4485-b24a-0e48198756d6)  

  <br>

- **Batch 2**  
  ![val_batch2_labels](https://github.com/user-attachments/assets/9b0dc91a-9e20-41bf-a6a7-aa0bf8af0fc1)  

  <br><br>

### Validation Predictions  

- **Batch 0**  
  ![val_batch0_pred](https://github.com/user-attachments/assets/149ae29f-c9ce-41ee-8898-730881fc7651)  

  <br>

- **Batch 1**  
  ![val_batch1_pred](https://github.com/user-attachments/assets/002597d6-65a2-4be5-8b95-9045bc7b9304)  

  <br>

- **Batch 2**  
  ![val_batch2_pred](https://github.com/user-attachments/assets/ff76ce82-4aff-4379-bca9-931d4260b2a7))  

  <br><br>
---
## Training

### Training batch

- **Batch 0**  
  ![train_batch0](https://github.com/user-attachments/assets/da08a1e5-0091-48bb-8366-120605539786) 

  <br>

- **Batch 1**  
  ![train_batch1](https://github.com/user-attachments/assets/0b152186-3ea2-4833-be79-773bdbc27a3e) 

  <br>

- **Batch 2**  
  ![train_batch2](https://github.com/user-attachments/assets/a89b3555-5f86-4695-988e-1c5506818b49)

  <br> 

- **Batch 6210**  
 ![train_batch6210](https://github.com/user-attachments/assets/72cae5b2-4dae-4f6c-a7b1-955edd31b3e1)   

  <br>

- **Batch 6211**  
  ![train_batch6211](https://github.com/user-attachments/assets/826baf02-4dca-4008-86ec-432b93a4f268)  

  <br>

- **Batch 6212**  
  ![train_batch6212](https://github.com/user-attachments/assets/5f2adcf6-6c70-489c-98b3-a4a5c2ee8bb2)  

  <br><br>
---

### Labels
![labels](https://github.com/user-attachments/assets/91135f60-5f4b-459b-84ab-19275e7c12eb)
 
---

### Label Correlogram  
![labels_correlogram](https://github.com/user-attachments/assets/66abbc0f-51b9-415a-854d-4d9e4122f1f6)  

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
