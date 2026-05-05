# 🐠 Aquavera

> **Akvaryumunu Bilimle Yönet** — Tropikal tatlı su akvaryumları için bilimsel temelli yönetim platformu.

## Hakkında

Aquavera, akvaryum sahiplerinin tank koşullarını izlemesini, su parametrelerini yorumlamasını ve bakım kararlarını **bilimsel literatüre dayanarak** vermesini sağlayan bir web platformudur. Sıfırdan başlayan amatörlerden ileri seviye akvaristlere kadar her seviyeye uygun.

**Vizyon:** Akvaryum bakımını duygu-bazlı bir hobi olmaktan çıkarıp, ölçülebilir ve sürdürülebilir bir ekosistem yönetimine dönüştürmek.

## Mevcut Durum

🟢 **Demo v1.0** — Modül A (Tank Değerlendirme) çalışıyor.

### Aktif Özellikler

- ✅ **Akıllı Tank Profili** — 5 adımda tank tanımlama
- ✅ **Kural Motoru** — 6 kategoride deterministik değerlendirme:
  - Filtre yeterliliği
  - Isıtıcı yeterliliği
  - Aydınlatma uygunluğu
  - Biyo-yük (stoklama)
  - Tank hacmi yeterliliği
  - Tür uyumluluğu
- ✅ **Adaptif Dil Sistemi** — Yeni başlayan ve ileri seviye için iki dilli açıklama
- ✅ **20 Tropikal Tür Veritabanı** — Bilimsel referansla derlenmiş

### Geliştirme Aşamasında

- 🔨 Parametre Yorumcusu (NH₃, NO₂, NO₃, pH, GH yorumlama)
- 🔨 Akvaryum Akademisi (Khan Academy tarzı eğitim platformu)
- 🔨 Akıllı Bakım Takvimi
- 🔨 Sarf Takip ve Maliyet Öngörüsü
- 🔨 Topluluk Özelliği

## Bilimsel Temel

Tüm değerlendirme kuralları aşağıdaki akademik kaynaklara dayanır:

- Boyd, C.E. (2015) *Water Quality: An Introduction*
- Spotte, S. (1992) *Captive Seawater Fishes*
- Walstad, D. (2003) *Ecology of the Planted Aquarium*
- Timmons & Ebeling (2010) *Recirculating Aquaculture*
- Hovanec & DeLong (1996) — Nitrifikasyon koloni dinamikleri
- FishBase (Froese & Pauly, 2024)

**Hiçbir AI veya tahmin yoktur** — tüm hesaplar deterministik kural motoruyla yapılır. Her sonuç açıklanabilir ve savunulabilir.

## Teknoloji

- **Frontend:** Vanilla HTML/CSS/JavaScript (demo)
- **Planlama:** Next.js + TypeScript + Tailwind (gerçek MVP için)
- **Backend:** Supabase (PostgreSQL + Auth) — gerçek MVP'de
- **Deploy:** Vercel
- **Domain:** aquavera.app (yakında)

## Lansman Yol Haritası

- [x] **Aşama 0:** Konsept doğrulama, demo geliştirme
- [ ] **Aşama 1:** Kayıt sistemi, veri saklama, MVP modülleri
- [ ] **Aşama 2:** Akvaryum Akademisi içerik üretimi
- [ ] **Aşama 3:** POS entegrasyonu, üyelik sistemi
- [ ] **Aşama 4:** Mobil uygulama (iOS + Android)

## Lisans

Şirket projesidir. Tüm hakları saklıdır.

## İletişim

Aquavera ekibi · [İletişim bilgisi gelecek]

---

*"Sağlıklı bir akvaryum, göründüğünden daha karmaşık."*
