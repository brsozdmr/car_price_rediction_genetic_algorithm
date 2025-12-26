# car_price_rediction_genetic_algorithm
Used car price prediction using Linear Regression and Genetic Algorithm
[EN]
# Honda Civic Price Prediction with Genetic Algorithm

This project aims to predict **used Honda Civic car prices** using a
**Linear Regression** model combined with **Genetic Algorithm (GA)–based feature selection**.

## 🚀 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Linear Regression
- Genetic Algorithm (Feature Selection)

## 📊 Data Preprocessing
- Removed currency symbols (`TL`) and thousand separators from price values
- Extracted numerical values from engine power and engine capacity fields
- Removed rows with missing data
- Converted categorical variables using **One-Hot Encoding**
- Dropped irrelevant and unused columns

## 🧬 Genetic Algorithm
- Goal: Select the optimal subset of features that minimizes prediction error
- Population size: 30
- Number of generations: 50
- Mutation rate: 5%
- Fitness function: `-Mean Squared Error (MSE)`

## 🤖 Model
- Linear Regression (`positive=True`)
- Evaluation metric: **Root Mean Squared Error (RMSE)**

## 🧪 User-Based Price Prediction
The model accepts user input and predicts the estimated vehicle price
after applying the same preprocessing and encoding steps.

Example input features:
- Model Year
- Mileage
- Engine Power
- Engine Capacity
- Transmission Type
- Color
- Trim Level
- Fuel Type

## 📈 Output
- Model performance is evaluated using **RMSE**
- Produces a predicted price value in Turkish Lira (TL) for user-provided data

## 📁 Files
- `civic-yeni-data.csv` : Dataset used in the project
- `main.py` : Full pipeline including preprocessing, GA feature selection, model training, and prediction

## 👤 Developer
**Barış Özdemir**

[TR]
# Honda Civic Price Prediction with Genetic Algorithm

Bu projede, ikinci el **Honda Civic** araçlarının fiyatlarını tahmin etmek amacıyla
**Lineer Regresyon** modeli kurulmuş ve **Genetik Algoritma (GA)** ile özellik seçimi yapılmıştır.

## 🚀 Kullanılan Teknolojiler
- Python
- Pandas, NumPy
- Scikit-learn
- Linear Regression
- Genetic Algorithm (Feature Selection)

## 📊 Veri Ön İşleme
- Fiyat bilgisinden `TL` ve nokta (`.`) karakterleri temizlendi
- Motor gücü ve motor hacmi string ifadelerden sayısal değerlere dönüştürüldü
- Eksik veriler temizlendi
- Kategorik değişkenler **One-Hot Encoding** ile dönüştürüldü
- Gereksiz sütunlar kaldırıldı

## 🧬 Genetik Algoritma
- Amaç: En düşük **MSE** değerini veren özellik alt kümesini bulmak
- Popülasyon: 30
- Nesil sayısı: 50
- Mutasyon oranı: %5
- Fitness fonksiyonu: `-Mean Squared Error`

## 🤖 Model
- Linear Regression (`positive=True`)
- Performans metriği: **RMSE**

## 🧪 Kullanıcıdan Veri Alarak Tahmin
Kullanıcıdan alınan araç bilgileri modele uygun şekilde dönüştürülerek
tahmini fiyat hesaplanır.

Örnek girişler:
- Model Yılı
- Kilometre
- Motor Gücü
- Motor Hacmi
- Şanzıman
- Renk
- Donanım Paketi
- Yakıt Türü

## 📈 Çıktı
Model, test verisi üzerinde **RMSE** değeri ile değerlendirilmiş
ve kullanıcı girdileriyle tahmini fiyat üretecek şekilde yapılandırılmıştır.

## 📁 Dosyalar
- `civic-yeni-data.csv` : Kullanılan veri seti
- `main.py` : Tüm model, GA ve tahmin süreci

## 👤 Geliştirici
**Barış Özdemir**

