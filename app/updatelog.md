# Update Log - Versi 1.1.5.2

## 🚀 Peningkatan Kecepatan & Keandalan Unduhan
- **Server Download Baru**: Menambahkan server baru sebagai sumber cadangan baru untuk pengunduhan manifest game. Hal ini meningkatkan tingkat keberhasilan unduhan manifest jika server utama mengalami gangguan.
- **Sistem Failover 5 Lapis**: Aplikasi sekarang secara otomatis mencoba mengunduh dari 5 sumber berbeda (Server Utama, Backup 1, 2, 3, dan Bypass) sebelum melaporkan kegagalan.

## 🛠️ Pembaruan Sistem
- **Update Versi 1.1.5.2**: Pembaruan internal untuk sinkronisasi dengan database di repositori utama.
- **Optimalisasi Koneksi**: Penyesuaian timeout dan penanganan error pada saat pengambilan data manifest dari Server.

# Update Log - Versi 1.1.5.1

## 📦 Steam Vault Overhaul (Fitur Baru)
- **Progress Bar Real-time**: Menambahkan `ttk.Progressbar` untuk melacak proses backup dan restore secara visual.
- **Bulk Restore (Restore Semua)**: Sekarang Anda dapat mengembalikan seluruh data save library Anda sekaligus dengan fitur "Restore All".
- **Kustomisasi Direktori**:
  - Tombol **"Change Dir"**: Ubah folder penyimpanan backup utama sesuai keinginan Anda.
  - **Manual Backup/Restore**: Pilihan untuk membackup ke atau merestore dari file ZIP spesifik secara manual di setiap kartu game.
- **Deteksi Save yang Lebih Canggih**:
  - Peningkatan deteksi untuk **Rockstar Games** (GTA V, GTA V Enhanced, GTA V Legacy, RDR2).
  - Peningkatan deteksi folder save **Ubisoft Connect** (berdasarkan akun user ID).

## ✨ Peningkatan UI & UX
- **Status Operasi yang Jelas**: Label status memberikan informasi detail tentang progres file selama operasi berlangsung.
- **UI Refresh**: Tombol kontrol baru (Change Dir, Restore All) ditambahkan ke bilah atas tab Vault.
- **Bilingual Support**: Log informasi sekarang sepenuhnya dalam Bahasa Indonesia.

## 🛠️ Perbaikan Bug & Optimasi
- Memperbaiki masalah deteksi path save untuk game Rockstar versi terbaru.
- Optimalisasi penanganan file ZIP untuk mencegah korupsi data saat proses backup terhenti.
- Perbaikan minor pada sistem scrolling tab Vault.
- Pembersihan kode internal untuk kestabilan aplikasi yang lebih baik.



# Update Log - Versi 1.1.5

## 📦 Steam Vault (Fitur Baru)
- **Backup Save Game**: Deteksi otomatis dan backup save game Anda ke dalam file ZIP.
- **Backup Screenshot**: Simpan screenshot Steam Anda dengan aman bersama data save.
- **Logika Restore**: Kembalikan data Anda dengan mudah hanya dengan satu klik.
- **Backup Semua**: Gunakan tombol "Backup All" untuk mengamankan seluruh library Anda sekaligus.
- **Manajemen Folder**: Backup tertata rapi dalam folder berformat `Nama Game (AppId)`.

## ✨ Peningkatan UI & UX
- **Resolusi Nama Dinamis**: Nama aplikasi sekarang secara otomatis diambil dari Steam Store di latar belakang (background) jika data nama belum tersedia.
- **Tab Log Pembaruan**: Menambahkan tab baru untuk memberikan informasi tentang perubahan dan fitur terbaru.
- **Gaya Modern**: Tombol dan tata letak yang diperhalus untuk memberikan kesan yang lebih premium.

## 🛠️ Perbaikan Bug
- Memperbaiki masalah di mana library lokal tidak menampilkan nama yang benar untuk beberapa game.
- Meningkatkan deteksi jalur (path) Steam untuk pengaturan multi-drive.
- Optimalisasi performa umum dan pembersihan kode.
