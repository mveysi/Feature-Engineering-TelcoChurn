# Proje Amacı
-Şirketi terk edecek müşterileri tahmin edebilecek bir makine öğrenmesi modeli geliştirilmesi istenmektedir. 
Bu proje 2. özellik mühendisliği projemizdir. Temel de feature engineering ne kadar etkili olduğunu gösterir. Bu proje de model optimizasyonu yapmadık. Model optimizasyonu ile daha iyi bir doğruluk oranı alabiliriz.

Hedef Değişken: Churn

Hedef değişkenimizi projemizin amacından anlayabiliyoruz.

![musteri-iliskileri_3](https://github.com/user-attachments/assets/ae11238a-db42-4f5d-90c5-c872f8982f63)

# Verideki Değişkenler

CustomerId: Müşteri İd’si

Gender:  Cinsiyet

SeniorCitizen:  Müşterinin yaşlı olup olmadığı (1, 0)

Partner:  Müşterinin bir ortağı olup olmadığı (Evet, Hayır)

Dependents:  Müşterinin bakmakla yükümlü olduğu kişiler olup olmadığı (Evet, Hayır)

tenure:  Müşterinin şirkette kaldığı ay sayısı

PhoneService:  Müşterinin telefon hizmeti olup olmadığı (Evet, Hayır)

MultipleLines:  Müşterinin birden fazla hattı olup olmadığı (Evet, Hayır, Telefon hizmeti yok)

InternetService:  Müşterinin internet servis sağlayıcısı (DSL, Fiber optik, Hayır)

OnlineSecurity:  Müşterinin çevrimiçi güvenliğinin olup olmadığı (Evet, Hayır, İnternet hizmeti yok)

OnlineBackup:  Müşterinin online yedeğinin olup olmadığı (Evet, Hayır, İnternet hizmeti yok)

DeviceProtection:  Müşterinin cihaz korumasına sahip olup olmadığı (Evet, Hayır, İnternet hizmeti yok)

TechSupport:  Müşterinin teknik destek alıp almadığı (Evet, Hayır, İnternet hizmeti yok)

StreamingTV:  Müşterinin TV yayını olup olmadığı (Evet, Hayır, İnternet hizmeti yok)

StreamingMovies:  Müşterinin film akışı olup olmadığı (Evet, Hayır, İnternet hizmeti yok)

Contract:  Müşterinin sözleşme süresi (Aydan aya, Bir yıl, İki yıl)

PaperlessBilling:  Müşterinin kağıtsız faturası olup olmadığı (Evet, Hayır)

PaymentMethod:  Müşterinin ödeme yöntemi (Elektronik çek, Posta çeki, Banka havalesi (otomatik), Kredi kartı (otomatik))

MonthlyCharges:  Müşteriden aylık olarak tahsil edilen tutar

TotalCharges:  Müşteriden tahsil edilen toplam tutar

### Churn:  Müşterinin kullanıp kullanmadığı (Evet veya Hayır)


