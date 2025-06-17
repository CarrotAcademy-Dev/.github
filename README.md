# Web-Based Management System v1.1 - Carrot Academy

---

## 🚀 Overview

Selamat datang di repository **Web-Based Management System v1.1** Carrot Academy!

Proyek ini adalah **fase awal (MVP - Minimum Viable Product)** dari sistem manajemen internal berbasis web yang akan menjadi **centralized platform** untuk operasional Carrot Academy. Pada versi `v1.1` ini, fokus utama kita adalah membangun **fitur-fitur esensial** yang paling krusial untuk memvalidasi konsep dan mendukung alur kerja dasar.

Kami berkomitmen untuk **iterasi cepat** dan **pengembangan bertahap**. Masukan dan kolaborasi dari seluruh tim akan sangat berharga untuk membentuk sistem ini menjadi solusi yang komprehensif di versi-versi mendatang.

---

## ✨ Fitur Utama (MVP - v1.1)

Berikut adalah daftar fitur utama yang ditargetkan untuk `v1.1`:

* **Manajemen Users**: Registrasi, login, dan dasar-dasar manajemen profil pengguna (admin, staf, dll.).
* **Modul Dashboard Dasar**: Tampilan ringkasan informasi operasional yang relevan.
* **Modul Pencatatan Data**: Fitur dasar untuk input dan view data operasional kunci.

---

## 🛠️ Tech Stack

Sistem ini dikembangkan menggunakan teknologi-teknologi berikut:

* **Frontend**: Vite with React.js, HTML/CSS/JavaScript
* **Backend**: GAS (Google Apps Script) (Temporary)
* **Database**: Spreadsheet (Temporary)
* **Deployment**: Vercel (Temporary)
* **Lain-lain**: Tailwind CSS, Redux.

---

## ⚙️ Getting Started (Untuk Developer)

Ikuti langkah-langkah di bawah ini untuk menjalankan proyek secara lokal:

1.  **Clone Repository:**
    ```bash
    git clone [https://github.com/CarrotAcademy/webdev-v1.1.git](https://github.com/CarrotAcademy/webdev-v1.1.git)
    cd webdev-v1.1
    ```

2.  **Instalasi Dependensi (Frontend):**
    ```bash
    npm install # atau yarn install
    ```

3.  **Konfigurasi Environment Variables:**
    Buat file `.env` dan isi dengan variabel-variabel yang diperlukan. Contoh:
    ```
    # .env (Contoh untuk Backend)
    DATABASE_URL="postgresql://user:password@localhost:5432/mydb"
    PORT=5000
    API_KEY="your_secret_key"
    ```
    *Pastikan untuk tidak mengunggah file `.env` ke Git (`.gitignore` must have `/.env`)*.

6.  **Jalankan Aplikasi:**
    * **Frontend:**
        ```bash
        npm start
        ```

7.  Aplikasi akan berjalan di `http://localhost:3000`

---

## 🤝 Kontribusi

Kami sangat menghargai kontribusi dari setiap anggota tim! Silakan ikuti panduan kontribusi di bawah ini:

1.  **Fork** repository ini.
2.  Buat **branch baru** untuk fitur atau perbaikan (`git checkout -b feature/nama-fitur` atau `bugfix/nama-bugfix`).
3.  Lakukan perubahan dan **commit** (`git commit -m "feat: Menambahkan fitur X"` atau `fix: Memperbaiki bug Y"`). Gunakan [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) untuk pesan commit yang rapi.
4.  **Push** ke branch kamu (`git push origin feature/nama-fitur`).
5.  Buat **Pull Request (PR)** ke branch `main` di repository utama.
6.  Pastikan **PR deskripsi jelas**, mencantumkan *problem*, *solution*, dan **referensi *issue* terkait** (misal: `Closes #123`).

---

## 🗺️ Roadmap

Setelah `v1.1` rilis, kami berencana untuk terus mengembangkan sistem ini. Beberapa fitur yang akan dipertimbangkan untuk versi mendatang antara lain:

* Integrasi ...
* Modul ...
* Peningkatan performa dan skalabilitas.
* *Ini akan di-update secara berkala sesuai kebutuhan dan feedback.*

---

## 📧 Kontak

Jika ada pertanyaan atau butuh bantuan lebih lanjut, silakan hubungi:

* Tim Developer Carrot Academy
* system@carrotacademy.com

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah Carrot Academy
