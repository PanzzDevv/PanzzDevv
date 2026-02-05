# 🎨 GitHub Profile README - PanzzDevv

Ini adalah repository khusus untuk **GitHub Profile README**.

## 📁 Struktur File

```
PanzzDevv/
├── README.md                          # Profile README utama
└── .github/
    └── workflows/
        ├── snake.yml                  # Auto-generate snake animation
        ├── metrics.yml                # Auto-generate GitHub metrics
        └── waka-readme.yml            # WakaTime integration (opsional)
```

## 🚀 Setup Guide

### 1. Push Repository ke GitHub

```bash
git init
git add .
git commit -m "Initial commit: Add profile README"
git branch -M main
git remote add origin https://github.com/PanzzDevv/PanzzDevv.git
git push -u origin main
```

### 2. Aktifkan GitHub Actions

Setelah push, GitHub Actions akan otomatis berjalan untuk generate snake animation.

⚠️ **PENTING**: Pergi ke **Settings > Actions > General** dan pastikan:
- "Read and write permissions" diaktifkan
- "Allow GitHub Actions to create and approve pull requests" dicentang

### 3. Setup METRICS_TOKEN (Opsional)

Untuk `metrics.yml`:
1. Buat Personal Access Token di [GitHub Settings](https://github.com/settings/tokens)
2. Berikan akses: `repo`, `user`
3. Tambahkan ke Repository Secrets dengan nama `METRICS_TOKEN`

### 4. Setup WakaTime (Opsional)

Untuk `waka-readme.yml`:
1. Daftar di [WakaTime](https://wakatime.com)
2. Install WakaTime plugin di VS Code
3. Dapatkan API Key dari WakaTime Dashboard
4. Tambahkan ke Repository Secrets:
   - `WAKATIME_API_KEY`: API Key dari WakaTime
   - `GH_TOKEN`: Personal Access Token dengan akses `repo`

### 5. Kustomisasi README

Edit bagian-bagian berikut di `README.md`:
- Ganti `YOUR_SPOTIFY_ID` dengan Spotify User ID kamu
- Ganti `YOUR_USER_ID` dengan GitHub User ID kamu
- Ganti `62xxxxxxxxxx` dengan nomor WhatsApp kamu
- Update link Saweria/Trakteer dengan akun kamu

## 🔄 Auto-Update Features

| Feature | Update Interval | Workflow |
|---------|-----------------|----------|
| 🐍 Snake Animation | Setiap 12 jam | `snake.yml` |
| 📊 GitHub Metrics | Setiap 24 jam | `metrics.yml` |
| ⏱️ WakaTime Stats | Setiap 24 jam | `waka-readme.yml` |

## 🎨 Customization Tips

1. **Ubah Tema**: Ganti `theme=tokyonight` dengan tema lain:
   - `radical`, `merko`, `gruvbox`, `dracula`, `nord`, dll.

2. **Ubah Warna Header**: Edit `customColorList` di capsule-render

3. **Tambah/Hapus Badge**: Edit bagian Tech Stack sesuai skill kamu

4. **Update Services**: Sesuaikan harga dan layanan di tabel Services

## 📞 Support

Butuh bantuan? Hubungi:
- Telegram: [@irfanff9](https://t.me/irfanff9)
- Email: Irfanstore014@gmail.com

---

**Made with ❤️ by PanzzDevv**
