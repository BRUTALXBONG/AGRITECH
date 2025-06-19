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


```markdown
## 📁 Folder Structure

```

AgriTech/
├── app.py                     # Main Flask application file
├── crop\_prediction.py         # Crop recommendation logic using Random Forest
├── disease\_prediction.py      # CNN-based model for plant disease detection
├── water\_requirement.py       # Water requirement prediction using regression
├── requirements.txt           # Python dependencies
├── templates/                 # HTML templates for the frontend UI
│   ├── index.html
│   ├── crop\_prediction.html
│   ├── disease\_prediction.html
│   └── water\_management.html
├── static/                    # Static assets (CSS, images, uploads)
│   └── uploads/               # Folder for uploaded leaf images
├── README.md                  # Project documentation (this file)

```
```


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


## 📚 References

- [PlantVillage Dataset - Kaggle](https://www.kaggle.com/datasets/emmarex/plantdisease)  
- [Crop Recommendation Dataset - Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/4GBWFV)  
- [Water Requirement Dataset - GitHub](https://github.com/MrYasssh/Optimal-Water-Usage-Prediction)

---

## 💻 How to Run This Project Locally

You can run the AgriTech web app on your local machine using the steps below.

---

### 🔗 Step 1: Download the Project Folder

1. Go to the shared Google Drive link:  
   [Click Here to Download](https://drive.google.com/file/d/1tDiBSyhitdaL0SLYgOQDuOq13ZDRrvvE/view)
2. Click the **Download** button (top-right corner).
3. Once downloaded, **extract** the ZIP file to your local system (e.g., into a folder named `AgriTech`).

---

### 🧑‍💻 Step 2: Open Project in VS Code

1. Open **Visual Studio Code**.
2. Click on `File > Open Folder` and select the extracted `AgriTech` folder.
3. Open a new terminal inside VS Code (`Ctrl + ~` or use the `Terminal > New Terminal` menu).

---

### 📦 Step 3: Install Python Dependencies

Make sure you have **Python 3.8+** and **pip** installed.

In the terminal, run:

pip install -r requirements.txt

### 📦 Step 4: Run the Flash App

## ✅ License
This project is part of the academic curriculum at NSHM Knowledge Campus and is meant for educational and non-commercial purposes.

---

_If you found this useful, please ⭐️ the repository or suggest improvements!_

