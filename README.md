# Farach Ishbachi — Portfolio Website

Website portofolio statis (HTML, CSS, JavaScript) yang siap di-deploy ke Vercel.

## Cara edit
1. Buka `index.html` menggunakan Visual Studio Code atau editor teks.
2. Cari teks yang ingin diubah (nama, deskripsi, pengalaman, proyek, email, GitHub).
3. Ganti `EMAIL_KAMU` dengan alamat email aktif.
4. Ganti `USERNAME_GITHUB` dengan username GitHub kamu.
5. Jika ingin menggunakan foto, ganti blok `.portrait-card` di bagian hero dengan elemen `<img>` dan sesuaikan CSS-nya.
6. Simpan file.

## Deploy paling mudah lewat GitHub + Vercel
1. Buat akun/login di https://github.com/
2. Buat repository baru, misalnya `farach-portfolio`.
3. Upload `index.html` dan `README.md` ke repository tersebut.
4. Buka https://vercel.com/ lalu login menggunakan GitHub.
5. Klik **Add New → Project**, pilih repository `farach-portfolio`.
6. Pada konfigurasi proyek, pilih **Framework Preset: Other**. Untuk situs HTML statis ini, biarkan Build Command kosong dan isi Output Directory dengan `.` jika diminta.
7. Klik **Deploy**.
8. Setelah selesai, Vercel memberikan alamat website `nama-project.vercel.app`.

## Catatan sebelum dipublikasikan
- Periksa kembali tanggal dan uraian pengalaman kerja.
- Tambahkan email, GitHub, foto profil, serta file CV PDF jika sudah siap.
- Tambahkan screenshot dan tautan demo/repository pada setiap proyek jika tersedia.
- Pastikan informasi pencapaian dan detail proyek sesuai bukti/portofolio yang dapat ditampilkan.
