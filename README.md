Kode wilayah

   Dump database PostgreSQL versi 16 berisi data geografis Indonesia.

Isi

Repositori ini berisi data geografis Indonesia yang diekstrak menjadi file SQL yang siap diimpor ke database PostgreSQL Anda.

Cara Pakai

Cukup jalankan satu perintah SQL ini, dan semua data akan langsung masuk ke database Anda.

  Impor via psql (Terminal)
  Bash

    psql -d <nama_database_anda> -f <nama_file_dump>.sql

  Impor via SQL Editor (misal: Datagrip, DBeaver, pgAdmin)
  1. Buka file .sql di editor pilihan Anda.
  2. Pastikan Anda terhubung ke database.
  3. Jalankan seluruh skrip dengan fitur "Run SQL Script" atau "Execute" (biasanya dengan Ctrl+Shift+F10 atau tombol panah hijau).

Catatan
    Kompatibel dengan PostgreSQL 16.
    Nama tabel: provinsi, kabupaten_kota, kecamatan, kelurahan_desa.

Lisensi

Repositori ini bersifat publik, silakan pakai sesuai kebutuhan.
