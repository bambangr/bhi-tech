# bintangharta.tech

Website PT Bintang Harta Indonesia.

- `site/` — yang tayang di bintangharta.tech (saat ini: halaman Segera Hadir). Auto-deploy dari branch `main` tiap 60 detik ke `/var/www/bintangharta` di VPS.
- `draft/` — Beranda company profile lengkap. Belum tayang; dipindah ke `site/` setelah SK AHU + KBLI baru tercatat di OSS.
- `deploy/` — docker-compose auto-deploy + konfigurasi Nginx.
