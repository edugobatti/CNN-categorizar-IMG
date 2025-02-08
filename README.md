# 🖼️ Projeto de Classificação de Imagens com Redes Neurais Convolucionais (CNN)

Este projeto consiste na implementação de um sistema de **classificação de imagens** utilizando uma arquitetura de **Rede Neural Convolucional (CNN)** em **Python**, com a biblioteca **TensorFlow**.

## 🚀 Tecnologias Utilizadas

- [Python 3.x](https://www.python.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [OpenCV](https://opencv.org/) *(opcional, para processamento de imagens)*

## 📌 Pré-requisitos

Antes de começar, você precisa ter:

- **Python 3.7 ou superior** instalado na sua máquina.
- Um ambiente virtual configurado (opcional, mas recomendado).
- Um dataset de imagens para treinamento e teste.

## 🔧 Instalação

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Crie um ambiente virtual (opcional, mas recomendado):
    ```sh
    python -m venv venv
    source venv/bin/activate  # No Windows, use: venv\Scripts\activate
    ```
3. Instale as dependências necessárias:
    ```sh
    pip install -r requirements.txt
    ```


## ▶️ Como Executar

Basta abrir o arquivo CNN.ipynb e executar o código. O notebook segue uma estrutura simples, onde um arquivo JSON define as pastas a serem criadas e as imagens a serem baixadas.

O formato esperado do dicionário é o seguinte:
 ```sh
mage_urls ={
    "pasta_com_categoria":["URL 1","URL 2","URL 3"]
}
 ```
 Cada chave do dicionário representa uma categoria de imagens, e a lista associada contém as URLs das imagens que serão baixadas automaticamente para a respectiva pasta.