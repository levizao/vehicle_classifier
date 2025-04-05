|<sub>BR</sub> [Português](readme.md)|<sub>EN</sub> [English](/readme.EN.md)|
|-|-


# 🧠 Classificador de Veículos com Transfer Learning usando MobileNetV2

Este projeto tem como objetivo construir um modelo de classificação de imagens para identificar diferentes tipos de veículos utilizando **Transfer Learning** com a arquitetura **MobileNetV2**.

## 📁 Dataset Utilizado

📎 [Vehicle Type Recognition Dataset - Kaggle](https://www.kaggle.com/datasets/kaggleashwin/vehicle-type-recognition/data)

O dataset contém imagens de veículos classificadas em quatro categorias:
- Carro
- Moto
- Ônibus
- Caminhão


## 🤖 Modelo Finalizado

#### [`vehicle_classifier.keras`](./vehicle_classifier.keras):  
   - Modelo treinado pronto para ser utilizado


## 🧪 Notebooks

O projeto é organizado em dois notebooks principais:

#### **1.** [`treinamento.ipynb`](./treinamento.ipynb):  
- Ambiente de desenvolvimento e treinamento do modelo.  
📎 [Colab](https://colab.research.google.com/drive/1QdqNC8LEQUAXhl_hCKT3Tye6qSJVMi4L?usp=sharing)

#### **2.** [`analise_de_classificacao.ipynb`](./analise_de_classificacao.ipynb):  
- Ambiente de testes e demonstração do modelo.  
📎 [Colab](https://colab.research.google.com/drive/1T08AM9mpdRqHAdX_8alojIfYAHuwLWfW?usp=sharing)

## 🛠️ Tecnologias e Bibliotecas

### Tecnologias Principais
- **Linguagem**: Python 3.13.2
- **Framework**: TensorFlow/Keras
- **Modelo Base**: MobileNetV2 (Transfer Learning)
- **Ambiente**: Google Colab/Jupyter

### Bibliotecas Principais
- **TensorFlow/Keras**: Para construção e treinamento do modelo
- **NumPy**: Manipulação numérica de dados
- **Matplotlib/Seaborn**: Visualizações e gráficos
- **OpenCV (cv2)**: Pré-processamento de imagens
- **KaggleHub**: Download do dataset
