# Kurnia Sejahtera — Website Landing Page

Landing page resmi untuk **Kurnia Sejahtera** — General Contractor pelaksana konstruksi fisik bangunan komersial *(hotel, ruko, kantor, klinik medis, studio bisnis)* dan residensial *(rumah tinggal mewah & renovasi bertingkat)*.

- **Homebase:** Banyumanik, Kota Semarang, Jawa Tengah
- **Jangkauan Proyek:** DKI Jakarta / Jabodetabek, Semarang, Jawa Tengah, D.I. Yogyakarta, seluruh Pulau Jawa hingga Pulau Bali
- **Kontak WhatsApp:** `+62 812-1914-0522` (`0812-1914-0522`)
- **Domain Resmi:** `https://kurniasejahtera.id/`

---

## 🏗️ Struktur File & Folder

```
Website Kurnia Sejahtera/
├── index.html                           # Landing page utama (Mobile-First, Tailwind CDN, Schema JSON-LD)
├── robots.txt                           # Aturan crawler Google & link sitemap
├── sitemap.xml                          # Peta situs XML dengan metadata gambar
├── Proposal_Logo_Kurnia_Sejahtera.html  # Halaman katalog & presentasi opsi logo
├── Logo_Opsi_1_Monogram_Arsitektur.jpg  # File aset logo opsi 1
├── Logo_Opsi_2_Pilar_Konstruksi.jpg     # File aset logo opsi 2
├── Logo_Opsi_3_Hexagonal_Shield.jpg     # File aset logo opsi 3
├── assets/
│   └── images/
│       ├── logo-kurnia-sejahtera.jpg    # Logo utama yang aktif di web
│       ├── proyek-*.jpg                 # Dokumentasi riil proyek komersial & residensial
│       ├── clients/                     # Logo resmi klien institusional & komersial
│       │   ├── logo-bank-danamon.png
│       │   ├── logo-fdc-dental-clinic.png
│       │   ├── logo-kuy-studio.png
│       │   ├── kikijaya-logo.png
│       │   └── logo-the-amartya.png
│       └── the-amartya/                 # Galeri proyek Hotel The Amartya Yogyakarta
├── .gitignore
└── README.md
```

---

## ✨ Fitur Unggulan

1. **Mobile-First & App-Like UX:**
   - Sticky Bottom Conversion Bar khusus smartphone dengan proteksi `safe-area-inset-bottom` untuk iPhone dan Android.
   - Tombol sentuhan jari memenuhi standar WCAG (≥ 44×44 px).
   - Filter portofolio interaktif dengan sistem swipe geser samping (*horizontal carousel*).
   - Stepped timeline alur kerja vertikal otomatis saat di layar ponsel.

2. **Skema & Standar Kontrak:**
   - **Termin 30% - 40% - 30%** transparan tanpa biaya tersembunyi.
   - Pengawasan mandor langsung oleh pemilik (*owner-supervised*).
   - Legalitas SPK bermaterai Rp10.000 dengan lampiran jadwal & spesifikasi SNI.

3. **SEO Organik Lokal & Geo-Targeting:**
   - Metadata Geo (`ID-JT`, Semarang coordinates `-7.0543, 110.4285`).
   - Penanaman kata kunci relevan (*"general contractor"*, *"kontraktor komersial"*, *"kontraktor terdekat"*).
   - Structured Data Schema.org (`LocalBusiness` & `OfferCatalog`) valid Google Rich Results.
   - Cakupan wilayah regional: DKI Jakarta, Semarang, D.I. Yogyakarta, Jawa Timur, hingga Bali.

---

## 🚀 Menjalankan Secara Lokal

Buka `index.html` langsung di browser, atau gunakan server statis lokal:

```bash
# Opsi 1: Python
python -m http.server 8000

# Opsi 2: Node.js (npx serve)
npx serve .
```

Akses di browser melalui: `http://localhost:8000`

---

## 📦 Deployment

Project ini merupakan static website murni (tanpa build step / npm dependency). Sangat kompatibel untuk di-deploy secara instan ke:
- **Cloudflare Pages**
- **Vercel**
- **GitHub Pages**
- **cPanel / Hosting Statis**
