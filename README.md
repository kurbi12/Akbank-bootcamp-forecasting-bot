# Akbank-bootcamp-forecasting-bot
This project is a simple forecasting bot built using the Tesla stock price dataset (2010–2020) from Kaggle.  It includes exploratory data analysis (EDA), a Linear Regression model, and evaluation metrics (R², RMSE).  Future improvements may include trying Random Forest or LSTM models and deploying the project with a Streamlit UI.
# 📊 Tesla Stock Forecasting Bot

## Veri Seti
- Kaggle Dataset: [Tesla Stock Price History](https://www.kaggle.com/datasets/adilshamim8/tesla-stock-price-history)  
- İçerik: Tesla’nın 2010–2020 arasındaki günlük açılış, kapanış, en yüksek, en düşük ve hacim verileri.

## Kullanılan Algoritmalar
- Linear Regression (baseline model)  
- (Opsiyonel) Random Forest / LSTM (gelecek çalışmalar için planlandı)

## Metrikler
- R² Score: ~0.90  
- RMSE: (senin notebook’taki çıktı değerini buraya ekle)  

## Teknik Açıklama
Projenin teknik adımları Kaggle Notebook içerisinde markdown hücreleriyle detaylı olarak açıklanmıştır.  
- Veri keşfi (EDA)  
- Görselleştirmeler (fiyat grafiği, tahmin grafiği)  
- Model eğitimi ve test edilmesi  
- Metriklerin hesaplanması ve yorumlanması  

## Ekler
- GPU ortamında çalıştırılabilir.  
- Gelecekte Streamlit UI ile deploy edilmesi planlanıyor.  

## Sonuç ve Gelecek Çalışmalar
- Model, Tesla fiyatlarını bir önceki günün fiyatına bakarak başarılı şekilde tahmin edebildi.  
- Daha gelişmiş modeller (Random Forest, LSTM) ile performans artırılabilir.  
- Gerçek zamanlı veri entegrasyonu (örneğin Yahoo Finance API) eklenerek canlı tahmin botu yapılabilir.  

## Linkler
- [Kaggle Notebook](https://www.kaggle.com/code/berkayeken/notebook3caea50338)  
- [Kaggle Dataset](https://www.kaggle.com/datasets/adilshamim8/tesla-stock-price-history)  
- [GitHub Repo] (https://github.com/kurbi12/Akbank-bootcamp-forecasting-bot)
