# Imam Website Kumpulan Cerpen

Website kumpulan cerpen **Imam Nur Hidayat** dengan desain biru pastel yang minimalis dan elegan. Website ini dibuat menggunakan HTML, CSS, dan JavaScript dalam satu file agar mudah dipelajari dan dipublikasikan.

## Fitur

- Desain responsif untuk desktop dan perangkat mobile
- Pencarian cerpen berdasarkan judul, kategori, ringkasan, atau isi cerita
- Filter kategori: Cinta, Persahabatan, Kehidupan, Motivasi, Fantasi, dan Refleksi
- Pengurutan cerita berdasarkan terbaru, terlama, atau judul
- Tampilan khusus untuk membaca cerita
- Koleksi cerpen favorit menggunakan `localStorage`
- Mode gelap
- Tahun copyright diperbarui secara otomatis

## Teknologi

- **HTML** — struktur halaman
- **CSS** — desain, warna, layout, dan responsivitas
- **JavaScript** — pencarian, filter, koleksi favorit, mode gelap, dan pembaca cerita
- **Google Fonts** — DM Sans dan Playfair Display

## Menjalankan secara lokal

1. Unduh atau clone repository ini.
2. Pastikan file `index.html` berada di folder utama proyek.
3. Buka `index.html` menggunakan browser seperti Google Chrome.

Tidak diperlukan instalasi package atau server untuk menjalankan versi sederhana ini.

## Deploy menggunakan GitHub Pages

1. Buka repository di GitHub.
2. Pilih **Settings → Pages**.
3. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/(root)`.
5. Klik **Save** dan tunggu proses deployment selesai.

Jika nama repository adalah `Imam-website-kumpulan-cerpen` dan username GitHub adalah `imamnurhidayat1`, alamat Pages yang diharapkan adalah:

`https://imamnurhidayat1.github.io/Imam-website-kumpulan-cerpen/`

## Menambahkan atau mengubah cerpen

Buka `index.html`, lalu cari bagian JavaScript:

```javascript
const stories = [
  // Data cerita berada di sini
];
```

Setiap cerita disimpan sebagai objek yang memiliki properti seperti:

- `id` — nomor unik cerita
- `title` — judul cerita
- `category` — kategori cerita
- `date` — tanggal dengan format `YYYY-MM-DD`
- `minutes` — perkiraan waktu membaca
- `icon` — emoji untuk ilustrasi kartu
- `excerpt` — ringkasan cerita
- `body` — isi lengkap cerita

Ganti contoh cerita dengan karya asli sebelum memublikasikan website.

## Catatan

- Cerita yang tersedia saat ini adalah **konten contoh/fiktif**.
- Koleksi favorit dan preferensi tema tersimpan di browser pengguna melalui `localStorage`.
- Website ini belum memiliki dashboard admin, database, atau sistem akun pengguna.
- Google Fonts membutuhkan koneksi internet agar font khusus dapat dimuat.

## Lisensi

Konten dan desain proyek ini dapat dikembangkan sesuai kebutuhan pemilik repository. Pastikan lu memiliki hak atas cerita, gambar, dan aset yang ditambahkan.
