# 🎮 Karar Verme ve Mini Oyunlar Paketi

Bu proje, hem eğlenceli vakit geçirmek hem de kararsız kalınan anlarda farklı felsefelerle sonuç bulmak için HTML, CSS ve JavaScript (Vanilla JS) kullanılarak geliştirilmiş 3 farklı web uygulamasını içermektedir.

Hiçbir sunucu veya veritabanı gereksinimi yoktur; tüm oyunlar doğrudan tarayıcı üzerinde çalışır.

---

## 📦 1. Kutu Yakalama Oyunu (Performans Odaklı Karar Verici)

![Kutu Yakalama Oyunu Arayüzü] 
<img width="1919" height="1079" alt="Ekran görüntüsü 2026-05-05 100633" src="https://github.com/user-attachments/assets/f974ec8a-383c-49c3-93d3-ea278a253e69" />

*(Buraya oyunun oynanış veya liderlik tablosu ekran görüntüsünü ekleyin)*

**Felsefesi:** Kararın rastgeleliğe değil, **bilek hakkına, hıza ve odağa** bağlı olmasını istediğiniz anlarda devreye girer. "Son dilim pizzayı kim yiyecek?" gibi kritik krizleri liyakatle çözer.

**Özellikler:**
* Sınırsız sayıda oyuncu ekleme desteği.
* 3 farklı zorluk seviyesi (Kolay: 1.5s, Orta: 1.0s, Zor: 0.5s kutu ekranda kalma süresi).
* Her oyuncu için 15 saniyelik adil zamanlayıcı.
* Oyun sonu puanlara göre otomatik sıralanan Liderlik Tablosu.

---

## 🎡 2. Şans Çarkı (Demokratik Karar Verici)

![Şans Çarkı Arayüzü]
<img width="1919" height="1079" alt="Ekran görüntüsü 2026-05-05 100708" src="https://github.com/user-attachments/assets/590ca07f-c3c5-4427-b15a-a28b8bdb20f8" />
*(Buraya seçeneklerin eklendiği ve çarkın döndüğü bir ekran görüntüsü ekleyin)*

**Felsefesi:** Seçeneklerin birbirine tamamen eşit olduğu ve sorumluluğun "kadere" bırakılmak istendiği durumlar için tasarlanmış tarafsız bir yargıçtır. 

**Özellikler:**
* Dinamik olarak sınırsız seçenek ekleme ve çıkarma (Sağ Menü).
* HTML5 Canvas ile dinamik çizilen dilimler ve otomatik açı hesaplamaları.
* Çarkın en az 5 tam tur dönmesini sağlayan gerçekçi fizik ve CSS `cubic-bezier` animasyonları.
* Dönüş bitiminde kazananı hesaplayan ve ekrana yazdıran akıllı sistem.

---

## 🎲 3. 20'lik Zar ve Gelişmiş Liste (Stratejik Karar Verici)

![20'lik Zar Arayüzü]
<img width="1919" height="1079" alt="Ekran görüntüsü 2026-05-05 100655" src="https://github.com/user-attachments/assets/5cfb9219-e763-40f4-955e-7a11f80670a6" />
*(Buraya min-max aralıklarının girildiği ve zarın olduğu bir ekran görüntüsü ekleyin)*

**Felsefesi:** Seçeneklerin eşit olmadığı, belirli kararlara ağırlık (olasılık) vermek istediğiniz karmaşık durumlar için risk yöneticisidir. Şansın sınırlarını siz çizersiniz, gerisini zarlara bırakırsınız.

**Özellikler:**
* Gelişmiş CSS `clip-path` kullanılarak tasarlanmış interaktif 20'lik zar (D20) görünümü.
* Eklenen her eylem için özel Minimum (Min) ve Maksimum (Max) değer aralığı atayabilme.
* Gelen zar sonucuna göre kuralları tarayan ve kazanan senaryoyu/senaryoları bulan algoritma.
* Dinamik eylem ekleme ve silme.

---

## 🚀 Kurulum ve Kullanım

Projeler tamamen istemci tarafında (Client-Side) çalışmaktadır. Herhangi bir kütüphane veya paket yöneticisi yüklemenize gerek yoktur.

1. Bu depoyu bilgisayarınıza klonlayın veya `.zip` olarak indirin:
   ```bash
   git clone [https://github.com/KULLANICI_ADINIZ/karar-verme-oyunlari.git](https://github.com/KULLANICI_ADINIZ/karar-verme-oyunlari.git)
   
Oynamak istediğiniz oyunun dizinine gidin.

İlgili .html dosyasını (örneğin cark.html) çift tıklayarak favori web tarayıcınızda (Chrome, Safari, Firefox vb.) açın.

🛠️ Kullanılan Teknolojiler
HTML5: Sayfa iskeleti ve Canvas API kullanımı.

CSS3: Modern arayüz tasarımı, Flexbox dizilimleri, animasyonlar (Transition) ve CSS Şekilleri (Clip-path).

JavaScript (ES6): DOM manipülasyonu, olay dinleyicileri (Event Listeners), matematiksel hesaplamalar ve rastgelelik üretimi (Math.random()).
