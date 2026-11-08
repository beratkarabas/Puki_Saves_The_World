# 🌿 Doğa Kahramanları & Sosyal Farkındalık Platformu

Doğa koruma, sıfır atık, iklim değişikliği ve ekolojik sürdürülebilirlik bilincini çocuklara ve gençlere aşılamak amacıyla geliştirilmiş interaktif web platformu ve eğitici çevre oyunu.

---

## 🚀 Proje Hakkında

Bu proje, hem bilgilendirici bir sosyal sorumluluk web platformunu hem de platform içerisine gömülü 4 seviyeli tam oynanabilir bir çevre kurtarma oyununu içermektedir. 

Platformun rehberi **Baykuş Puki**, kullanıcıları doğa sorunları hakkında bilgilendirir ve interaktif görevlerle doğayı kurtarmaya davet eder.

### 🌟 Temel Özellikler

1. **📱 Modern & Duyarlı (Responsive) Web Platformu (`index.html`):**
   - **Sol Sabit Menü:** Tek sayfa uygulama (SPA) mimarisiyle çalışan 6 dinamik kategori (*Ana Sayfa, Projelerimiz, Bilgilendirme, Etkinlikler, Eğitsel Oyunlar, İletişim*).
   - **Canlı Saat & Takvim:** Sağ üstte anlık güncellenen saniyeli dijital saat ve güncel Türkçe takvim.
   - **İlham Veren Sözler Paneli:** Mustafa Kemal Atatürk, Hayrettin Karaca ve çevre düşünürlerinin ilham veren sözleri ve "Yeni Söz Getir" butonu.
   - **Günün Eko-Görevi:** Günlük sürdürülebilirlik görevleri ve XP kazanma mekanizması.
   - **İnteraktif Ekolojik Ayak İzi Hesaplayıcı:** Plastik tüketimine göre yıllık etki ve tasarruf önerisi.
   - **5 Atık Türü Rehberi & Çevre Testi (Quiz):** 4 soruluk anında geri bildirimli mini çevre bilgisi testi.
   - **Etkinlik Kayıt Sistemi:** Fidan dikimi ve kıyı temizliği etkinlikleri için interaktif kayıt modalı.

2. **🎮 4 Seviyeli Doğa Kurtarma Oyunu (`oyun.html`):**
   - **1. Seviye (Parkı Temizle):** Yerdeki organik ve geri dönüştürülebilir atıklar, doğru çöp kutularına (yeşil ve mavi) ayrıştırılır. Park temizlenince güneş açar.
   - **2. Seviye (Denizleri ve Kaplumbağayı Kurtar):** Denizdeki plastik atıklar temizlenir, ardından kurtarma makası ile kaplumbağa kurtarılır.
   - **3. Seviye (Şehrin Havasını Temizle):** Fabrika bacalarına filtreler takılır, evlerin çatılarına güneş panelleri yerleştirilerek hava kirliliği %0'a indirilir.
   - **4. Seviye (Orman Yangınını Söndür ve Yeşert):** Ağaçlardaki yangın alevleri söndürülür, yerdeki cam atıklar toplanır, fidanlar dikilir ve yağmur bulutuyla orman yeniden yeşertilir.
   - **Büyük Final & Ödül Sergisi:** 4 rozetin tamamı sergilenir ve Puki doğa kahramanını tebrik eder.
   - **Web Audio API:** Harici ses dosyasına gerek olmadan tarayıcıda üretilen müzik ve ses efektleri.

---

## 📂 Dosya Yapısı

```
├── index.html          # Ana web platformu (SPA, Navigasyon, Quiz, Sayaçlar, vb.)
├── oyun.html           # 4 Seviyeli tam oynanabilir eğitici oyun
├── maskot/             # Baykuş Puki maskot görselleri (happy, sad, fear, normal)
├── seviye_1/           # Park seviyesi arka planları ve atık görselleri
├── seviye_2/           # Deniz seviyesi arka planları ve canlı görselleri
├── seviye_3/           # Şehir seviyesi arka planları ve filtre görselleri
├── seviye_4/           # Orman seviyesi arka planları, ateş ve fidan görselleri
└── README.md           # Proje dokümantasyonu
```

---

## 🌐 Vercel Üzerinde Yayınlama Kılavuzu

Projeyi GitHub'a yükledikten sonra Vercel ile 1 dakikada canlıya alabilirsiniz:

1. **GitHub'a Yükleyin:**
   - [github.com](https://github.com) adresinde yeni bir repo oluşturun (Örn: `doga-kahramanlari`).
   - Bu klasördeki tüm dosyaları repoya yükleyin.

2. **Vercel'e Bağlayın:**
   - [vercel.com](https://vercel.com) adresine GitHub hesabınızla giriş yapın.
   - **"Add New..." ➔ "Project"** butonuna tıklayın.
   - Oluşturduğunuz GitHub reposunu seçin ve **"Import"** deyin.
   - **"Deploy"** butonuna basın.

3. **Canlıda! 🎉**
   - Vercel size anında `https://doga-kahramanlari.vercel.app` şeklinde ücretsiz bir bağlantı verecektir. Bu linki doğrudan paylaşabilirsiniz.

---

## 🛠️ Kullanılan Teknolojiler

- **HTML5 & CSS3:** Modern Flexbox/Grid mimarisi, CSS Keyframe animasyonları, Cam (Glassmorphism) efektleri.
- **JavaScript (Vanilla JS):** SPA geçişleri, dinamik quiz motoru, ayak izi hesaplayıcı, canlı dijital saat.
- **Web Audio API:** Sentezlenmiş arka plan müziği ve gerçekçi ses efektleri.
- **Google Fonts:** 'Fredoka' & 'Quicksand' tipografileri.
