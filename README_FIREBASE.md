# Panduan Firebase untuk ElectroLearn Lab 3D

Versi ini sudah memiliki lapisan sinkronisasi Firestore untuk akun siswa/guru dan nilai.

## 1. Buat proyek Firebase
1. Buka https://console.firebase.google.com/
2. Buat project baru.
3. Tambahkan Web App (`</>`).
4. Salin objek `firebaseConfig`.
5. Buka `index.html`, lalu ganti nilai `firebaseConfig` dengan konfigurasi milikmu.

## 2. Aktifkan Firestore
1. Masuk ke **Build → Firestore Database**.
2. Klik **Create database**.
3. Untuk pengujian awal, gunakan mode pengujian hanya sementara.
4. Setelah selesai menguji, ubah Rules agar lebih aman.

## 3. Deploy ulang ke GitHub Pages
Unggah `index.html` dan `README_FIREBASE.md` ke repository. Pastikan `index.html` berada di folder utama.

## Catatan penting
- Versi ini memakai koleksi `elearn_users` dan `elearn_scores`.
- Ini adalah integrasi prototipe. Data password masih berada dalam struktur data aplikasi, sehingga jangan gunakan untuk data pengguna sungguhan.
- Untuk penggunaan nyata, login sebaiknya dipindahkan ke Firebase Authentication dan akses guru dibatasi melalui Security Rules.
- Jika konfigurasi Firebase belum diisi, aplikasi tetap berjalan dalam mode lokal.
