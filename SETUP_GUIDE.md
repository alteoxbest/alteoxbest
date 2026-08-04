# 🚀 @alteoxbest GitHub Profil & Yılan (Snake) Oyunu Kurulum Rehberi

Bu rehber, hazırladığımız Matte Dark temalı profil README'sini ve Otomatik Katkı Yılanı (Snake Game) animasyonunu **@alteoxbest** GitHub hesabında aktif etmen için adım adım yol gösterir.

---

## 1️⃣ GitHub'da Profil Deposu (Repository) Oluşturma

1. GitHub'a giriş yap ve sağ üstteki **`+`** butonuna basıp **`New repository`** seçeneğini seç.
2. **Repository name** kısmına tam olarak **`alteoxbest`** yaz.
   - GitHub sana *"You found a secret! alteoxbest/alteoxbest is a ✨special✨ repository..."* mesajını gösterecektir.
3. Repozitoyu **`Public`** (Açık) olarak işaretle.
4. **`Add a README file`** seçeneğini işaretleme (çünkü kendi hazırladığımız README.md dosyasını yükleyeceğiz).
5. **`Create repository`** butonuna tıkla.

---

## 2️⃣ GitHub Action İzinlerini Açma (Yılan Oyunu İçin ŞART 🐍)

Otomatik yılan animasyonunun çalışıp yeşil kareleri yemesi için GitHub Workflow'una yazma izni vermelisin:

1. Oluşturduğun `alteoxbest/alteoxbest` deposunda üst taraftaki **`Settings`** sekmesine tıkla.
2. Sol menüden **`Actions`** > **`General`** bölümüne git.
3. Sayfayı aşağı kaydırıp **`Workflow permissions`** başlığını bul.
4. **`Read and write permissions`** seçeneğini işaretle.
5. **`Save`** butonuna basarak kaydet.

---

## 3️⃣ Dosyaları GitHub'a Yükleme

Bu klasördeki tüm dosyaları terminal / komut satırı ile hemen GitHub'a gönderebilirsin:

```bash
git init
git add .
git commit -m "feat: add matte dark profile & snake workflow for @alteoxbest"
git branch -M main
git remote add origin https://github.com/alteoxbest/alteoxbest.git
git push -u origin main
```

*(Veya GitHub web arayüzünde `uploading an existing file` seçeneği ile `README.md` ve `.github/workflows/snake.yml` dosyalarını yükleyebilirsin).*

---

## 4️⃣ Yılan Oyunu Otomatik Nasıl Çalışacak?

- `.github/workflows/snake.yml` dosyası sayesinde yılan animasyonu **her 12 saatte bir** ve her kod yüklediğinde otomatik çalışır.
- GitHub katkı grafiğindeki (contributions) tüm commitlerini yiyen güncel yılan animasyonunu oluşturup profilinde sergiler.
- Dilersen GitHub'da **`Actions`** sekmesine girip **`Generate Snake Animation`** > **`Run workflow`** diyerek yılanı manuel olarak da hemen çalıştırabilirsin!

🎉 **Tebrikler! Profilin artık ThaTiemsz seviyesinde premium, mat dark ve canlı!**
