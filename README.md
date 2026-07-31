# Pedjoeang-Tanah-Air-Old-

Pedjoeang-Tanah-Air-Old- adalah game action-platformer bertema era kolonial yang dibuat dengan Construct 2 dan dibungkus dengan NW.js. Repo ini sudah berisi build siap jalan, jadi kamu bisa langsung menjalankannya di Windows tanpa install dependency tambahan.

## Isi Project

- `nw.exe` dan file runtime NW.js lain di root folder.
- `package.nw`, yaitu arsip yang berisi file game utama.
- Asset game seperti gambar, audio, dan script runtime Construct 2.

File utama game ada di dalam `package.nw` dan entry point-nya adalah `index.html`.

## Cara Menjalankan di Windows

1. Download release repo ini ke komputer kamu.
2. Pastikan semua file hasil extract tetap berada dalam satu folder yang sama.
3. Jalankan `nw.exe` dengan cara double-click, atau buka terminal di folder itu lalu jalankan:

```powershell
.\nw.exe .
```

4. Game akan terbuka di jendela NW.js.

Kalau game tidak muncul, pastikan kamu menjalankan `nw.exe` dari folder yang sama dengan `package.nw`.

