# MBA UWTSD — Sistem Manajemen (versi aplikasi)

Aplikasi satu-file untuk mengelola proses MBA University of Wales Trinity Saint David
(program via Human Academy, Jepang): jadwal seleksi, berkas, subsidi 教育訓練給付金,
modul perkuliahan, dan tesis. Antarmuka 3 bahasa (Indonesia / English / 日本語).

## Cara pakai

Buka: https://lynsjpn.github.io/mba-uwtsd-app/

Semua data disimpan di browser Anda sendiri (localStorage) — tidak ada server, tidak ada
pengiriman data ke mana pun. Repo ini **tidak memuat data pribadi**: isian dan naskah
dimuat pengguna sendiri lewat tombol **Buka Data** (file JSON), dan disimpan lokal di
perangkat masing-masing.

- **Simpan Data** — mengunduh seluruh isian Anda sebagai satu file JSON (cadangan).
- **Buka Data** — memuat kembali file JSON tersebut di perangkat lain.

## Catatan

Angka biaya, nama modul, dan struktur subsidi mengikuti informasi publik di
mba.athuman.com dan situs 厚生労働省; verifikasi ulang sebelum dipakai untuk keputusan.
