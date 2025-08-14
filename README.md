# 🌲 Forest Cover Type Prediction

## 📌 Overview
This project predicts the **forest cover type** (7 different classes) for a 30m × 30m patch of land in **Roosevelt National Forest, Colorado**, using environmental and geospatial data.

**Cover Type Classes:**
1. Spruce/Fir  
2. Lodgepole Pine  
3. Ponderosa Pine  
4. Cottonwood/Willow  
5. Aspen  
6. Douglas-fir  
7. Krummholz  

---

## 📂 Dataset
- The dataset contains 54 features + 1 target column (`Cover_Type`).
- Example features:  
  - `Elevation`  
  - `Aspect`  
  - `Slope`  
  - `Horizontal_Distance_To_Hydrology`  
  - `Soil_Type` (40 binary columns)  
  - `Wilderness_Area` (4 binary columns)  

---

## ⚙️ Requirements
Install dependencies with:
```bash
pip install -r requirements.txt
