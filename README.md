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
<img width="1849" height="916" alt="image" src="https://github.com/user-attachments/assets/8eaf5de1-109c-4c45-bac2-c71d203643c4" />


```md
![Ana Sayfa](screenshots/homepage.png)
```

---

## Giriş Sayfası

<img width="1864" height="907" alt="image" src="https://github.com/user-attachments/assets/d8fa79fd-8c33-4b77-abff-a050040a182d" />


```md
![Giriş](screenshots/login.png)
```

---

## Kayıt Sayfası

<img width="1844" height="906" alt="image" src="https://github.com/user-attachments/assets/bbda959b-397a-4447-a1eb-d52a69072b95" />


```md
![Kayıt](screenshots/register.png)
```

---

## İlanlar Sayfası

<img width="1866" height="788" alt="image" src="https://github.com/user-attachments/assets/980984c6-3b0c-44e5-92ba-f881b58a93e2" />


```md
![İlanlar](screenshots/listings.png)
```

---

## İlan Detay Sayfası

<img width="1863" height="844" alt="image" src="https://github.com/user-attachments/assets/9d7d52e1-fcd3-4eb0-be54-d85b437f8947" />


```md
![İlan Detayı](screenshots/listing-detail.png)
```

---

## Profil Sayfası

<img width="1842" height="912" alt="image" src="https://github.com/user-attachments/assets/cafb74c3-101c-4421-896c-3b3eee8c0a91" />


```md
![Profil](screenshots/profile.png)
```

---

## Mesajlaşma Sistemi

<img width="1838" height="903" alt="image" src="https://github.com/user-attachments/assets/8ee5294d-7a66-41d9-a245-dc8fe1e4c9ca" />


```md
![Mesajlaşma](screenshots/messages.png)
```

---

## Ev Arkadaşı Eşleştirme

<img width="1855" height="906" alt="image" src="https://github.com/user-attachments/assets/8a866929-2d51-42b8-9b5a-2c120c46a4f8" />


```md
![Eşleştirme](screenshots/match.png)
```

---

## Yönetici Paneli

<img width="1848" height="904" alt="image" src="https://github.com/user-attachments/assets/667e9d59-8d98-453c-9e4f-7da3b5c03e1b" />


```md
![Admin](screenshots/admin.png)
```

---

# 🎥 Lansman Videosu

https://youtu.be/BJKZr4FfNJQ

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
