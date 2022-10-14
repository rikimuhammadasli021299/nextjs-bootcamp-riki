---
title: "Kapan Menggunakan Static Generation v.s. Server-side Rendering"
date: "2020-10-14"
---

Sebaiknya gunakan **Static Generation** (dengan dan tanpa data) bila memungkinkan karena halaman Anda dapat dibuat sekali dan disajikan oleh CDN, yang membuatnya jauh lebih cepat daripada meminta server merender halaman pada setiap permintaan.

Anda dapat menggunakan Static Generation untuk berbagai jenis halaman, termasuk:

- Marketing Pages
- Posting blog
- Daftar produk E-Commerce
- Bantuan dan dokumentasi

Anda harus bertanya pada diri sendiri: "Dapatkah saya melakukan pre-render halaman ini **sebelum** permintaan pengguna?" Jika jawabannya ya, maka Anda harus memilih Static Generation.

Di sisi lain, Static Generation **bukan** ide yang baik jika Anda tidak dapat melakukan pre-render halaman sebelum permintaan pengguna. Mungkin halaman Anda menampilkan data yang sering diperbarui, dan konten halaman berubah pada setiap permintaan.

Dalam hal ini, Anda dapat menggunakan **Server-Side Rendering**. Ini akan lebih lambat, tetapi halaman pre-render akan selalu up-to-date. Atau Anda dapat melewati pre-rendering dan menggunakan JavaScript sisi klien untuk mengisi data.
