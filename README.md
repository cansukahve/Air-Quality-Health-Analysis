# 🌍 Hava Kalitesi ve Sağlık Etkileri Analizi (Air Quality & Health Analysis)

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-blue?style=for-the-badge)

## 📌 Proje Özeti
Bu proje, hava kirliliği parametreleri (PM2.5, PM10, NO2, O3) ile halk sağlığı üzerindeki etkileri (hastane başvuruları) arasındaki ilişkiyi analiz etmek amacıyla geliştirilmiştir. 

**İş Zekası (Business Intelligence)** dersi kapsamında hazırlanan bu çalışma, reaktif (tepki veren) sağlık yönetiminden proaktif (önleyici) sağlık yönetimine geçişte verinin nasıl kullanılabileceğini göstermektedir.

---

## 📊 Dashboard Önizlemesi

*(Lütfen `Images` klasöründeki ekran görüntülerini buraya eklediğinden emin ol. Aşağıdaki kod, Images klasöründeki dosyayı çeker.)*

### 1. Genel Bakış (Overview)
![Dashboard Genel Bakış](Images/dashboard_screenshot_1.png)

### 2. Detaylı Analiz
![Harita ve Detaylar](Images/dashboard_map_view.png)

---

## 🎯 Projenin Amacı ve Çıkarımlar
Bu dashboard karar vericilere şu konularda stratejik içgörüler sunar:
* **Kirlilik ve Sağlık İlişkisi:** AQI (Hava Kalitesi İndeksi) arttıkça hastane başvurularındaki artışın gözlemlenmesi.
* **Bölgesel Analiz:** Hangi şehirlerin (Urban/Suburban) daha yüksek risk altında olduğu.
* **Kapasite Planlaması:** Kirlilik zirve yaptığında hastane kapasitelerinin yeterlilik durumu.

> **Ana Çıkarım:** Analizler sonucunda, PM2.5 seviyesindeki artışların hastane başvurularını doğrudan etkilediği ve sağlık kaynaklarının buna göre optimize edilmesi gerektiği görülmüştür.

---

## 📂 Dosya Yapısı
Bu depo (repository) aşağıdaki gibi düzenlenmiştir:

| Klasör / Dosya | Açıklama |
| :--- | :--- |
| `Air_Quality_Dashboard.pbix` | **Power BI Dashboard dosyası (Ana Proje).** |
| `/Data` | Analizde kullanılan ham veri seti (`air_quality_health_dataset.csv`). |
| `/Docs` | Projenin akademik raporu ve detaylı açıklamaları (`Project_Report.pdf`). |
| `/Images` | Dashboard ekran görüntüleri. |

---

## 🛠 Kullanılan Teknolojiler ve Veri Seti
* **Araçlar:** Microsoft Power BI, Excel.
* **Veri Seti:** Hava kalitesi, meteorolojik veriler ve hastane kayıtlarını içeren kapsamlı bir veri seti kullanılmıştır.
    * *Not: Veri seti eğitim amaçlıdır ve simülasyon/sentetik veriler (gelecek tarihler vb.) içerebilir.*

---

## 🚀 Nasıl Çalıştırılır?
1.  Bu repoyu indirin (Download ZIP) veya klonlayın.
2.  `Air_Quality_Dashboard.pbix` dosyasını **Microsoft Power BI Desktop** uygulaması ile açın.
3.  Veri kaynağı yolu hatası alırsanız, `Data` klasöründeki CSV dosyasını Power BI üzerinden tekrar tanıtın.
