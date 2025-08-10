# LearnLingo
Test User:
Name: testlingo
E-mail: testlingo@test.com
Pw: testlingo

**LearnLingo**, dil öğretmenlerini bulmak ve deneme dersi ayarlamak için kullanılan bir web uygulamasıdır. Kullanıcıların öğretmenleri incelemesine, hesap oluşturmasına/giriş yapmasına, favori öğretmen eklemesine ve deneme dersi talebi göndermesine olanak tanır.

## 🔍 Proje Açıklaması

LearnLingo, dil öğrenme platformunu simüle etmek amacıyla geliştirilmiş ön yüz (frontend) odaklı bir projedir. Amacı, kullanıcıların aşağıdaki işlemleri yapabileceği temiz ve duyarlı (responsive) bir kullanıcı arayüzü sunmaktır:

- Profesyonel dil öğretmenlerini görüntülemek
- Kişisel hesap oluşturarak giriş yapmak
- Favori öğretmenleri eklemek
- Seçilen öğretmenle deneme dersi rezervasyonu yapmak

Uygulama, birden fazla sayfa arasında yönlendirme, kullanıcıya özel korumalı veri ve Firebase ile gerçek zamanlı etkileşim içerir.

---

## 📄 Özellikler

- 🔐 **Kimlik Doğrulama** – Firebase Auth ile kayıt olma, giriş yapma ve çıkış yapma
- 👨‍🏫 **Öğretmenleri İncele** – Öğretmen kartlarında bilgiler, yorumlar ve ders seçenekleri
- 💛 **Favoriler** – Giriş yapan kullanıcılar favori öğretmenleri kaydedebilir
- 📬 **Deneme Dersi Rezervasyonu** – Öğretmenle deneme dersi talebi gönderme
- 🔄 **Kalıcı Durum (State)** – Kullanıcı verileri ve favoriler Firebase Realtime Database'de saklanır
- 📱 **Duyarlı Tasarım** – Masaüstü, tablet ve mobil ekranlara uyumlu

---

## 📁 Sayfalar

- `/` – **Ana Sayfa**: Platform hakkında genel bilgi
- `/teachers` – Tüm mevcut dil öğretmenlerinin listesi
- `/favorites` – Kullanıcının favori öğretmenleri (sadece giriş yaptıktan sonra erişilebilir)

---

## 🛠 Kullanılan Teknolojiler

- **React** (hooks ile birlikte)
- **React Router DOM** – istemci tarafı yönlendirme
- **Firebase** – kimlik doğrulama ve gerçek zamanlı veritabanı
- **React Hook Form + Yup** – formlar ve doğrulama
- **React Modal** – deneme dersi için modal pencere
- **React Hot Toast** – bildirimler
- **Axios** – veri çekme işlemleri
- **CSS Modules** – bileşenlere özel stillendirme

---

## 🧩 Gereksinimler & Fonksiyonel Özellikler

- Kullanıcı kayıt olabilir ve giriş yapabilir
- Sistem, mevcut oturum açmış kullanıcıyı tanır
- Kullanıcı tüm öğretmenleri detaylı bilgiyle görebilir
- Öğretmenler favorilere eklenebilir veya çıkarılabilir
- Sadece giriş yapan kullanıcılar favorileri görebilir ve düzenleyebilir
- Kullanıcılar, herhangi bir öğretmenle deneme dersi talebinde bulunabilir
- Arayüz duyarlıdır ve CSS modülleri ile tutarlı şekilde stillendirilmiştir

---

## 🚀 Başlarken

### 1. Repoyu klonlayın:

```bash
git https://github.com/ferhatipek/LearnLingo.git
cd learnlingo
npm install
npm run dev
