# Work Assignment SE Project

## Overview Assignment
Dalam tugas ini kamu akan diminta untuk membuat pengembangan aplikasi snake
game di sesi Basic Programming sebelumnya dengan framework scrum menggunakan Jira,
dan Github sebagai tempat menyimpan project repository. Kamu juga diminta untuk deploy
hasil aplikasi game snake yang telah di kembangkan ke Github Page menggunakan CI/CD
agar aplikasi bisa diakses oleh public.

## SE-SnakeGame Requirement
- Membuat user story dan child issue pada framework scrum di Jira untuk
menggambarkan tugas yang akan dibuat dalam pengembangan aplikasi snake game
- Membuat wireframe/prototype untuk menggambarkan pengembangan aplikasi snake
game yang akan dibuat
- Ubah character snake yang berbentuk kotak menjadi gambar kepala ular dan badan
ular akan terus memanjang ketika memakan apple
- Buat 2 apple yang bisa dimakan oleh ular
  - Ini akan menambah score ketika ular memakannya
  - Ini akan berpindah ke posisi acak ketika ular memakannya
- Menambahkan 3 nyawa untuk integrasi checkpoint antar level yang di render di kiri
atas canvas (Jika nyawa habis maka game diulang ke level 1)
- Menambahkan 5 level Game Snake yang akan terus meningkat ketika score
bertambah dengan kelipatan 5
  - Rules:
    - Tambahkan dinding penghalang pada setiap level yang berbeda-beda dan
    ketika ular menabrak akan mengurangi nyawa
    - Tambahkan kecepatan snake setiap level bertambah
- Menambahkan ikon nyawa yang bisa dimakan
  - Rules:
    - Ini akan menambah nyawa dan score ketika ular memakannya,
    - Buat warna yang berbeda dengan apple atau buat dia berkedip
    - Buat dia muncul ketika score ular ada di bilangan primer
- Menambahkan sound effect:
  - Sound snake makan apple
  - Sound snake menabrak obstacles atau thorn
  - Sound ketika naik level
  - Sound ketika game over (nyawa habis)
- Tampilkan nilai score dan kecepatan pada layar game snake
  - Pastikan nilainya berubah ketika ada update
- Membuat game snake bisa diakses public menggunakan Github Page
  - Setup dengan CI untuk deploy ke Github Page.

# Material Coverage
- Analysis & Planning
- Agile
- Basic Programming
- Version Control
- Github & CI/CD
