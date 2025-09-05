# 🚀 Emrullah Dizman - Kişisel Portfolyo Sitesi

Modern ve responsive bir kişisel portfolyo web sitesi. HTML, CSS, JavaScript ve Bootstrap kullanılarak geliştirilmiştir.

## ✨ Özellikler

### 🎨 Tasarım
- **Modern Renk Paleti**: Gece mavisi, beyaz ve altın sarısı
- **Responsive Tasarım**: Tüm cihazlarda mükemmel görünüm
- **Animasyonlu Geçişler**: Scroll animasyonları ve hover efektleri
- **Modern Yazı Tipleri**: Google Fonts (Poppins) kullanımı

### 📱 Sayfa Bölümleri
- **Hero Section**: Etkileyici giriş bölümü
- **Hakkımda**: Biyografi ve yetenekler
- **Projeler**: Demo projeler galerisi
- **İletişim**: İletişim formu ve sosyal medya linkleri

### 🛠️ Teknolojiler
- HTML5
- CSS3 (Custom Properties, Flexbox, Grid)
- JavaScript (ES6+)
- Bootstrap 5.3.0
- Font Awesome 6.4.0
- AOS (Animate On Scroll)

## 🚀 Kurulum

1. **Projeyi İndirin**
   ```bash
   git clone [repository-url]
   cd portfolyo-sitesi
   ```

2. **Dosyaları Açın**
   - `index.html` dosyasını web tarayıcınızda açın
   - Veya bir local server kullanın

3. **Local Server (Opsiyonel)**
   ```bash
   # Python ile
   python -m http.server 8000
   
   # Node.js ile
   npx serve .
   
   # PHP ile
   php -S localhost:8000
   ```

## 📁 Dosya Yapısı

```
portfolyo-sitesi/
├── index.html          # Ana HTML dosyası
├── style.css           # CSS stilleri
├── script.js           # JavaScript kodları
└── README.md           # Bu dosya
```

## 🎯 Özellikler Detayı

### Hero Section
- Animasyonlu arka plan
- Typing effect ile isim animasyonu
- Parallax scrolling efekti
- Responsive butonlar

### Hakkımda Bölümü
- Kısa biyografi
- Yetenekler grid'i
- Hover animasyonları
- İkon tabanlı skill gösterimi

### Projeler Bölümü
- Kart tabanlı proje gösterimi
- Hover efektleri
- Demo ve GitHub linkleri
- Responsive grid layout

### İletişim Bölümü
- Form validasyonu
- WhatsApp direkt mesaj
- Instagram DM yönlendirmesi
- E-posta gönderimi
- Bildirim sistemi

## 🎨 Özelleştirme

### Renkleri Değiştirme
`style.css` dosyasındaki CSS değişkenlerini düzenleyin:

```css
:root {
    --primary-color: #1e3a8a;    /* Ana renk */
    --secondary-color: #fbbf24;  /* İkincil renk */
    --accent-color: #3b82f6;     /* Vurgu rengi */
}
```

### İçerik Güncelleme
- `index.html` dosyasında metinleri değiştirin
- Proje resimlerini güncelleyin
- Sosyal medya linklerini ekleyin

### Animasyon Ayarları
`script.js` dosyasında AOS ayarlarını düzenleyin:

```javascript
AOS.init({
    duration: 1000,        // Animasyon süresi
    easing: 'ease-in-out', // Geçiş tipi
    once: true,            // Sadece bir kez çalışsın
    mirror: false          // Geri dönüş animasyonu
});
```

## 📱 Responsive Özellikler

- **Desktop**: Tam özellikli görünüm
- **Tablet**: Optimize edilmiş layout
- **Mobile**: Mobil uyumlu navigasyon ve layout

## 🔧 Tarayıcı Desteği

- ✅ Chrome (90+)
- ✅ Firefox (88+)
- ✅ Safari (14+)
- ✅ Edge (90+)

## 📞 İletişim Bilgileri

Projeyi özelleştirmek için aşağıdaki bilgileri güncelleyin:

### WhatsApp
```html
<a href="https://wa.me/905XXXXXXXXX" target="_blank">
```

### Instagram
```html
<a href="https://instagram.com/emrullahdizman" target="_blank">
```

### E-posta
```html
<a href="mailto:emrullah@example.com">
```

## 🚀 Performans Optimizasyonları

- **Lazy Loading**: Görsel yükleme optimizasyonu
- **Throttled Scroll Events**: Scroll performansı
- **CSS Animations**: GPU hızlandırmalı animasyonlar
- **Minified Dependencies**: Küçültülmüş dosyalar

## 📝 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Commit edin (`git commit -m 'Add some AmazingFeature'`)
4. Push edin (`git push origin feature/AmazingFeature`)
5. Pull Request oluşturun

## 📞 Destek

Herhangi bir sorunuz varsa:
- GitHub Issues kullanın
- E-posta gönderin: emrullah@example.com

---

**Not**: Bu proje demo amaçlı oluşturulmuştur. Gerçek kullanım için iletişim bilgilerini ve proje linklerini güncellemeyi unutmayın. 