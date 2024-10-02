# Point of Sale Application

Aplikasi Point of Sale (POS) ini dirancang untuk melacak penjualan, stok, dan transaksi. Dibangun menggunakan Laravel dan Bootstrap dengan database SQLite, aplikasi ini menyediakan fitur lengkap untuk manajemen penjualan dan persediaan dengan data dummy yang siap digunakan.

## Teknologi yang Digunakan

- **Laravel**: Framework PHP untuk pengembangan backend.
- **Bootstrap**: Framework CSS untuk antarmuka pengguna.
- **SQLite**: Database ringan yang sudah terintegrasi.

## Persyaratan

Untuk menjalankan aplikasi ini, disarankan menggunakan [Laravel Herd](https://herd.laravel.com/). Jika Laravel Herd tidak tersedia, Anda bisa menjalankan aplikasi dengan perintah:

## Cara Menjalankan Aplikasi

1. Clone repository ini ke dalam direktori lokal Anda.
2. Jalankan perintah berikut untuk menginstall dependensi:
   ```
   composer install
   npm install && npm run dev
   ```
3. Setup file `.env` dan konfigurasikan database dengan SQLite. Anda bisa menggunakan perintah:
   ```
   cp .env.example .env
   php artisan key:generate
   ```
4. Migrasi dan seed database:
   ```
   php artisan migrate --seed
   ```
5. Jalankan server lokal menggunakan Laravel Herd atau perintah:
   ```
   php artisan serve
   ```

## Login Awal

Gunakan kredensial berikut untuk login pertama kali:

- **Username**: `admin`
- **Password**: `4dm1n@123`

## Fitur Aplikasi

1. **Supplier Management**:
   - Membuat, mengedit, menampilkan, dan menghapus supplier.
2. **Category Management**:
   - Membuat, mengedit, menampilkan, dan menghapus kategori barang.
3. **Product Management**:
   - Membuat, mengedit, menampilkan, dan menghapus barang.
4. **Payment Method Management**:
   - Membuat, mengedit, menampilkan, dan menghapus metode pembayaran.
5. **User Profile Management**:
   - Mengedit dan menampilkan profil user.
6. **User Management**:
   - Membuat, mengedit, menampilkan, dan menghapus user.
7. **User Presence Tracking**:
   - Melacak kehadiran user berdasarkan login.
8. **Transaction Management**:
   - Melakukan transaksi penjualan.
9. **Sales Report**:
   - Menampilkan laporan penjualan dengan filter.

## Kontak

Untuk pertanyaan lebih lanjut, Anda dapat menghubungi saya melalui Instagram: [@mhqif](https://instagram.com/mhqif).
