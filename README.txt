WEBSITE TUGAS 3 - ARIEF BUDIMAN
NIM: 23.53.027115

STRUKTUR
- index.html             : Beranda / biodata
- materi.html            : Materi Komputasi Awan
- portofolio.html        : Portofolio Tugas 1, 2, dan 3
- assets/css/style.css   : Tampilan website
- assets/js/main.js      : Menu navigasi mobile dan interaksi placeholder
- assets/images/         : Simpan foto Anda di folder ini

MENGGANTI PLACEHOLDER FOTO
1. Simpan foto Anda ke assets/images/ dengan nama profil.jpg.
2. Pada index.html, cari blok <div class="photo-placeholder">...</div>.
3. Ganti blok tersebut dengan:
   <img src="assets/images/profil.jpg" alt="Foto Arief Budiman"
        style="width:100%;height:100%;object-fit:cover;border-radius:48% 48% 9px 9px">

MENGGANTI TAUTAN TUGAS 1 DAN 2
Buka portofolio.html, cari href="#" pada tombol Tugas 1 dan Tugas 2,
lalu ganti # dengan URL publik tugas masing-masing. Ubah juga ringkasan
deskripsi sesuai isi tugas sebenarnya.

DEPLOYMENT GITHUB PAGES
1. Buat repository publik bernama tugas3-cloud-2353027115.
2. Upload seluruh isi folder ini (index.html harus di root repository).
3. Buka Settings > Pages.
4. Pada Build and deployment, pilih Deploy from a branch.
5. Pilih branch main dan folder /(root), lalu Save.
6. Tunggu URL Pages aktif, lalu uji di jendela privat.

CATATAN
Website menggunakan Google Fonts melalui internet; jika font eksternal tidak tersedia,
website tetap menggunakan font cadangan. Jangan mengunggah data pribadi sensitif.
