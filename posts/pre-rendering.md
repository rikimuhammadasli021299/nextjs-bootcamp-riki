---
title: "Two Forms of Pre-rendering"
date: "2020-10-14"
---

Next.js memiliki dua bentuk pre-rendering: **Static Generation** dan **Server-side Rendering**. Perbedaannya terletak pada **kapan** ini menghasilkan HTML untuk sebuah halaman.

- **Static Generation** adalah metode pre-rendering yang menghasilkan HTML pada **build time**. HTML pre-render kemudian _reused_ pada setiap permintaan.
- **Server-side Rendering** adalah metode pre-rendering yang menghasilkan HTML pada **setiap permintaan**.

Yang penting, Next.js memungkinkan Anda **memilih** formulir pre-rendering mana yang akan digunakan untuk setiap halaman. Anda dapat membuat aplikasi Next.js "hybrid" dengan menggunakan Static Generation untuk sebagian besar halaman dan menggunakan Server-side Rendering untuk halaman lainnya.
