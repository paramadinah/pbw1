# Source Code & Referensi Belajar Mahasiswa

Repository ini menjadi pusat **source code, contoh program, materi praktikum, dan referensi pembelajaran** selama perkuliahan.

Gunakan repository ini untuk menjalankan contoh program, memahami cara kerja kode, melakukan eksperimen, dan mengembangkan solusi versi sendiri.


---

## 🛠️ Tools

Untuk menjalankan project secara lokal, gunakan salah satu **local development environment** berikut:

| Environment | Keterangan                                                   |
| :---------- | :----------------------------------------------------------- |
| **XAMPP**   | Local development environment untuk menjalankan aplikasi web |
| **Laragon** | Alternatif XAMPP untuk local development                     |

> **XAMPP dan Laragon merupakan alternatif. Pilih salah satu sesuai environment yang digunakan.**

Tools pendukung:

* **Visual Studio Code** - editor source code
* **Git** - version control
* **GitHub** - repository dan distribusi source code
* **Web Browser** - menjalankan dan menguji aplikasi

---

## Clone Repository

Jika baru pertama kali menggunakan repository ini, buka **PowerShell / Terminal**:

```bash
git clone <URL-REPOSITORY>
```

Contoh:

```bash
git clone https://github.com/username/nama-repository.git
```

Masuk ke folder repository:

```bash
cd nama-repository
```

Kemudian buka menggunakan Visual Studio Code:

```bash
code .
```

---

## Update Source Code

Jika repository sudah pernah di-clone, tidak perlu melakukan `clone` ulang.

Masuk ke folder repository:

```bash
cd nama-repository
```

Kemudian jalankan:

```bash
git pull
```

`git pull` digunakan untuk mengambil source code dan materi terbaru dari repository GitHub.

```text
GitHub
   │
   │  git pull
   ▼
Local Repository
   │
   ▼
Visual Studio Code
```

---

## Menjalankan Project

Pilih **salah satu** local development environment:

```text
XAMPP  atau  Laragon
```

Tidak perlu menjalankan keduanya secara bersamaan.

### XAMPP

Letakkan repository di:

```text
C:\xampp\htdocs\
```

Contoh:

```text
C:\xampp\htdocs\nama-repository\
```

Kemudian:

1. Buka **XAMPP Control Panel**.
2. Jalankan **Apache**.
3. Jalankan **MySQL** jika project membutuhkan database.
4. Buka browser.
5. Akses:

```text
http://localhost/nama-repository/
```

---

### Laragon

Letakkan repository di:

```text
C:\laragon\www\
```

Contoh:

```text
C:\laragon\www\nama-repository\
```

Kemudian:

1. Buka **Laragon**.
2. Klik **Start All**.
3. Pastikan web server sudah berjalan.
4. Buka project melalui browser.

Jika menggunakan fitur **Auto Virtual Hosts**, project biasanya dapat diakses melalui:

```text
http://nama-repository.test
```

> URL `.test` bergantung pada konfigurasi Laragon.

---

## Eksperimen

Source code di repository ini bukan untuk sekadar di-copy-paste.

Coba lakukan perubahan kecil, jalankan kembali program, lalu amati perbedaannya.

Beberapa hal yang dapat dilakukan:

* Mengubah HTML
* Mengubah CSS
* Mengubah JavaScript
* Menambahkan fitur
* Mengubah struktur kode
* Mencoba konfigurasi berbeda
* Menemukan dan memperbaiki error
* Membuat implementasi versi sendiri

> **Jangan takut membuat error. Memahami mengapa kode gagal adalah bagian dari belajar programming.**

---

## Learning Approach

```text
Read
 ↓
Run
 ↓
Modify
 ↓
Experiment
 ↓
Break
 ↓
Fix
 ↓
Understand
 ↓
Create
```

Gunakan source code sebagai bahan untuk **belajar melalui praktik**, bukan sebagai jawaban akhir.

---

## Troubleshooting

Jika menemukan error:

1. Baca pesan error secara keseluruhan.
2. Identifikasi file dan baris kode yang bermasalah.
3. Periksa perubahan terakhir yang dilakukan.
4. Cari penyebabnya, bukan hanya gejalanya.
5. Perbaiki secara bertahap.
6. Jalankan kembali program.
7. Jika masih mengalami kendala, diskusikan dengan dosen atau teman.

---

## Notes

* Gunakan **XAMPP atau Laragon**, bukan keduanya secara bersamaan.
* XAMPP menggunakan `C:\xampp\htdocs\` sebagai document root secara default.
* Laragon menggunakan `C:\laragon\www\` sebagai document root secara default.
* Gunakan `git pull` untuk mendapatkan source code terbaru.
* Jangan menghapus atau mengubah file penting tanpa memahami fungsinya.
* Untuk eksperimen besar, gunakan branch atau salinan project.

---

<p align="center">

**Learn by doing. Build with understanding.**

</p>
