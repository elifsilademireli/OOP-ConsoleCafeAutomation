# Kahve Sipariş Uygulaması

Bu proje, bir kahve sipariş uygulamasının temel özelliklerini simüle eden bir konsol uygulamasını içermektedir. Kullanıcı, giriş yapma, kahve seçimi, sepet yönetimi, sipariş ve ödeme gibi işlemleri gerçekleştirebilir. Proje, C# programlama dili kullanılarak geliştirilmiştir.

## Temel Özellikler

- Müşteri profili oluşturma.
- Kahve menüsünden kahve seçimi yapma.
- Kahve boyutu ve süt seçimi.
- Sepeti görüntüleme ve yönetme.
- Sipariş oluşturma ve ödeme.
- Kampanya ve indirim bilgilerini görüntüleme.
- Müşteri profili güncelleme.

## Kullanılan Teknolojiler

- C# Programlama Dili

## Çalışma Prensipleri

- Konsol tabanlı bir uygulama olarak kullanıcı ile etkileşim.
- Nesne tabanlı programlama prensiplerine uygun kodlama.

## Proje Detayları

- Kullanıcı dostu arayüz.
- Sepet ve sipariş yönetimi.
-	Kampanya ve indirim bilgileri.

## Proje Mimarisi ve Akış Şeması

![Başlıksız Diyagram drawio (1)](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/57462901-0de9-408e-8ac0-9b1fe2a5e658)

## Gereksinimler ve Kurulum Adımları
1.	Visual Studio kurulu olmalı.
2.	Proje dosyalarını bilgisayarınıza indirin.
3.	Visual Studio'da proje dosyalarını açın.
4.	Projeyi derleyin ve çalıştırın.

## Kullanım Senaryoları

### Kullanıcı Girişi:

- Projeyi başlattıktan sonra kullanıcı, giriş yapma ekranıyla karşılaşacaktır.
- Kullanıcı adını ve şifresini girdikten sonra giriş yap butonuna tıklar.

![bilgi girişi](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/902f08ec-c0c9-46d4-af1f-3c2b55db202b)
  
![bilgi girişi görüntüsü](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/80a87867-600e-4c42-b6c1-8f3e458502e7)

### AnaMenü

![ana menü](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/3bf00bba-88c0-4a64-9beb-610dccdc0d49)


### Kahve Seçimi:

- Giriş yaptıktan sonra kullanıcı, kahve menüsünden istediği bir kahve türünü seçer.
- Menüdeki seçenekler arasında gezinir ve favori kahvesini bulduktan sonra seçer.

 ![kahve menüsü](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/255f6f24-3545-45f2-acfb-f2da18476a76)

### Boyut ve Süt Seçimi:

- Kullanıcı, seçtiği kahve için boyutunu belirler.
- Ayrıca, kahvesine eklemek istediği süt tipini seçer. Örneğin, süt, badem sütü, vs.

 ![boyut seçimi](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/7505a118-6208-4220-8b64-7d814ecf06e0)
  
![başka ister misiniz](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/690b8483-f8f6-438a-848c-c52a1e8716fb)



### Sepet Yönetimi:

- Kullanıcı, seçtiği kahveyi sepetine ekleyerek siparişini oluşturur.
- Sepetini görüntüler ve isteğe bağlı olarak başka ürün ekler.
- İsterse seçtiği kahveleri seçime bağlı olarak silebilir.

  ![sepeti göster](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/8b9e3a8a-f29d-4035-b2da-d2b7d0a688c9)
  
![sepeti sil yeniiiiii](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/48a21718-aa3f-4f77-83c4-c77464e59d06)


### İndirim Kodu Kullanımı:

- Kullanıcı, siparişini tamamlamadan önce bir indirim kodu ekleyebilir.
- İndirim kodunu girer ve sepet toplamı indirimle güncellenir.

  ![kampanya indirim](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/362ef1e8-d20d-4a67-b68e-ddb74e346e2f)


### Sipariş ve Ödeme:

- Kullanıcı, sepetindeki ürünleri kontrol ettikten sonra siparişi tamamlar.
- Ödeme yöntemini seçer ve gerekli bilgileri girer.
- Siparişi onaylar ve ödemesini gerçekleştirir.

  ![ödemeekranı](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/78c5fa5d-f8a1-4996-832b-078a11896ae3)
![nakit ödeme](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/a57f7a33-907e-45ea-8218-e7ff521eb81f)
![kredikartı](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/dfd9dce3-af96-4d66-bace-7108634c264f)
![bankahavalesi](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/c3807320-1abb-4408-a482-96a3b6285cef)


### Profil Bilgileri Güncelleme:

- Kullanıcı, hesap profilini görüntüler ve güncelleme seçeneğine tıklar.
- İlgili bilgilerini (ad soyad, e-posta, adres bilgisi) günceller ve değişiklikleri kaydeder.

  ![profil güncelleme](https://github.com/elifsilademireli/OOP-ConsoleCafeAutomation/assets/152613912/d72f8193-f7b1-4fae-812c-6b99b5af8ed8)


## Sorunlar ve Çözümler

1. **Sorun: Kullanıcının Geçersiz Bir Kahve Seçmesi Durumu:**
   - **Çözüm:** Hata mesajları ile kullanıcıyı bilgilendirme. Kullanıcıya geçerli bir kahve seçimi yapması için uyarı mesajları gösterilir.

2. **Sorun: Kullanıcının İstenilen Şekilde Bir Değer Girmemesi Durumu:**
   - **Çözüm:** Girişlerde çeşitli kontroller yapılır:
     - Boş değer kontrolü: Kullanıcıdan alınan girişlerin boş olup olmadığı kontrol edilir.
     - Kullanıcı adı kontrolü: Kullanıcı adının istenen formatta olup olmadığı kontrol edilir.
     - E-posta format kontrolü: Kullanıcının girdiği e-posta adresinin geçerli bir formatta olup olmadığı kontrol edilir.

3. **Sorun: Boş Sepet Uyarısı:**
   - **Çözüm:** Sipariş tamamlanmadan önce sepetin boş olup olmadığı kontrol edilir. Boş sepet durumunda kullanıcıya uygun bir hata mesajı gösterilir.

4. **Sorun: Kredi Kartı Bilgilerinde Hane Kontrolü:**
   - **Çözüm:** Kullanıcının girdiği kredi kartı bilgilerinin geçerli bir uzunlukta olup olmadığı kontrol edilir. Hatalı uzunlukta kart bilgisi girilirse, kullanıcıya hata mesajı gösterilir.

5. **Sorun: İndirim Kullanım Sınırlaması:**
   - **Çözüm:** Kullanıcının belirli bir indirim kodunu kaç kez kullanabileceği kontrol edilir. Kullanıcı, izin verilen sınırları aşarsa, hata mesajı ile bilgilendirilir.

### Kod İnceleme:
- Encapsulation, Inheritance, Polymorphism, Abstraction Kullanımı

  
