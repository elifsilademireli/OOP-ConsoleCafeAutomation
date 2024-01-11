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

## Gereksinimler ve Kurulum Adımları
1.	Visual Studio kurulu olmalı.
2.	Proje dosyalarını bilgisayarınıza indirin.
3.	Visual Studio'da proje dosyalarını açın.
4.	Projeyi derleyin ve çalıştırın.

## Kullanım Senaryoları

### Kullanıcı Girişi:

- Projeyi başlattıktan sonra kullanıcı, giriş yapma ekranıyla karşılaşacaktır.
- Kullanıcı adını ve şifresini girdikten sonra giriş yap butonuna tıklar.

### Kahve Seçimi:

- Giriş yaptıktan sonra kullanıcı, kahve menüsünden istediği bir kahve türünü seçer.
- Menüdeki seçenekler arasında gezinir ve favori kahvesini bulduktan sonra seçer.

### Boyut ve Süt Seçimi:

- Kullanıcı, seçtiği kahve için boyutunu belirler.
- Ayrıca, kahvesine eklemek istediği süt tipini seçer. Örneğin, süt, badem sütü, vs.

### Sepet Yönetimi:

- Kullanıcı, seçtiği kahveyi sepetine ekleyerek siparişini oluşturur.
- Sepetini görüntüler ve isteğe bağlı olarak başka ürün ekler.

### İndirim Kodu Kullanımı:

- Kullanıcı, siparişini tamamlamadan önce bir indirim kodu ekleyebilir.
- İndirim kodunu girer ve sepet toplamı indirimle güncellenir.

### Sipariş ve Ödeme:

- Kullanıcı, sepetindeki ürünleri kontrol ettikten sonra siparişi tamamlar.
- Ödeme yöntemini seçer ve gerekli bilgileri girer.
- Siparişi onaylar ve ödemesini gerçekleştirir.

### Profil Bilgileri Güncelleme:

- Kullanıcı, hesap profilini görüntüler ve güncelleme seçeneğine tıklar.
- İlgili bilgilerini (ad soyad, e-posta, adres bilgisi) günceller ve değişiklikleri kaydeder.

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

  
