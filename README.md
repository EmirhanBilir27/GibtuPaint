# 🎨 GibtuPaint Studio

**GibtuPaint Studio**, tarayıcı üzerinde çalışan, hafif, hızlı ve güçlü bir web tabanlı grafik editörüdür. Saf HTML5, CSS3 ve Vanilla JavaScript kullanılarak geliştirilmiştir. Herhangi bir harici kütüphane veya bağımlılık gerektirmeden doğrudan tarayıcıda çalışır.

![GibtuPaint Studio Screenshot](https://via.placeholder.com/1200x630.png?text=GibtuPaint+Studio+UI) <!-- Görsel eklemek isterseniz burayı güncelleyebilirsiniz -->

---

## ✨ Öne Çıkan Özellikler

### 🖌️ Zengin Araç Yelpazesi
* **Fırça (Brush) & Keskin Kalem (Pencil):** Boyut ve opaklık ayarlı çizim araçları.
* **Silgi (Eraser):** Katman yapısına duyarlı temizleme aracı.
* **Sprey / Hava Fırçası (Airbrush):** Dağınık noktasal boyama.
* **Kova Dolgu (Flood Fill):** Tolerans/hassasiyet ayarlı alan boyama.
* **Vektörel Şekiller (Shapes):** Düz çizgi, ok çizgisi, dikdörtgen, oval/daire ve 5 kollu yıldız çizimi.
* **Metin Ekleme (Text):** Özelleştirilebilir font, kalınlık ve eğiklik ayarlı metin aracı.
* **Renk Damlalığı (Eyedropper):** Tuval üzerindeki herhangi bir pikseden renk alma.
* **Görüntü Kaydırma (Pan / Hand Tool):** Geniş tuvallerde kolay gezinme.

### 📚 Katman (Layer) Yönetimi
* Birden fazla katman oluşturma, silme, sıralama ve çoğaltma.
* Katman görünürlüğünü açma/kapatma ve katman kilitleme.
* Katman bazlı **Opaklık (Opacity)** ayarı.
* **Karışım Modları (Blend Modes):** Normal, Çarpan (Multiply), Ekran (Screen), Kaplama (Overlay), Karart ve Aydınlat.

### 🎭 Filtreler ve Görüntü İşleme
* Parlaklık ve Kontrast ayarlamaları.
* Renkleri Ters Çevirme (Invert), Siyah-Beyaz (Grayscale) ve Sepya (Sepia) filtreleri.
* Bulanıklaştırma (Blur) efekti.
* Yatay ve Dikey Tuval Döndürme (Flip Horizontal / Vertical).

### 💾 İçe ve Dışa Aktarma
* Çalışmaları **PNG** veya **JPG** formatında yüksek kalitede indirme.
* Katman yapılarını ve proje durumunu koruyan **`.json` Proje Kaydetme & Yükleme** desteği.
* Harici resim dosyalarını doğrudan tuvale aktarma.

---

## ⌨️ Klavye Kısayolları

Çalışma hızınızı artırmak için GibtuPaint geniş bir kısayol desteği sunar:

| Kısayol | İşlev |
| :--- | :--- |
| `B` | Fırça Aracı |
| `P` | Kalem Aracı |
| `E` | Silgi Aracı |
| `A` | Sprey Aracı |
| `G` | Kova Dolgu Aracı |
| `U` | Şekiller Aracı |
| `T` | Metin Aracı |
| `M` | Seçim Aracı |
| `I` | Renk Damlalığı |
| `H` | Kaydırma / El Aracı |
| `Space` | Geçici Kaydırma (Basılı tutun) |
| `[` / `]` | Fırça Boyutunu Küçült / Büyüt |
| `Ctrl + Z` | Geri Al (Undo) |
| `Ctrl + Y` | İleri Al (Redo) |
| `Ctrl + C` | Seçimi Kopyala |
| `Ctrl + V` | Seçimi Yapıştır |
| `Ctrl + 0` | Yakınlaştırmayı (Zoom) Sıfırla |
| `F11` | Tam Ekran Modu |

---

## 🚀 Kurulum ve Çalıştırma

Proje bağımlılıksız (Vanilla JS) geliştirildiği için herhangi bir `npm install` veya sunucu kurulumu gerektirmez.

1. Projeyi klonlayın:
   ```bash
   git clone https://github.com/KULLANICI_ADI/gibtupaint-studio.git
   ```
2. Proje klasörüne gidin:
   ```bash
   cd gibtupaint-studio
   ```
3. `index.html` dosyasını herhangi bir modern web tarayıcısında (Chrome, Firefox, Edge, Safari) açın.

---

## 🌐 GitHub Pages ile Yayınlama

Bu projeyi doğrudan ücretsiz olarak **GitHub Pages** üzerinden canlıya alabilirsiniz:

1. Deponuzun (Repository) **Settings** sekmesine gidin.
2. Sol menüden **Pages** seçeneğine tıklayın.
3. **Branch** kısmından `main` (veya `master`) dalını ve `/ (root)` klasörünü seçip **Save** butonuna basın.
4. Birkaç dakika içinde uygulamanız canlı yayın bağlantısını alacaktır!

---

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır. Dilediğiniz gibi geliştirebilir ve kullanabilirsiniz.