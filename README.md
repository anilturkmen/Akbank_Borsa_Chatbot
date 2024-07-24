# Stock Price Prediction Using LSTM

This project involves developing a stock price prediction model using Long Short-Term Memory (LSTM) neural networks. The application is designed to help users predict stock prices based on historical data, which includes features like Date, Open, High, Low, Close, Volume, Dividends, Stock Splits, Ticker, and Adjusted Close prices.

## Project Overview

The project includes the following components:
- **Data Preparation**: Preprocessing and preparing the stock market data.
- **Model Development**: Building and training the LSTM model.
- **Application Deployment**: Creating an interactive application to use the trained model for predictions.

## Files in the Repository

- `app.py`: The main application script to run the web interface.
- `model.ipynb`: The Jupyter Notebook containing the model development and training process.

## Installation

To get started, clone this repository and install the necessary dependencies.

```bash
git clone <repository_url>
cd <repository_directory>
pip install -r requirements.txt
Kullanılan Teknolojiler

Python
TensorFlow/Keras
NumPy
Pandas
Matplotlib
Kurulum

Depoyu Kopyalayın:

bash
Kodu kopyala
git clone https://github.com/kullanici_adi/proje_adi.git
cd proje_adi
Gerekli Paketleri Yükleyin:

Proje gereksinimlerini yüklemek için aşağıdaki komutu çalıştırın:

bash
Kodu kopyala
pip install -r requirements.txt
Kullanım

Veri Hazırlama:

Verinizi data/ klasörüne yerleştirin. Veri seti Date, Open, High, Low, Close, Volume, Dividends, Stock Splits, Ticker, ve Adjusted Close sütunlarını içermelidir.

Modeli Eğitme:

Aşağıdaki komutu kullanarak modeli eğitin:

bash
Kodu kopyala
python app.py --train
Tahmin Yapma:

Eğitilmiş modeli kullanarak tahmin yapmak için aşağıdaki komutu kullanın:

bash
Kodu kopyala
python app.py --predict
Proje Yapısı

app.py: Uygulama dosyası, model eğitimi ve tahmin işlemlerini içerir.
data/: Veri setlerinin bulunduğu klasör.
models/: Eğitilmiş modellerin kaydedildiği klasör.
notebooks/: Jupyter Notebook dosyaları ve analizler.
