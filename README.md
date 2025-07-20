# 🎯 QR Code Generator Stylish & Scan-Safe

Web app berbasis HTML + JavaScript untuk membuat QR code dari link secara otomatis. Dilengkapi dengan gambar overlay (misalnya logo) yang tetap aman dipindai berkat error correction tinggi. Tampilan bersih dengan card-style UI, SVG icons, dark mode toggle, dan fitur download PNG.

## ✨ Fitur Utama
- Paste link → QR code langsung muncul.
- Upload gambar overlay yang ditampilkan di tengah QR.
- Tombol "Cancel Gambar" untuk hapus overlay logo.
- Download QR sebagai PNG.
- Toggle Dark Mode dengan ikon.
- Layout bersih, responsif, dan modern dengan SVG icons.
- QR tetap bisa di-scan karena pakai error correction level `H`.

## 🚀 Cara Pakai
1. Paste URL ke kolom input.
2. Upload gambar (format PNG transparan direkomendasikan).
3. QR code otomatis tampil di canvas.
4. Klik **Download** untuk menyimpan sebagai gambar.
5. Klik **Cancel Gambar** untuk hapus logo dari QR.
6. Gunakan **Dark Mode Toggle** untuk tampilan gelap.

## 💡 Teknologi yang Digunakan
- HTML5, CSS3, JavaScript
- [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator)
- SVG inline icons tanpa dependensi eksternal


## 📸 Preview
<img width="1919" height="1033" alt="Screenshot 2025-07-20 205652" src="https://github.com/user-attachments/assets/933eac06-29f9-45af-a7bf-9ab0b9a4c7e9" />

## 📌 Tips Teknis
- Gambar overlay sebaiknya tidak lebih dari 25–30% area QR.
- Gunakan PNG transparan untuk hasil terbaik.
- Kontras tinggi sangat penting: QR hitam di atas latar putih.
- QR code menggunakan koreksi level `H` agar tetap terbaca.

## 📜 Lisensi
Aplikasi ini dapat digunakan bebas untuk keperluan pribadi, edukasi, atau komersial dengan atribusi. Lisensi bisa disesuaikan sesuai kebutuhan proyekmu.

---

