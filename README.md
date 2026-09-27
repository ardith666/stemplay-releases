# StemPlay — Releases

Binary installer untuk **StemPlay**, aplikasi desktop pemisah stem audio (vokal, drum, bass, dan lainnya) yang berjalan sepenuhnya di komputer Anda.

Repo ini **hanya berisi binary rilis**. Kode sumber aplikasi ada di repo terpisah yang bersifat private.

## Download

Semua binary ada di halaman [Releases](https://github.com/ardith666/stemplay-releases/releases). Unduh langsung dari sana — jangan ambil file dari sumber lain.

### macOS

Pilih sesuai jenis Mac Anda (**Apple menu → About This Mac**):

| Mac | File |
|---|---|
| Apple Silicon (M1/M2/M3/M4) | `StemPlay-<versi>-mac-arm64.dmg` |
| Intel | `StemPlay-<versi>-mac-x64.dmg` |

Pasang dengan membuka `.dmg` lalu seret ikon **StemPlay** ke **Applications**.

### Windows

| File | Keterangan |
|---|---|
| `StemPlay-<versi>-win-x64.exe` | Installer, dipasang sekali klik |
| `StemPlay-<versi>-win-x64.zip` | Versi portable, extract lalu jalankan `StemPlay.exe` |

**Windows akan menampilkan "Windows protected your PC".** Ini muncul karena StemPlay belum memakai sertifikat code signing berbayar, bukan karena file rusak. Cara membukanya:

1. Klik **More info**
2. Klik **Run anyway**

Alternatif: klik kanan `.exe` → **Properties** → centang **Unblock** di bagian bawah → **Apply** → **OK**.

## Angka checksum

Setiap rilis menyertakan `latest.yml` dan `latest-mac.yml` yang berisi ukuran serta SHA-512 tiap file. File `.blockmap` juga disertakan untuk keperluan pembaruan otomatis.

## Data dan privasi

- Lagu dan setelan tersimpan di folder data aplikasi lokal di komputer Anda.
- Tidak ada data yang dikirim ke server mana pun.
- Pemisahan stem dilakukan secara lokal memakai FFmpeg yang sudah disertakan di dalam aplikasi.
