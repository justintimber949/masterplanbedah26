---
title: "11 — MASTERPLAN GAP KONTEN"
description: "Gap analysis — semua konten klinis spesifik yang belum ada di repositori. Referensi untuk prioritas nulis selanjutnya."
date: 2026-06-17
tags:
  - masterplan
  - gap-analysis
  - todo
  - index
  - koas
  - bedah
aliases:
  - masterplan gap
  - gap konten
  - 11
  - prioritas nulis
---

# 📋 11 — MASTERPLAN GAP KONTEN

> **Taufiq · FKIK UIN Malang · RSUD Karsa Husada Batu · 2026**
> *Lihat juga: [[00 - MASTERPLAN UTAMA STASE BEDAH|← Masterplan Utama]] · [[10 - MASTERPLAN BASIC CALCULATIONS|← Basic Calc 10]]*

---

## 🧭 CARA PAKAI DOKUMEN INI

> [!tip] Peta Gap, Bukan Konten Belajar
> Dokumen ini berbeda dari file lain. Ini adalah **peta semua yang belum ada** di repositori — bukan materi untuk dipelajari, tapi **daftar tugas** yang perlu dikerjakan.
>
> **Cara pakai:**
> - **Bagian A** = topik klinis spesifik yang belum ditulis **sama sekali** di file manapun
> - **Bagian B** = prioritas nulis — mana yang harus dikerjakan duluan
>
> Verifikasi folder (file mana yang sudah ada vs belum per sub-stase) ada di [[12 - MASTERPLAN VERIFIKASI FOLDER|file 12]].
>
> Tiap kali mau nulis konten baru, cek dulu di sini apakah topik itu sudah terdaftar sebagai gap. Kalau iya, kerjakan dan centang.

> [!abstract] Kenapa File Ini Dibuat
> - Supaya ada **satu sumber kebenaran** tentang apa yang sudah dan belum ada
> - **Memprioritaskan** pekerjaan nulis — mana yang urgent, mana yang bisa nanti
> - Mencegah **nulis ulang** topik yang sudah ada
> - Bisa jadi acuan saat minta Claude ngerjain topik baru

---

## 🚨 BAGIAN A — GAP KONTEN SPESIFIK (BELUM ADA SAMA SEkALI)

> [!danger] Definisi: "Belum Ada Sama Sekali"
> Topik-topik di bawah ini **tidak disebutkan** di file manapun — baik di masterplan 00–10, file konten individu, suplemen 09, maupun basic calculations 10A. Ini adalah konten baru yang perlu **ditambahkan dari nol**.

---

### A.1 — Rasio 3:1 Crystalloid-to-Blood Loss

| Atribut | Detail |
|---------|--------|
| **Topik** | Rasio klasik resusitasi: 3 ml kristaloid per 1 ml estimasi blood loss |
| **Lokasi target** | `10 - MASTERPLAN BASIC CALCULATIONS` Seksi A |
| **Jenis** | Kalkulasi klinis + konteks historis |
| **Urgensi** | 🔴 **Tinggi** — masih ditanyakan di ujian/OSCE |

> [!info] Penjelasan
> Di dokumen saat ini hanya ada rasio modern 1:1:1 (PRBC:FFP:Plt) untuk massive transfusion protocol. Rasio klasik **3:1** tidak disebut sama sekali. Konsep ini penting sebagai pengetahuan dasar meski sudah digantikan DCR.

**Outline konten yang dibutuhkan:**
- Rumus: **3 ml kristaloid per 1 ml estimasi blood loss**
- Contoh: pasien kehilangan 1000 ml darah → butuh 3000 ml kristaloid
- Mengapa 3:1: kristaloid hanya ~30% yang bertahan di intravaskular (sisanya ke interstitium)
- Keterbatasan 3:1: overload cairan, hemodilusi, koagulopati dilusional
- Transisi ke DCR modern 1:1:1

---

### A.2 — Anion Gap & Interpretasi

| Atribut | Detail |
|---------|--------|
| **Topik** | Rumus, interpretasi, dan aplikasi klinis Anion Gap |
| **Lokasi target** | `10 - MASTERPLAN BASIC CALCULATIONS` Seksi H |
| **Jenis** | Kalkulasi dasar |
| **Urgensi** | 🟡 **Sedang** — dasar interpretasi AGD di ICU/IGD |

**Outline:**
- Rumus: **AG = Na − (Cl + HCO₃)** — normal 8–12 mEq/L
- AG tinggi (AGMA): MUDPILES / GOLDMARK
- AG normal (non-AGMA): HARDASS
- Koreksi AG untuk hipoalbuminemia: `AG + 2,5 × (4 − albumin)`
- Contoh kasus: pasien sepsis dengan asidosis metabolik

---

### A.3 — PaO₂/FiO₂ Ratio (P/F Ratio) & Definisi ARDS Berlin

| Atribut | Detail |
|---------|--------|
| **Topik** | P/F ratio, definisi ARDS Berlin, interpretasi hipoksemia |
| **Lokasi target** | `10 - MASTERPLAN BASIC CALCULATIONS` Seksi H atau `05 - MASTERPLAN IGD 2` — `5B` |
| **Jenis** | Kalkulasi klinis + definisi |
| **Urgensi** | 🔴 **Tinggi** — dipakai terus di ICU bedah |

**Outline:**
- Rumus: **P/F = PaO₂ ÷ FiO₂** (PaO₂ mmHg, FiO₂ desimal)
- Contoh: PaO₂ 80 pada FiO₂ 0,4 → P/F = 200
- Interpretasi: Normal > 400; Mild ARDS 200–300; Moderate 100–200; Severe < 100
- Estimasi FiO₂ dari alat O₂ (tabel)
- Contoh kasus: pasien post-laparotomi dengan sesak

---

### A.4 — Child-Pugh Score

| Atribut | Detail |
|---------|--------|
| **Topik** | Skor Child-Pugh untuk klasifikasi sirosis & risiko bedah |
| **Lokasi target** | `07 - MASTERPLAN BEDAH UMUM` — `7F` |
| **Jenis** | Skoring klinis |
| **Urgensi** | 🟡 **Sedang** — penting untuk operasi pada pasien sirosis |

**Outline:**
- 5 parameter: bilirubin, albumin, PT/INR, asites, ensefalopati (skor 1–3 per parameter)
- Kelas A (5–6): risiko rendah
- Kelas B (7–9): risiko sedang
- Kelas C (10–15): risiko tinggi
- Contoh: pasien sirosis akan kolesistektomi

---

### A.5 — MELD Score

| Atribut | Detail |
|---------|--------|
| **Topik** | Model for End-Stage Liver Disease — mortalitas 3 bulan |
| **Lokasi target** | `07 - MASTERPLAN BEDAH UMUM` — `7F` atau suplemen |
| **Jenis** | Skoring klinis |
| **Urgensi** | 🟡 **Sedang** |

**Outline:**
- MELD = 3,78 × ln(bilirubin) + 11,2 × ln(INR) + 9,57 × ln(kreatinin) + 6,43
- MELD > 14 = risiko tinggi operasi elektif
- Digunakan di transplantasi hepatik

---

### A.6 — Wells Criteria for DVT (Detail Scoring)

| Atribut | Detail |
|---------|--------|
| **Topik** | Wells score untuk probabilitas DVT sebelum imaging |
| **Lokasi target** | `07 - MASTERPLAN BEDAH UMUM` — `7E` |
| **Jenis** | Skoring klinis |
| **Urgensi** | 🟡 **Sedang** — di masterplan `7E` disebut sepintas tanpa skor |

**Outline:**
- 10 komponen: kanker aktif, paralisis, bedah besar, nyeri sepanjang vena, edema tungkai, calf swelling > 3 cm, pitting edema, vena kolateral, DVT sebelumnya, diagnosis alternatif
- Skor ≤ 1 = low; 2 = moderate; ≥ 3 = high
- Management berdasarkan probabilitas + D-dimer

---

### A.7 — NIHSS Score (Detail)

| Atribut | Detail |
|---------|--------|
| **Topik** | National Institutes of Health Stroke Scale — 11 item |
| **Lokasi target** | `02 - MASTERPLAN BEDAH SARAF` — `2E` |
| **Jenis** | Skoring klinis |
| **Urgensi** | 🟡 **Sedang** — di `2E.1` disebut tanpa detail |

**Outline:**
- 11 komponen: kesadaran, gaze, visual, facial palsy, motorik (L+R), ataksia, sensori, bahasa, disartria, extinction
- Skor 0–42; ≥ 16 = stroke berat
- Tabel ringkas untuk IGD

---

### A.8 — Glasgow-Imrie Score (Alternatif Ranson untuk Pankreatitis)

| Atribut | Detail |
|---------|--------|
| **Topik** | Imrie/Glasgow score — alternatif lebih simpel dari Ranson |
| **Lokasi target** | `03 - MASTERPLAN BEDAH DIGESTIF` — `3E` |
| **Jenis** | Skoring klinis |
| **Urgensi** | 🟡 **Sedang** |

**Outline:**
- 8 kriteria (vs 11 Ranson): usia > 55, WBC > 15.000, GDS > 180, BUN > 45, Ca < 8, albumin < 3,2, LDH > 600, PaO₂ < 60
- ≥ 3 = pankreatitis berat
- Lebih praktis dari Ranson

---

### A.9 — BISAP Score (Pankreatitis)

| Atribut | Detail |
|---------|--------|
| **Topik** | Bedside Index for Severity in Acute Pancreatitis |
| **Lokasi target** | `03 - MASTERPLAN BEDAH DIGESTIF` — `3E` |
| **Jenis** | Skoring klinis |
| **Urgensi** | 🟢 **Rendah** |

**Outline:**
- BUN > 25, impaired mental status, SIRS ≥ 2, age > 60, pleural effusion
- Masing-masing 1 poin; skor ≥ 3 = berat

---

### A.10 — Osmolal Gap

| Atribut | Detail |
|---------|--------|
| **Topik** | Osmolal gap untuk deteksi toksin (metanol, etilen glikol) |
| **Lokasi target** | `10 - MASTERPLAN BASIC CALCULATIONS` Seksi H |
| **Jenis** | Kalkulasi lab |
| **Urgensi** | 🟢 **Rendah** |

---

### A.11 — FRAX Score

| Atribut | Detail |
|---------|--------|
| **Topik** | FRAX — risiko fraktur 10 tahun untuk skrining osteoporosis |
| **Lokasi target** | `08 - MASTERPLAN BEDAH ORTOPEDI` — `8F` |
| **Jenis** | Skoring klinis |
| **Urgensi** | 🟢 **Rendah** |

---

### A.12 — Kumpulan Rasio Penting — Cek Status

| Rasio | Status | Lokasi (kalau sudah ada) |
|-------|:------:|-------------------------|
| **3:1** crystalloid:blood loss | ❌ **GAP** | — |
| **4:1** Baxter (4 ml/kg/%TBSA) | ✅ Ada | `10A` Seksi D |
| **1:1:1** PRBC:FFP:Plt | ✅ Ada | `10A` Seksi A, `5B` |
| **1:4** insulin:glukosa (drip) | ❌ **GAP** | — |
| **1:1** insulin:D50 (tiap 10 unit insulin + 50 ml D50%) | ⚠️ Ada di `10A` tapi tidak disebut sebagai rasio | `10A` A5 |
| **3:1** kompresi:ventilasi CPR dewasa | ❌ **GAP** | — |
| **30:2** kompresi:ventilasi CPR dewasa | ❌ **GAP** | — |

---

## 🎯 BAGIAN B — PRIORITAS NULIS GAP KONTEN

> [!todo] Urutan Prioritas — Dari Paling Urgen

#### 🔴 Prioritas 1 — Gap Kritis
- [ ] **A.1 — Rasio 3:1** crystalloid:blood loss → tambah ke `10 - MASTERPLAN BASIC CALCULATIONS` Seksi A
- [ ] **A.3 — P/F Ratio & definisi ARDS Berlin** → tambah ke `10` Seksi H atau `5B`

#### 🟡 Prioritas 2 — Gap Sedang
- [ ] **A.2 — Anion Gap & Interpretasi** → tambah ke `10` Seksi H
- [ ] **A.4 — Child-Pugh Score** → tambah ke `07 – Bedah Umum` — `7F`
- [ ] **A.5 — MELD Score** → tambah ke `07` atau suplemen
- [ ] **A.6 — Wells Criteria DVT** detail → tambah ke `07` — `7E`
- [ ] **A.7 — NIHSS Score** detail → tambah ke `02 — Bedah Saraf` — `2E`
- [ ] **A.8 — Glasgow-Imrie Score** → tambah ke `03 — Bedah Digestif` — `3E`

#### 🟢 Prioritas 3 — Gap Lanjutan
- [ ] **A.9 — BISAP Score** → `3E`
- [ ] **A.10 — Osmolal Gap** → `10` H
- [ ] **A.11 — FRAX Score** → `08 — Bedah Ortopedi` — `8F`
- [ ] **A.12 — Rasio lain** (1:4 insulin:glukosa, 30:2 CPR) → `10`

---

## 🔁 INSTRUKSI UNTUK SESI LANJUTAN

> [!info] Copy-paste ini ke Claude baru saat mau nulis konten gap

```
Saya Taufiq, koas bedah di RSUD Karsa Husada Batu, FKIK UIN Malang.

Ini file GAP ANALYSIS saya (11) yang berisi semua topik yang belum ada:
[TEMPEL FILE 11 INI]

Sedang mengerjakan: [GAP KODE] — [NAMA TOPIK/STASE]
Contoh: "Gap A.1 — Rasio 3:1 Crystalloid-to-Blood Loss untuk ditambahkan ke file 10 Seksi A"
Atau: "Buat file 7A — Kelenjar Tiroid.md dari masterplan 07"

Format untuk file konten individu wajib (urutan jangan diubah):
1. Opening kasus (naratif IGD/Poli RSUD Karsa Husada Batu, 2-3 paragraf, diakhiri "Nah, kamu mau ngapain sekarang?")
2. Kenapa ini penting (bukan definisi — konteks klinis, apa yang fatal kalau miss)
3. Dasar yang harus diketahui (ANALOGI DULU, istilah medis belakangan; petunjuk gambar 📸)
4. Cara berpikir di depan pasien
5. Tatalaksana (stabilisasi → non-operatif → kapan konsul → indikasi operasi → monitoring)
6. Yang sering ditanya konsulen (format: ❓ → ✅, 5-10 poin)
7. Checklist sebelum konsul/visite

Gaya: bahasa Indonesia santai seperti senior residen ngobrol di ruang jaga, akurat secara medis.
Output: satu file .md lengkap, Quartz-compatible (YAML frontmatter, Obsidian callouts, wikilinks).
```

---

## 🔗 KONEKSI KE FILE LAIN

> [!note] File Ini Berhubungan Langsung Dengan

| File | Koneksi |
|------|---------|
| [[00 - MASTERPLAN UTAMA STASE BEDAH\|Masterplan Utama]] | Induk semua stase |
| [[10 - MASTERPLAN BASIC CALCULATIONS\|Basic Calc 10]] | Target utama untuk gap A.1, A.2, A.3, A.10 |
| [[12 - MASTERPLAN VERIFIKASI FOLDER\|Verifikasi Folder 12]] | Data folder & file per sub-stase |
| [[09 - MASTERPLAN SUPLEMEN\|Suplemen 09]] | Topik suplemen lintas stase |

---

*Terakhir diupdate: 17 Juni 2026 · Taufiq · Koas Bedah FKIK UIN Malang · RSUD Karsa Husada Batu*
*Lihat juga: [[00 - MASTERPLAN UTAMA STASE BEDAH|Masterplan Utama]] · [[10 - MASTERPLAN BASIC CALCULATIONS|Basic Calc 10]] · [[12 - MASTERPLAN VERIFIKASI FOLDER|Verifikasi Folder 12]]*
