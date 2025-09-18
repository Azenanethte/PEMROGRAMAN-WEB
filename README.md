# 📘Analisis section

---

## 📂 Pertemuan 1
Analisis bisa dilihat di link berikut:  
👉 [Klik di sini](https://drive.google.com/drive/folders/1EoFQHFqPB8ktB13OpGieetTotnUnfeSa)
Petunjuk : Buka dokumen 1.

---

## 📂 Pertemuan 2
Analisis bisa dilihat di link berikut:  
👉 [Klik di sini](https://drive.google.com/drive/folders/1EoFQHFqPB8ktB13OpGieetTotnUnfeSa)
Petunjuk : Buka dokumen 2.

---

## 📂 Pertemuan 3
### Analisis Website Portfolio

Website portofolio ini dibangun menggunakan HTML5 dengan styling utama dari Tailwind CSS. 
Bagian `<head>` digunakan untuk menyimpan konfigurasi awal seperti judul halaman, meta charset, meta viewport agar responsif di berbagai perangkat, serta link eksternal ke Tailwind dan Remixicon untuk ikon. Bagian ini tidak muncul di layar, tetapi penting untuk mengatur tampilan dan fungsionalitas web.  

Isi utama berada di dalam `<body>` yang dibagi ke dalam beberapa section. Bagian paling atas terdapat navbar (`<nav>`) berisi tautan internal menuju About, Projects, dan Contact. Selanjutnya pada Hero Section digunakan elemen `<h1>`, `<p>`, dan `<img>` untuk menampilkan sambutan, deskripsi singkat, serta foto kecil berbentuk bulat dengan efek animasi.

Section About berisi informasi diri dengan teks deskriptif dan foto formal, ditulis menggunakan `<h2>`, `<p>`, dan `<img>`. Section Experience menampilkan riwayat kegiatan dalam bentuk timeline, dibuat dengan kombinasi `<div>`, heading, dan paragraf. Lalu Quotes Section menambahkan kutipan pribadi sebagai penguat identitas. Semua bagian dipisahkan rapi menggunakan layout dan class bawaan Tailwind.  

Terakhir, Contact Section menyediakan tombol email sebagai cara menghubungi pemilik portofolio, sedangkan `<footer>` berisi hak cipta sederhana. Secara keseluruhan, struktur HTML memanfaatkan elemen dasar seperti `<div>` untuk wadah, `<span>` untuk penekanan teks, serta class Tailwind untuk styling seperti warna, ukuran font, bayangan, dan animasi.

---


## 📂 Pertemuan 4
### Analisis halaman galery

Bagian galeri dibangun dengan struktur utamanya berupa sebuah `<section>` dengan id `"gallery"`, di dalamnya ada judul, lalu sebuah `<div>` yang berfungsi sebagai kontainer grid tempat menampung kumpulan `<img>` foto.

Pertama, dari sisi kontainer section galeri, digunakan class `py-20 px-6 md:px-20 bg-white`. Ini berarti section tersebut memiliki padding atas-bawah yang cukup besar (`py-20` setara 5rem), padding kiri-kanan kecil di layar kecil (`px-6` setara 1.5rem) dan lebih lebar di layar medium ke atas (`md:px-20` setara 5rem). Background diberi warna putih (`bg-white`) agar tampil bersih dan netral dibanding section lain yang menggunakan gradasi atau transparansi.

Kedua, judul "Galeri Foto Lucu" menggunakan class `text-3xl font-bold mb-10 text-center text-amber-600`. Class ini memberikan ukuran font besar (`text-3xl`), tebal (`font-bold`), margin bawah (`mb-10`) supaya ada jarak dari grid foto, teks rata tengah (`text-center`), serta pewarnaan oranye-kuning (`text-amber-600`) sehingga menonjol dari background putih.

Selanjutnya, bagian inti dari galeri ada pada `<div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">`. Inilah yang mengatur tata letak grid. Dengan `grid`, kontainer menggunakan CSS Grid. Default-nya hanya ada satu kolom (`grid-cols-1`) sehingga di layar kecil foto tampil satu per baris. Namun, pada layar lebih besar, jumlah kolom bertambah: dua kolom di layar berukuran "small" ke atas (`sm:grid-cols-2`) dan tiga kolom di layar berukuran "medium" ke atas (`md:grid-cols-3`). Spasi antar item diatur dengan `gap-6` yang memberi jarak sekitar 1.5rem antar gambar.

Masing-masing `<img>` memiliki kumpulan class: `rounded-lg border-4 border-[chocolate] opacity-80 hover:opacity-100 hover:scale-105 transition transform`. Pertama, `rounded-lg` membuat sudut gambar membulat sehingga tampil lebih lembut dibandingkan kotak tajam. Lalu `border-4 border-[chocolate]` menambahkan garis tepi tebal dengan warna cokelat, yang memberi konsistensi dengan tema sidebar. Class `opacity-80` menurunkan transparansi default gambar, sehingga terlihat agak pudar. Ketika kursor diarahkan ke gambar, dua efek muncul: `hover:opacity-100` membuat gambar tampil jelas penuh, dan `hover:scale-105` membuat gambar sedikit membesar (zoom-in). Agar transisi ini tidak terasa kasar, class `transition transform` memastikan perubahannya berjalan dengan efek animasi yang halus.

---
## Postingan materi CSS (linkedin) :

https://www.linkedin.com/posts/nabilah-anwar-7ba50832b_css-selektor-activity-7374428824593412097-EOQ0?utm_source=share&utm_medium=member_android&rcm=ACoAAFMw5n4B_KUyskMCO9pfe35f4I6YFjjlifo

---
