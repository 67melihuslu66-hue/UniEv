<div align="center">
# 🏠 UniEv

### Üniversite Ev Bulma ve Ev Arkadaşı Eşleştirme Platformu

Kocaeli Sağlık ve Teknoloji Üniversitesi  
Yazılım Laboratuvarı II – Proje 3  
2025-2026 Bahar Dönemi
</div>

---

# 📖 Proje Açıklaması

UniEv, üniversite öğrencilerinin güvenli ve hızlı bir şekilde konaklama bulabilmesi amacıyla geliştirilmiş modern bir web platformudur.

Platform sayesinde öğrenciler:

- Ev ilanlarını görüntüleyebilir,
- Ev sahipleriyle iletişim kurabilir,
- Ev arkadaşı bulabilir,
- Favori ilanlarını kaydedebilir,
- Gerçek zamanlı mesajlaşabilir,
- Güvenlik analizlerinden yararlanabilir.

Sistem aynı zamanda kullanıcı güvenliğini artırmak amacıyla çeşitli doğrulama ve güvenlik mekanizmaları içermektedir.

---

# 🎯 Projenin Amacı

Öğrencilerin güvenli, hızlı ve kolay şekilde konaklama bulabilmesini sağlamak.

Ayrıca:

- Güvenli ilanların öne çıkarılması,
- Dolandırıcılık riskinin azaltılması,
- Ev sahibi ve öğrenciler arasındaki iletişimin kolaylaştırılması,
- Uyumlu ev arkadaşlarının eşleştirilmesi

amaçlanmıştır.

---

# ✨ Özellikler

## 🔐 Kimlik Doğrulama ve Güvenlik

- Kullanıcı Kayıt Sistemi
- JWT Tabanlı Kimlik Doğrulama
- E-Posta Doğrulama
- Şifre Sıfırlama
- Hesap Kilitleme Koruması
- Rol Bazlı Yetkilendirme
- Yönetici Yetkilendirme Sistemi

---

## 👤 Kullanıcı Yönetimi

- Profil Oluşturma
- Profil Güncelleme
- Profil Fotoğrafı Yükleme
- Bütçe Tercihleri
- Yaşam Tarzı Tercihleri
- Kullanıcı Puanlama Sistemi

---

## 🏠 İlan Yönetimi

- İlan Oluşturma
- İlan Güncelleme
- İlan Silme
- Fotoğraf Yükleme
- Fiyat Filtreleme
- Şehir Filtreleme
- Detaylı İlan Görüntüleme

---

## 💬 Gerçek Zamanlı Mesajlaşma

- Kullanıcılar Arası Mesajlaşma
- Görsel ve Dosya Gönderimi
- Socket.IO Desteği
- Gerçek Zamanlı Güncellemeler

---

## ❤️ Favoriler

- Favori İlan Ekleme
- Favori İlanları Yönetme

---

## 🚨 Güvenlik Özellikleri

- Dolandırıcılık Skoru Analizi
- Şüpheli İlan Bildirme
- Güvenlik İndeksi
- Yönetici Moderasyonu

---

## 🔔 Bildirim Sistemi

- Gerçek Zamanlı Bildirimler
- Kullanıcı Uyarıları

---

## 🤝 Ev Arkadaşı Eşleştirme

- Uyumluluk Analizi
- Yaşam Tarzı Bazlı Eşleştirme
- Akıllı Öneriler

---

## 📊 Yönetici Paneli

- Kullanıcı Yönetimi
- İlan Yönetimi
- Rapor Yönetimi
- Denetim Kayıtları (Audit Logs)

---

# 🛠 Kullanılan Teknolojiler

## Backend

- Python
- FastAPI
- SQLAlchemy
- Socket.IO
- JWT Authentication
- Argon2 Password Hashing

## Frontend

- HTML5
- CSS3
- JavaScript
- Jinja2 Templates

## Veritabanı

- SQLite

## Diğer Araçlar

- Git
- GitHub
- REST API
- E-Posta Servisleri

---

# ⚙️ Kurulum Adımları

## 1. Projeyi Klonlayın

```bash
git clone https://github.com/KULLANICI_ADINIZ/UniEv.git
```

## 2. Proje Klasörüne Girin

```bash
cd UniEv
```

## 3. Sanal Ortam Oluşturun

```bash
python -m venv venv
```

## 4. Sanal Ortamı Aktifleştirin

### Windows

```bash
venv\Scripts\activate
```

### Linux / MacOS

```bash
source venv/bin/activate
```

## 5. Bağımlılıkları Kurun

```bash
pip install -r requirements.txt
```

---

# ▶️ Projeyi Çalıştırma

```bash
uvicorn main:socket_app --host 0.0.0.0 --port 8000
```

Uygulama:

```text
http://localhost:8000
```

adresinde çalışacaktır.

---

# 📸 Ekran Görüntüleri

## Ana Sayfa

🔴🔴🔴 BURAYA ANA SAYFA GÖRSELİNİ EKLEYİN 🔴🔴🔴

```md
![Ana Sayfa](screenshots/homepage.png)
```

---

## Giriş Sayfası

🔴🔴🔴 BURAYA GİRİŞ SAYFASI GÖRSELİNİ EKLEYİN 🔴🔴🔴

```md
![Giriş](screenshots/login.png)
```

---

## Kayıt Sayfası

🔴🔴🔴 BURAYA KAYIT SAYFASI GÖRSELİNİ EKLEYİN 🔴🔴🔴

```md
![Kayıt](screenshots/register.png)
```

---

## İlanlar Sayfası

🔴🔴🔴 BURAYA İLANLAR SAYFASI GÖRSELİNİ EKLEYİN 🔴🔴🔴

```md
![İlanlar](screenshots/listings.png)
```

---

## İlan Detay Sayfası

🔴🔴🔴 BURAYA İLAN DETAY SAYFASI GÖRSELİNİ EKLEYİN 🔴🔴🔴

```md
![İlan Detayı](screenshots/listing-detail.png)
```

---

## Profil Sayfası

🔴🔴🔴 BURAYA PROFİL SAYFASI GÖRSELİNİ EKLEYİN 🔴🔴🔴

```md
![Profil](screenshots/profile.png)
```

---

## Mesajlaşma Sistemi

🔴🔴🔴 BURAYA MESAJLAŞMA SAYFASI GÖRSELİNİ EKLEYİN 🔴🔴🔴

```md
![Mesajlaşma](screenshots/messages.png)
```

---

## Ev Arkadaşı Eşleştirme

🔴🔴🔴 BURAYA EŞLEŞTİRME SAYFASI GÖRSELİNİ EKLEYİN 🔴🔴🔴

```md
![Eşleştirme](screenshots/match.png)
```

---

## Yönetici Paneli

🔴🔴🔴 BURAYA YÖNETİCİ PANELİ GÖRSELİNİ EKLEYİN 🔴🔴🔴

```md
![Admin](screenshots/admin.png)
```

---

# 🎥 Lansman Videosu

🔴🔴🔴 BURAYA LANSMAN VİDEOSU LİNKİNİ EKLEYİN 🔴🔴🔴

```md
[Projeyi İzle](VIDEO_LINKI)
```

---

# 🗂 Klasör Yapısı

```text
UniEv/
│
├── core/
│   ├── auth.py
│   └── security.py
│
├── routers/
│   ├── auth.py
│   ├── users.py
│   ├── listings.py
│   ├── messages.py
│   ├── match.py
│   ├── ratings.py
│   ├── admin.py
│   └── ...
│
├── services/
├── sockets/
├── templates/
├── static/
├── uploads/
├── screenshots/
├── documentation/
├── tests/
│
├── database.py
├── main.py
├── requirements.txt
├── .gitignore
└── README.md
```

---

# 🔄 Geliştirme Önerileri

- Mobil uygulama geliştirilmesi
- Yapay zeka destekli eşleştirme sistemi
- Harita entegrasyonu
- Üniversite doğrulama sistemi
- Çoklu dil desteği
- Online ödeme sistemi
- Gelişmiş güvenlik analizleri

---

# 🧪 Testler

```bash
pytest
```

🔴 Test dosyalarınız varsa burada açıklayın.

---

# 👥 Proje Ekibi

## Grup Adı

### CodeForge Şarjör Projesi

| Öğrenci No | Ad Soyad | Rol |
|------------|----------|------|
| 230501002 | Kusai Aksoy | Takım Lideri |
| 230502064 | Hashem Salem | Veri Modeli |
| 230501055 | Namik Hasan | UML Diyagramları |
| 230502053 | Rama Hasanatu | Arayüz Tasarımı |
| 230501059 | Melih Kamil Uslu | Dokümantasyon & Arayüz Tasarımı |

---

# 📌 Görev Dağılımı

### 👨‍💼 Kusai Aksoy
**Takım Lideri**

- Proje yönetimi
- Görev koordinasyonu
- Sistem planlaması

### 🗄️ Hashem Salem
**Veri Modeli**

- Veritabanı tasarımı
- Veri modeli geliştirme

### 📊 Namik Hasan
**UML Diyagramları**

- Use Case Diyagramları
- Class Diyagramları
- Sequence Diyagramları

### 🎨 Rama Hasanatu
**Arayüz Tasarımı**

- UI Tasarımı
- UX İyileştirmeleri

### 📝 Melih Kamil Uslu
**Dokümantasyon & Arayüz Tasarımı**

- README hazırlanması
- GitHub düzenlemeleri
- Teknik dokümantasyon
- Arayüz geliştirmeleri

---

# 📄 Lisans

Bu proje, Kocaeli Sağlık ve Teknoloji Üniversitesi Yazılım Laboratuvarı II dersi kapsamında eğitim amaçlı geliştirilmiştir.

---

# 🙏 Teşekkürler

Kocaeli Sağlık ve Teknoloji Üniversitesi

Yazılım Laboratuvarı II

2025-2026 Bahar Dönemi

---

<div align="center">

⭐ Projeyi beğendiyseniz GitHub üzerinden yıldız vermeyi unutmayın.

### 🚀 CodeForge Takımı Tarafından Geliştirildi

</div>
