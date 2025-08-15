# Web-Scraping-Time-Series-for-Weather-Prediction
Bu proje, **maksimum ve minimum sıcaklık verilerine** dayalı olarak İstanbul için hava durumu tahmini yapmayı amaçlamaktadır.  
Veriler, özel olarak geliştirilen bir **web scraping** süreci ile güvenilir meteorolojik kaynaklardan toplanmıştır.  
⚠️ Veri toplama sürecine ait kodlar, proje kapsamında paylaşılmamaktadır.

---

## 📂 Veri Süreci
1. **Veri Toplama** → Web scraping yöntemiyle günlük maksimum ve minimum sıcaklık verileri çekilmiştir.  
2. **Veri Temizleme** → Eksik ve hatalı gözlemler temizlenmiş, veri tutarlılığı sağlanmıştır.  
3. **Zaman Serisi Hazırlığı** → Veriler tarih sırasına göre düzenlenmiş ve analiz için hazır hale getirilmiştir.  
4. **Modelleme** → Farklı zaman serisi yöntemleri ile tahminleme yapılmıştır.  

---

## 🛠 Kullanılan Modeller
- Naïve
- ETS(A,A,A)
- Holt-Winters
- ARIMA
- SARIMA
- Prophet

---

## 📊 Sonuç ve Değerlendirme
- **ARIMA** modeli, kısa vadeli tahminlerde en düşük hata oranlarını vermiştir.  
- **SARIMA**, mevsimsel döngüleri başarılı şekilde yakalamış ancak kısa vadede ARIMA kadar iyi performans göstermemiştir.  
- **ETS** ve **Holt-Winters**, mevsimsellik ve trendi iyi modelleyerek dengeli sonuçlar üretmiştir.  
- **Prophet**, trend ve mevsimsellik ayrıştırmasında esnek olmasına rağmen hata oranı biraz daha yüksektir.  

📌 **En iyi kısa vadeli model:** ARIMA  
📌 **Mevsimsel analiz için güçlü alternatif:** SARIMA  

---
> **Not:** Bu proje, akademik bir çalışma kapsamında geliştirilmiştir.

