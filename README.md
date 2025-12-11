# End-4 Quickshell Customized

Konfigurasi Quickshell yang telah dikustomisasi berdasarkan [end-4/dots-hyprland](https://github.com/end-4/dots-hyprland).

## Perubahan dari Konfigurasi Default

### Bar (BarContent.qml)

- **Active Window** - Dinonaktifkan (`visible: false`)
- **Resource Indicators** - Hanya menampilkan CPU (RAM dan Swap disembunyikan)
- **Media Control** - Dinamis, hanya muncul saat ada media yang diputar
  - Judul dan artis tersembunyi secara default
  - Muncul dengan animasi slide saat icon musik di-hover
- **Battery Indicator** - Dipindah ke grup indikator kanan (bersama volume, network, bluetooth)
- **Layout Tengah** - Resources/Media diposisikan terpisah dari Clock dan Workspaces untuk menjaga simetri bar

### Panel Families (shell.qml)

- **Waffle Panel** - Ditambahkan `iiOverview` agar Task View berfungsi di panel family waffle

### Aplikasi (Config.qml)

- **Task Manager** - Menggunakan `plasma-systemmonitor`

## Screenshot

*Tambahkan screenshot bar Anda di sini*

## Instalasi

1. Backup konfigurasi Quickshell Anda yang ada
2. Clone repository ini ke `~/.config/quickshell/ii`
3. Reload Quickshell

```bash
# Backup
mv ~/.config/quickshell/ii ~/.config/quickshell/ii.backup

# Clone
git clone git@github.com:immualifin/end4-costumized.git ~/.config/quickshell/ii

# Reload Quickshell (atau restart session)
```

## Dependensi

- [Quickshell](https://github.com/quickshell-mirror/quickshell)
- [Hyprland](https://hyprland.org/)
- `plasma-systemmonitor` (untuk Task Manager)

## Credits

- Konfigurasi asli: [end-4/dots-hyprland](https://github.com/end-4/dots-hyprland)
