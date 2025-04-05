|<sub>BR</sub> [Português](readme.md)|<sub>EN</sub> [English](/readme.EN.md)|
|-|-


# 🧠 Vehicle Classifier with Transfer Learning using MobileNetV2

This project aims to build an image classification model to identify different types of vehicles using **Transfer Learning** with the **MobileNetV2** architecture.

## 📁 Dataset Used

📎 [Vehicle Type Recognition Dataset - Kaggle](https://www.kaggle.com/datasets/kaggleashwin/vehicle-type-recognition/data)

The dataset contains vehicle images classified into four categories:
- Car
- Motorcycle
- Bus
- Truck


## 🤖 Finalized Model

#### [`vehicle_classifier.keras`](./vehicle_classifier.keras):  
   - Trained model ready for use


## 🧪 Notebooks

The project is organized into two main notebooks:

#### **1.** [`training.ipynb`](./training.ipynb):  
- Development environment and model training.  
📎 [Colab](https://colab.research.google.com/drive/1QdqNC8LEQUAXhl_hCKT3Tye6qSJVMi4L?usp=sharing)

#### **2.** [`classification_analysis.ipynb`](./classification_analysis.ipynb):  
- Testing environment and model demonstration.  
📎 [Colab](https://colab.research.google.com/drive/1T08AM9mpdRqHAdX_8alojIfYAHuwLWfW?usp=sharing)

## 🛠️ Technologies and Libraries

### Main Technologies
- **Language**: Python 3.13.2
- **Framework**: TensorFlow/Keras
- **Base Model**: MobileNetV2 (Transfer Learning)
- **Environment**: Google Colab/Jupyter

### Main Libraries
- **TensorFlow/Keras**: For model building and training
- **NumPy**: Numerical data manipulation
- **Matplotlib/Seaborn**: Visualizations and graphs
- **OpenCV (cv2)**: Image preprocessing
- **KaggleHub**: Dataset download
