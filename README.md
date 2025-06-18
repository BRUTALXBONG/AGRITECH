# 🌾 AgriTech: Revolutionizing Agriculture with ML & DL

## 📌 Project Overview

AgriTech is an AI-powered web platform that provides three critical services for farmers:

- ✅ **Crop Recommendation**  
- ✅ **Plant Disease Detection**  
- ✅ **Water Requirement Prediction**

It leverages real-world agricultural datasets, deep learning with CNNs, and ensemble methods like Random Forest to support farmers in making informed, sustainable decisions.

---

## 🚀 Features

### 🌱 Crop Recommendation System
- **Model**: Random Forest Classifier
- **Input Features**: Nitrogen, Phosphorus, Potassium, pH, temperature, humidity, rainfall
- **Output**: Best crop for given conditions
- **Accuracy**: ~95.2%

### 🌿 Plant Disease Detection
- **Model**: Convolutional Neural Network (CNN)
- **Dataset**: 162,916 labeled leaf images (38 classes)
- **Architecture**: 3 Conv layers → Dense → Softmax
- **Accuracy**: ~95.3%
- **Functionality**: Users can upload leaf images for disease prediction

### 💧 Water Requirement Prediction
- **Model**: Random Forest Regressor
- **Input**: Soil type, crop stage, temperature, evapotranspiration, rainfall, etc.
- **Output**: Water needed (liters/day) for any land area
- **Performance**:  
  - R² Score: 0.94  
  - MAE: ~0.83

---

## 🛠 Technology Stack

| Layer      | Tools / Libraries                |
|------------|----------------------------------|
| Frontend   | HTML, CSS                        |
| Backend    | Flask (Python)                   |
| ML/DL      | Scikit-learn, TensorFlow         |
| Deployment | Cloud-ready (local Flask setup)  |

---

## 📁 Folder Structure
├── crop_prediction.py # Crop recommendation model
├── disease_prediction.py # CNN-based disease detection
├── water_requirement.py # Water requirement regressor
├── app.py # Flask backend
├── templates/ # HTML files
├── static/ # CSS and uploads
├── README.md # Project documentation

---

## 🧪 Model Evaluation

| Task                    | Accuracy / Score     |
|-------------------------|----------------------|
| Crop Recommendation     | 95.2%                |
| Disease Detection (CNN) | 95.3%                |
| Water Prediction (RF)   | R² = 0.94, MAE = 0.83|

---

## 📈 Future Enhancements
- 📡 Integrate real-time weather APIs
- 📱 Launch as a mobile app for accessibility
- 🌐 IoT integration for live soil & weather data
- 🔄 Expand disease dataset to include more crops

---

## 🧑‍💻 Contributors

- Soumyadeep Dutta  
- Koustav Santra  

---

## 📸 Demo Preview

_Add screenshots here:_
- Home page UI
- Crop recommendation form
- Leaf upload and prediction output
- Water requirement input and results

---

## 📚 References

- [PlantVillage Dataset - Kaggle](https://www.kaggle.com/datasets/emmarex/plantdisease)  
- [Crop Recommendation Dataset - Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/4GBWFV)  
- [Water Requirement Dataset - GitHub](https://github.com/MrYasssh/Optimal-Water-Usage-Prediction)

---

## ✅ License
This project is part of the academic curriculum at NSHM Knowledge Campus and is meant for educational and non-commercial purposes.

---

_If you found this useful, please ⭐️ the repository or suggest improvements!_

