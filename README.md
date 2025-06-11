# EncryptionDecryption-
Kriptoloji Web Uygulaması
Bu proje, modern kriptografi algoritmalarını kullanarak güvenli veri şifreleme ve şifre çözme işlemlerini gerçekleştiren bir web uygulamasıdır.  RSA ve SHA-256 gibi güçlü kriptografi algoritmalarını kullanarak verilerinizi güvenli bir şekilde korumanızı sağlar.

🛡️ Kullanılan Kriptografi Algoritmaları.
![image](https://github.com/user-attachments/assets/343eb694-9adf-4b17-8273-46e4b1c81bfb)
![image](https://github.com/user-attachments/assets/4071a542-d7d8-430d-a3c7-2c2d0f05b90e)

## Projenin Yapıldığı Diller ve Teknolojiler Temel Teknolojiler:

HTML5: Sayfa yapısı

CSS3: Tasarım ve görsel düzenlemeler

JavaScript/jQuery: Dinamik etkileşimler ve fonksiyonellik
Kullanılan Kütüphaneler:
JSEncrypt: RSA algoritmaları için
CryptoJS: SHA256 hash fonksiyonu için
Font Awesome: İkonlar ve görsel iyileştirmeler için


## Ana Bölümler:
RSA Anahtarları Üretme
RSA ile Metin Şifreleme
RSA ile Şifre Çözme
SHA256 Hash Üretme
RSA Anahtarları Üretme


## (Rivest–Shamir–Adleman) Asymmetric Encryption.
RSA, asimetrik şifreleme algoritmasıdır ve açık anahtar kriptografisinin temelini oluşturur.
![image-1](https://github.com/user-attachments/assets/6febe644-1928-4323-88c9-a9170cfe11f1)
![image-3](https://github.com/user-attachments/assets/1455551b-7445-43cf-baa3-a364ac99e3d5)

RSA Şifreleme Arayüzü
İşlev:
## RSA algoritması ile genel anahtar kullanarak metin şifreleme.

Çalışma Yöntemi:
Şifrelenecek metni gir

Genel anahtarı gir (anahtar üretme bölümünden alınabilir).
Şifrele butonuna tıkla.
Şifrelenmiş metni sonuç alanından kopyala.

## (Rivest–Shamir–Adleman) Decryption with RSA.
![image-4](https://github.com/user-attachments/assets/70d5cf0d-9af6-4c61-849e-21449f2ee7b8)

![image-5](https://github.com/user-attachments/assets/ede567b0-a35f-41a3-a0fb-d0af22944882)

![image-10](https://github.com/user-attachments/assets/12069a98-6c40-490c-a810-991f8b63a730)

 RSA Şifre Çözme Arayüzü
İşlev:
## RSA ile şifrelenmiş metinleri özel anahtarla çözme
Çalışma Yöntemi:
Şifrelenmiş metni gir
Eşleşen özel anahtarı gir
Çöz butonuna tıkla.
Orijinal metni sonuç alanında gör.


 ## SHA-256 (Secure Hash Algorithm 256-bit)
SHA-256, kriptografik hash fonksiyonudur ve veri bütünlüğünü sağlamak için kullanılır.
Metin veya dosya için SHA256 hash değeri üretme.
![alt text](image-6.png)
![alt text](image-7.png)
![alt text](image-8.png)
Çalışma Yöntemi:
Giriş yöntemini seç (metin veya dosya).
Metin gir veya dosya seç.
Hash üret butonuna tıkla.
Sonuç alanından hash değerini kopyala.

## 3. Hash Üret Butonu
 İşlem Kontrolleri:

 Animasyonlu buton (tıklama efekti)
İşlem sırasında dönen yükleme ikonu
Başarılı/başarısız işlem sonrası geri bildirim

## 🔄 İş Akışı
Metin Hashleme:
Kullanıcı metin alanına verisini girer
"Hash Üret" butonuna tıklar
Sistem anında SHA256 hash'ini hesaplar
Sonuç alanında hash değeri görüntülenir
## Dosya Hashleme:
Kullanıcı "Dosya Seç" butonuna tıklar
Bilgisayarından bir dosya seçer
Dosya bilgileri arayüzde görüntülenir
"Hash Üret" butonuna tıklanır
Dosya içeriği okunur ve hash hesaplanır
Sonuç alanında hash değeri gösterilir
## ⚙️ Teknik Özellikler
Performans Optimizasyonu:
Büyük dosyalar için chunk işleme
Web Worker ile arka planda hash hesaplama
İptal mekanizması (uzun süren işlemler için).

## 🚀Proje Özellikleri
Şifreleme İşlemleri
RSA ile asimetrik şifreleme
SHA-256 ile hash oluşturma
Şifre Çözme İşlemleri
AES ile simetrik şifre çözme
RSA ile asimetrik şifre çözme
Hash doğrulama
## Güvenlik Özellikleri
Güvenli anahtar yönetimi
Rastgele anahtar üretimi
Güvenli veri depolama
Şifreleme anahtarlarının güvenli saklanması
