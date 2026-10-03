# PROJECT CONTEXT & TIM PRODUKSI WEB DESIGN

## 1. Identitas Tim & Peran
- **Owner / Director:** Digistack Online Tech
- **Klien:** Kurnia Sejahtera (General Contractor Komersial & Residensial)
- **Tech Stack:** HTML5 Semantic, Tailwind CSS (CDN), Vanilla JavaScript ES6, Cloudflare Pages/Workers
- **Workflow / Susunan Tim:**
  1. **UI/UX Architect:** Merancang wireframe, visual tokens, alur konversi, & copywriting.
  2. **Builder (Senior Frontend Developer):** Menulis, merapikan, dan mengeksekusi kode fungsional live.
  3. **Performance Auditor:** Menguji Core Web Vitals, optimasi aset gambar, dan kecepatan load.
  4. **Security Auditor:** Menguji keamanan link eksternal (`rel="noopener"`), sanitasi form, dan privasi kredensial.
  5. **SEO & A11y Auditor:** Menguji semantik HTML5, Schema.org Local SEO, heading hierarchy, alt text, dan aksesibilitas.

---

## 2. Profil Bisnis & Brand Identity Klien
- **Nama Bisnis:** Kurnia Sejahtera Kontraktor
- **Bidang:** General Contractor & Jasa Konstruksi (Komersial, Perhotelan, Ruko, Hunian Mewah, Bangun Baru & Renovasi)
- **Cakupan Wilayah:** D.I. Yogyakarta, Semarang, Jawa Tengah, Jawa Timur, Jawa Barat, Jakarta, hingga Bali.
- **WhatsApp Konsultasi:** `+62 812-1914-0522` (`https://wa.me/6281219140522`)
- **Domain Rencana:** `kurniasejahtera.id` (status: menunggu termin DP klien untuk aktivasi domain)
- **Nilai Unggulan (USP):**
  - SPK Bermaterai & Garansi Pemeliharaan Pasca-Proyek (Retensi).
  - Skema Termin Pembayaran Transparan (30% - 40% - 30%).
  - Pengawasan langsung Mandor Utama di lapangan setiap hari.
  - Material Berstandar SNI (Beton K-250, Besi Ulir SNI, Hollow Galvanis).

---

## 3. Palet Warna & Visual Token (60 - 30 - 10 Rule)
- **60% Dominan (Alabaster / Off-White):**
  - Background bersih: `#FFFFFF`, `#F8FAFC`, `#F1F5F9`, `#E2E8F0`
- **30% Sekunder (Deep Navy & Slate):**
  - Teks & Struktur: `#0F1E36`, `#0A1322`, `#1E293B`
- **10% Aksen (Bronze Gold & Emerald):**
  - Bronze Gold: `#DFBF88`, `#D5AF74`, `#B08D5B`
  - Emerald Green: `#10B981`, `#059669` (Konversi & WhatsApp)

---

## 4. Repositori & Deployment Live
- **GitHub Repository:** [`https://github.com/digistackonline-tech/Kurnia-Sejahtera-Website`](https://github.com/digistackonline-tech/Kurnia-Sejahtera-Website) (Branch: `main`)
- **Hosting / Staging:** Cloudflare Workers / Pages
- **Cloudflare Service:** `kurnia-sejahtera-website` (Auto-deploy setiap ada git push ke `main`)

---

## 5. Struktur Berkas Proyek (`D:\Claude\Project\Digistack Klien\Website Kurnia Sejahtera\`)
```text
├── index.html                  # File landing page utama lengkap & responsif
├── PROJECT-CONTEXT.md          # Dokumen panduan konteks proyek ini
├── sitemap.xml                 # Sitemap XML untuk indexing mesin pencari
├── robots.txt                  # Panduan bot perayap Googlebot / Bing
├── README.md                   # Dokumentasi teknis proyek
└── assets/
    └── images/
        ├── logo-kurnia-sejahtera.jpg
        ├── proyek-1-rumah-tropis-tembalang.jpg
        ├── proyek-2-interior-kitchen-banyumanik.jpg
        ├── proyek-3-fasad-mewah-bsb-city.jpg
        ├── proyek-4-struktur-konstruksi-ungaran.jpg
        ├── proyek-amartya-hotel-jogja.jpg
        ├── proyek-amartya-interior-bathroom.jpg
        ├── proyek-amartya-interior-suite.jpg
        ├── the-amartya/        # 14 foto scaffolding/pengerjaan & 14 foto hasil serah terima
        │   ├── amartya-konstruksi-01.jpg s/d 14.jpg
        │   └── amartya-proyek-01.jpg s/d 14.jpg
        └── kuy-studio/         # 13 foto referensi pengerjaan plafon, scaffolding & studio
            └── studio-proyek-01.jpg s/d 13.jpg
```

---

## 6. Fitur Utama yang Sudah Selesai Dibangun di `index.html`
1. **Navbar Sticky Blur:** Logo monogram, teks nama brand `Kurnia Sejahtera` tanpa batasan kota, menu anchor link, tombol WhatsApp CTA.
2. **Hero Banner Modern (Infinit Architect Style):**
   - Lengkungan pita arsitektur (*curved ribbon*) dengan aksen bronze.
   - 3 floating circle badges berbingkai putih timbul (*Proyek Berjalan, Garansi 100%, SNI Material*).
   - Display typography 2-warna tegas dengan pill button CTA.
   - Dual-slide auto-rotating carousel dengan slider kontrol manual.
3. **Baris Kredibilitas & Statistik:** 4 pilar metrik pencapaian (RAB Transparan, Termin Aman, Nol Biaya Siluman, Mandor Lapangan).
4. **Layanan Unggulan:** 4 kartu layanan interaktif lengkap dengan detail spesifikasi.
5. **Galeri Dokumentasi Proyek (Smooth Horizontal Marquee):**
   - **Baris 1:** Hotel The Amartya Yogyakarta (scaffolding fasad & lobi + suite room & sanitair mewah).
   - **Baris 2:** Kuy Studio & Creative Workspace (scaffolding plafon tinggi, jalur kabel ME, akustik wood grid + studio siap pakai).
   - **Baris 3:** Hunian Mewah & Bangun Baru (pembesian kolom SNI, pengecoran beton K-250 + rumah tropis Tembalang & fasad BSB City).
   - **Interactive Lightbox Modal:** Klik pada gambar memunculkan preview resolusi penuh, detail teknis, dan tombol WhatsApp pre-filled otomatis.
   - **Auto-pause on hover/touch & tombol geser manual `<` dan `>`.**
6. **Alur Kerja 5 Tahap:** Standar operasional transparan dari konsultasi awal hingga masa retensi garansi.
7. **Kalkulator RAB Interaktif:** Perhitungan estimasi biaya per m² berbasis tipe bangunan.
8. **Testimoni Klien & FAQ Interaktif:** Accordion tanya-jawab seputar legalitas, termin, dan garansi.
9. **SEO On-Page & Schema.org:** JSON-LD entity markup `GeneralContractor`, OpenGraph, Twitter Cards, meta viewport mobile-first.

---

## 7. Status & Langkah Selanjutnya (Roadmap)
1. **Menunggu DP Klien:** Untuk proses registrasi domain utama `kurniasejahtera.id` dan setting DNS Cloudflare.
2. **Audit Tim:**
   - **Performance Audit:** Optimasi lazy loading aset foto, evaluasi ukuran webp/jpg.
   - **Security Audit:** Verifikasi tautan eksternal, no-referrer/noopener pada link WA dan maps.
   - **SEO & A11y Audit:** Pengecekan kontras warna teks, rasio heading H1-H3, dan atribut ARIA pada modal.