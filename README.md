<p align="center">
  <img src="[images/Image 23 Kas 2025 06_04_11.png](https://raw.githubusercontent.com/gokce-yuksel/olist-ecommerce-analysis/3da26bd8f7b125a4647cdb618c6f4d286eea6ff2/images/Image%2023%20Kas%202025%2006_04_11.png)" alt="Olist Brazilian E-Commerce Analysis" width="850">
</p>



# olist-ecommerce-analysis
Brazilian E-Commerce Data Analysis with Python

![Python](https://img.shields.io/badge/Python-3.10-yellow)
![EDA](https://img.shields.io/badge/EDA-Exploratory%20Analysis-blue)
![Statistics](https://img.shields.io/badge/Statistics-T--Test%20%7C%20ANOVA%20%7C%20ChiSquare-green)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Charts-orange)


# 📦 Olist Brazilian E-Commerce Data Analysis  
*Brazilian Online Retail – Data Exploration, Statistics, Visualization & A/B Testing*

[![Dataset Badge](https://img.shields.io/badge/Dataset-Kaggle-blue)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
[![Python](https://img.shields.io/badge/Python-3.10-yellow)]()
[![Colab](https://img.shields.io/badge/Colab-Notebook-orange)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()

---

## 📌 Proje Hakkında
Bu proje, **Olist** tarafından sağlanan kapsamlı Brezilya e-ticaret veri setini analiz ederek iş süreçleri, müşteri davranışları ve sipariş operasyonları hakkında anlamlı içgörüler üretmeyi amaçlar.

Çalışma boyunca:
- Veri temizleme  
- Keşifsel veri analizi (EDA)  
- Görselleştirme  
- Hipotez testleri (T-test, ANOVA, Ki-Kare)  
- İş çıkarımlarının oluşturulması  
adımları uygulanmıştır.

📄 Notebook dosyası: **`olist_analysis.ipynb`**

---

## 📂 Proje Yapısı

```plaintext
/olist-ecommerce-analysis
│
├── olist_analysis.ipynb        # Ana analiz notebook'u
├── README.md                    # Bu dosya
└── /images                      # Kaydedilen grafikler



🧠 Kullanılan Veri Seti

Kaynak:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

İçerik:

7 tablo

100.000+ sipariş

70.000+ müşteri

3 yıllık işlemler

Ödeme, ürün, teslimat, yorum ve müşteri bilgileri

🎯 Projenin Hedefleri

Bu çalışmanın analitik amaçları:

🛒 Müşteri davranışlarını anlamak

🚚 Teslimat sürelerini ve sipariş başarısını analiz etmek

⭐ Müşteri memnuniyeti ile operasyon arasındaki ilişkiyi incelemek

💳 Ödeme yöntemlerinin teslimat başarısına etkisini ölçmek

📈 Kategori bazlı fiyat ve ürün farklılıklarını test etmek

🔍 A/B testleri ve istatistiksel testlerle hipotez doğrulamak

📊 Temel Bulgular
⭐ 1. Müşteri Memnuniyeti

Ortalama puan 4.08

%77’si 4 veya 5 puan → yüksek memnuniyet

1 puan veren müşteriler genelde gecikme yaşamış

🚚 2. Teslimat Süresi İçgörüleri

Hızlı teslimat alan müşteriler anlamlı şekilde daha yüksek memnuniyet bildiriyor (T-Test, p < 0.001)

Teslimat gecikmeleri yorumlarda belirgin

🏷️ 3. Ürün Kategorileri (ANOVA)

Kategoriler arasında toplam sipariş fiyatı anlamlı farklılık gösteriyor (p < 0.001)

En yoğun ürün kategorileri: cama_mesa_banho, esporte_lazer, moveis_decoracao

💳 4. Ödeme Yöntemi – Teslimat İlişkisi (Ki-Kare)

Ödeme yöntemi ile teslim edilme durumu arasında anlamlı ilişki var

Kredi kartı siparişlerinde teslim edilmeme oranı çok düşük

Boleto/voucher siparişleri daha riskli


📈 Görsel Örnekler

README içinde grafik göstermek için:

![Delivery Boxplot](images/delivery_boxplot.png)
![Review Distribution](images/review_scores.png)


🛠️ Kullanılan Teknolojiler

Python

Pandas, NumPy

Plotly, Matplotlib

SciPy (T-Test, ANOVA, Chi-Square)

Google Colab


💾 Colab’da Grafik Kaydetme Kodu
fig.write_image("images/delivery_boxplot.png")



📘 Sonuç

Bu proje, Olist veri seti üzerinden:

Operasyonel performansı

Müşteri memnuniyetini

Ürün & fiyat stratejilerini

Ödeme yöntemlerinin risk analizini

istatistiksel olarak değerlendirmeyi ve iş çıkarımları üretmeyi başarmıştır.

👤 Katkıda Bulunan

Gökçe Yüksel
Data Analyst | Python & SQL | Machine Learning
