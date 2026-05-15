# 🌸 Kayuki Japanese Course - LPK Landing Page

Proyek ini adalah portofolio website *landing page* yang dirancang khusus untuk Lembaga Pelatihan Kerja (LPK), lembaga kursus bahasa, atau institusi pendidikan dan yayasan lainnya. Website ini dibangun dengan antarmuka yang modern, bersih, dan berfokus pada konversi pendaftar siswa baru melalui integrasi pendaftaran langsung via WhatsApp.

## ✨ Fitur Utama

* **Desain Responsif:** Tampilan yang optimal di berbagai perangkat (Mobile, Tablet, Desktop) berkat pendekatan *mobile-first* dari Tailwind CSS.
* **Navigasi Lengkap & Sticky Header:** Memudahkan pengguna untuk memindai informasi dengan cepat (Beranda, Tentang Kami, Program, Dokumentasi, Testimoni, Kontak).
* **Katalog Program Interaktif:** Menampilkan kelas/program dengan tombol detail yang akan memunculkan *Modal/Pop-up* berisi deskripsi lengkap.
* **Pendaftaran Terintegrasi WhatsApp:** Formulir pendaftaran dinamis yang secara otomatis merangkai pesan (nama, alamat, program pilihan) dan mengarahkan calon siswa ke WhatsApp Admin secara *seamless*.
* **Animasi & UI Modern:** Menggunakan gradien khusus, *shadow* elemen, efek *hover*, dan tombol *Floating WhatsApp* untuk meningkatkan *User Experience* (UX).

## 🛠️ Teknologi yang Digunakan

* **HTML5:** Struktur dasar halaman yang semantik.
* **Tailwind CSS (via CDN):** *Utility-first framework* untuk *styling* antarmuka yang cepat dan terstandarisasi.
* **Vanilla JavaScript:** Mengatur logika fungsionalitas *smooth scroll*, navigasi *modal pop-up*, manipulasi DOM, dan penanganan *submit* form.
* **FontAwesome:** Penyedia ikon vektor yang relevan.

## 🚀 Panduan Instalasi & Penggunaan

Proyek ini merupakan halaman web statis. Tidak memerlukan instalasi *package* seperti Node.js atau *local server* yang rumit untuk dijalankan.

1.  **Clone repositori ini:**
    ```bash
    git clone https://github.com/username-anda/nama-repo.git
    ```
2.  **Buka folder proyek:**
    ```bash
    cd nama-repo
    ```
3.  **Jalankan aplikasi:**
    Buka file `index.html` langsung di *browser* Anda (Chrome/Firefox/Safari), atau gunakan ekstensi seperti **Live Server** di teks editor (VS Code) untuk *live reload*.

## ⚙️ Panduan Kustomisasi

Untuk menyesuaikan *landing page* ini dengan *branding* lembaga atau yayasan lain:

* **Nomor Kontak WhatsApp:** Cari variabel `const companyWa = "62855555555555";` di dalam tag `<script>` bagian bawah, dan ganti dengan nomor institusi/klien Anda (gunakan kode negara tanpa tanda '+').
* **Skema Warna:** Ganti *class* warna pada komponen Tailwind (misalnya mengganti `text-red-600` atau `bg-red-600` menjadi warna identitas lembaga Anda).
* **Aset Visual:** Ubah tautan *placeholder image* (`https://picsum.photos/...`) dengan *link* foto dokumentasi atau aset grafis yang sebenarnya.

## 💡 Catatan Pengembangan (Integrasi CMS)

Untuk pengembangan lebih lanjut tingkat *production*, struktur HTML dan *class* Tailwind statis ini dapat dengan mudah diadaptasi menjadi tema kustom untuk *Content Management System* (CMS) seperti **WordPress**. Anda dapat memecah struktur ini menjadi blok-blok *Custom Post Type* atau membungkusnya sebagai *widget* kustom Elementor untuk mempermudah klien dalam mengelola program dan memperbarui galeri secara mandiri tanpa harus menyentuh kode.

---
*Dibuat sebagai portofolio pengembangan web.*
