# 🎵 Django Music Platform

Modern bir müzik streaming platformu. Django ile geliştirilmiş, AI destekli öneriler, favoriler sistemi ve gelişmiş arama özellikleri içerir.

## ✨ Özellikler

- 🎧 **Audio Player**: HTML5 tabanlı müzik çalar
- ❤️ **Favoriler Sistemi**: Şarkı, albüm ve sanatçıları favorilere ekleme
- 🤖 **AI Öneriler**: Akıllı müzik önerileri
- 🔍 **Gelişmiş Arama**: Şarkı, sanatçı ve albüm arama
- 📱 **Responsive Tasarım**: Mobil uyumlu arayüz
- 👤 **Session Tabanlı**: Kullanıcı deneyimi takibi
- 📊 **Admin Panel**: Django admin ile yönetim

## 🚀 Kurulum

### Gereksinimler
- Python 3.8+
- Django 4.2+

### Adımlar

1. **Repository'yi klonlayın:**
```bash
git clone https://github.com/yasin2121/django-music-platform.git
cd django-music-platform
```

2. **Virtual environment oluşturun:**
```bash
python -m venv venv
venv\Scripts\activate  # Windows
```

3. **Gerekli paketleri yükleyin:**
```bash
pip install django
```

4. **Veritabanını migre edin:**
```bash
python manage.py migrate
```

5. **Test verilerini yükleyin:**
```bash
python manage.py create_test_data
```

6. **Admin kullanıcısı oluşturun:**
```bash
python manage.py createsuperuser
```

7. **Sunucuyu başlatın:**
```bash
python manage.py runserver
```

8. **Tarayıcıda açın:**
```
http://127.0.0.1:8000
```

## 📋 Sayfalar

- **Ana Sayfa**: `/` - En son albümler, popüler şarkılar ve öneriler
- **Şarkılar**: `/songs/` - Tüm şarkılar listesi
- **Sanatçılar**: `/artists/` - Sanatçılar galerisi
- **Albümler**: `/albums/` - Albüm koleksiyonu
- **Arama**: `/search/` - Kapsamlı arama
- **Favoriler**: `/favorites/` - Favori içerikler
- **Öneriler**: `/recommendations/` - AI destekli öneriler
- **Admin**: `/admin/` - Yönetim paneli

## 🎯 Kullanım

### Müzik Çalma
- Şarkı listesinden play butonuna basın
- Audio player alt kısımda açılır
- Demo mode ile 3 dakikalık simülasyon

### Favoriler
- Kalp ikonuna tıklayarak favorilere ekleyin
- Favori sayfasından koleksiyonunuzu görün

### Öneriler
- AI algoritması dinleme geçmişinize göre öneriler sunar
- Farklı türlerde karışık öneriler alın

## 🏗️ Mimari

### Models
- **Song**: Şarkı bilgileri
- **Artist**: Sanatçı profilleri
- **Album**: Albüm detayları
- **Genre**: Müzik türleri
- **Playlist**: Çalma listeleri
- **Favorite**: Favori sistemim
- **PlayHistory**: Dinleme geçmişi
- **Recommendation**: AI önerileri

### Özellikler
- **Session-based tracking**: Oturum tabanlı takip
- **AI Recommendation Engine**: Akıllı öneri motoru
- **Responsive Design**: Bootstrap 5.3.0
- **Modern UI**: Font Awesome 6.0.0

## 🔧 Teknolojiler

- **Backend**: Django 4.2.23
- **Database**: SQLite (geliştirme), PostgreSQL (prodüksiyon)
- **Frontend**: Bootstrap 5.3.0, JavaScript ES6+
- **Icons**: Font Awesome 6.0.0
- **Audio**: HTML5 Audio API

## 📄 Lisans

Bu proje MIT lisansı altında yayınlanmıştır.

## 👤 Geliştirici

**Yasin** - [GitHub](https://github.com/yasin2121)

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add amazing feature'`)
4. Branch'i push edin (`git push origin feature/amazing-feature`)
5. Pull Request açın

## 📝 Todo

- [ ] Gerçek MP3 dosya yükleme
- [ ] User authentication sistemi
- [ ] Playlist oluşturma/düzenleme
- [ ] Social sharing özellikleri
- [ ] Advanced audio filters
- [ ] Mobile app development

---
⭐ **Projeyi beğendiyseniz yıldız vermeyi unutmayın!**
