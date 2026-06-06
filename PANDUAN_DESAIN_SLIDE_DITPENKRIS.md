# PANDUAN DESAIN SLIDE — DIREKTORI DATA DAN INFORMASI
## Direktorat Pendidikan Kristen, Ditjen Bimas Kristen Kemenag RI
### Versi Referensi: TW 2 Tahun 2026

---

## DAFTAR ISI
1. [Identitas Visual Global](#1-identitas-visual-global)
2. [Struktur File Gambar & Repository](#2-struktur-file-gambar--repository)
3. [Komponen Tetap (Recurring Components)](#3-komponen-tetap-recurring-components)
4. [SLIDE 01 — Cover / Halaman Judul](#4-slide-01--cover--halaman-judul)
5. [SLIDE 02 — Section Divider (Bagian N)](#5-slide-02--section-divider-bagian-n)
6. [SLIDE 03 — Data Chart: Line Chart + Narasi (Kanan)](#6-slide-03--data-chart-line-chart--narasi-kanan)
7. [SLIDE 04 — Data Chart: Line Chart + Narasi (Kiri Bawah)](#7-slide-04--data-chart-line-chart--narasi-kiri-bawah)
8. [SLIDE 05 — Data Chart: Bar Chart + Narasi (Kiri) + Callout Badge](#8-slide-05--data-chart-bar-chart--narasi-kiri--callout-badge)
9. [SLIDE 06 — Data Chart: Horizontal Bar Chart + Narasi (Kiri)](#9-slide-06--data-chart-horizontal-bar-chart--narasi-kiri)
10. [SLIDE 07 — Statistik Utama (2 Panel) + Chart Kecil + Foto Dekoratif](#10-slide-07--statistik-utama-2-panel--chart-kecil--foto-dekoratif)
11. [SLIDE 08 — Data Jabatan: 2 Kolom Chart + Foto Polaroid + Highlight Number](#11-slide-08--data-jabatan-2-kolom-chart--foto-polaroid--highlight-number)
12. [SLIDE 09 — Data Jabatan: 2 Kolom Chart + Foto Cutout + Highlight Number](#12-slide-09--data-jabatan-2-kolom-chart--foto-cutout--highlight-number)
13. [SLIDE 10 — Data Table + KPI Card + Foto Cutout](#13-slide-10--data-table--kpi-card--foto-cutout)
14. [SLIDE 11 — Data Split: 2 Sub-Kelompok Bar Chart + Narasi Bawah](#14-slide-11--data-split-2-sub-kelompok-bar-chart--narasi-bawah)
15. [SLIDE 12 — Data Sebaran: Dual Horizontal Bar Chart Full Width + Peta Background](#15-slide-12--data-sebaran-dual-horizontal-bar-chart-full-width--peta-background)
16. [SLIDE 13 — Data Akreditasi: 2 Baris Panel (Foto Hexagon + Arrow + Number + Chart)](#16-slide-13--data-akreditasi-2-baris-panel-foto-hexagon--arrow--number--chart)
17. [SLIDE 14 — Data Siswa: Bar Chart (Kiri) + Donut Chart (Kanan) + Callout Label](#17-slide-14--data-siswa-bar-chart-kiri--donut-chart-kanan--callout-label)
18. [SLIDE 15 — Data Guru: Bar Chart Tengah + Narasi Bawah dalam Box](#18-slide-15--data-guru-bar-chart-tengah--narasi-bawah-dalam-box)
19. [SLIDE 16 — Data ANBK: KPI Card + Narasi + Tabel](#19-slide-16--data-anbk-kpi-card--narasi--tabel)
20. [SLIDE 17 — Data Pertumbuhan: 2 Kolom (Foto + Bar Chart + Callout Target)](#20-slide-17--data-pertumbuhan-2-kolom-foto--bar-chart--callout-target)
21. [SLIDE 18 — Data Tenaga: 2 Panel (Narasi + Chart) + Background Hijau Full](#21-slide-18--data-tenaga-2-panel-narasi--chart--background-hijau-full)
22. [SLIDE 35 — Penutup / Closing](#22-slide-35--penutup--closing)
23. [Pola Desain Tambahan & Varian](#23-pola-desain-tambahan--varian)
24. [Panduan Reproduksi Slide Baru](#24-panduan-reproduksi-slide-baru)

---

## 1. IDENTITAS VISUAL GLOBAL

### 1.1 Dimensi Kanvas
| Parameter | Nilai |
|---|---|
| Ukuran | 1440 × 810 px (16:9 widescreen) |
| Resolusi | 96 DPI (screen) / 150 DPI (print) |
| Orientasi | Landscape |
| Tool Sumber | Canva |

### 1.2 Palet Warna Utama
| Nama Warna | Hex | Penggunaan |
|---|---|---|
| Hijau Tua (Primary) | `#1B4D2E` | Judul, background section, footer kiri |
| Hijau Sedang | `#2E7D32` | Grafik PTKKN/SMTK, aksen, ikon |
| Hijau Muda | `#4CAF50` | Grafik PTKKS/SMAK, chart bar alternating |
| Hijau Pastel | `#A5C8A5` | Background accent ringan |
| Kuning Emas (Accent 1) | `#F5B800` | Footer strip, garis dekoratif, chevron |
| Kuning Muda (Accent 2) | `#FDD835` | Grafik PTKKS alternating, callout |
| Abu-abu Terang (BG) | `#F2F2F2` / `#EDEDED` | Background canvas utama |
| Putih | `#FFFFFF` | Card, panel, teks di area gelap |
| Hitam Lembut | `#1A1A1A` / `#222222` | Teks body |
| Hijau Box Narasi | `#2E5E30` | Box narasi analitik |
| Hijau Tua Solid | `#1B4D2E` | Footer kiri, section header |

### 1.3 Tipografi
| Elemen | Font | Weight | Ukuran (approx) | Warna |
|---|---|---|---|---|
| Judul Slide (Title) | Montserrat | Bold (700) | 36–52 px | Hijau Tua `#1B4D2E` |
| Sub-judul (Subtitle) | Montserrat | Regular (400) | 24–32 px | Hijau Tua |
| Kata Kunci Bold dalam Judul | Montserrat | Bold (700) | sama dengan judul | Hitam `#222222` |
| Angka Statistik Utama | Montserrat | Bold (700) | 56–80 px | Hijau Tua / Kuning |
| Label Statistik | Montserrat | Regular (400) | 16–20 px | Hitam / Abu |
| Teks Narasi Body | Montserrat | Regular (400) | 13–16 px | Hitam / Putih |
| Teks Bold dalam Narasi | Montserrat | Bold (700) | sama dengan narasi | Hitam / Putih |
| Label Chart (Axis) | Montserrat | Regular (400) | 11–13 px | Hitam |
| Nilai Data pada Chart | Montserrat | Bold (700) | 12–14 px | Hitam / Putih |
| Label Footer | Montserrat | Regular (400) | 14–16 px | Putih |
| Label "Penyusun" | Montserrat | Bold (700) + Regular | 13 px | Putih |
| Sumber Data | Montserrat | Italic (400) | 13–15 px | Putih / Hitam |
| Teks Callout Badge | Montserrat | Bold (700) | 16–22 px | Putih / Hijau Tua |

> **Catatan:** Seluruh tipografi menggunakan **Montserrat** (Google Fonts). Tidak ada font kedua. Variasi melalui weight: Regular, Bold, Italic.

### 1.4 Gaya Visual Keseluruhan
- **Nature-inspired / Edu-Green**: motif daun, tanaman, padang rumput hijau, pohon.
- **Photo-collage style**: foto manusia dan gedung di-cutout (background dihapus) dan diletakkan melayang di atas elemen lain.
- **Data-driven infographic**: grafik dominan, dilengkapi narasi analitik.
- **Semi-flat design** dengan depth dari bayangan ringan dan foto overlap.

---

## 2. STRUKTUR FILE GAMBAR & REPOSITORY

### 2.1 Struktur Folder
```
/assets/
├── logos/
│   ├── logo_kemenag.png              ← Logo Kemenag RI (lambang Garuda + buku)
│   ├── logo_kemenag_berdampak.png    ← Logo "Kemenag Berdampak" (grafik biru-oranye)
│   └── logo_pusaka.png               ← Logo "Pusaka" (ikon tangan-daun, biru)
├── backgrounds/
│   ├── bg_cover_gedung_kemenag.jpg   ← Foto gedung Kemenag RI malam hari (cover/penutup)
│   ├── bg_padang_rumput_hijau.png    ← Padang rumput hijau (section divider)
│   ├── bg_tanah_tanam.png            ← Rumput + tanah (digunakan di beberapa slide data)
│   └── bg_peta_indonesia_dots.png    ← Peta Indonesia titik-titik abu (slide sebaran)
├── decorative/
│   ├── dec_angin_spiral_biru.png     ← Ilustrasi angin spiral/wave biru (cover)
│   ├── dec_daun_hijau_01.png         ← Daun hijau melayang kiri atas
│   ├── dec_daun_hijau_02.png         ← Daun hijau melayang kanan bawah
│   ├── dec_daun_hijau_03.png         ← Daun hijau melayang kiri bawah
│   ├── dec_daun_kuning_kanan.png     ← Gradasi kuning-hijau pojok kanan (cover)
│   ├── dec_tanaman_tumbuh_01.png     ← Ilustrasi bibit/tanaman kecil tumbuh
│   ├── dec_tanaman_tumbuh_02.png     ← Tanaman lebih besar dengan tanah
│   ├── dec_pohon_hijau.png           ← Pohon hijau berdiri (section divider)
│   ├── dec_pita_emas.png             ← Pita/ribbon emas dekoratif (slide negeri)
│   ├── dec_chevron_kuning_besar.png  ← Chevron / panah ganda kuning besar
│   ├── dec_panah_naik_hijau.png      ← Ikon panah naik (growth indicator)
│   ├── dec_panah_diagonal_hijau.png  ← Panah diagonal kanan-atas (growth indicator)
│   ├── dec_koin_rp_01.png            ← Ikon koin Rp emas (slide sertifikasi)
│   ├── dec_koin_rp_02.png            ← Variasi koin Rp lebih besar
│   ├── dec_bintang_sparkle.png       ← Bintang kecil / sparkle kuning
│   ├── dec_burung_terbang.png        ← Siluet burung terbang (slide dosen)
│   ├── dec_kertas_terbang.png        ← Ilustrasi pesawat kertas (slide sebaran)
│   ├── dec_confetti_emas.png         ← Confetti emas jatuh (slide guru)
│   ├── dec_kurva_emas_ribbon.png     ← Ribbon/kurva emas lengkung (slide negeri)
│   ├── dec_robekan_kertas_putih.png  ← Efek robekan/torn paper atas (slide tenaga)
│   ├── dec_tanda_panah_spiral.png    ← Tanda panah hitam spiral (slide jabatan)
│   └── dec_target_lingkaran.png      ← Ikon target/crosshair hijau (slide pertumbuhan)
├── illustrations/
│   ├── ill_gedung_sekolah_dasar.png  ← Ilustrasi gedung sekolah warna-warni
│   ├── ill_gedung_kampus_hijau.png   ← Ilustrasi gedung kampus isometric hijau
│   ├── ill_magnifier_3d.png          ← Ilustrasi kaca pembesar 3D kuning-oranye
│   ├── ill_sertifikat_3d.png         ← Ilustrasi sertifikat/piagam 3D dengan tanaman
│   ├── ill_ikon_dosen_01.png         ← Ikon karakter dosen (jabatan) — Asisten Ahli
│   ├── ill_ikon_dosen_02.png         ← Ikon karakter dosen (jabatan) — Lektor
│   ├── ill_ikon_dosen_03.png         ← Ikon karakter dosen (jabatan) — Lektor Kepala
│   ├── ill_ikon_dosen_04.png         ← Ikon karakter dosen (jabatan) — Guru Besar
│   ├── ill_ikon_gedung_sdtk.png      ← Ilustrasi gedung SDTK (merah-atap segitiga)
│   ├── ill_ikon_gedung_smptk.png     ← Ilustrasi gedung SMPTK (biru modern)
│   ├── ill_ikon_sekolah_kuning.png   ← Ilustrasi sekolah kecil kuning-hijau (SMTK/SMAK)
│   ├── ill_grafik_pertumbuhan_3d.png ← Ikon grafik batang naik 3D (growth box)
│   └── ill_karakter_cs_3d.png        ← Karakter 3D petugas (headset, laptop)
├── photos/
│   ├── photo_mahasiswi_cutout.jpg    ← Foto mahasiswi (cutout, tas, tersenyum)
│   ├── photo_wisudawan_group.jpg     ← Foto kelompok wisudawan toga (cutout)
│   ├── photo_dosen_mengajar.jpg      ← Foto dosen pria mengajar (cutout)
│   ├── photo_dosen_wanita_kerja.jpg  ← Foto dosen/profesional wanita (cutout)
│   ├── photo_siswa_sma_pria.jpg      ← Foto siswa SMA pria medali (cutout)
│   ├── photo_siswa_sma_wanita.jpg    ← Foto siswa SMA wanita medali (cutout)
│   ├── photo_siswa_sd_group.jpg      ← Foto anak SD group ceria (cutout)
│   ├── photo_siswa_smp_pria.jpg      ← Foto siswa SMP pria tas (cutout)
│   ├── photo_siswa_sma_pria_kacamata.jpg ← Foto siswa SMA kacamata biru (cutout)
│   ├── photo_guru_wanita_batik.jpg   ← Foto guru wanita batik biru (cutout)
│   ├── photo_asn_pria_tablet.jpg     ← Foto ASN pria + tablet (cutout)
│   ├── photo_pria_profesional_buku.jpg ← Foto pria profesional buku (cutout)
│   ├── photo_wanita_hitam_tablet.jpg ← Foto wanita profesional hitam + tablet (cutout)
│   ├── photo_siswa_sd_wisuda.jpg     ← Foto siswa topi wisuda (cutout, slide SD)
│   ├── photo_foto_kelas_guru.jpg     ← Foto interior kelas + guru (persegi)
│   ├── photo_perpustakaan.jpg        ← Foto interior perpustakaan (persegi)
│   ├── photo_ruang_komputer.jpg      ← Foto ruang komputer/lab (persegi)
│   ├── photo_kampus_gedung.jpg       ← Foto eksterior gedung kampus (persegi)
│   ├── photo_gedung_sekolah_ntt.jpg  ← Foto gedung sekolah NTT (persegi, sebaran)
│   ├── photo_gedung_sdtk_real.jpg    ← Foto gedung SDTK nyata (slide SDTK)
│   ├── photo_gedung_smptk_real.jpg   ← Foto gedung SMPTK nyata (slide SMPTK)
│   └── photo_siswa_anbk.jpg          ← Foto siswa mengerjakan ANBK (cutout kanan)
└── backgrounds_slide/
    ├── bg_green_full_solid.png       ← Background hijau tua solid (slide tenaga)
    └── bg_dotted_dark_green.png      ← Background titik-titik hijau tua (slide jabatan 08)
```

### 2.2 Konvensi Penamaan
- **`logo_`** = logo institusi/program
- **`bg_`** = background layer (full-slide)
- **`dec_`** = elemen dekoratif (tidak mengandung teks)
- **`ill_`** = ilustrasi vektor/3D
- **`photo_`** = foto manusia atau bangunan nyata

---

## 3. KOMPONEN TETAP (RECURRING COMPONENTS)

Komponen berikut muncul di hampir setiap slide dan harus dibuat konsisten.

### 3.1 Header Logo Bar
**Posisi:** Top-left, ± Y: 20–35px dari atas, X: 30–40px dari kiri  
**Urutan komponen (kiri → kanan):**
1. `logo_kemenag.png` — lebar ≈ 55px, rasio dijaga
2. `logo_kemenag_berdampak.png` — lebar ≈ 120px
3. `logo_pusaka.png` — lebar ≈ 65px
- Jarak antar logo: ≈ 10–15px
- Logo tidak memiliki background tambahan, langsung di atas bg slide

### 3.2 Footer Bar
**Posisi:** Bottom of slide, full-width  
**Tinggi total:** ≈ 52–58px  
**Struktur layering footer (bawah ke atas):**

| Layer | Warna | Posisi | Konten |
|---|---|---|---|
| Layer 1 (paling bawah) | Hijau Tua `#1B4D2E` | Full width, H ≈ 40px | Teks "Subdirektorat X" atau "Ditjen Bimas Kristen Kemenag RI" |
| Layer 2 (di atas hijau) | Kuning Emas `#F5B800` | Full width, H ≈ 8px, tepat di atas layer 1 | Garis strip kuning pembatas |
| Layer 3 (kanan) | Kuning Emas, diagonal | Pojok kanan, segitiga overlap | Aksen segitiga / diagonal kuning |

**Teks Footer Kiri:** `Montserrat Regular 14–16px Putih`  
**Teks Footer Kanan (jika ada):** "Penyusun: [Nama]" → `Montserrat Bold + Regular 13px Putih`

### 3.3 Garis Pembatas Sumber Data (Source Line)
**Posisi:** Di atas footer, biasanya Y: ≈ 720–740px  
**Elemen:**
- Kotak/pill rounded hijau tua: berisi teks "Sumber: [NAMA], *cutoff* [Tanggal]"
  - Warna bg: `#1B4D2E` atau `#2E5E30`
  - Teks: `Montserrat Regular 13–14px Italic Putih`
  - Border radius: ≈ 8px
- Garis horizontal tipis di bawah/samping kotak sumber: warna Hijau Tua, tebal ≈ 2px
- Ikon panah diagonal `dec_panah_diagonal_hijau.png` di pojok kanan bawah (growth indicator)

### 3.4 Background Canvas
- **Default:** Warna `#F2F2F2` (abu sangat terang / off-white)
- **Alternatif slide gelap:** Hijau tua solid `#1B4D2E`

---

## 4. SLIDE 01 — COVER / HALAMAN JUDUL

**Template Type:** Cover  
**Nomor Slide:** 1 (dan direplikasi sebagai slide 35 untuk penutup)

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | Warna `#F2F2F2` | Full slide |
| 2 | **BG Kiri — Kotak Hijau** | Shape persegi panjang, warna `#2E7D32` | Kiri, X:0 Y:0, W≈560px H≈720px, pojok kanan atas rounded |
| 3 | **Foto Gedung Kemenag** | `bg_cover_gedung_kemenag.jpg` | Di dalam / overlap kotak hijau, W≈520px, tengah kotak |
| 4 | **Dekorasi Angin Spiral** | `dec_angin_spiral_biru.png` | Tengah-kanan kotak hijau, overlap ke area kanan, W≈580px |
| 5 | **Dekorasi Daun Kiri Atas** | `dec_daun_hijau_01.png` | X≈80px Y≈10px, W≈100px, rotasi ≈-20° |
| 6 | **Dekorasi Daun Kiri Bawah** | `dec_daun_hijau_03.png` | X≈10px Y≈650px, W≈140px |
| 7 | **Dekorasi Kuning-Hijau Kanan** | `dec_daun_kuning_kanan.png` | Pojok kanan, X≈1350px Y≈280px, W≈120px |
| 8 | **Logo Bar** | Lihat §3.1 | Top-right: X≈700px Y≈310px (cover: logo di kanan atas area teks) |
| 9 | **Judul Besar** | Text | Kanan tengah, X≈700px Y≈400px |
| 10 | **Sub-judul** | Text | Di bawah judul, X≈700px Y≈520px |
| 11 | **Footer Bar** | Lihat §3.2 | Bottom |

**Khusus Cover:** Logo bar diletakkan di sisi KANAN (bukan top-left), di atas teks judul.

### Hierarki Teks Cover
```
[Logo Kemenag] [Logo Kemenag Berdampak] [Logo Pusaka]

[JUDUL UTAMA]          ← Montserrat Bold 52px, Hijau Tua #1B4D2E
[Sub-judul baris 2]

[Keterangan/Sub-keterangan]  ← Montserrat Regular 28px, Hijau Tua
[Baris keterangan 2]
```

### Komponen Spesifik Cover
- **Kotak Hijau Kiri:** Shape dengan `border-radius` ≈ 30px di pojok kanan atas dan kanan bawah
- **Foto Gedung:** Overlay gelap 20% untuk depth
- **Angin Spiral:** Z-index di atas foto gedung, semi-transparent pojok kanan
- **Footer Cover:** Teks "Ditjen Bimas Kristen Kemenag RI" (bukan nama subdirektorat)

---

## 5. SLIDE 02 — SECTION DIVIDER (BAGIAN N)

**Template Type:** Section Separator  
**Contoh:** "Bagian 1 – Subdirektorat Pendidikan Tinggi", "Bagian 2 – …", "Bagian 3 – …"

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | Warna `#F2F2F2` | Full slide |
| 2 | **Padang Rumput** | `bg_padang_rumput_hijau.png` | Bottom half, Y≈500px, full width, H≈310px |
| 3 | **Foto Gedung Sekolah** | `photo_gedung_sekolah_ntt.jpg` (atau sesuai bagian) | Kiri bawah, X≈0 Y≈400px, W≈500px |
| 4 | **Pohon Hijau** | `dec_pohon_hijau.png` | Tengah kiri, X≈430px Y≈330px, W≈160px |
| 5 | **Foto-foto Kolase (kanan)** | 3 foto disusun diagonal: `photo_foto_kelas_guru.jpg`, `photo_perpustakaan.jpg`, `photo_ruang_komputer.jpg` | Kanan, X≈750–1400px, overlap berurutan |
| 6 | **Foto Cutout Utama** | `photo_mahasiswi_cutout.jpg` (atau sesuai bagian) | Tengah kanan, X≈680px Y≈100px, H≈680px |
| 7 | **Logo Bar** | Lihat §3.1 | Top-left |
| 8 | **Teks "Bagian N"** | Text | Kiri tengah, X≈80px Y≈290px |
| 9 | **Teks Nama Subdirektorat** | Text | Di bawah "Bagian N", X≈80px Y≈360px |
| 10 | **Garis Biru Dekoratif** | Shape horizontal tipis, warna `#4A90D9` | Di antara foto kolase dan footer, W≈600px |
| 11 | **Footer Bar** | Lihat §3.2 | Bottom — Kiri: nama subdirektorat, Kanan: "Penyusun: [Nama]" |

### Hierarki Teks Section Divider
```
Bagian [N]             ← Montserrat Bold 48px, Hijau Tua #1B4D2E
Subdirektorat          ← Montserrat Regular 44px, Hijau Tua
Pendidikan             ← (baris lanjutan)
[Nama Jenjang]         ← (baris lanjutan)
```

### Layout Foto Kolase Kanan (3 foto)
- Foto 1 (paling kiri): sedikit di belakang, rotasi ≈ -3°
- Foto 2 (tengah): overlap foto 1 di depan, tanpa rotasi
- Foto 3 (paling kanan): overlap foto 2 di depan, rotasi ≈ +3°
- Semua foto: `border-radius` ≈ 0, style "polaroid datar" tanpa bingkai

---

## 6. SLIDE 03 — DATA CHART: LINE CHART + NARASI (KANAN)

**Template Type:** Data Infographic — Line Chart Kiri + Narasi + Foto Dekoratif Kanan  
**Contoh:** Data PTKK Swasta 2020–2025

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` | Full slide |
| 2 | **Foto Gedung Background** | `photo_kampus_gedung.jpg` | Bottom, full width, H≈250px, opacity ≈ 70% |
| 3 | **Overlay Gradasi** | Gradient putih-ke-transparan | Atas foto, H≈100px, agar teks terbaca |
| 4 | **Dekorasi Daun Kiri** | `dec_daun_hijau_01.png` | X≈30px Y≈160px, W≈80px |
| 5 | **Dekorasi Tanaman Kanan** | `dec_tanaman_tumbuh_01.png` | Top-right, X≈1200px Y≈0px, W≈300px |
| 6 | **Line Chart** | Chart komponen | Kiri-tengah, X≈80px Y≈220px, W≈600px H≈380px |
| 7 | **Box Narasi Analitik** | Shape rounded rectangle, bg `#2E5E30` | Kanan, X≈780px Y≈300px, W≈450px H≈280px, border-radius 16px |
| 8 | **Teks dalam Box Narasi** | Text Putih | Di dalam box narasi |
| 9 | **Logo Bar** | §3.1 | Top-left |
| 10 | **Judul Slide** | Text | Kiri atas, X≈80px Y≈100px |
| 11 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

### Line Chart Spesifikasi
- **Tipe:** Line chart tunggal
- **Warna garis:** Hijau Tua `#1B4D2E`, tebal 3px
- **Data point:** Lingkaran solid warna sama, radius 6px
- **Label nilai:** Di atas titik, Montserrat Bold 13px, hitam
- **Axis X:** Tahun (2020–2025)
- **Axis Y:** Jumlah, gridlines horizontal abu tipis
- **Background chart:** Transparan (mengambil bg canvas)

### Box Narasi Analitik
- **Background:** `#2E5E30` (hijau tua agak gelap)
- **Border-radius:** 16px
- **Padding:** 24px
- **Teks:** Montserrat Regular 13px Putih
- **Bold di dalam narasi:** Montserrat Bold 13px Putih
- **Tidak ada ikon di dalam box**

---

## 7. SLIDE 04 — DATA CHART: LINE CHART + NARASI (KIRI BAWAH)

**Template Type:** Data Infographic — Foto Cutout Kiri + Line Chart Kanan + Narasi Bawah Gelap  
**Contoh:** Data PTKK Negeri 2020–2025

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` → bawah menjadi kuning terang | Full slide |
| 2 | **Dekorasi Ribbon Emas** | `dec_kurva_emas_ribbon.png` | Top-right, X≈1100px Y≈0, W≈360px |
| 3 | **Foto Cutout Wisudawan** | `photo_wisudawan_group.jpg` | Kiri tengah, X≈0px Y≈80px, H≈620px |
| 4 | **Line Chart** | Chart komponen | Kanan, X≈700px Y≈150px, W≈620px H≈360px |
| 5 | **Box Narasi Bawah** | Shape rectangle, bg `#2E5E30` | Bottom strip, Y≈590px, full width kanan, H≈160px |
| 6 | **Teks Narasi** | Text Putih dalam box | Di dalam box narasi |
| 7 | **Chevron / Panah Naik Hijau** | `dec_panah_naik_hijau.png` | Pojok kanan box narasi, X≈1310px Y≈610px, W≈100px |
| 8 | **Logo Bar** | §3.1 | Top-left |
| 9 | **Judul Slide** | Text | Top-right area, X≈700px Y≈110px, rata kanan |
| 10 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

### Perbedaan dengan Slide 03
- Narasi di **bawah** (full-width strip), bukan kotak terpisah di kanan
- Foto cutout di **kiri**
- Judul rata **kanan**
- Dekorasi ribbon emas di pojok kanan atas

---

## 8. SLIDE 05 — DATA CHART: BAR CHART + NARASI (KIRI) + CALLOUT BADGE

**Template Type:** Data Infographic — Narasi Kiri + Bar Chart Kanan (di dalam frame laptop/monitor) + Badge  
**Contoh:** Data Akreditasi Program Studi PTKK 2020–2025

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` | Full slide |
| 2 | **Gradasi Pastel Kanan** | Gradient oranye/yellow terang | Bottom-right, W≈400px |
| 3 | **Foto Laptop/Monitor** | `photo_laptop_mockup.jpg` atau ilustrasi | Kanan, X≈700px Y≈100px, H≈500px |
| 4 | **Bar Chart** | Chart komponen | Di dalam frame laptop, X≈750px Y≈150px |
| 5 | **Badge Callout "Tidak Terakreditasi"** | Shape bubble/speech, bg hijau `#7CB37E` | Top-right, X≈1100px Y≈30px, W≈260px |
| 6 | **Angka dalam Badge** | Text | Di dalam badge |
| 7 | **Foto Tangan + Ijazah** | `photo_tangan_ijazah_cutout.jpg` | Kiri-tengah, X≈350px Y≈200px, H≈400px |
| 8 | **Teks Narasi** | Text hitam | Kiri, X≈80px Y≈250px |
| 9 | **Logo Bar** | §3.1 | Top-left |
| 10 | **Judul Slide** | Text | Kiri atas, X≈80px Y≈90px |
| 11 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

### Badge Callout Spesifikasi
- **Shape:** Rounded rectangle dengan ekor (speech bubble ke bawah) atau ellipse
- **Background:** Hijau pastel `#7CB37E`
- **Teks baris 1:** "Tidak Terakreditasi" — Montserrat Bold 16px Putih
- **Angka besar:** Montserrat Bold 56px Putih (contoh: "308")

### Bar Chart dalam Frame
- **Tipe:** Vertical bar chart (kolom)
- **Warna bar:** Gradasi Hijau Tua → Hijau Muda → Biru Muda (menunjukkan tren waktu)
- **Label nilai:** Di atas bar, Bold 13px
- **Axis X:** Tahun (2020–2025)
- **Axis Y:** Jumlah prodi
- **Judul dalam frame:** "Prodi Terakreditasi" — Montserrat Regular 16px

---

## 9. SLIDE 06 — DATA CHART: HORIZONTAL BAR CHART + NARASI (KIRI)

**Template Type:** Data Infographic — Narasi Kiri + Horizontal Bar Chart Tengah + Foto Kanan  
**Contoh:** Data Dosen PTKK 2020–2026

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` | Full slide |
| 2 | **Padang Rumput Bawah** | `bg_tanah_tanam.png` | Bottom, Y≈580px, H≈230px |
| 3 | **Foto Kampus Bawah** | `photo_kampus_gedung.jpg` | Bottom-left, opacity 80% |
| 4 | **Dekorasi Burung Terbang** | `dec_burung_terbang.png` | Top-right, X≈950px Y≈20px, W≈250px |
| 5 | **Foto Dosen Mengajar (Kanan)** | `photo_dosen_mengajar.jpg` | Kanan, X≈1100px Y≈100px, H≈450px |
| 6 | **Foto Kelas (Kanan dalam kotak)** | `photo_foto_kelas_guru.jpg` | Top-right, X≈1050px Y≈80px, W≈280px H≈180px, rounded |
| 7 | **Horizontal Bar Chart** | Chart komponen | Tengah, X≈470px Y≈240px, W≈580px H≈330px |
| 8 | **Teks Narasi** | Text hitam | Kiri, X≈80px Y≈270px, W≈350px |
| 9 | **Foto Mahasiswa Group** | `photo_mahasiswi_cutout.jpg` | Kiri bawah, X≈130px Y≈450px, H≈300px |
| 10 | **Logo Bar** | §3.1 | Top-left |
| 11 | **Judul Slide** | Text | Top-left, X≈80px Y≈95px |
| 12 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

### Horizontal Bar Chart Spesifikasi
- **Tipe:** Horizontal bar chart
- **Warna bar:** Hijau Tua (2020–2023) → Biru Muda (2024–2025) — menunjukkan periode berbeda
- **Label nilai:** Di dalam atau di ujung bar, Montserrat Bold 14px Putih/Hitam
- **Axis Y:** Tahun (2020–2025), label kiri
- **Axis X:** Angka jumlah dosen, gridlines vertikal abu

---

## 10. SLIDE 07 — STATISTIK UTAMA (2 PANEL) + CHART KECIL + FOTO DEKORATIF

**Template Type:** KPI + Detail Chart — Foto Sertifikasi Kiri + 2 Panel Stat + Mini Bar Chart  
**Contoh:** Data Sertifikasi Dosen

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` | Full slide |
| 2 | **Foto Sertifikat 3D** | `ill_sertifikat_3d.png` | Kiri-tengah, X≈30px Y≈120px, H≈500px |
| 3 | **Dekorasi Koin Rp 01** | `dec_koin_rp_01.png` | X≈300px Y≈140px, W≈80px |
| 4 | **Dekorasi Koin Rp 02** | `dec_koin_rp_02.png` | X≈430px Y≈80px, W≈60px |
| 5 | **Dekorasi Koin Rp kecil** | `dec_koin_rp_01.png` (kecil) | X≈60px Y≈650px, W≈70px |
| 6 | **Box Stat "Sudah"** | Shape white rounded rect | Tengah, X≈560px Y≈260px, W≈300px H≈200px, shadow |
| 7 | **Box Stat "Belum"** | Shape white rounded rect | Kanan box, X≈880px Y≈260px, W≈300px H≈200px, shadow |
| 8 | **Chevron Pemisah** | `dec_chevron_kuning_besar.png` | Antara 2 box, X≈830px Y≈320px, W≈80px |
| 9 | **Teks dalam Box Stat** | Text | Di dalam masing-masing box |
| 10 | **Foto Wanita Profesional** | `photo_wanita_hitam_tablet.jpg` | Kanan, X≈1220px Y≈200px, H≈450px |
| 11 | **Mini Bar Chart (PTKKN+PTKKS)** | Chart komponen | Bottom-center, X≈500px Y≈500px, W≈750px H≈220px |
| 12 | **Legend Chart** | Dots + teks hijau/kuning | Di atas chart, X≈520px Y≈490px |
| 13 | **Kotak Sumber** | §3.3 | Kiri bawah, X≈40px Y≈640px |
| 14 | **Logo Bar** | §3.1 | Top-left |
| 15 | **Judul Slide (Area Kanan Atas)** | Text rata kanan | X≈560px Y≈120px, W≈700px, rata tengah/kanan |
| 16 | **Footer** | §3.2 | Bottom |

### Box Statistik Spesifikasi
```
┌─────────────────────┐  ┌─────────────────────┐
│  Sudah              │  │  Belum              │
│                     │  │                     │
│  1,635              │  │  4,782              │
│  Dosen              │  │  Dosen              │
└─────────────────────┘  └─────────────────────┘
```
- **Label atas** ("Sudah"/"Belum"): Montserrat Bold 22px, Hijau Tua / Hitam
- **Angka utama:** Montserrat Bold 56px, Hijau Tua `#1B4D2E`
- **Sub-label** ("Dosen"): Montserrat Regular 18px, Abu-abu
- **Border-radius:** 16px
- **Shadow:** `0 4px 12px rgba(0,0,0,0.12)`

### Mini Bar Chart Spesifikasi
- **Tipe:** Grouped vertical bar (2 series: PTKKN hijau, PTKKS kuning)
- **Axis X:** Tahun (2019–2025)
- **Setiap pasang bar sangat tipis** (W≈25px) dengan gap
- **Nilai di atas bar:** 11px

---

## 11. SLIDE 08 — DATA JABATAN: 2 KOLOM CHART + FOTO POLAROID + HIGHLIGHT NUMBER

**Template Type:** Jabatan Akademik — Dark Green BG + 2 Chart + Foto Polaroid + Highlight Stats  
**Contoh:** Data Asisten Ahli & Lektor

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas Gelap** | `bg_dotted_dark_green.png` atau warna `#1A3A1C` + pattern dots | Full slide |
| 2 | **Foto Polaroid Kiri Atas** | `photo_foto_kelas_guru.jpg` | X≈750px Y≈30px, W≈280px, style polaroid (border putih 8px) |
| 3 | **Foto Polaroid Kanan Atas** | `photo_mahasiswi_cutout.jpg` (versi group study) | X≈1050px Y≈10px, W≈300px, style polaroid |
| 4 | **Overlay Gradasi Gelap** | Gradient hitam dari bawah | Bottom half, untuk readability chart |
| 5 | **Highlight Number Kiri "Asisten Ahli"** | Text + ikon | Kiri, X≈80px Y≈200px |
| 6 | **Highlight Number Kanan "Lektor"** | Text + ikon | Kanan, X≈820px Y≈220px |
| 7 | **Ikon Jabatan** | `ill_ikon_dosen_01.png` (Asisten), `ill_ikon_dosen_02.png` (Lektor) | Di atas angka, H≈55px |
| 8 | **Box Chart Kiri** | Shape white rounded rect | X≈60px Y≈280px, W≈620px H≈290px |
| 9 | **Box Chart Kanan** | Shape white rounded rect | X≈750px Y≈280px, W≈580px H≈290px |
| 10 | **Chart Kiri (Asisten Ahli)** | Grouped bar chart dalam box | Di dalam box kiri |
| 11 | **Chart Kanan (Lektor)** | Grouped bar chart dalam box | Di dalam box kanan |
| 12 | **Tanda Panah Spiral** | `dec_tanda_panah_spiral.png` | Antara highlight number dan chart, X≈600px Y≈260px |
| 13 | **Narasi Bawah** | Text hitam (di area putih) | X≈60px Y≈595px, W≈650px |
| 14 | **Logo Bar** | §3.1 | Top-left |
| 15 | **Judul Slide** | Text | Top-left di bawah logo, X≈60px Y≈80px |
| 16 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

### Highlight Number Jabatan
```
[IKON_JABATAN]
ASISTEN AHLI          ← Montserrat Bold 18px, Kuning #F5B800
1,497                 ← Montserrat Bold 52px, Kuning #F5B800
```

### Foto Polaroid Style
- White border: 8px solid white
- Shadow: `0 6px 16px rgba(0,0,0,0.3)`
- Slight rotation alternating (+2° / -2°)

---

## 12. SLIDE 09 — DATA JABATAN: 2 KOLOM CHART + FOTO CUTOUT + HIGHLIGHT NUMBER

**Template Type:** Jabatan Akademik Lanjutan — Light BG + 2 Chart + Foto Cutout Tengah  
**Contoh:** Data Lektor Kepala & Guru Besar

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` | Full slide |
| 2 | **Dekorasi Daun Kiri** | `dec_daun_hijau_01.png` | X≈20px Y≈380px, W≈100px |
| 3 | **Dekorasi Daun Kanan** | `dec_daun_hijau_02.png` | X≈1280px Y≈350px, W≈120px |
| 4 | **Foto Cutout Wisuda Belakang** | `photo_siswa_sd_wisuda.jpg` (cutout) | Top-center, X≈550px Y≈20px, H≈280px, opacity rendah sbg bg |
| 5 | **Foto Cutout Wisuda Group** | `photo_wisudawan_group.jpg` (cutout tangan ke atas) | Top-right, X≈1000px Y≈0px, H≈300px |
| 6 | **Foto Cutout Profesional** | `photo_pria_profesional_buku.jpg` | Center, X≈600px Y≈200px, H≈500px |
| 7 | **Buku + Laptop Prop** | `dec_buku_laptop_rumput.png` | Center-bottom, di bawah foto profesional |
| 8 | **Box Chart Kiri (Lektor Kepala)** | Shape white rounded rect, border hijau | X≈30px Y≈270px, W≈520px H≈260px |
| 9 | **Box Chart Kanan (Guru Besar)** | Shape white rounded rect, border hijau | X≈820px Y≈270px, W≈520px H≈260px |
| 10 | **Chart Kiri** | Grouped bar chart | Di dalam box kiri |
| 11 | **Chart Kanan** | Grouped bar chart | Di dalam box kanan |
| 12 | **Highlight "Lektor Kepala"** | Text + ikon | Top-left di atas box kiri |
| 13 | **Highlight "Guru Besar"** | Text + ikon | Top-right di atas box kanan |
| 14 | **Narasi Kiri Bawah** | Text | X≈30px Y≈570px, W≈450px |
| 15 | **Narasi Kanan Bawah** | Text | X≈820px Y≈570px, W≈450px |
| 16 | **Logo Bar** | §3.1 | Top-left |
| 17 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

---

## 13. SLIDE 10 — DATA TABLE + KPI CARD + FOTO CUTOUT

**Template Type:** Tabel Data + KPI Card + Foto Siswa  
**Contoh:** Data Asesmen Nasional (ANBK) SMTK & SMAK

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` | Full slide |
| 2 | **Dekorasi Confetti / Gold** | `dec_confetti_emas.png` | Top-right, X≈1200px Y≈0, W≈250px |
| 3 | **Dekorasi Gold Kiri** | `dec_bintang_sparkle.png` | X≈70px Y≈90px, W≈30px |
| 4 | **Foto Siswa Kiri** | `photo_siswa_sma_pria_kacamata.jpg` | Kiri, X≈30px Y≈80px, H≈680px |
| 5 | **Foto Siswa Kanan** | `photo_siswa_anbk.jpg` | Kanan, X≈1200px Y≈120px, H≈540px |
| 6 | **KPI Card "Sekolah"** | Shape white rounded rect | Top-right area, X≈700px Y≈90px, W≈270px H≈100px |
| 7 | **KPI Card "Siswa"** | Shape white rounded rect | X≈990px Y≈90px, W≈270px H≈100px |
| 8 | **Ikon dalam KPI Card** | `ill_ikon_gedung_kuning.png` / `ill_ikon_siswa.png` | Di dalam card kiri/kanan |
| 9 | **Tabel Data** | Table komponen | Center-bottom, X≈400px Y≈420px, W≈800px |
| 10 | **Panah Diagonal (di antara KPI dan tabel)** | `dec_tanda_panah_spiral.png` | X≈560px Y≈310px |
| 11 | **Teks Narasi** | Text | Kanan atas, X≈690px Y≈200px, W≈450px |
| 12 | **Logo Bar** | §3.1 | Top-left |
| 13 | **Judul Slide** | Text | Kiri atas, X≈400px Y≈80px (kiri-tengah) |
| 14 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

### Tabel Data Spesifikasi
```
┌─────────────┬─────────────┬─────────────┐
│  Jenjang    │  Sekolah    │  Siswa      │  ← Header: bg Kuning #F5B800, Bold Hijau Tua
├─────────────┼─────────────┼─────────────┤
│  SMTK       │  106        │  1.884      │  ← Row 1: bg Putih
├─────────────┼─────────────┼─────────────┤
│  SMAK       │  59         │  1.218      │  ← Row 2: bg Abu sangat muda
└─────────────┴─────────────┴─────────────┘
```
- Header bg: Kuning `#F5B800`, teks Hijau Tua Bold 16px
- Row teks: Hitam Regular + Bold 16px
- Border: Hijau Tua 1.5px
- Col Jenjang: Bold

---

## 14. SLIDE 11 — DATA SPLIT: 2 SUB-KELOMPOK BAR CHART + NARASI BAWAH

**Template Type:** Dual Group Comparison — 2 Horizontal Bar Chart + Narasi Bawah Panjang  
**Contoh:** Data Pertumbuhan SMTK dan SMAK 2022–2026

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` | Full slide |
| 2 | **Dekorasi Pojok Kanan** | Gradasi biru muda diagonal | Top-right, W≈300px H≈200px |
| 3 | **Foto Kelas Interior** | `photo_foto_kelas_guru.jpg` | Kiri-tengah, X≈0 Y≈100px, W≈430px H≈450px, opacity 90% |
| 4 | **Dekorasi Buku Terbang** | `dec_buku_terbang.png` | Bottom-right, X≈1250px Y≈500px, W≈220px |
| 5 | **Dekorasi Panah Diagonal** | `dec_panah_diagonal_hijau.png` | Bottom-right, X≈1380px Y≈690px |
| 6 | **Ikon Gedung SMTK** | `ill_ikon_sekolah_kuning.png` | Tengah kiri atas chart kiri, X≈440px Y≈150px, H≈70px |
| 7 | **Ikon Gedung SMAK** | `ill_ikon_sekolah_kuning.png` | Tengah kanan atas chart kanan, X≈940px Y≈150px, H≈70px |
| 8 | **Tanda Panah Spiral Kiri** | `dec_tanda_panah_spiral.png` hitam | Dari ikon ke chart kiri, X≈520px Y≈190px |
| 9 | **Tanda Panah Spiral Kanan** | `dec_tanda_panah_spiral.png` hitam | Dari ikon ke chart kanan, X≈1020px Y≈190px |
| 10 | **Horizontal Bar Chart Kiri (SMTK)** | Chart komponen, warna gradient hijau tua→kuning→krem | X≈430px Y≈240px, W≈430px H≈220px |
| 11 | **Horizontal Bar Chart Kanan (SMAK)** | Chart komponen, warna gradient hijau tua→kuning→krem | X≈910px Y≈240px, W≈430px H≈220px |
| 12 | **Label Highlight Kiri** | Text | Di atas chart kiri: "SMTK (+) 140 > **145**" |
| 13 | **Label Highlight Kanan** | Text | Di atas chart kanan: "SMAK (+) 52 > **78**" |
| 14 | **Narasi Panjang Bawah** | Text hitam | X≈80px Y≈590px, W≈1280px, 1 paragraf |
| 15 | **Logo Bar** | §3.1 | Top-left |
| 16 | **Judul Slide** | Text rata tengah | Top-center, X≈80px Y≈80px |
| 17 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

### Label Highlight Format
```
SMTK (+)               ← Montserrat Bold 18px, Hijau Tua
140 > 145              ← "140 > " Regular 28px, "145" Bold 28px Hitam
```

### Bar Chart Warna Per Tahun
| Tahun/Periode | Warna Bar |
|---|---|
| 2022/2023 | Hijau Tua `#2E5E30` |
| 2023/2024 | Kuning `#F5B800` |
| 2024/2025 | Krem/Oranye muda `#F0C070` |
| 2025/2026 | Krem muda `#F0DEB0` |

---

## 15. SLIDE 12 — DATA SEBARAN: DUAL HORIZONTAL BAR CHART FULL WIDTH + PETA BACKGROUND

**Template Type:** Sebaran Provinsi — Peta Background + 2 Kolom Horizontal Bar Chart  
**Contoh:** Data Sebaran SMTK dan SMAK Per Provinsi Tahun 2026

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` | Full slide |
| 2 | **Peta Indonesia Dots** | `bg_peta_indonesia_dots.png` | Center, X≈250px Y≈170px, W≈950px, opacity 30% |
| 3 | **Padang Rumput Bawah** | `bg_tanah_tanam.png` | Bottom, Y≈590px |
| 4 | **Tanaman Tumbuh Kanan** | `dec_tanaman_tumbuh_02.png` | Bottom-right, X≈1280px Y≈380px, H≈350px |
| 5 | **Foto Siswa SD Group** | `photo_siswa_sd_group.jpg` | Bottom-center, X≈640px Y≈480px, H≈280px |
| 6 | **Pesawat Kertas Kiri** | `dec_kertas_terbang.png` | Bottom-left, X≈30px Y≈580px, W≈120px |
| 7 | **Horizontal Bar Chart Kiri (provinsi barat)** | Chart komponen, 2 series SMTK+SMAK | X≈60px Y≈130px, W≈580px H≈450px |
| 8 | **Horizontal Bar Chart Kanan (provinsi timur)** | Chart komponen, 2 series SMTK+SMAK | X≈750px Y≈130px, W≈580px H≈450px |
| 9 | **Legend (SMTK hijau + SMAK kuning)** | Dots + teks | Di atas masing-masing chart |
| 10 | **Annotation Box** | Rounded rect putih outline hijau | Center antara 2 chart: "SMTK: 145 sekolah / SMAK: 78 sekolah" |
| 11 | **Logo Bar** | §3.1 | Top-left |
| 12 | **Judul Slide** | Text rata tengah/kanan | Top, X≈300px Y≈55px |
| 13 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

### Dual Bar Chart Sebaran
- **Provinsi tanpa data:** Hanya nama label, tanpa bar
- **Warna:** SMTK = Hijau `#2E7D32`, SMAK = Kuning `#F5B800`
- **Bar tipis:** H≈12px per bar
- **Spacing antar provinsi:** 4px
- **Font label provinsi:** Montserrat Regular 10px

---

## 16. SLIDE 13 — DATA AKREDITASI: 2 BARIS PANEL (FOTO HEXAGON + ARROW + NUMBER + CHART)

**Template Type:** Akreditasi Detail — 2 Baris (SMTK atas, SMAK bawah), masing-masing: Foto Hexagon + Label + Panah + Angka + Horizontal Bar Chart  
**Contoh:** Data Sekolah SMTK dan SMAK serta Status Akreditasi 2026

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` | Full slide |
| 2 | **Foto Latar Rumput Kanan** | `bg_tanah_tanam.png` | Right side, X≈900px, partial |
| 3 | **Foto Profesional Buku** | `photo_pria_profesional_buku.jpg` | Right, X≈1100px Y≈60px, H≈680px |
| 4 | **Row 1 — Hexagon Frame SMTK** | Shape hexagon/polygon, border Kuning 3px | X≈60px Y≈200px, W≈150px H≈150px |
| 5 | **Row 1 — Foto dalam Hexagon** | `photo_siswa_sma_pria.jpg` | Clip-mask hexagon, W≈150px |
| 6 | **Row 1 — Label "SMTK"** | Text + arrow | X≈70px Y≈180px |
| 7 | **Row 1 — Chevron Arrow** | `dec_chevron_kuning_besar.png` | X≈210px Y≈230px, W≈50px |
| 8 | **Row 1 — Number Circles** | Shape circle hijau tua + hijau muda | X≈270px Y≈200px |
| 9 | **Row 1 — Horizontal Bar Chart** | Chart komponen (A/B/C/TT/BT) | X≈430px Y≈190px, W≈560px H≈180px |
| 10 | **Row 2 — Hexagon Frame SMAK** | Shape hexagon/polygon, border Kuning | X≈60px Y≈420px, W≈150px |
| 11 | **Row 2 — Foto dalam Hexagon** | `photo_siswa_sma_wanita.jpg` | Clip-mask hexagon |
| 12 | **Row 2 — Label "SMAK"** | Text + arrow | X≈70px Y≈400px |
| 13 | **Row 2 — Chevron Arrow** | `dec_chevron_kuning_besar.png` | X≈210px Y≈450px |
| 14 | **Row 2 — Number Circles** | Shape circle hijau | X≈270px Y≈420px |
| 15 | **Row 2 — Horizontal Bar Chart** | Chart komponen (A/B/C/TT/BT) | X≈430px Y≈410px, W≈560px H≈180px |
| 16 | **Logo Bar** | §3.1 | Top-left |
| 17 | **Judul Slide** | Text rata tengah | Top, X≈80px Y≈65px |
| 18 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

### Hexagon Foto + Label Struktur
```
        ┌──────────────────────┐
 [foto] → [SMTK] ›› [139 Swasta]  → [Horizontal Bar Chart Status Akreditasi]
  hex            ›› [6 Negeri  ]
        └──────────────────────┘
```
- Lingkaran angka Swasta: bg Hijau Muda, teks Bold Putih, diameter 60px
- Lingkaran angka Negeri: bg Hijau Tua, teks Bold Putih, diameter 55px
- Label "Swasta"/"Negeri": di bawah angka, Regular 12px

### Bar Chart Akreditasi
- **Tipe:** Horizontal bar
- **Kategori Y:** A, B, C, TT, BT
- **Warna:** A=Hijau, B=Hijau Muda, C=Krem Oranye, TT=Abu, BT=Salmon
- **Label nilai di ujung bar:** Bold 13px

---

## 17. SLIDE 14 — DATA SISWA: BAR CHART (KIRI) + DONUT CHART (KANAN) + CALLOUT LABEL

**Template Type:** Siswa Dual Chart — 2 Kolom Horizontal Bar Kiri + Donut Kanan + Callout Bubble  
**Contoh:** Data Siswa pada SMTK dan SMAK 2022–2026

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` | Full slide |
| 2 | **Ilustrasi Ikon Pensil Karakter** | `ill_karakter_pensil_kacamata.png` | Right-center, X≈1050px Y≈100px, H≈350px |
| 3 | **Horizontal Bar Chart SMTK** | Chart komponen, hijau | Kiri atas, X≈60px Y≈180px, W≈430px H≈200px |
| 4 | **Horizontal Bar Chart SMAK** | Chart komponen, kuning | Kiri bawah, X≈60px Y≈420px, W≈430px H≈200px |
| 5 | **Callout Bubble "SMTK"** | Shape speech bubble, bg Kuning `#F5B800` | X≈490px Y≈200px |
| 6 | **Callout Bubble "SMAK"** | Shape speech bubble, bg Kuning `#F5B800` | X≈490px Y≈430px |
| 7 | **Foto Cutout SMTK** | `photo_siswa_smp_pria.jpg` | Di dalam/dekat bubble SMTK |
| 8 | **Foto Cutout SMAK** | `photo_siswa_sma_pria.jpg` | Di dalam/dekat bubble SMAK |
| 9 | **Donut Chart** | Chart komponen | Right, X≈880px Y≈180px, W≈320px H≈320px |
| 10 | **Label Tengah Donut** | Text | Center donut: "2026" |
| 11 | **Label Luar Donut** | Text | Luar donut: "SMAK 4258", "SMTK 7619" |
| 12 | **Narasi Bawah** | Text hitam, Bold+Regular mix | X≈60px Y≈650px, W≈1250px |
| 13 | **Logo Bar** | §3.1 | Top-left |
| 14 | **Judul Slide** | Text rata kanan | Top-right, X≈500px Y≈60px |
| 15 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

### Callout Bubble SMTK/SMAK
```
┌──────────────────┐
│ SMTK             │  ← Montserrat Bold 18px, Putih
│ Sekolah Teologi  │  ← Montserrat Regular 13px, Putih
│ Kristen          │
└──────────────────┘
```
- Shape: rounded rect dengan ekor kiri
- Background: Kuning `#F5B800`

### Donut Chart
- **2 segments:** SMTK (Hijau Tua, ≈64%) + SMAK (Kuning, ≈36%)
- **Stroke width:** 50px
- **Center text:** "2026" Bold 28px Hitam

---

## 18. SLIDE 15 — DATA GURU: BAR CHART TENGAH + NARASI BAWAH DALAM BOX

**Template Type:** Guru/SDM — Grouped Bar Chart + Foto Cutout Kanan + Box Narasi Analitik  
**Contoh:** Data Guru pada SMTK dan SMAK 2022–2026

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` | Full slide |
| 2 | **Dekorasi Confetti Emas** | `dec_confetti_emas.png` | Top-right, X≈1100px Y≈0 |
| 3 | **Foto Kelas dengan Guru** | `photo_foto_kelas_guru.jpg` | Kiri, X≈0 Y≈150px, W≈490px H≈340px, rounded-right corners |
| 4 | **Dekorasi Panah Kuning** | `dec_panah_diagonal_kuning.png` | Di atas foto, menunjuk ke chart |
| 5 | **Grouped Bar Chart (SMTK+SMAK)** | Chart komponen | Center, X≈480px Y≈140px, W≈620px H≈370px |
| 6 | **Legend Chart** | Dots + teks | Di atas chart |
| 7 | **Foto Guru Wanita Batik** | `photo_guru_wanita_batik.jpg` | Kanan, X≈1170px Y≈80px, H≈520px |
| 8 | **Foto ASN Pria Tablet** | `photo_asn_pria_tablet.jpg` | Kanan bawah, X≈1270px Y≈380px, H≈350px |
| 9 | **Box Narasi Bawah** | Shape rounded rect, border Hijau, bg Putih/Krem | X≈60px Y≈560px, W≈1050px H≈170px |
| 10 | **Ikon Grafik 3D** | `ill_grafik_pertumbuhan_3d.png` | Di dalam box narasi, kiri, W≈60px |
| 11 | **Teks Narasi** | Text dalam box | Di dalam box narasi |
| 12 | **Foto Gedung SMTK** | `photo_gedung_sekolah_ntt.jpg` | Bottom-left kecil, di bawah box |
| 13 | **Logo Bar** | §3.1 | Top-left |
| 14 | **Judul Slide** | Text | Top-left, X≈80px Y≈80px |
| 15 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

### Grouped Bar Chart Spesifikasi (Guru)
- **2 Series:** SMTK (Hijau Tua) + SMAK (Hijau Muda)
- **Axis X:** Tahun ajaran (2022/2023 – 2025/2026)
- **Bar gap dalam group:** 4px
- **Gap antar group:** 24px
- **Label nilai di atas bar:** Bold 12px

### Box Narasi Analitik (Bawah)
- **Background:** Putih / Krem `#FAFAF0`
- **Border:** Hijau Tua `#1B4D2E`, 2px, radius 12px
- **Ikon kiri:** `ill_grafik_pertumbuhan_3d.png`, H=50px
- **Teks:** Regular 13px, Bold untuk angka kunci

---

## 19. SLIDE 16 — DATA ANBK: KPI CARD + NARASI + TABEL

*(Lihat Slide 13 §13 di atas — format serupa dengan KPI Card top + Tabel bawah)*

**Perbedaan utama:**
- Foto cutout siswa kiri dan kanan
- KPI Card menggunakan ikon sekolah dan ikon siswa
- Tabel di bawah dengan warna header kuning
- Panah spiral hitam dari KPI ke tabel

---

## 20. SLIDE 17 — DATA PERTUMBUHAN: 2 KOLOM (FOTO + BAR CHART + CALLOUT TARGET)

**Template Type:** Dual School Type — 2 Panel Sejajar, masing-masing: Foto Real + Horizontal Bar + Callout Growth  
**Contoh:** Data Pertumbuhan SDTK dan SMPTK 2022–2026

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Canvas** | `#F2F2F2` | Full slide |
| 2 | **Panel Kiri (SDTK)** | Shape rounded rect, bg putih, border hijau | X≈40px Y≈110px, W≈580px H≈480px |
| 3 | **Foto SDTK** | `photo_gedung_sdtk_real.jpg` | Di dalam panel kiri, top, W≈full, H≈180px |
| 4 | **Label "SDTK"** | Text hijau bold + subtitle | Di dalam panel atas foto |
| 5 | **Horizontal Bar Chart SDTK** | Chart komponen (4 tahun) | Di dalam panel kiri, bawah foto |
| 6 | **Callout Growth SDTK** | Shape pill/badge, bg Kuning | Bottom panel kiri: "55 > **84 Sekolah**" |
| 7 | **Ikon Target** | `dec_target_lingkaran.png` | Di dalam callout kiri |
| 8 | **Panel Kanan (SMPTK)** | Shape rounded rect, bg putih, border hijau | X≈750px Y≈110px, W≈580px H≈480px |
| 9 | **Foto SMPTK** | `photo_gedung_smptk_real.jpg` | Di dalam panel kanan, top |
| 10 | **Label "SMPTK"** | Text hijau bold + subtitle | Di dalam panel atas foto |
| 11 | **Horizontal Bar Chart SMPTK** | Chart komponen (4 tahun) | Di dalam panel kanan, bawah foto |
| 12 | **Callout Growth SMPTK** | Shape pill/badge, bg Kuning | Bottom panel kanan: "94 > **136 Sekolah**" |
| 13 | **Ikon Target** | `dec_target_lingkaran.png` | Di dalam callout kanan |
| 14 | **Box Narasi Bawah** | Shape rounded rect, bg Krem, border hijau | X≈40px Y≈620px, W≈1360px, H≈85px |
| 15 | **Ikon Magnifier** | `ill_magnifier_3d.png` | Di dalam box narasi, kiri, H≈55px |
| 16 | **Teks Narasi** | Text hitam | Di dalam box narasi |
| 17 | **Logo Bar** | §3.1 | Top-left |
| 18 | **Judul Slide** | Text rata kanan | Top-right, X≈400px Y≈45px |
| 19 | **Footer + Sumber** | §3.2 + §3.3 | Bottom |

### Panel Foto + Data Style
```
┌────────────────────────────┐
│   [FOTO GEDUNG REAL]       │
│   SDTK                     │ ← Bold 20px Hijau Tua
│   Sekolah Dasar Teologi    │ ← Regular 14px
│   Kristen                  │
├────────────────────────────┤
│   [Horizontal Bar Chart]   │
├────────────────────────────┤
│ 🎯 Peningkatan             │
│    55 > 84 Sekolah         │ ← Bold 20px Hitam
└────────────────────────────┘
```

---

## 21. SLIDE 18 — DATA TENAGA: 2 PANEL (NARASI + CHART) + BACKGROUND HIJAU FULL

**Template Type:** Dark BG Full Green — Torn Paper Top + 2 Panel (Narasi Kiri + Chart Kanan)  
**Contoh:** Data Tenaga Kependidikan SDTK dan SMPTK 2022–2026

### Urutan Pembuatan (Layer dari bawah ke atas)

| Urutan | Elemen | File/Komponen | Posisi & Ukuran |
|---|---|---|---|
| 1 | **Background Hijau Solid** | Warna `#2E7D32` | Full slide |
| 2 | **Dekorasi Robekan Kertas Putih** | `dec_robekan_kertas_putih.png` | Top, full width, H≈120px |
| 3 | **Dekorasi Panah Naik Kanan** | `dec_panah_naik_hijau.png` | Top-right, X≈1250px Y≈0, W≈200px, warna putih/muda |
| 4 | **Panel Kiri "Gambaran"** | Shape rounded rect, bg Putih | X≈40px Y≈150px, W≈550px H≈390px |
| 5 | **Label Header "Gambaran"** | Shape pill, bg Kuning | Top panel kiri: "Gambaran" teks Bold Hijau Tua |
| 6 | **Bullet Points Narasi** | Text Hitam + Ikon Check Kuning | Di dalam panel kiri |
| 7 | **Ilustrasi CS 3D** | `ill_karakter_cs_3d.png` | Di dalam panel kiri, kanan bawah, H≈180px |
| 8 | **Panel Kanan "Data"** | Shape rounded rect, bg Putih | X≈650px Y≈150px, W≈680px H≈390px |
| 9 | **Label Header "Data"** | Shape pill, bg Kuning | Top panel kanan: "Data" teks Bold Hijau Tua |
| 10 | **Ikon Magnifier** | `ill_magnifier_3d.png` | Di dalam panel kanan, kiri atas ikon, H≈80px |
| 11 | **Grouped Bar Chart** | Chart komponen (SDTK+SMPTK) | Di dalam panel kanan |
| 12 | **Legend** | Dots + teks | Di atas chart dalam panel |
| 13 | **Logo Bar** | §3.1 | Top-left (di atas robekan kertas) |
| 14 | **Judul Slide** | Text Putih rata tengah | Tengah atas, Y≈65px |
| 15 | **Footer + Sumber** | §3.2 | Bottom (footer tetap) |

### Panel Gambaran (Kiri) Bullet Style
```
☑ [Teks poin 1]   ← Ikon check/centang kuning 20px + Regular 13px Hitam
  [baris lanjutan]

☑ [Teks poin 2]
  [baris lanjutan]
```
- Ikon check: kotak kuning dengan tanda centang putih
- Teks: Montserrat Regular 13px Hitam

### Header Panel Pill
- **Shape:** Rounded rect penuh (pill), bg Kuning `#F5B800`
- **Teks:** Montserrat Bold 16px, Hijau Tua `#1B4D2E`
- **Posisi:** Top-center of panel, sedikit overlap ke luar panel

---

## 22. SLIDE 35 — PENUTUP / CLOSING

**Template Type:** Closing (identik dengan Cover)

Gunakan template yang **sama persis dengan Slide 01** (Cover), dengan perubahan:
- **Judul besar:** "Sekian dan Terima Kasih"
- **Sub-judul:** Tetap sama (nama laporan + periode)
- **Footer:** "Ditjen Bimas Kristen Kemenag RI" (sama dengan cover)
- Semua elemen visual identik dengan cover

---

## 23. POLA DESAIN TAMBAHAN & VARIAN

### 23.1 Varian Posisi Judul
| Varian | Posisi | Digunakan pada |
|---|---|---|
| **Kiri-Atas** | X≈80px Y≈90px | Slide 3, 6, 8, 11, 15, 18 |
| **Kanan-Atas** (rata kanan) | X≈500–700px Y≈60–110px | Slide 4, 14, 17 |
| **Tengah-Atas** | X≈80px Y≈65px, center align | Slide 11, 12, 13 |
| **Kiri-Tengah** (Section) | X≈80px Y≈290px | Slide 2, 10 |

### 23.2 Warna Chart Per Tipe Data
| Tipe Data | Series 1 | Series 2 |
|---|---|---|
| PTKKN vs PTKKS | Hijau `#2E7D32` | Kuning `#F5B800` |
| SMTK vs SMAK | Hijau Tua `#1B4D2E` | Hijau Muda `#66BB6A` |
| SDTK vs SMPTK | Hijau Tua `#2E7D32` | Hijau Muda `#90CAF9` |
| Single Series (tren) | Gradasi Hijau Tua→Biru Muda | — |
| Akreditasi A/B/C/TT/BT | Hijau/HijauMuda/Krem/Abu/Salmon | — |

### 23.3 Efek Foto Cutout
Semua foto manusia di-cutout (background removal) dengan karakteristik:
- **Edge:** Halus, tidak kasar
- **Shadow:** Ringan di bawah objek (drop shadow)
- **Placement:** Melayang di atas elemen lain (Z-index tinggi)
- **Scale:** Besar, tidak proporsional dengan elemen lain untuk efek dramatis

### 23.4 Ikon Indikator Pertumbuhan
Tiga jenis digunakan:
1. `dec_panah_diagonal_hijau.png` — pojok kanan bawah, ukuran ≈70px, selalu hadir di slide data
2. `dec_panah_naik_hijau.png` — lebih besar, digunakan di slide dengan growth story kuat
3. `dec_chevron_kuning_besar.png` — digunakan sebagai pemisah statistik (antara "Sudah" dan "Belum")

---

## 24. PANDUAN REPRODUKSI SLIDE BARU

### 24.1 Checklist Per Slide
Sebelum menyelesaikan setiap slide, pastikan:
- [ ] Logo Bar §3.1 ada di top-left (kecuali cover: di kanan)
- [ ] Footer Bar §3.2 ada di bottom (full width, hijau tua + strip kuning)
- [ ] Kotak Sumber Data §3.3 ada (pill hijau + teks sumber + tanggal cutoff)
- [ ] Ikon panah diagonal §3.3 ada di pojok kanan bawah (kecuali cover/section divider)
- [ ] Font konsisten: **Montserrat** satu-satunya font
- [ ] Warna hijau tua `#1B4D2E` untuk elemen utama
- [ ] Warna kuning `#F5B800` untuk aksen

### 24.2 Menentukan Template Yang Dipakai
```
Slide baru → Pertanyaan:
1. Apakah ini halaman pertama/terakhir?  → Gunakan Template COVER (§4/§22)
2. Apakah ini pemisah bagian?            → Gunakan Template SECTION DIVIDER (§5)
3. Apakah data berupa 1 chart + narasi?  → Pilih §6 (narasi kanan) atau §7 (narasi bawah)
4. Apakah data berupa KPI besar + chart? → Gunakan Template §10
5. Apakah data berupa 2 tipe sekolah?    → Gunakan Template §14 atau §20
6. Apakah data berupa sebaran wilayah?   → Gunakan Template §15
7. Apakah background gelap?             → Gunakan Template §21
```

### 24.3 Ukuran & Posisi Default untuk Canva
Semua ukuran di atas dalam satuan **pixel** untuk kanvas **1440 × 810 px**.  
Saat menggunakan Canva dengan ukuran kustom 1440×810, semua posisi di atas dapat digunakan langsung.

### 24.4 Penempatan Gambar dari Repository
Untuk mengganti gambar:
1. Upload file ke folder sesuai kategori (`/assets/photos/`, `/assets/decorative/`, dst.)
2. Ganti file lama dengan file baru menggunakan **nama yang sama persis**
3. Pastikan dimensi rasio gambar sesuai agar tidak terdistorsi
4. Foto manusia: pastikan background sudah dihapus (PNG transparan)

---

*Dokumen ini dibuat berdasarkan analisis visual mendalam terhadap file:*  
`v1_PPT_Dirpen_Direktori_Data_dan_Informasi_Ditpenkris_TW_2_2026.pdf`  
*35 slide, dibuat dengan Canva, penyusun: Hizkia Adiwiguna*  
*Font tunggal: Montserrat (Google Fonts) — Regular, Bold, Italic*
