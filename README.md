# EncryptionDecryption-
Kriptoloji Web Uygulaması
Bu proje, modern kriptografi algoritmalarını kullanarak güvenli veri şifreleme ve şifre çözme işlemlerini gerçekleştiren bir web uygulamasıdır.  RSA ve SHA-256 gibi güçlü kriptografi algoritmalarını kullanarak verilerinizi güvenli bir şekilde korumanızı sağlar.

🛡️ Kullanılan Kriptografi Algoritmaları.
![image-1](https://github.com/user-attachments/assets/9d699973-78f0-40b2-8ddc-38b7785988fa)

![alt text](image.png)
![alt text](image-9.png)
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
![alt text](image-1.png)
![alt text](image-3.png)
RSA Şifreleme Arayüzü
İşlev:
## RSA algoritması ile genel anahtar kullanarak metin şifreleme.

Çalışma Yöntemi:
Şifrelenecek metni gir

Genel anahtarı gir (anahtar üretme bölümünden alınabilir).
Şifrele butonuna tıkla.
Şifrelenmiş metni sonuç alanından kopyala.

## (Rivest–Shamir–Adleman) Decryption with RSA.
![alt text](image-4.png)
![alt text](image-5.png)
![alt text](image-10.png)
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
