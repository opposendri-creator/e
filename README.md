# 🧁 Dapu Mulia - E-Commerce Kue & Snack

Website e-commerce untuk **Dapu Mulia** - Toko kue dan snack homemade berkualitas.

## Fitur
- 🏠 Halaman Home dengan hero banner
- 🛍️ Katalog produk kue & snack
- 🛒 Keranjang belanja interaktif
- 📱 Integrasi WhatsApp untuk pemesanan
- ⚙️ Panel Admin (Klik ikon gear atau Ctrl+A) untuk kelola produk
- 🎨 Tema orange yang hangat & modern
- 📱 Responsive (Mobile Friendly)

## ⚠️ PENTING: Cara Menyimpan Perubahan Produk Secara Permanen

Data produk default ada di file **`js/data.js`**. Ketika Anda menambah/edit/hapus produk lewat **Panel Admin (⚙️)**, perubahan hanya tersimpan di **localStorage browser ANDA SAJA**.

Jika Anda upload website ke hosting (GitHub Pages, dll) dan orang lain membukanya, mereka tetap melihat data LAMA dari file `data.js`.

### Agar perubahan bisa dilihat semua orang:

#### 🔹 Cara Cepat (Export & Ganti)
1. Buka website di browser Anda
2. Klik ikon ⚙️ di navbar (atau tekan `Ctrl + A`) untuk buka Panel Admin
3. Lakukan perubahan produk (tambah/edit/hapus)
4. Klik tombol **"Export data.js"** di pojok kanan atas panel
5. File `data.js` akan ter-download ke komputer Anda
6. **Ganti/Langkahi** file `js/data.js` yang lama di folder project dengan file yang baru di-download
7. Upload ulang semua file project ke hosting
8. ✅ Semua orang sekarang akan melihat data yang sudah di-update!

#### 🔹 Cara Manual (Edit Langsung)
1. Buka file `js/data.js` di code editor (VS Code)
2. Edit array `baseProducts` sesuai kebutuhan
3. Simpan file dan upload ulang ke hosting

> 💡 **Tips:** Setiap kali selesai mengelola produk di Panel Admin, selalu klik **"Export data.js"** dan ganti file aslinya agar perubahan tersimpan permanen!

## Teknologi
- HTML5
- CSS3 (Flexbox & Grid)
- JavaScript (Vanilla)
- Font Awesome Icons

## Cara Hosting di GitHub Pages
1. Buat repository baru di GitHub
2. Upload semua file folder `dapu-mulia` ke repository
3. Buka Settings > Pages > Pilih branch `main` folder `/ (root)`
4. Klik Save, tunggu beberapa menit
5. Website akan live di `https://[username].github.io/dapu-mulia`

## Kontak
- WhatsApp: 081273127063

