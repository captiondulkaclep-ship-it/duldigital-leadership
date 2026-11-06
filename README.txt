# DULDIGITAL PROJECTS — Leadership Knowledge

Website statis responsif berisi 23 artikel, pencarian, kategori, dialog baca artikel, like/share awal, dan diskusi komentar.

## Penting tentang komentar
- Tanpa konfigurasi Supabase, komentar hanya tersimpan di browser/perangkat yang digunakan (mode demo).
- Agar komentar tersimpan online dan dapat dibaca semua pengunjung, buat project Supabase, jalankan `supabase-schema.sql` di SQL Editor, lalu isi `SUPABASE_URL` dan `SUPABASE_ANON_KEY` di bagian awal script pada `index.html`.
- Gunakan hanya anon/public key. Jangan pernah memasukkan service_role key ke website.
- Contoh komentar Rizal dan Siti diberi label sebagai komentar contoh.
- Like dan share awal 3.000.000 dan 1.000.000 adalah angka tampilan awal, bukan statistik historis. Penghitungan real lintas pengunjung memerlukan tabel dan kebijakan tambahan.

## Publikasi melalui Vercel
1. Ekstrak ZIP ini.
2. Upload seluruh isi folder ke repository GitHub baru.
3. Buka Vercel, pilih Add New → Project, lalu import repository tersebut.
4. Framework preset: Other. Build command dan output directory dikosongkan/default.
5. Klik Deploy.

Karena situs berupa HTML statis, tidak memerlukan proses build.
