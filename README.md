# Template Website Informatika SMP

Template website pembelajaran Informatika untuk kelas 7, 8, dan 9. Dibuat dengan HTML, CSS, dan JavaScript sederhana agar mudah diedit pemula dan dapat dipublikasikan gratis melalui GitHub Pages.

## Struktur folder

```text
template-website-informatika/
├── index.html
├── README.md
├── assets/
│   ├── css/style.css
│   └── js/main.js
├── kelas-7/
│   ├── index.html
│   ├── materi/index.html
│   ├── soal/index.html
│   └── game/index.html
├── kelas-8/ ...
└── kelas-9/ ...
```

## Cara memakai template

1. Ekstrak file ZIP di komputer.
2. Buka `index.html` untuk melihat beranda. Jika ingin mengedit, gunakan Visual Studio Code atau editor teks.
3. Buka `kelas-7/index.html`, `kelas-8/index.html`, atau `kelas-9/index.html` untuk mengganti deskripsi kelas.
4. Tambahkan materi/soal/game ke folder yang sesuai. File PDF, gambar, atau presentasi bisa diletakkan di folder tersebut lalu ditautkan dari halaman HTML.
5. Ganti nama sekolah dan identitas portal pada file HTML sesuai kebutuhan.

## Upload ke GitHub

1. Masuk atau daftar di https://github.com
2. Klik tombol **+** di kanan atas → **New repository**.
3. Isi nama repository, misalnya `informatika-smp`, pilih **Public**, lalu klik **Create repository**.
4. Pada halaman repository, pilih **Add file → Upload files**.
5. Ekstrak ZIP terlebih dahulu, lalu unggah **isi folder** template (jangan hanya mengunggah file ZIP). Klik **Commit changes**.
6. Buka **Settings → Pages**.
7. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
8. Pilih branch **main** dan folder **/(root)**, lalu klik **Save**.
9. Tunggu beberapa menit. Alamat website akan muncul di halaman GitHub Pages, biasanya `https://USERNAME.github.io/informatika-smp/`.

## Cara menambahkan materi PDF

1. Unggah PDF ke folder, misalnya `kelas-7/materi/berpikir-komputasional.pdf`.
2. Buka `kelas-7/materi/index.html`.
3. Tambahkan tautan seperti ini:

```html
<a href="berpikir-komputasional.pdf" target="_blank" rel="noopener">
  Buka materi Berpikir Komputasional (PDF)
</a>
```

## Catatan penting

- GitHub Pages cocok untuk website statis: HTML, CSS, JavaScript, gambar, PDF, dan game yang berjalan di browser.
- GitHub Pages tidak menyediakan database atau login siswa otomatis. Untuk kuis yang menyimpan nilai siswa, diperlukan layanan/backend tambahan.
- Tautan dalam template memakai alamat relatif agar tetap berfungsi ketika dipublikasikan di alamat GitHub Pages yang memiliki nama repository.
