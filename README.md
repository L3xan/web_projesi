# 💰 Kişisel Bütçe Yönetimi

## 📝 Proje Açıklaması 
Bu proje, kullanıcıların kişisel finansal durumlarını kolayca takip etmelerini ve bütçelerini profesyonelce yönetmelerini sağlayan web tabanlı bir uygulamadır. Özellikle kısıtlı bütçelerle yaşayan öğrencilerin gelir ve gider dengelerini kurabilmeleri, harcamalarını görselleştirip finansal hedeflerine ulaşmaları amaçlanmıştır.

## 🎯 Hedef Kullanıcılar
* Öğrenciler
* Bütçesini, günlük harcamalarını ve birikim hedeflerini modern bir arayüzle takip etmek isteyen bireyler

## ✨ Temel Özellikler
* **Kullanıcı Yönetimi:** Şifreleme (Hash) yöntemiyle güvenli Kayıt Olma, Giriş Yapma ve Oturum (Session) yönetimi.
* **Gelişmiş Dashboard:** Güncel bakiyeyi tek ekranda sunan dinamik kontrol paneli.
* **Finansal Hedef (Kumbara):** Kullanıcıların belirli bir birikim hedefi koyabilmesi ve hedefe ne kadar yaklaştığını gösteren ilerleme çubuğu (Progress Bar).
* **Veri Görselleştirme:** Giderlerin kategorilere göre dağılımını gösteren interaktif pasta grafiği.
* **Kategorik İşlemler:** Emojilerle zenginleştirilmiş kategorilerle Gelir/Gider ekleme, düzenleme ve silme işlemleri (CRUD).
* **Gelişmiş Raporlama (Takvim):** Seçilen aya göre toplam gelir, gider ve net durumu gösteren, gün gün harcama dökümü veren detaylı rapor sayfası.
* **Modern ve Akıcı Arayüz:** İşlem onayları ve bildirimler için animasyonlu pop-up pencereleri.

## 💻 Kullanılan Teknolojiler
Bu projenin geliştirilmesinde aşağıdaki teknolojiler kullanılmıştır:
* **Frontend (Önyüz):** HTML5, CSS3, JavaScript
* **Kütüphaneler:** Chart.js (Grafikler), SweetAlert2 (Animasyonlu Bildirimler)
* **Backend (Arkayüz):** PHP (PDO mimarisi kullanılmıştır)
* **Veritabanı:** MySQL

## 🚀 Kurulum
Projeyi kendi yerel bilgisayarınızda (localhost) çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. XAMPP, WAMP veya benzeri bir yerel sunucu ortamını bilgisayarınıza kurun.
2. Bu projeyi indirin veya terminal üzerinden klonlayın: `git clone https://github.com/L3xan/kisisel-butce-yonetimi.git`
3. Proje klasörünü yerel sunucunuzun kök dizinine (örneğin XAMPP için `htdocs` klasörü) taşıyın.
4. XAMPP kontrol panelinden Apache ve MySQL servislerini başlatın.
5. Tarayıcınızdan `http://localhost/phpmyadmin` adresine gidin ve `ogrenci_finans` adında yeni bir veritabanı oluşturun (Karşılaştırma dilini `utf8mb4_unicode_ci` seçin).
6. Proje dizininde bulunan `database.sql` dosyasının içindeki SQL kodlarını kopyalayıp phpMyAdmin'deki SQL sekmesinden çalıştırarak tabloları oluşturun.
7. Tarayıcınızda `http://localhost/kisisel-butce-yonetimi` adresine giderek uygulamayı çalıştırın ve ilk kaydınızı oluşturun!

## 🌐 Canlı Link
Henüz yayınlanmadı. (Proje yayına alındığında link buraya eklenecektir.)
