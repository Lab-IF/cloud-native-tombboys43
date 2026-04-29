# 📝 Jawaban — 01. React vs Next.js

| Info | Detail |
|------|--------|
| **Nama** | TOMMY KURNIAWAN |
| **NIM** | 105841121423 |
| **Halaman** | 01. React vs Next.js |
| **Tanggal** | 29 April 2026, 14.18 |

---

## 📝 Kuis Singkat

### 1. Next.js adalah...

**Jawaban:** _Next.js adalah framework berbasis React yang digunakan untuk membangun aplikasi web dengan fitur tambahan seperti server-side rendering (SSR), static site generation (SSG), routing otomatis, dan optimasi performa._

### 2. Mana yang TIDAK perlu di-install manual di Next.js?

**Jawaban:** _Routing (karena sudah otomatis disediakan oleh Next.js)._

### 3. Saat install Next.js, agar menggunakan JavaScript (bukan TypeScript), kita harus pilih...

**Jawaban:** _Pilih No saat ditanya “Use TypeScript?”._

### 4. Apakah komponen React bisa dipakai di Next.js?

**Jawaban:** _Ya, semua komponen React bisa digunakan di Next.js karena Next.js dibangun di atas React._

### 5. Sebutkan minimal 3 fitur yang Next.js berikan di atas React biasa!

**Jawaban:** _1. Routing otomatis berbasis file (file-based routing)
2. Server-Side Rendering (SSR)
3. Static Site Generation (SSG)
4. API Routes (membuat backend sederhana)_

---

## ✏️ Jawaban Latihan

### Latihan 1 — Halaman Utama

_Pada Next.js, halaman utama (homepage) dibuat secara otomatis berdasarkan struktur folder. Jika menggunakan App Router, file app/page.js akan langsung menjadi halaman /. Jika menggunakan Pages Router, file pages/index.js akan menjadi halaman utama.

Hal ini terjadi karena Next.js menggunakan konsep file-based routing, yaitu setiap file di dalam folder tertentu otomatis menjadi sebuah rute (route)._

### Latihan 2 — Halaman About

_Untuk membuat halaman baru seperti halaman About, cukup membuat file baru di dalam folder app/about/page.js atau pages/about.js.

Next.js akan otomatis mengubah nama folder atau file tersebut menjadi URL. Dalam kasus ini, file about akan menjadi alamat /about._

### Latihan 3 — Tantangan: Bandingkan Routing

_erbedaan utama antara routing pada React biasa dan Next.js terletak pada cara pengaturannya.

1. React (React Router)

Pada React, routing tidak tersedia secara bawaan, sehingga harus menggunakan library tambahan seperti react-router-dom. Developer perlu menuliskan konfigurasi routing secara manual, misalnya menentukan path dan komponen yang akan ditampilkan.

Kelebihannya adalah fleksibilitas yang tinggi, namun kekurangannya lebih rumit dan membutuhkan setup tambahan.

2. Next.js

Pada Next.js, routing sudah tersedia secara otomatis tanpa perlu install library tambahan. Sistemnya menggunakan file-based routing, yaitu nama file atau folder langsung menjadi URL.

Sebagai contoh:
app/page.js → /
app/about/page.js → /about

Kelebihannya:
Lebih sederhana
Lebih cepat dalam pengembangan
Minim konfigurasi_
kesimpulannya: Next.js mempermudah pembuatan website karena banyak fitur sudah tersedia secara otomatis, terutama dalam hal routing. Hal ini membuat proses pengembangan menjadi lebih efisien dibandingkan React biasa yang masih memerlukan pengaturan tambahan.
---

## 📊 Ringkasan

| Metrik | Nilai |
|--------|-------|
| Total dijawab | 0 / 8 |
| Skor kuis | 0 / 4 (0%) |
| Latihan terisi | 0 / 3 |

---

_Dibuat otomatis oleh Sistem Kuis Pertemuan 00_
