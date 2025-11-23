<p align="center">
  <img src="https://raw.githubusercontent.com/gokce-yuksel/olist-ecommerce-analysis/main/images/banner.png" width="850">
</p>

# 📦 Olist Brazilian E-Commerce Data Analysis
**Brazilian Online Retail – Data Cleaning, Exploratory Data Analysis, Customer Behavior Insights & A/B Testing**

![Python](https://img.shields.io/badge/Python-3.10-yellow)
![EDA](https://img.shields.io/badge/EDA-Exploratory%20Data%20Analysis-blue)
![Statistics](https://img.shields.io/badge/Statistics-T--Test%20%7C%20ANOVA%20%7C%20ChiSquare-green)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Charts-orange)
![Colab](https://img.shields.io/badge/Colab-Notebook-orange)

---

## 🔍 Proje Hakkında
Brezilya'nın en büyük e-ticaret platformlarından **Olist** tarafından sağlanan veri seti kullanılarak:

- Sipariş akışı  
- Ürün & kategori yapısı  
- Müşteri lokasyonları  
- Teslimat süreleri  
- Ödeme davranışları  
- Müşteri memnuniyeti skorları  

analiz edilmiştir.

Bu çalışma, operasyonel süreçlerin anlaşılmasını ve müşteri davranışlarına yönelik **veri destekli içgörüler** üretilmesini amaçlar.

---

## 📊 Analiz Kapsamı

### **1️⃣ Veri Ön İşleme**
- Eksik verilerin incelenmesi ve temizlenmesi  
- Tarih kolonlarının `datetime` formatına dönüştürülmesi  
- Outlier tespiti  
- Yeni hesaplanmış metriklerin oluşturulması (örn. `delivery_time`)

---

## **📈 Görselleştirme Sonuçları**

### **🟦 Sipariş Toplam Fiyat Dağılımı**
![Order Total Price Histogram](images/order_total_price_hist.png)

---

### **🟪 En Çok Ürüne Sahip İlk 15 Kategori**
![Top 15 Product Categories](images/top15_product_categories.png)

---

### **🟧 Ödeme Yöntemi Dağılımı**
![Payment Type Distribution](images/payment_type_distribution.png)

---

### **🟩 Teslimat Süresi Dağılımı — Histogram**
![Delivery Time Histogram](images/delivery_time_hist.png)

---

### **🟩 Teslimat Süresi — Boxplot**
![Delivery Time Boxplot](images/delivery_time_boxplot.png)

---

### **🟦 Müşteri Memnuniyet Skor Dağılımı**
![Review Score Distribution](images/review_score_distribution.png)

---

### **🟨 Teslimat Hızı ve Müşteri Memnuniyeti**
*(Hızlı teslim vs yavaş teslim — T-test sonucu görselleştirilmiştir)*  
![Delivery Time vs Review Score](images/delivery_time_vs_review_score_boxplot.png)

---

### **🟥 Kategori Bazında Sipariş Değerleri (ANOVA)**
![Category Total Price Boxplot](images/category_total_price_boxplot.png)

---

### **🟫 Ödeme Yöntemine Göre Teslim Edilme Oranları (Chi-Square)**
![Payment Delivery Rate](images/payment_delivery_rate_bar.png)

---

## **📈 İstatistiksel Testler**

### **1️⃣ Teslimat Süresi → Memnuniyet (T-Testi)**
- p-değeri: **0.0000**
- **Anlamlı fark vardır.**
- Hızlı teslim alan müşteriler daha yüksek memnuniyet bildirir.

---

### **2️⃣ Ürün Kategorileri → Sipariş Değeri (ANOVA)**
- p-değeri: **0.0000**
- **Kategoriler arasında fiyat açısından anlamlı fark vardır.**

---

### **3️⃣ Ödeme Yöntemi → Siparişin Tamamlanması (Chi-Square)**
- p-değeri: **6.99e-36**
- **Bazı ödeme yöntemleri daha yüksek başarısızlık oranına sahiptir.**

---

## 📁 Kullanılan Veri Seti
Kaggle – **Brazilian E-Commerce Public Dataset by Olist**  
🔗 https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## 🚀 Notebook
Notebook dosyası: **Olist_Veri_Analizi_Projesi.ipynb**  
Tüm veri temizleme, analiz ve görselleştirmeler adım adım anlatılmıştır.

---

## 🧠 Kazanımlar
Bu projede:

- Veri temizleme  
- Gerçek iş verisinde EDA  
- Plotly ile interaktif grafik üretimi  
- İstatistiksel hipotez testleri  
- Operasyonel metrik çıkarımı  
- Veri hikayeleştirme  

yetkinlikleri geliştirilmiştir.

---

## 📄 Lisans  
MIT Lisansı altında sunulmuştur.

---

## 🤝 İletişim  
Her türlü geri bildirim ve öneri için memnuniyetle dönüş yaparım!
