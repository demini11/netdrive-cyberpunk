# NETDRIVE // Cyberpunk APK via GitHub Actions

> Build APK otomatis di cloud — **tanpa install apapun di PC kamu!**

---

## 🚀 CARA PAKAI (5 Langkah)

### Langkah 1 — Buat akun GitHub (gratis)
Kalau belum punya: https://github.com/signup

---

### Langkah 2 — Buat repository baru
1. Buka https://github.com/new
2. Repository name: `netdrive-cyberpunk`
3. Pilih **Public**
4. Klik **Create repository**

---

### Langkah 3 — Upload semua file ini ke GitHub

**Cara A: Upload via browser (paling mudah)**
1. Di halaman repo kamu, klik **uploading an existing file**
2. Drag & drop semua file/folder dari ZIP ini
3. Klik **Commit changes**

**Cara B: Via Git (jika punya Git terinstall)**
```bash
# Ekstrak ZIP ini, lalu:
cd netdrive-github
git init
git add .
git commit -m "Initial commit - NETDRIVE Cyberpunk"
git branch -M main
git remote add origin https://github.com/NAMA_KAMU/netdrive-cyberpunk.git
git push -u origin main
```

---

### Langkah 4 — Tunggu build otomatis (~5-10 menit)
1. Buka repo di GitHub
2. Klik tab **Actions**
3. Lihat workflow **Build NETDRIVE APK** berjalan
4. Tunggu sampai ada centang hijau ✅

---

### Langkah 5 — Download APK
**Cara A: Via Releases (link permanen)**
1. Di repo GitHub, klik **Releases** (sidebar kanan)
2. Klik file `NETDRIVE-Cyberpunk-v1.0-X.apk`
3. APK langsung terdownload!

**Cara B: Via Actions Artifact**
1. Klik tab **Actions** → klik run terbaru
2. Scroll ke bawah, lihat **Artifacts**
3. Klik `NETDRIVE-APK` untuk download

---

## 📱 CARA INSTALL APK DI HP ANDROID

1. Transfer APK ke HP (via WhatsApp, Google Drive, kabel USB, dll)
2. Buka **Pengaturan** HP
3. Cari **"Sumber tidak dikenal"** atau **"Install app dari sumber lain"**
   - Samsung: Pengaturan → Aplikasi → menu ⋮ → Akses khusus → Install app tidak dikenal
   - Xiaomi/MIUI: Pengaturan → Privasi → Izinkan sumber tidak dikenal
   - Stock Android: Pengaturan → Keamanan → Sumber tidak dikenal
4. Izinkan browser/file manager untuk install
5. Buka file `.apk` → **Install**
6. Selesai! Icon NETDRIVE muncul di layar

---

## 🔄 Update App
Setiap kali kamu push perubahan ke GitHub → APK otomatis ter-build ulang → download versi terbaru dari Releases.

---

## ❓ FAQ

**Q: Gratis?**
A: Ya! GitHub Actions gratis untuk repo public (2000 menit/bulan untuk private).

**Q: Berapa lama build?**
A: Sekitar 5-10 menit pertama kali, berikutnya lebih cepat karena ada cache.

**Q: APK aman?**
A: Ya, APK di-build dari kode kamu sendiri secara transparan di GitHub.

**Q: Bisa upload ke Play Store?**
A: Bisa, tapi butuh build APK Release + signing keystore. Minta ke Claude untuk panduan itu.
