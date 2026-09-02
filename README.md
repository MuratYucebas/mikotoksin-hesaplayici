# Yücebaş Food - AB 2023/2782 Mikotoksin Numune Alma Hesaplayıcısı

## 🔐 Email Korumalı Hesaplayıcı

Bu proje, **AB Komisyonu (AB) 2023/2782** Mikotoksin Numune Alma Yönetmeliğine uygun olarak partiler için numune alma planı oluşturan interaktif bir web hesaplayıcısıdır.

### ✨ Özellikler

- **Email Giriş Koruması**: Sayfaya erişmek için email doğrulaması gereklidir
- **Email Format Validasyonu**: Geçerli email formatı (örn: name@domain.com) kontrol edilir
- **Responsive Tasarım**: Mobil, tablet ve desktop cihazlarda çalışır
- **Kurumsal Kimlik**: Yücebaş Food logosu ve kurumsal renkler
- **Otomatik Hesaplama**: Parametreleri değiştirirken sonuçlar anında güncellenir

### 🚀 Nasıl Kullanılır

1. **Sayfayı Açma**
   - `index.html` dosyasını tarayıcıda açın
   - veya GitHub Pages URL'sini ziyaret edin

2. **Email Girme**
   - Email adresinizi girin (örn: `kullanici@yucebas.com`)
   - "Devam Et" butonuna tıklayın

3. **Hesaplayıcıyı Kullanma**
   - Toplam Parti Büyüklüğü (kg) girin
   - Birim Paket Ağırlığı (kg) girin
   - Ambalaj Tipini seçin (Vakumlu/Normal)
   - Sonuçlar otomatik olarak hesaplanır

4. **Çıkış Yapma**
   - Sağ üstteki "Çıkış Yap" butonuna tıklayın
   - Email formuna döneceksiniz

### 📁 Dosya Yapısı

```
.
├── index.html                          # Ana sayfa (GitHub Pages için)
├── mikotoksin_ornekleme V2.html       # Ana HTML dosyası
├── README.md                           # Bu dosya
└── assets/
    └── logo.jpg                        # Yücebaş Food logosu
```

### 🔧 Teknik Detaylar

- **HTML5**: Semantik ve modern HTML
- **CSS3**: Responsive grid ve flexbox tasarımı
- **JavaScript**: İstemci taraflı email validasyonu ve hesaplama
- **localStorage/sessionStorage**: Email hafızası (mevcut olduğunda)

### 📋 Mevzuat Referansları

- **AB Regülasyon (AB) 2023/2782**: Mikotoksin Numune Alma Yönetmeliği
- **Ek I Bölüm II.C**: Numune alma prosedürleri
- **Tablo 2**: Kuru incir standardı

### 🌐 GitHub Pages'te Yayınlama

1. **GitHub'da Repository Oluştur**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Email-protected sampling calculator"
   ```

2. **GitHub'a Push Et**
   ```bash
   git remote add origin https://github.com/[USERNAME]/[REPO].git
   git push -u origin main
   ```

3. **GitHub Pages Ayarla**
   - Repository Settings → Pages
   - Branch: `main`
   - Folder: `/ (root)`
   - Save

4. **Erişim Linki**
   - `https://[USERNAME].github.io/[REPO]/`

### 📝 Örnek Giriş Değerleri

| Parametre | Değer |
|-----------|-------|
| Toplam Parti | 4.800 kg |
| Birim Paket | 15 kg |
| Ambalaj | Vakumlu |
| **Sonuç** | **30 paket açılacak** |

### 💬 Sorular & Desteği

Destek için: `info@yucebas.com`

---

**Sürüm**: 2.0  
**Son Güncelleme**: 2026-09-02  
**Geliştirici**: Murat Yücebaş
