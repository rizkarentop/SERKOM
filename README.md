# Kopi Ulee Kareng

Landing page dan CRUD produk menggunakan Laravel 12.

## Teknologi
- PHP 8.2
- Laravel 12
- MySQL
- Blade dan CSS

## Cara Menjalankan
1. Jalankan `composer install`.
2. Salin `.env.example` menjadi `.env` jika diperlukan.
3. Atur koneksi database pada `.env`.
4. Jalankan `php artisan key:generate`.
5. Jalankan `php artisan migrate --seed`.
6. Jalankan `php artisan serve`.
7. Buka `http://127.0.0.1:8000`.

## Fitur
- Landing page produk Kopi Ulee Kareng
- Daftar produk
- Tambah, edit, dan hapus produk
- Validasi dan notifikasi
- Pengujian manual dan feature test

## Struktur Utama
- `app/Models/Product.php`
- `app/Http/Controllers/ProductController.php`
- `routes/web.php`
- `resources/views/`
- `tests/Feature/ProductFlowTest.php`

## Pengujian
Jalankan `php artisan test`.

## Penyusun
Nama peserta: ...
Kelas: ...
Tanggal: ...
