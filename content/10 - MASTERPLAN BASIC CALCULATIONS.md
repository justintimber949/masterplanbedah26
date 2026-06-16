---
title: "10 — MASTERPLAN BASIC CALCULATIONS & CLINICAL FORMULAS"
description: "Fondasi kalkulasi klinis & rumus-rumus yang dipakai lintas semua stase bedah — referensi terpusat untuk jaga malam di RSUD Karsa Husada Batu."
date: 2026-06-01
tags:
  - masterplan
  - kalkulasi
  - rumus
  - lintas-stase
  - basic-science
  - index
aliases:
  - masterplan kalkulasi
  - rumus bedah
  - clinical formulas
  - basic calculations
  - 10
---

# 🧮 10 — MASTERPLAN BASIC CALCULATIONS & CLINICAL FORMULAS

> **Taufiq · FKIK UIN Malang · RSUD Karsa Husada Batu · 2026**
> *Lihat juga: [[00 - MASTERPLAN UTAMA STASE BEDAH|← Masterplan Utama]] · [[09 - MASTERPLAN SUPLEMEN|← Suplemen 09]]*

---

## 🧭 CARA PAKAI FILE INI

> [!tip] Ini adalah "Lembar Contekan Terpusat" untuk Semua Stase
> File ini **berbeda dari file 09**. File 09 berisi topik klinis spesifik yang terlewat di stase tertentu. File ini berisi **fondasi kalkulasi dan rumus** yang kamu butuhkan di setiap stase, setiap shift — dari cara hitung cairan resusitasi sampai cara interpretasi ABG jam 3 pagi.
>
> **Lampirkan file ini bersama file 00, masterplan stase, dan file 09** setiap kali membuat materi individual yang melibatkan kalkulasi klinis.
>
> Tidak perlu dibaca dari awal sampai akhir. Gunakan seperti kamus — cari seksi yang kamu butuhkan, baca konteksnya, ikuti contoh kasusnya.

> [!abstract] Filosofi File Ini
> Rumus tanpa konteks hanya hafalan. Di sini, setiap rumus diikuti dengan **kenapa rumus ini ada**, **apa yang bisa salah kalau kamu salah hitung**, dan **contoh kasus dari IGD RSUD Karsa Husada Batu** yang membuat angka-angka itu terasa nyata — bukan sekadar latihan matematika.

---

## 📋 DAFTAR SEKSI

| Seksi | Topik | Konten Utama |
|:-----:|-------|--------------|
| **A** | Resusitasi & Cairan | Syok, maintenance, defisit, transfusi, elektrolit |
| **B** | Obat-Obatan Darurat | Vasopressor drip, analgetik, antibiotik, antikoagulan |
| **C** | Monitoring & Interpretasi | Vital sign, saturasi, urine output, skoring IGD |
| **D** | Kalkulasi Luka Bakar | Rule of Nine, Baxter, variasi kasus |
| **E** | Kalkulasi Ortopedi | Traksi, estimasi blood loss, gips |
| **F** | Kalkulasi Pediatri | BB estimasi, vital sign anak, dosis, cairan anak |
| **G** | Nutrisi & Perioperatif | Kalori, puasa, enteral vs parenteral |
| **H** | Lab & Interpretasi Cepat | ABG, elektrolit, koagulasi, laktat, CBC |

---

## 💧 SEKSI A — RESUSITASI & CAIRAN

---

### A1 — Klasifikasi Syok & Resusitasi Cairan

> [!abstract] Analogi Pertama: Syok adalah "Jaringan yang Kehausan"
> Bayangkan sel-sel tubuhmu adalah kota kecil yang butuh pasokan air bersih (oksigen). Syok terjadi ketika pipa utama (pembuluh darah) tidak bisa mengalirkan cukup air ke seluruh kota — entah karena airnya berkurang (hipovolemik), pompanya rusak (kardiogenik), pipanya bocor semua (distributif), atau ada sumbatan di jalur keluar (obstruktif). Solusinya beda untuk tiap penyebab.

#### Empat Jenis Syok — Bedakan Dulu Sebelum Kasih Cairan

| Jenis | Mekanisme Utama | JVP/CVP | Kulit | Nadi | Contoh |
|-------|----------------|---------|-------|------|--------|
| **Hipovolemik** | Volume intravaskular kurang | ↓ | Dingin, lembab, pucat | Lemah, cepat | Perdarahan, dehidrasi, luka bakar |
| **Distributif** | Vasodilatasi masif → pooling perifer | ↓ atau N | Hangat, merah (awal) | Bounding (awal) | Sepsis, anafilaksis, neurogenik |
| **Kardiogenik** | Pompa jantung gagal | ↑ | Dingin, lembab | Lemah, cepat | Infark miokard, gagal jantung akut |
| **Obstruktif** | Outflow tersumbat | ↑ | Dingin | Lemah | Tension pneumo, tamponade, PE masif |

> [!danger] JANGAN Kasih Cairan Masif pada Syok Kardiogenik atau Obstruktif
> Ini adalah kesalahan yang membunuh. Kardiogenik → inotropik. Tension pneumo → needle decompression dulu. Tamponade → pericardiocentesis. Cairan hanya untuk hipovolemik dan distributif.

#### ATLS Hemorrhagic Shock Classification — Hafal Tabel Ini

| | **Grade I** | **Grade II** | **Grade III** | **Grade IV** |
|---|------------|-------------|--------------|-------------|
| **Kehilangan darah** | < 750 ml / < 15% EBV | 750–1500 ml / 15–30% | 1500–2000 ml / 30–40% | > 2000 ml / > 40% |
| **HR** | < 100 | 100–120 | 120–140 | > 140 |
| **TD Sistolik** | Normal | Normal | ↓ | ↓↓ |
| **Tekanan Nadi** | Normal / melebar | Menyempit | Menyempit | Menyempit |
| **RR** | 14–20 | 20–30 | 30–40 | > 35 |
| **Urine Output** | > 30 ml/jam | 20–30 ml/jam | 5–15 ml/jam | < 5 ml/jam |
| **GCS** | Normal / sedikit cemas | Cemas | Bingung | Letargis/tidak sadar |
| **Resusitasi** | Kristaloid ± | Kristaloid | Kristaloid + darah | **Darah segera** |

> [!tip] Cara Ingat: "Tekanan Nadi Menyempit = Sudah Grade II"
> Tekanan nadi = sistolik − diastolik (normal 40 mmHg). Saat hipovolemia, tubuh vasokonstriksi → diastolik naik → tekanan nadi menyempit. Ini tanda pertama yang bisa kamu ukur dengan tensimeter biasa sebelum pasien tampak hipotensif. Menyempit di Grade II, sebelum sistolik turun.

#### Rumus Estimasi EBV (Estimated Blood Volume)

```
EBV = Berat Badan (kg) × Faktor Usia

Faktor Usia:
  Neonatus prematur : 95 ml/kg
  Neonatus aterm    : 85 ml/kg
  Bayi < 1 tahun    : 80 ml/kg
  Anak 1–12 tahun   : 75 ml/kg
  Dewasa pria       : 70 ml/kg
  Dewasa wanita     : 65 ml/kg
```

**Contoh Kasus IGD RSUD Karsa Husada Batu:**
> Pasien pria 60 kg, fraktur femur kanan tertutup, pucat, nadi 118x/menit, TD 100/75 mmHg, gelisah.
>
> EBV = 60 kg × 70 ml/kg = **4.200 ml**
> Tekanan nadi = 100 − 75 = 25 mmHg → menyempit → Grade II
> Estimasi kehilangan darah fraktur femur = 800–1500 ml → sesuai Grade II (15–30% dari 4200 ml = 630–1260 ml)
> Resusitasi: kristaloid hangat 1–2 L bolus → evaluasi respons

#### Resusitasi Cairan Pertama di IGD

**Langkah 1: Akses Vena**
- 2 jalur IV besar (minimal 16G, ideal 14G) di antecubital
- Ambil darah untuk lab bersamaan saat memasang IV (DPL, elektrolit, koagulasi, goldar, crossmatch, laktat)

**Langkah 2: Bolus Cairan Awal**
```
Kristaloid hangat (RL atau NaCl 0,9%):
  Dewasa : 1–2 Liter dalam 15–30 menit
  Anak   : 20 ml/kgBB dalam 20 menit (bisa diulang sampai 3×)
```

> [!warning] RL vs NaCl 0,9% — Pilih yang Mana?
> Keduanya acceptable. Tapi **NaCl 0,9% dalam jumlah besar → asidosis hiperkloremik** (klorida terlalu banyak → bikarbonat berkurang). Lebih aman pakai RL untuk resusitasi volume besar. NaCl 0,9% masih pilihan untuk resusitasi pada TBI (RL hipotonik relatif, kontraindikasi TBI).

**Langkah 3: Evaluasi Respons (setelah bolus pertama)**
```
Respons Baik (Transient/Non-Responder?) :
  ↓ HR, ↑ TD, urine output membaik, CRT < 2 detik, laktat turun → Responder → lanjut maintenance
  Membaik lalu memburuk lagi → Transient Responder → kemungkinan masih ada perdarahan aktif → siap darah
  Tidak ada perbaikan → Non-Responder → darah segera + pertimbangkan sumber perdarahan bedah
```

**Langkah 4: Target Resusitasi**
```
MAP          : ≥ 65 mmHg (TBI: ≥ 80 mmHg)
Urine output : ≥ 0,5 ml/kgBB/jam (dewasa) / ≥ 1 ml/kgBB/jam (anak)
Laktat       : < 2 mmol/L (atau clearance > 10%/2 jam)
Suhu         : > 36°C (hipotermia memperberat koagulopati)
```

#### Damage Control Resuscitation — Untuk Trauma Berat

Bila ada perdarahan masif aktif, **hindari kristaloid berlebihan** → encerkan faktor koagulasi → perdarahan makin parah. Ganti dengan:

```
Rasio komponen darah: PRBCs : FFP : Platelet = 1 : 1 : 1

Contoh:
  Pasien dengan massive hemorrhage (> 10 unit PRBCs/24 jam anticipated)
  → Aktifkan Massive Transfusion Protocol (MTP)
  → Berikan PRBCs + FFP + Plt secara bersamaan dalam rasio 1:1:1
  → TXA (Tranexamic Acid) 1 gram IV dalam 10 menit → dalam 3 jam pertama!
  → Kalsium glukonat 1 gram IV tiap 4 unit darah
```

> [!tip] Kenapa Kalsium pada Transfusi Masif?
> Darah donor mengandung **sitrat** (antikoagulan pengawet) yang mengkelasi kalsium bebas dalam darah pasien. Kalsium rendah → kontraksi jantung dan koagulasi terganggu. Tiap 4 unit darah → berikan Ca glukonat 1 gram IV pelan.

---

### A2 — Cairan Maintenance: Holliday-Segar & 4-2-1 Rule

> [!abstract] Analogi: Cairan Maintenance adalah "Bayar Tagihan Harian Tubuh"
> Tubuh setiap hari "membuang" cairan — lewat urin, nafas, keringat, feses. Maintenance adalah pengganti keluaran harian ini saat pasien tidak bisa minum sendiri (puasa, tidak sadar, post-op). Bukan untuk resusitasi — untuk mempertahankan status quo.

#### Holliday-Segar Formula (untuk menghitung kebutuhan cairan harian)

```
BB 0–10 kg   : 100 ml/kgBB/hari
BB 10–20 kg  : + 50 ml/kgBB/hari (untuk setiap kg di atas 10 kg)
BB > 20 kg   : + 20 ml/kgBB/hari (untuk setiap kg di atas 20 kg)
```

**Contoh Kasus:**
> Anak 25 kg, post-apendektomi, masih puasa.
>
> 10 kg pertama  : 10 × 100 = 1.000 ml
> 10 kg berikutnya: 10 × 50 = 500 ml
> 5 kg sisanya   : 5 × 20 = 100 ml
> **Total: 1.600 ml/hari = ~67 ml/jam**

> Dewasa 70 kg:
> 10 × 100 = 1.000 ml
> 10 × 50 = 500 ml
> 50 × 20 = 1.000 ml
> **Total: 2.500 ml/hari = ~104 ml/jam**

#### 4-2-1 Rule (untuk menghitung kecepatan drip per jam — versi cepat)

```
BB 0–10 kg   : 4 ml/kgBB/jam
BB 10–20 kg  : + 2 ml/kgBB/jam (untuk setiap kg di atas 10 kg)
BB > 20 kg   : + 1 ml/kgBB/jam (untuk setiap kg di atas 20 kg)
```

**Contoh Kasus:**
> Pria 70 kg, post-op tiroidektomi, puasa semalam.
>
> 10 kg pertama : 10 × 4 = 40 ml/jam
> 10 kg berikutnya: 10 × 2 = 20 ml/jam
> 50 kg sisanya : 50 × 1 = 50 ml/jam
> **Total: 110 ml/jam**
>
> Pilihan cairan: **RL atau NaCl 0,9% + KCl 20 mEq/L** (ganti kalium yang hilang dari urin)

> [!warning] Maintenance Bukan Terapi — Jangan Pakai untuk Resusitasi
> Cairan maintenance dihitung untuk pasien yang **status cairannya sudah normal**. Kalau pasien datang dengan syok atau dehidrasi, koreksi defisit dulu (A1 dan A3), baru masuk ke maintenance rate.

#### Cairan Maintenance Standar yang Dipakai

| Kondisi Pasien | Pilihan Cairan Maintenance |
|---------------|---------------------------|
| Dewasa post-op umum | RL 1500–2000 ml/hari atau NaCl 0,9% + KCl 20 mEq/L |
| Pasien dengan TBI | NaCl 0,9% (bukan RL — RL sedikit hipotonik) |
| Anak | RL atau NaCl 0,45% + Dextrose 5% + KCl (sesuai elektrolit) |
| Pasien dengan hiponatremia | NaCl 0,9% atau NaCl 3% (tergantung derajat) |
| Luka bakar hari 1 | Ringer Laktat (Baxter formula — lihat Seksi D) |

---

### A3 — Defisit Cairan & Replacement

> [!abstract] Analogi: Defisit Cairan adalah "Hutang yang Harus Dilunasi Dulu"
> Sebelum bisa bayar tagihan harian (maintenance), kamu harus lunaskan hutang yang sudah ada (defisit). Pasien dehidrasi atau post-puasa panjang punya "hutang cairan" yang perlu dihitung dan diganti sebelum kamu bisa menghitung kebutuhan maintenancenya.

#### Menghitung Defisit Cairan pada Dehidrasi

```
Defisit Cairan (liter) = BB (kg) × % Dehidrasi × 10

Atau:
Defisit = (Na serum aktual − Na normal) × TBW × 0,6 (untuk hipernatremia)

Derajat Dehidrasi Klinis:
  Ringan  (3–5%)  : haus, mulut kering, turgor sedikit turun
  Sedang  (6–9%)  : mata cekung, turgor sangat turun, oliguria
  Berat   (≥10%)  : letargi, tidak produksi air mata, tanda syok
```

**Contoh Kasus:**
> Anak 20 kg, diare 3 hari, mata cekung, rewel → dehidrasi sedang (8%)
>
> Defisit = 20 kg × 8% × 10 = **1.600 ml**
> Tambahkan maintenance: 1.600 ml/hari (dari Holliday-Segar contoh sebelumnya)
> Tambahkan ongoing losses: perkirakan volume diare (~100 ml/episode × jumlah episode)
>
> **Total cairan 24 jam = Defisit + Maintenance + Ongoing losses**
> = 1.600 + 1.600 + 500 = **3.700 ml/hari**
>
> Cara pemberian: ½ defisit dalam 8 jam pertama, ½ sisanya dalam 16 jam berikutnya, sambil maintenance berjalan

#### Defisit Cairan Akibat Puasa Pre-Operatif

```
Defisit Puasa = Maintenance rate (ml/jam) × Lama Puasa (jam)

Contoh:
  Pasien 70 kg (maintenance 110 ml/jam), puasa 8 jam
  Defisit puasa = 110 × 8 = 880 ml

Cara penggantian (aturan klasik):
  ½ defisit pada jam pertama intraoperatif
  ¼ defisit pada jam kedua
  ¼ defisit pada jam ketiga
  + Maintenance rate + Surgical losses
```

> [!note] ERAS Protocol Mengubah Ini
> Dengan protokol ERAS modern, pasien boleh minum cairan bening sampai 2 jam pre-operasi → defisit puasa jauh lebih kecil. Tapi di RSUD yang belum ERAS penuh, tetap hitung defisit seperti di atas.

#### Third Space Losses (Kehilangan ke Ruang Ketiga)

Selama operasi abdomen besar, cairan berpindah dari intravaskular ke jaringan interstitial dan rongga tubuh → tidak bisa dipakai → butuh replacement.

```
Third Space Losses (estimasi per jam operasi):
  Operasi minor (superfisial, kulit)  : 2–4 ml/kgBB/jam
  Operasi medium (thoraks, ortopedi)  : 4–6 ml/kgBB/jam
  Operasi besar (abdomen terbuka)     : 6–10 ml/kgBB/jam

Total cairan intraoperatif per jam:
  = Maintenance + Defisit puasa (distribusi) + Third space + Estimated blood loss replacement
```

---

### A4 — Transfusi Darah: Kapan, Berapa, Rumus

#### Indikasi Transfusi Eritrosit (PRBCs)

```
Trigger transfusi:
  Hb < 7 g/dL  → transfusi pada pasien stabil (TRICC trial)
  Hb < 8 g/dL  → transfusi pada pasien dengan penyakit jantung koroner / TBI
  Hb < 10 g/dL → transfusi pada pasien dengan iskemia miokard aktif
  Hb berapapun → transfusi bila ada syok hemoragik dengan perdarahan aktif
```

> [!tip] Hemoglobin vs Hematokrit
> Yang kamu ukur sering hematokrit (Hct). Konversi kasar: **Hb (g/dL) ≈ Hct (%) ÷ 3**. Jadi Hct 21% ≈ Hb 7 g/dL.

#### Rumus Volume PRBCs yang Dibutuhkan

```
Volume PRBCs (ml) = [(Hb target − Hb aktual) × BB (kg) × 3] ÷ Hb donor

Atau versi lebih simpel (asumsi 1 unit PRBCs = 250–300 ml, Hb donor ~24 g/dL):
  1 unit PRBCs → naikan Hb ~1 g/dL pada dewasa 70 kg

Rumus lain yang sering dipakai:
  Volume PRBCs = (Hb target − Hb aktual) × BB × 0,3

Contoh:
  Pasien 60 kg, Hb 5,5 g/dL, target Hb 9 g/dL
  Volume = (9 − 5,5) × 60 × 0,3 = 3,5 × 60 × 0,3 = 63 ml? → tidak, pakai rumus dengan 3
  Volume = (9 − 5,5) × 60 × 3 ÷ 24 = 3,5 × 60 × 3 ÷ 24 = 26,25 ml... → terlalu sedikit

  Pakai yang paling praktis:
  Target kenaikan 3,5 g/dL pada pasien 60 kg:
  Jumlah unit = 3,5 g/dL ÷ 1 g/dL per unit (per 70 kg) × (60/70) ≈ 3 unit PRBCs
```

> [!note] Pakai Rule of Thumb yang Lebih Mudah
> Di IGD: **1 unit PRBCs ≈ naik Hb 1 g/dL pada pasien 70 kg**. Sesuaikan proporsional untuk berat badan berbeda. Cek Hb post-transfusi 1 jam setelah transfusi selesai.

#### Komponen Darah Lainnya

| Komponen | Volume/Unit | Indikasi | Efek yang Diharapkan |
|----------|------------|---------|---------------------|
| **FFP** (Fresh Frozen Plasma) | 200–250 ml | Koagulopati, reversal warfarin, DIC | Naikkan faktor koagulasi; PT/APTT memanjang |
| **Trombosit** (Platelet Concentrate) | 50–70 ml/unit | Plt < 50.000 (dengan perdarahan) atau < 100.000 (pre-op) | Naik ~5.000–10.000/unit per 70 kg |
| **Cryoprecipitate** | 15–20 ml/unit | Fibrinogen < 1 g/L, hemofilia A, vWD | Fibrinogen naik; 10 unit cryo → naik ~1 g/L |
| **PRC/Washed RBC** | Seperti PRBCs | Riwayat reaksi alergi transfusi multipel | Sama dengan PRBCs |

---

### A5 — Koreksi Elektrolit

> [!abstract] Analogi: Elektrolit adalah "Konduktor Listrik Tubuh"
> Saraf dan otot bekerja dengan impuls listrik yang bergantung pada gradien elektrolit di membran sel. Kalau Na terlalu rendah → otak membengkak. K terlalu tinggi → jantung berhenti. Ca terlalu rendah → tetani dan kejang. Setiap koreksi punya kecepatan maksimal yang tidak boleh dilanggar — terlalu cepat bisa lebih berbahaya dari penyakitnya sendiri.

#### Koreksi Natrium (Na)

**Hiponatremia (Na < 135 mEq/L)**

```
Defisit Na = (Na target − Na aktual) × TBW

TBW (Total Body Water):
  Pria dewasa   : BB × 0,6
  Wanita dewasa : BB × 0,5
  Lansia pria   : BB × 0,5
  Lansia wanita : BB × 0,45
  Anak          : BB × 0,6–0,7

Contoh:
  Pria 70 kg, Na = 118 mEq/L, target 125 mEq/L (perbaiki perlahan)
  TBW = 70 × 0,6 = 42 L
  Defisit Na = (125 − 118) × 42 = 294 mEq Na
```

> [!danger] Batas Kecepatan Koreksi Na — MUTLAK
> **Maksimal 8–10 mEq/L per 24 jam** (beberapa guideline: 10–12 mEq/L/24 jam)
> Koreksi terlalu cepat → **Osmotic Demyelination Syndrome (ODS)** / Central Pontine Myelinolysis → paralisis, koma, kematian. Ini tidak bisa dibalik.
>
> Pengecualian: hiponatremia simtomatis berat (kejang, GCS turun) → NaCl 3%, 1–2 ml/kgBB bolus, naikan Na 1–2 mEq/L segera (hanya untuk stop kejang), lalu kembali ke koreksi lambat.

**Hipernatremia (Na > 145 mEq/L)**

```
Defisit Air Bebas = TBW × [(Na aktual ÷ Na normal) − 1]
                  = TBW × [(Na aktual ÷ 140) − 1]

Contoh:
  Wanita 60 kg, Na = 158 mEq/L
  TBW = 60 × 0,5 = 30 L
  Defisit = 30 × [(158 ÷ 140) − 1] = 30 × 0,129 = 3,85 L ≈ 3,9 L

Ganti dengan D5W atau NaCl 0,45%
Kecepatan koreksi: turunkan Na maksimal 10–12 mEq/L per 24 jam
```

#### Koreksi Kalium (K)

**Hipokalemia (K < 3,5 mEq/L)**

```
Estimasi defisit K:
  K 3,0–3,5 mEq/L → defisit ~100–200 mEq total body K
  K 2,5–3,0 mEq/L → defisit ~200–400 mEq
  K < 2,5 mEq/L   → defisit > 400 mEq (hipokalemia berat)

Pemberian KCl IV:
  Perifer : maksimal 10 mEq/jam (encer dalam 100–250 ml, tetes lambat — nyeri bila terlalu cepat)
  Sentral (CVC): maksimal 20 mEq/jam (monitoring EKG kontinu!)
  
Oral (bila pasien bisa minum):
  Kalium sitrat / KCl oral 40–80 mEq/hari dibagi 2–4 dosis
```

> [!danger] KCl JANGAN diberikan IV Bolus Langsung (Undiluted)
> Ini menyebabkan cardiac arrest dari hiperkalemia akut. KCl selalu diencerkan dalam cairan dan diberikan perlahan dengan monitoring EKG.

**Hiperkalemia (K > 5,5 mEq/L)**

| Kadar K | Klinis | Tindakan |
|---------|--------|---------|
| 5,5–6,0 | Asimtomatis | Batasi intake K, furosemide, kayexalate |
| 6,0–6,5 | Perubahan EKG (peaked T waves) | Kalsium glukonat + terapi di bawah |
| > 6,5 atau simtomatis | Aritmia, kelemahan | **DARURAT** → urutan di bawah |

```
Urutan tatalaksana hiperkalemia darurat:
  1. Kalsium Glukonat 10% — 10–20 ml IV pelan (3–5 menit) → stabilisasi membran sel jantung
     (Onset: 1–3 menit, durasi 30–60 menit — ini bukan menurunkan K, tapi melindungi jantung)
  2. Insulin 10 unit + Dextrose 50% 50 ml IV → masukkan K ke dalam sel (onset 15–30 menit)
  3. Natrium bikarbonat 50–100 mEq IV → bila ada asidosis (onset 15–30 menit)
  4. Salbutamol nebulasi 10–20 mg → masukkan K ke sel (onset 30 menit)
  5. Furosemide 40–80 mg IV → buang K lewat urin (perlu fungsi ginjal)
  6. Kayexalate (natrium polistiren sulfonat) oral/enema → buang K lewat saluran cerna (lambat, jam)
  7. Hemodialisis → bila semua di atas tidak cukup atau gagal ginjal berat
```

#### Koreksi Kalsium (Ca)

**Hipokalsemia (Ca total < 8,5 mg/dL atau Ca ion < 1,1 mmol/L)**

> [!warning] Koreksi Ca harus mempertimbangkan Albumin!
> Sekitar 40% kalsium terikat albumin. Pada hipoalbuminemia, Ca total rendah tapi Ca ion bisa normal.
>
> **Koreksi Ca berdasarkan albumin:**
> Ca terkoreksi = Ca terukur + 0,8 × (4 − Albumin pasien)
>
> Contoh: Ca terukur 7,8 mg/dL, albumin 2,5 g/dL
> Ca terkoreksi = 7,8 + 0,8 × (4 − 2,5) = 7,8 + 1,2 = **9,0 mg/dL → sebenarnya normal!**

```
Hipokalsemia simtomatis (Chvostek, Trousseau, tetani, kejang):
  Kalsium Glukonat 10% — 10–20 ml IV pelan dalam 10 menit → dapat diulang
  Lanjut infus: 10 ampul (100 ml) dalam 1L D5W atau NaCl, jalankan 50–100 ml/jam

Hipokalsemia ringan-sedang asimtomatis:
  Kalsium karbonat atau kalsium sitrat oral 1–3 g/hari + Vitamin D aktif (Calcitriol 0,25–0,5 mcg/hari)
```

---

## 💊 SEKSI B — OBAT-OBATAN DARURAT

---

### B1 — Vasopressor & Inotropik: Cara Hitung Drip

> [!abstract] Analogi: Vasopressor adalah "Pompa Darurat" yang Kamu Kendalikan
> Vasopressor bekerja per menit — dosis sedikit naik, tekanan darah naik; turunkan sedikit, bisa drop. Ini bukan obat yang bisa ditulis dosis sekali lalu ditinggal. Kamu harus tahu cara menghitung drip per mcg/kg/menit, cara menyesuaikan, dan kapan targetnya sudah tercapai.

#### Cara Membuat Larutan Vasopressor Standard

**Norepinefrin (Noradrenalin) — First-Line Septic Shock**

```
Konsentrasi standar: 4 mg dalam 250 ml NaCl 0,9% = 16 mcg/ml
(atau 8 mg dalam 250 ml = 32 mcg/ml bila perlu konsentrasi lebih tinggi)

Dosis awal: 0,1–0,2 mcg/kgBB/menit
Titrasi: naik 0,05–0,1 mcg/kgBB/menit tiap 5–10 menit sampai MAP ≥ 65 mmHg
Dosis umum: 0,01–3 mcg/kgBB/menit (dosis > 1 mcg/kgBB/menit = refrakter, tambah vasopressin)

Cara hitung kecepatan (ml/jam):
Kecepatan (ml/jam) = Dosis (mcg/kgBB/menit) × BB (kg) × 60 ÷ Konsentrasi (mcg/ml)

Contoh: pasien 60 kg, dosis 0,2 mcg/kgBB/menit, konsentrasi 16 mcg/ml
= 0,2 × 60 × 60 ÷ 16 = 720 ÷ 16 = 45 ml/jam
```

**Dopamin**

```
Konsentrasi standar: 200 mg dalam 250 ml = 800 mcg/ml

Efek berdasarkan dosis:
  2–5 mcg/kgBB/menit   : dopaminergik → vasodilatasi renal (efek ginjal minimal, kontroversial)
  5–10 mcg/kgBB/menit  : beta-1 → inotropik + kronotropik
  > 10 mcg/kgBB/menit  : alfa-1 → vasokonstriksi

Dosis awal septic shock: 5–10 mcg/kgBB/menit

Cara hitung kecepatan (ml/jam):
= Dosis × BB × 60 ÷ Konsentrasi
= 5 mcg/kgBB/mnt × 60 kg × 60 ÷ 800 mcg/ml = 22,5 ml/jam
```

**Epinefrin (Adrenalin)**

```
Untuk anafilaksis:
  IM (BUKAN IV): 0,3–0,5 mg (larutan 1:1000) di paha anterolateral
  Bisa diulang tiap 5–15 menit

Untuk cardiac arrest (ACLS):
  1 mg IV tiap 3–5 menit

Untuk vasopressor ICU:
  Konsentrasi: 1 mg dalam 250 ml = 4 mcg/ml
  Dosis: 0,01–0,5 mcg/kgBB/menit
  Cara hitung sama seperti norepinefrin
```

**Dobutamin — Inotropik Murni (Untuk Syok Kardiogenik)**

```
Konsentrasi standar: 250 mg dalam 250 ml = 1000 mcg/ml

Dosis: 2,5–20 mcg/kgBB/menit
Efek: meningkatkan curah jantung, sedikit vasodilatasi (turunkan afterload)
Perhatian: bisa sebabkan takikardia dan aritmia

Cara hitung:
Pasien 70 kg, dosis 5 mcg/kgBB/menit, konsentrasi 1000 mcg/ml:
= 5 × 70 × 60 ÷ 1000 = 21 ml/jam
```

> [!tip] Cara Mudah Ingat Konsentrasi Standard
> Buat kartu kecil dan tempel di dinding ruang jaga. Tiap RS bisa punya standar berbeda. Konfirmasi dengan perawat ICU/HCU di RSUD Karsa Husada Batu tentang konsentrasi yang dipakai di sana.

---

### B2 — Analgetik di IGD

#### Pilihan Analgetik Berdasarkan Intensitas Nyeri (WHO Ladder)

```
Ringan (VAS 1–3):
  Paracetamol IV 1 gram tiap 6–8 jam (maksimal 4 gram/hari)
  NSAID: Ketorolac 15–30 mg IV/IM tiap 6–8 jam (maksimal 5 hari)

Sedang (VAS 4–6):
  Paracetamol + NSAID
  Tramadol 50–100 mg IV pelan (risk mual, seizure pada dosis tinggi)

Berat (VAS 7–10):
  Morfin 0,05–0,1 mg/kgBB IV pelan (titrasi 2–4 mg tiap 5–10 menit)
  Fentanyl 1–2 mcg/kgBB IV (onset lebih cepat, durasi lebih pendek dari morfin)
```

**Rumus Dosis Opioid Praktis**

```
Morfin IV:
  Loading: 0,05–0,1 mg/kgBB → titrasi tiap 5–10 menit sampai nyeri terkontrol
  Maintenance: 1–4 mg/jam infus kontinu atau 2–4 mg IV PRN tiap 2–4 jam

  Contoh: Pasien 70 kg post-laparotomi, nyeri berat
  Loading: 0,05 × 70 = 3,5 mg → berikan 3–4 mg IV pelan, evaluasi setelah 10 menit
  Bila belum cukup, berikan 2 mg lagi, evaluasi, dst.

Fentanyl IV:
  1–2 mcg/kgBB IV → onset 1–2 menit, durasi 30–60 menit
  Pasien 70 kg: 70–140 mcg → berikan 50–100 mcg pelan tiap 5 menit sampai nyeri terkontrol
```

> [!danger] Nalokson — Antidot Opioid
> Bila terjadi depresi napas dari opioid (RR < 12, SpO₂ turun, pin-point pupil, tidak sadar):
> **Nalokson 0,4 mg IV** → bisa diulang tiap 2–3 menit sampai 3× (total 1,2 mg)
> Onset sangat cepat (1–2 menit). Durasi pendek (30–45 menit) → opioid bisa "kembali" bekerja → monitor ketat setelah pemberian.

#### Anestesi Lokal — Dosis Maksimal

```
Lidokain tanpa epinefrin : 3–4 mg/kgBB (maksimal 300 mg)
Lidokain dengan epinefrin: 7 mg/kgBB (maksimal 500 mg)

Bupivakain              : 2,5 mg/kgBB (maksimal 175 mg) → JANGAN pakai dengan epinefrin IV
Ropivakain              : 3 mg/kgBB (lebih aman dari bupivakain untuk kardiotoksisitas)

JANGAN gunakan epinefrin di:
  → Jari tangan/kaki, hidung, telinga, penis → vasokonstriksi → iskemia → nekrosis

Contoh untuk hecting luka 5 cm:
  Pasien 70 kg, Lidokain 2% (20 mg/ml), tanpa epinefrin
  Dosis maks = 70 × 3 = 210 mg = 10,5 ml larutan 2%
  Untuk luka 5 cm, biasanya cukup 3–5 ml → jauh di bawah batas aman
```

---

### B3 — Antibiotik Empirik Bedah

> [!abstract] Prinsip: Tepat Sasaran, Jangan Berlebihan
> Antibiotik empirik dipilih berdasarkan bakteri yang paling mungkin sesuai sumber infeksi — bukan "paling kuat yang ada". Terlalu luas tanpa indikasi → resistensi bakteri. Terlalu sempit → terapi gagal.

#### Panduan Antibiotik Empirik per Kondisi Bedah

| Kondisi | Bakteri Tersangka | Antibiotik Empirik | Dosis |
|---------|-----------------|-------------------|-------|
| **Peritonitis / perforasi GIT** | E. coli, Klebsiella, Bacteroides, Enterococcus | Ceftriaxone + Metronidazole | Ceftriaxone 1–2 g/24 jam IV + Metro 500 mg/8 jam IV |
| **Kolesistitis / kolangitis** | E. coli, Klebsiella, Enterococcus | Ceftriaxone + Metronidazole | Sama di atas |
| **Kolangitis berat / ICU** | + Pseudomonas coverage | Pip-Tazo atau Meropenem | Pip-Tazo 4,5 g/8 jam IV atau Meropenem 1 g/8 jam IV |
| **Abses intra-abdomen** | Anaerob + gram negatif | Pip-Tazo atau Ceftriaxone + Metro | Sesuai di atas |
| **Urosepsis** | E. coli, Klebsiella, Pseudomonas | Ceftriaxone atau Cefepime | Ceftriaxone 2 g/24 jam IV atau Cefepime 1–2 g/8–12 jam IV |
| **Fraktur terbuka Grade I–II** | S. aureus, Streptococcus | Cefazolin | 1–2 g IV/8 jam, mulai dalam 1 jam dari injury |
| **Fraktur terbuka Grade III** | + gram negatif | Cefazolin + Gentamisin | Cefazolin 1–2 g/8 jam + Gentamisin 5 mg/kgBB/24 jam |
| **Fournier's Gangrene** | Polimikrobial: aerob + anaerob ± jamur | Meropenem + Metronidazole ± Flukonazol | Meropenem 1 g/8 jam + Metro 500 mg/8 jam |
| **Luka bakar terinfeksi** | S. aureus, Pseudomonas | Pip-Tazo atau Cefepime | Pip-Tazo 4,5 g/8 jam IV |
| **Septic arthritis** | S. aureus | Cloxacillin atau Cefazolin | Cloxacillin 2 g/6 jam IV atau Cefazolin 2 g/8 jam IV |
| **Osteomielitis akut** | S. aureus | Cloxacillin atau Cefazolin | Cloxacillin 150–200 mg/kgBB/hari IV (anak) |
| **Abses otak** | Streptococcus, Bacteroides, gram negatif | Ceftriaxone + Metronidazole ± Vancomycin | Ceftriaxone 2 g/12 jam + Metro 500 mg/8 jam |

> [!warning] Konfirmasi Pola Resistensi Lokal RSUD Karsa Husada Batu
> Panduan di atas adalah panduan umum. Pola resistensi E. coli dan Klebsiella terhadap cephalosporin di Indonesia sudah tinggi di beberapa daerah. Konsultasikan dengan bagian mikrobiologi atau dokter senior untuk pola lokal. Selalu ambil kultur SEBELUM antibiotik bila memungkinkan.

#### Profilaksis Antibiotik Pre-Operatif

```
Prinsip: satu dosis, 30–60 menit sebelum insisi kulit

Operasi bersih (herniorafi, tiroidektomi):
  Cefazolin 1–2 g IV

Operasi bersih-terkontaminasi (kolesistektomi, apendektomi non-perforasi):
  Cefazolin 1–2 g IV + Metronidazole 500 mg IV

Operasi kolorektal elektif:
  Cefazolin 1–2 g + Metronidazole 500 mg IV (+ bowel prep oral opsional)

Redose intraoperatif:
  Bila operasi > 3–4 jam atau EBL > 1500 ml → ulangi dosis profilaksis
```

---

### B4 — Antikoagulan: Heparin Drip & Reversal

#### Unfractionated Heparin (UFH) Drip

```
Indikasi: DVT, PE, sindrom koroner akut, fibrilasi atrial dengan trombus, oklusi arteri akut

Dosis loading: 80 unit/kgBB IV bolus (atau 5.000 unit flat dose)
Dosis maintenance: 18 unit/kgBB/jam infus kontinu

Cara membuat drip:
  25.000 unit UFH dalam 250 ml NaCl 0,9% = 100 unit/ml

Contoh: Pasien 70 kg
  Loading: 80 × 70 = 5.600 unit → berikan 56 ml larutan 100 unit/ml bolus
  Maintenance: 18 × 70 = 1.260 unit/jam → 12,6 ml/jam → bulatkan 13 ml/jam

Monitoring: APTT target 60–100 detik (1,5–2,5× normal)
  Cek APTT 6 jam setelah mulai atau perubahan dosis
  Sesuaikan dosis berdasarkan nomogram heparin
```

#### LMWH (Low Molecular Weight Heparin) — Enoxaparin

```
Terapi DVT/PE:
  1 mg/kgBB subkutan tiap 12 jam (atau 1,5 mg/kgBB tiap 24 jam)

Profilaksis DVT:
  0,4 ml (4.000 anti-Xa unit) subkutan sekali sehari

Tidak perlu monitoring rutin kecuali pada:
  Gagal ginjal berat (GFR < 30) → sesuaikan dosis atau ganti UFH
  Kehamilan → cek anti-Xa level
  BB ekstrem (< 45 kg atau > 150 kg)
```

#### Reversal Antikoagulan

```
UFH → Protamin Sulfat
  1 mg protamin netralisir ~100 unit UFH yang diberikan dalam 2–3 jam terakhir
  Dosis maksimal single dose: 50 mg
  Berikan IV pelan (10–15 menit) → reaksi anafilaktoid bila terlalu cepat

LMWH → Protamin (parsial, ~60–75% efektif)
  1 mg protamin per 1 mg enoxaparin yang diberikan dalam 8 jam terakhir

Warfarin → Vitamin K + FFP (bila emergensi) atau PCC (Prothrombin Complex Concentrate)
  Warfarin + perdarahan aktif: Vitamin K 10 mg IV pelan + FFP 10–15 ml/kgBB
  Atau PCC 25–50 unit/kgBB (lebih cepat dan volume lebih kecil dari FFP)

DOAC (Dabigatran) → Idarucizumab 5 g IV
DOAC (Rivaroxaban/Apixaban) → Andexanet alfa (bila tersedia) atau PCC
```

---

### B5 — Obat Emergensi Penting Lainnya

#### Manitol 20% — untuk Edema Serebri / TIK Tinggi

```
Dosis: 0,25–1 g/kgBB IV bolus cepat (dalam 10–20 menit)
Onset: 15–30 menit
Durasi: 4–6 jam

Contoh: Pasien 60 kg, TBI berat, tanda herniasi
  Dosis: 0,5 × 60 = 30 g Manitol 20%
  Volume: 30 g ÷ 0,2 g/ml = 150 ml Manitol 20%
  → Berikan 150 ml dalam 10–15 menit

Monitoring:
  Osmolalitas serum target: 300–320 mOsm/kg
  Jika osmolalitas > 320 → stop (risiko gagal ginjal)
  Serum Na, urine output ketat

Dapat diulang tiap 4–6 jam bila perlu (cek osmolalitas sebelum dosis berikutnya)
```

#### NaCl 3% — Alternatif/Tambahan Manitol

```
Dosis untuk edema serebri:
  150–250 ml IV dalam 30 menit (bolus)
  Atau infus kontinu 1–2 ml/kgBB/jam

Target Na serum: 150–155 mEq/L (mild hypernatremia dipertahankan untuk efek osmotik)

Untuk hiponatremia simtomatis (kejang aktif):
  1–2 ml/kgBB NaCl 3% IV dalam 10–20 menit
  Naikan Na 1–2 mEq/L untuk hentikan kejang, lalu koreksi lambat
```

#### Tranexamic Acid (TXA)

```
Untuk trauma dengan perdarahan (CRASH-2 trial):
  1 gram IV dalam 10 menit (bolus pelan)
  → HARUS diberikan dalam 3 jam pertama dari cedera
  → Setelah 3 jam: tidak efektif, mungkin berbahaya (meningkatkan mortalitas)
  Dosis kedua: 1 gram IV dalam 8 jam kemudian

Untuk perdarahan post-partum, operasi elektif:
  1 gram IV pelan

JANGAN pakai bila:
  Trombosis aktif (DVT, PE, MI)
  Hematuria (bisa menyumbat ureter dengan bekuan)
```

#### Furosemid — Diuretik Loop

```
Dosis dewasa:
  IV: 20–40 mg pelan, bisa dinaikkan sampai 80–200 mg untuk edema refrakter
  Onset: 5–15 menit (IV), 30–60 menit (oral)

Untuk edema paru akut:
  40–80 mg IV bolus → evaluasi urine output dalam 30–60 menit

Untuk mengkoreksi cairan berlebih (overload):
  1 mg/kgBB IV → titrasi sampai urine output target tercapai

Perhatian:
  Dapat menyebabkan hipokalemia, hiponatremia, hipomagnesemia → cek elektrolit
  Gagal ginjal: mungkin butuh dosis lebih tinggi (dosis lebih besar tapi tetap hati-hati)
```

---

## 📊 SEKSI C — MONITORING & INTERPRETASI

---

### C1 — Tanda Vital Normal per Usia

> [!info] Konteks: Nilai Normal Berbeda-Beda — Jangan Pakai Angka Dewasa untuk Anak
> Neonatus dengan HR 80 = bradikardia. Anak 2 tahun dengan RR 36 = normal. Interpretasi vital sign yang salah karena pakai referensi usia yang keliru bisa menyebabkan over-treatment atau miss diagnosis kritis.

#### Tabel Tanda Vital Normal per Usia

| Usia | HR (bpm) | RR (/mnt) | TD Sistolik (mmHg) | TD Minimal Dapat Diterima |
|------|---------|-----------|-------------------|--------------------------|
| **Neonatus (0–28 hari)** | 100–160 | 40–60 | 60–90 | > 60 |
| **Bayi (1–12 bulan)** | 100–160 | 30–60 | 70–100 | > 70 |
| **Toddler (1–3 tahun)** | 90–150 | 24–40 | 80–110 | > 70 + (2 × usia tahun) |
| **Prasekolah (3–5 tahun)** | 80–140 | 22–34 | 80–110 | > 70 + (2 × usia tahun) |
| **Sekolah (6–12 tahun)** | 70–120 | 18–30 | 90–120 | > 80 |
| **Remaja (12–18 tahun)** | 60–100 | 12–20 | 100–130 | > 90 |
| **Dewasa** | 60–100 | 12–20 | 100–140 / 60–90 | MAP ≥ 65 mmHg |
| **Lansia (> 65 tahun)** | 60–100 | 12–20 | Sama dewasa (tapi hipertensi lebih umum) | MAP ≥ 70 mmHg |

#### Rumus TD Sistolik Minimal Anak

```
Tekanan sistolik minimal yang dapat diterima pada anak:
  < 1 tahun  : > 70 mmHg
  1–10 tahun : > 70 + (2 × usia dalam tahun) mmHg
  > 10 tahun : > 90 mmHg

Contoh:
  Anak 5 tahun TD 88/54 → minimal = 70 + (2×5) = 80 → TD 88 masih oke (tapi perhatikan tren!)
  Anak 5 tahun TD 72/40 → di bawah minimal → tanda syok → tindakan segera
```

---

### C2 — Oksigenasi: Alat O₂ & Target Saturasi

#### Pilihan Alat O₂ dan Flow Rate

| Alat | Flow O₂ (L/mnt) | FiO₂ yang Dicapai | Indikasi |
|------|----------------|-------------------|---------|
| **Nasal Kanul** | 1–6 | 24–44% | Hipoksemi ringan, nyaman untuk jangka panjang |
| **Simple Face Mask** | 5–10 | 35–60% | Hipoksemi sedang, butuh FiO₂ > 44% |
| **Non-Rebreather Mask (NRM)** | 10–15 | 60–90% | Hipoksemi berat, penanganan awal semua pasien kritis |
| **Venturi Mask** | 2–15 | 24–60% (terkontrol) | PPOK (butuh FiO₂ terkontrol, jangan terlalu tinggi) |
| **BVM (Bag-Valve-Mask)** | 10–15 | ~100% | Pasien apnea atau butuh ventilasi positif |
| **Intubasi + Ventilator** | Sesuai setting | 21–100% (FiO₂ diatur) | GCS ≤ 8, gagal napas, kebutuhan kontrol napas |

#### Target SpO₂ per Kondisi Klinis

```
SpO₂ target umum         : ≥ 95%
TBI                       : ≥ 95% (hipoksia = cedera sekunder)
Stroke                    : 94–99% (jangan supra-normal → oksidatif stress)
PPOK (eksaserbasi)        : 88–92% (hindari menekan drive hipoksik)
Syok/resusitasi aktif     : ≥ 95%
Post-cardiac arrest       : 94–96% (hindari hiperoksemia)
Neonatus prematur         : 90–95% (hiperoksemia → retinopathy of prematurity)
Luka bakar dengan CO      : 100% NRM (CO poisoning: SpO₂ tidak akurat, target 100% O₂ selalu)
```

> [!danger] SpO₂ Normal TIDAK Berarti Oksigenasi Jaringan Normal
> CO poisoning: SpO₂ bisa 99% tapi pasien hipoksia berat (karboksihemoglobin terdeteksi sama seperti oksihemoglobin oleh pulse oximeter). Ukur COHb dengan co-oximetry atau blood gas yang dikalibrasi khusus.

---

### C3 — Urine Output: Cara Hitung & Interpretasi

#### Target Urine Output per Kondisi

```
Normal / Post-op umum         : 0,5 ml/kgBB/jam (dewasa) = ~30–50 ml/jam
Resusitasi syok hipovolemik   : 0,5–1,0 ml/kgBB/jam
Resusitasi luka bakar (Baxter): 0,5–1,0 ml/kgBB/jam → panduan utama titrasi cairan Baxter
Rhabdomiolisis                : 1–3 ml/kgBB/jam (paksa diuresis untuk flush mioglobin)
TBI                           : 0,5 ml/kgBB/jam (jangan berlebihan → edema otak)
Anak                          : 1 ml/kgBB/jam
Neonatus                      : 2 ml/kgBB/jam
```

#### Definisi Oliguria & Langkah Evaluasi

```
Oliguria: < 0,5 ml/kgBB/jam selama ≥ 2 jam berturut-turut

Langkah evaluasi oliguria:
  1. Cek kateter: tersumbat? terlipat? posisi salah? → flush kateter dahulu
  2. Cek status cairan: apakah dehidrasi/kurang volume? → passive leg raise test
  3. Cek tekanan darah: MAP < 65? → perbaiki perfusi ginjal
  4. Cek urin rutin: proteinuria, hematuria, silinder → arah diagnosis AKI
  5. Cek urea/kreatinin: AKI pre-renal vs renal vs post-renal
  
Pre-renal:
  Na urin < 20 mEq/L
  FENa < 1%   [FENa = (Na urin × Kr serum) ÷ (Na serum × Kr urin) × 100]
  Urea urin/serum > 20
  → Respons terhadap pemberian cairan

AKI renal (tubular necrosis):
  Na urin > 40 mEq/L
  FENa > 2%
  Silinder granular di urinalisis
  → Tidak respons dengan cairan
```

---

### C4 — Skoring Klinis yang Wajib Hafal di Semua Stase

#### qSOFA (Quick Sepsis-Related Organ Failure Assessment)

```
Skor 1 poin untuk tiap kriteria:
  □ RR ≥ 22/menit
  □ GCS berubah (< 15)
  □ Tekanan sistolik ≤ 100 mmHg

qSOFA ≥ 2 → kemungkinan sepsis → evaluasi SOFA score lengkap, mulai resusitasi
```

#### Alvarado Score (Apendisitis)

```
M — Migration nyeri ke RLQ     : 1 poin
A — Anoreksia                   : 1 poin
N — Nausea/vomiting             : 1 poin
T — Tenderness McBurney         : 2 poin
R — Rebound tenderness          : 1 poin
E — Elevasi suhu > 37,3°C       : 1 poin
L — Leukositosis > 10.000       : 2 poin
S — Shift to left               : 1 poin
Total: 10 poin

≤ 4 → risiko rendah, pertimbangkan pulang/observasi
5–6 → meragukan, USG/CT scan
≥ 7 → risiko tinggi → apendektomi
```

#### Kocher Criteria (Septic Arthritis Anak vs Transient Synovitis)

```
1 poin untuk tiap:
  □ Demam > 38,5°C
  □ ESR > 40 mm/jam
  □ WBC > 12.000/μL
  □ Non-weight-bearing
  □ CRP > 2 mg/dL (bila tersedia)

0 poin  : 0,2% kemungkinan septic arthritis
1 poin  : 3%
2 poin  : 40%
3 poin  : 93%
4–5 poin: > 99% → drainase segera tanpa tunggu konfirmasi lebih lanjut
```

#### Blatchford Score (UGIB — Perlu Endoskopi?)

```
Komponen dan poin:
  BUN ≥ 25 mmol/L            : 6 poin
  BUN 10–25 mmol/L           : 2–4 poin
  Hb < 10 g/dL (pria)       : 6 poin
  Hb < 12 g/dL (pria)       : 3 poin
  Hb < 10 g/dL (wanita)     : 6 poin
  TD sistolik < 90 mmHg     : 3 poin
  HR ≥ 100 bpm               : 1 poin
  Melena                     : 1 poin
  Sinkop                     : 2 poin
  Penyakit hati              : 2 poin
  Gagal jantung              : 2 poin

Skor 0 → risiko sangat rendah → rawat jalan mungkin aman
Skor ≥ 1 → rawat inap + endoskopi
```

#### Ranson Criteria (Pankreatitis Akut — Prediksi Keparahan)

```
Saat Masuk:
  □ Usia > 55 tahun         : 1 poin
  □ Leukosit > 16.000/μL   : 1 poin
  □ Glukosa > 200 mg/dL    : 1 poin
  □ LDH > 350 IU/L         : 1 poin
  □ AST > 250 IU/L         : 1 poin

Dalam 48 Jam:
  □ Ht turun > 10%          : 1 poin
  □ BUN naik > 5 mg/dL     : 1 poin
  □ Ca serum < 8 mg/dL     : 1 poin
  □ PaO₂ < 60 mmHg        : 1 poin
  □ Base deficit > 4 mEq/L : 1 poin
  □ Fluid sequestration > 6 L : 1 poin

< 3 poin  : pankreatitis ringan, mortalitas < 1%
3–4 poin  : mortalitas ~15%
5–6 poin  : mortalitas ~40%
> 6 poin  : mortalitas ~100%
```

---

## 🔥 SEKSI D — KALKULASI LUKA BAKAR

---

### D1 — Rule of Nine & Metode Lain

> [!abstract] Analogi: Tubuh Dibagi-Bagi Seperti Pizza
> Rule of Nine membagi permukaan tubuh menjadi bagian-bagian yang masing-masing 9% (atau kelipatannya). Bayangkan tubuh sebagai pizza yang dipotong — tiap irisan punya ukuran yang bisa kamu hitung.

#### Rule of Nine — Dewasa

```
Area Tubuh               TBSA (%)
─────────────────────────────────
Kepala + Leher           9%
Dada depan               9%
Perut depan              9%
Punggung atas            9%
Punggung bawah           9%
Lengan kanan (seluruh)   9%
Lengan kiri (seluruh)    9%
Paha kanan               9%
Tungkai bawah kanan      9%
Paha kiri                9%
Tungkai bawah kiri       9%
Genitalia/Perineum       1%
─────────────────────────────────
TOTAL                    100%
```

> [!warning] Rule of Nine TIDAK Akurat untuk Anak — Pakai Lund-Browder!
> Pada anak, kepala relatif lebih besar dan kaki lebih kecil dibanding dewasa. Persentase berubah sesuai usia.

#### Koreksi untuk Anak (Lund-Browder yang Disederhanakan)

| Area | Bayi < 1 th | 5 th | 10 th | Dewasa |
|------|------------|------|-------|--------|
| Kepala | 18% | 13% | 11% | 9% |
| Paha (tiap sisi) | 5,5% | 6,5% | 7,5% | 9% |
| Tungkai bawah (tiap sisi) | 3,5% | 4,5% | 6% | 7% |
| Badan depan | 18% | 18% | 18% | 18% |
| Badan belakang | 18% | 18% | 18% | 18% |

#### Palm Method — Untuk Luka Bakar Tidak Beraturan

```
Telapak tangan pasien (termasuk jari-jari) = 1% TBSA

Berguna untuk:
  Luka bakar tersebar tidak merata (percikan, kontak singkat)
  Luka bakar yang sulit diukur dengan Rule of Nine
  Estimasi cepat di lapangan

Contoh:
  Luka bakar dari percikan minyak panas di lengan dan perut
  Estimasi dengan "berapa telapak tangan yang bisa menutupi area luka?"
  = 7 telapak → 7% TBSA
```

> [!tip] Jangan Masukkan Derajat I dalam Perhitungan TBSA
> Untuk keperluan resusitasi Baxter, hitung **HANYA derajat IIA, IIB, dan III**. Derajat I (kemerahan saja, tanpa bula) tidak dimasukkan karena tidak memerlukan penggantian cairan seperti luka bakar yang lebih dalam.

---

### D2 — Formula Baxter (Parkland) — Step by Step

> [!abstract] Analogi: Baxter Formula adalah "Resep Cairan untuk 24 Jam Pertama"
> Luka bakar besar menyebabkan kebocoran kapiler masif — cairan keluar dari pembuluh darah ke jaringan interstitial dan ke permukaan luka. Tubuh kehilangan volume intravaskular cepat. Formula Baxter adalah panduan berapa banyak cairan yang harus dimasukkan dalam 24 jam pertama untuk mencegah syok.

#### Formula Baxter

```
Total cairan 24 jam = 4 ml × Berat Badan (kg) × % TBSA (derajat II dan III)

Pembagian:
  ½ total → diberikan dalam 8 jam PERTAMA
  ½ total → diberikan dalam 16 jam BERIKUTNYA

PENTING: 8 jam dihitung dari WAKTU KEJADIAN, bukan dari waktu tiba di IGD!

Cairan: Ringer Laktat (RL) — bukan NaCl 0,9% (hindari asidosis hiperkloremik)
```

#### Langkah Kalkulasi Step by Step

**Langkah 1: Tentukan TBSA (derajat II + III saja)**
**Langkah 2: Hitung total cairan 24 jam**
**Langkah 3: Bagi ½ untuk 8 jam pertama**
**Langkah 4: Hitung mundur berapa jam sejak kejadian**
**Langkah 5: Tentukan kecepatan drip yang harus dikejar**

#### Contoh Kasus 1 — Datang Segera Setelah Kejadian

> Pria 60 kg, luka bakar dari ledakan kompor gas, terkena di dada depan (9%) + lengan kanan (9%) + perut depan (9%), mayoritas derajat IIB–III. Tiba di IGD 30 menit setelah kejadian.
>
> **TBSA = 27%** (9 + 9 + 9)
>
> **Total cairan 24 jam = 4 × 60 × 27 = 6.480 ml RL**
>
> **½ pertama (8 jam) = 3.240 ml**
> Karena baru 30 menit sejak kejadian, masih punya 7,5 jam untuk ½ pertama.
> Kecepatan = 3.240 ml ÷ 7,5 jam = **432 ml/jam**
>
> **½ kedua (16 jam berikutnya) = 3.240 ml**
> Kecepatan = 3.240 ÷ 16 = **202 ml/jam**

#### Contoh Kasus 2 — Datang Terlambat (Sudah 4 Jam Setelah Kejadian)

> Wanita 50 kg, luka bakar air panas dari pabrik, 35% TBSA derajat IIA–IIB. Tiba di IGD 4 jam setelah kejadian karena dibawa dari daerah jauh.
>
> **Total cairan 24 jam = 4 × 50 × 35 = 7.000 ml RL**
>
> **½ pertama untuk 8 jam dari kejadian = 3.500 ml**
> Sudah 4 jam terlewat → sisa 4 jam untuk berikan 3.500 ml
> Kecepatan = 3.500 ÷ 4 = **875 ml/jam** (harus "kejar" cairan yang terlambat)
>
> **½ kedua (16 jam berikutnya) = 3.500 ml**
> Kecepatan = 3.500 ÷ 16 = **218 ml/jam**

#### Titrasi Baxter Berdasarkan Urine Output

> [!success] Angka Baxter Hanya Panduan Awal — Yang Utama adalah Urine Output
> Formula memberikan starting point. Tapi tiap pasien berbeda. Titrasi berdasarkan:
>
> **Target urine output: 0,5–1 ml/kgBB/jam**
>
> Urine output < 0,5 ml/kgBB/jam → percepat cairan (+20% dari rate saat ini)
> Urine output > 1 ml/kgBB/jam → perlambat cairan (−20% dari rate saat ini)
> Re-evaluasi tiap 1–2 jam dan sesuaikan

#### Hari Kedua dan Seterusnya

```
24 jam kedua:
  Kristaloid: ½ dari total hari pertama
  Koloid (albumin 5%): 0,3–0,5 ml/kgBB/% TBSA (mulai setelah 18–24 jam, saat barrier vaskular membaik)
  Dextrose 5%: untuk ganti insensible water loss (500–1000 ml/hari pada luka bakar besar)

Contoh lanjutan kasus 1 (pria 60 kg, 27% TBSA):
  Hari 1 total: 6.480 ml
  Hari 2 kristaloid: 6.480 ÷ 2 = 3.240 ml RL
  Hari 2 koloid: 0,4 × 60 × 27 = 648 ml albumin 5%
```

---

### D3 — Kalkulasi Khusus: Luka Bakar Anak & Inhalasi

#### Modifikasi untuk Anak (Galveston Formula)

```
Total cairan 24 jam = 5.000 ml/m² luka bakar + 2.000 ml/m² luas permukaan tubuh total

Luas permukaan tubuh (BSA) dapat dihitung dengan:
  BSA (m²) ≈ √(BB kg × Tinggi cm ÷ 3.600)

Atau estimasi cepat:
  < 10 kg  : BB × 0,03 + 0,05
  10–40 kg : BB × 0,02 + 0,19
  > 40 kg  : Pakai formula Mosteller

Pembagian sama dengan Baxter: ½ dalam 8 jam pertama, ½ dalam 16 jam berikutnya
Cairan: RL + Dextrose 5% (anak butuh glukosa karena glikogen lebih terbatas)
```

#### Luka Bakar Inhalasi — Tambahan Cairan

```
Luka bakar inhalasi meningkatkan kebutuhan cairan 30–50% dari kalkulasi Baxter standar.

Contoh:
  Pasien 60 kg, 30% TBSA + inhalasi
  Baxter standar = 4 × 60 × 30 = 7.200 ml
  Tambahan inhalasi = +30–50% = tambah 2.160–3.600 ml
  Total = 9.360–10.800 ml/24 jam → titrasi ketat dengan UO target

Tanda inhalasi yang harus dicurigai:
  Terbakar di ruang tertutup, bulu hidung hangus, suara serak, sputum jelaga
  → intubasi profilaktik sebelum edema airway memburuk
  → SpO₂ bisa normal palsu (CO poisoning) → berikan O₂ 100% NRM sampai COHb terkonfirmasi normal
```

---

## 🦴 SEKSI E — KALKULASI ORTOPEDI

---

### E1 — Estimasi Blood Loss per Fraktur

> [!abstract] Analogi: Tulang yang Patah Seperti Pipa yang Bocor di Dalam Tembok
> Kamu tidak bisa melihat langsung berapa darah yang keluar ke jaringan sekitar fraktur. Tapi kamu bisa estimasi berdasarkan tulang mana yang patah — karena tiap tulang punya kapasitas kehilangan darah yang khas.

#### Tabel Estimasi Blood Loss per Lokasi Fraktur

| Lokasi Fraktur | Estimasi Blood Loss |
|---------------|-------------------|
| **Radius/Ulna** | 250–500 ml |
| **Humerus** | 500–750 ml |
| **Tibia/Fibula** | 500–1.000 ml |
| **Femur shaft (tertutup)** | 800–1.500 ml |
| **Pelvis (stabil)** | 500–1.500 ml |
| **Pelvis (tidak stabil)** | 1.500–4.000 ml (bisa masif!) |
| **Fraktur terbuka** | Tambahkan 30–50% dari estimasi tertutup |

> [!danger] Jangan Tertipu "Tidak Ada Luka Terbuka"
> Fraktur femur tertutup pada pasien yang tampak "baik-baik saja" bisa sudah kehilangan 1–1,5 liter darah ke dalam paha. Pemuda berotot besar dengan fraktur femur bilateral bisa kehilangan 2–3 liter darah secara internal sebelum tekanan darahnya turun. Selalu resusitasi berdasarkan estimasi blood loss, bukan penampilan luar saja.

---

### E2 — Traksi: Jenis & Berat Beban

#### Traksi Kulit (Skin Traction)

```
Indikasi:
  Anak dengan fraktur femur (< 2–3 tahun)
  Sementara sebelum operasi (NOF lansia, femur dewasa muda)
  Reduksi fraktur kecil (Bryant traction untuk anak < 2 tahun)

Berat beban:
  Maksimal 4–6 kg (dewasa) — lebih dari itu merusak kulit
  Anak: maksimal 1–2 kg

Cara pemasangan:
  Traksi tape (plester khusus) atau foam boot sepanjang tibia-ankle
  Berikan traksi searah sumbu tulang (sedikit elevasi kaki untuk counter-traction)
  Periksa sirkulasi distal tiap 2 jam (nadi, CRT, sensasi)
```

#### Traksi Skeletal (Skeletal Traction)

```
Indikasi:
  Fraktur femur dewasa (sambil tunggu ORIF)
  Fraktur subtrokanterik
  Situasi di mana operasi ditunda

Pin melalui:
  Distal femur (condyl) → untuk fraktur proksimal femur/subtrokanterik
  Proksimal tibia (tuberkulum tibia) → untuk fraktur shaft femur (paling sering)
  Kalkaneus → untuk fraktur tibia proksimal / distal femur

Berat beban skeletal:
  1/7 berat badan sebagai panduan awal (misal BB 70 kg → 10 kg)
  Mulai dengan 1/10 BB → evaluasi alignment di foto → sesuaikan

Monitoring harian:
  Nadi distal, sensori, gerak → komplikasi pin (infeksi pin tract, migrasi)
  Foto follow-up → konfirmasi alignment
```

---

### E3 — Prinsip Gips & Splint

#### Jenis Immobilisasi dan Kapan Dipakai

```
AKUT (< 48–72 jam setelah cedera, masih ada edema):
  → SPLINT / POSTERIOR SLAB (tidak sirkumferensial)
  → Kenapa? Edema yang berkembang di dalam gips penuh bisa menyebabkan sindrom kompartemen

SETELAH EDEMA STABIL (> 48–72 jam):
  → Gips penuh (sirkumferensial) atau functional brace
```

#### Ketebalan Gips (Lapisan Plaster of Paris)

```
Orang dewasa normal:
  Tubuh besar / beban tinggi (gips tungkai bawah, femur): 10–12 lapisan
  Tubuh kecil (gips lengan bawah): 8–10 lapisan

Anak-anak:
  6–8 lapisan (lebih sedikit karena beban lebih ringan)

Ingat: tambahkan padding (wool/cotton) yang cukup terutama di tulang-tulang penonjol:
  Maleolus medial/lateral, kalkaneus (tumit), patela, olecranon, epicondylus humeri
  → Padding kurang → pressure sore → nekrosis kulit bawah gips
```

#### Waktu Angkat Gips (Panduan Umum)

| Fraktur | Waktu Gips/Splint |
|---------|------------------|
| Colles' (radius distal) | 6 minggu |
| Klavikula (arm sling) | 4–6 minggu |
| Jari tangan (non-displaced) | 3–4 minggu |
| Scaphoid | 8–12 minggu (bahkan lebih lama) |
| Tibia (non-displaced) | 8–12 minggu |
| Fraktur iga (konservatif) | Analgetik, bukan gips — tidak digips! |

---

## 👶 SEKSI F — KALKULASI PEDIATRI

---

### F1 — Estimasi Berat Badan Anak

> [!abstract] Kenapa Penting: Salah BB = Salah Dosis = Bahaya
> Di IGD darurat dengan anak tidak sadar dan tidak ada wali yang tahu berat badan anak, kamu perlu estimasi cepat untuk hitung dosis obat, cairan, dan intervensi. Ini bukan opsional — ini wajib.

#### Rumus Estimasi BB Anak per Usia

```
Bayi 3–12 bulan:
  BB (kg) = (usia bulan ÷ 2) + 4

Anak 1–5 tahun:
  BB (kg) = 2 × (usia tahun + 4)
  atau: BB (kg) = (usia tahun × 2) + 8

Anak 6–12 tahun:
  BB (kg) = 3 × usia tahun

Anak > 12 tahun:
  Gunakan tabel BMI atau estimasi visual

Contoh:
  Anak 3 tahun → 2 × (3+4) = 14 kg
  Anak 8 tahun → 3 × 8 = 24 kg
```

> [!tip] Broselow Tape — Alat Terbaik Kalau Tersedia
> Broselow tape mengukur panjang badan anak dari kepala ke tumit → memberikan estimasi BB + dosis obat + ukuran alat (ETT, NGT, IV) sekaligus. Lebih akurat dari formula usia. Kalau ada di IGD RSUD Karsa Husada Batu → pakai ini.

---

### F2 — Ukuran Endotracheal Tube (ETT) Anak

```
Ukuran ETT (diameter dalam, mm):
  Neonatus prematur : 2,5–3,0
  Neonatus aterm   : 3,0–3,5
  Usia 1–2 tahun   : 3,5–4,0
  Usia > 2 tahun   : (usia ÷ 4) + 4

Contoh:
  Anak 6 tahun → (6 ÷ 4) + 4 = 1,5 + 4 = 5,5 mm

Kedalaman insersi ETT (cm dari bibir):
  = Ukuran ETT × 3
  Contoh: ETT 5,5 mm → insersi 5,5 × 3 = 16,5 cm dari bibir

Alternatif kedalaman: usia ÷ 2 + 12

Pipa dengan cuff vs tanpa cuff:
  < 8 tahun: tradisional tanpa cuff (tapi pedoman modern makin banyak pakai cuff kecil)
  ≥ 8 tahun: pakai cuff (diameter lebih kecil 0,5 mm dari formula tanpa cuff)
```

---

### F3 — Resusitasi Cairan Anak

#### Initial Fluid Resuscitation Pediatri (Syok)

```
Bolus cairan:
  20 ml/kgBB RL atau NaCl 0,9% dalam 20 menit → IV atau IO
  Evaluasi setelah bolus pertama
  Ulangi hingga 3× (60 ml/kgBB total) bila belum respons

Syok septik/distributif:
  Hati-hati cairan berlebih → dapat memperberat ARDS dan disfungsi miokard
  Setelah 2–3 bolus tanpa respons → mulai vasopressor (dopamin atau epinefrin)

Syok hipovolemik/hemoragik berat:
  Setelah 2 bolus kristaloid tanpa respons → pertimbangkan transfusi PRBCs 10 ml/kgBB
```

#### Maintenance Cairan Pediatri

Gunakan Holliday-Segar atau 4-2-1 rule dari Seksi A2. Jenis cairan yang lazim:

```
Bayi < 3 bulan          : Dextrose 10% (butuh lebih banyak glukosa)
Bayi 3 bulan – 2 tahun  : Dextrose 5% + NaCl 0,45% + KCl 10–20 mEq/L
Anak 2–12 tahun         : RL atau NaCl 0,9% ± Dextrose 5%
Anak > 12 tahun         : Seperti dewasa (RL atau NaCl 0,9%)
```

---

### F4 — Intraosseous (IO) Access

> [!info] IO adalah Penyelamat di Saat Akses IV Tidak Bisa Didapat dalam 90 Detik
> Terutama pada anak dalam kondisi syok/arrest, vena perifer kolaps dan sangat sulit dikanulasi. IO memberikan akses ke medullary cavity yang langsung berhubungan dengan sirkulasi vena sentral. **Semua obat dan cairan yang bisa diberikan IV bisa diberikan IO.**

#### Lokasi IO dan Teknik

```
Lokasi utama:
  Tibia proksimal (paling sering): 1–3 cm di bawah tuberositas tibia, sisi anteromedial
  Femur distal: 2–3 cm di atas kondil lateral femur (anak > 5 tahun)
  Humerus proksimal: tuberositas mayor (dewasa)
  Sternum: hanya untuk dewasa dengan EZ-IO spesifik

Cara pemasangan manual (bila EZ-IO tidak ada):
  Jarum IO khusus atau jarum sumsum tulang 16–18G
  Tegak lurus tulang, putar-tekan (drilling motion) sampai terasa "pop" (masuk rongga meduler)
  Aspirasi: bisa keluar sumsum tulang (konfirmasi posisi)
  Flush dengan NaCl → harus mengalir lancar tanpa resistensi
  Fiksasi dengan pita perekat, pasang tanda "IO"

EZ-IO (power drill):
  15 mm (pink): < 3 kg
  25 mm (biru): 3–39 kg
  45 mm (kuning): > 40 kg atau jaringan lunak tebal

Dosis obat via IO:
  SAMA dengan dosis IV → flush tiap setelah pemberian obat dengan 5–10 ml NaCl
```

---

## 🥗 SEKSI G — NUTRISI & PERIOPERATIF

---

### G1 — Kebutuhan Kalori: Cara Hitung

#### Harris-Benedict Equation (Basal Metabolic Rate)

```
Pria:
  BMR = 88,4 + (13,4 × BB kg) + (4,8 × TB cm) − (5,68 × Usia tahun)

Wanita:
  BMR = 447,6 + (9,25 × BB kg) + (3,10 × TB cm) − (4,33 × Usia tahun)

Kalori total = BMR × Faktor Aktivitas/Stres:
  Istirahat total (bed rest)   : × 1,0–1,2
  Post-op minor                : × 1,2–1,4
  Post-op mayor, trauma sedang : × 1,4–1,6
  Sepsis, luka bakar besar     : × 1,6–2,0
  Luka bakar > 40% TBSA        : × 2,0–2,5
```

#### Aturan Praktis (Tidak Perlu Kalkulator)

```
Estimasi cepat kebutuhan kalori:
  Pasien sakit ringan-sedang : 25–30 kkal/kgBB/hari
  Pasien sakit berat/ICU     : 25–35 kkal/kgBB/hari
  Luka bakar besar            : 35–40 kkal/kgBB/hari
  Undernutrisi berat          : mulai 15–20 kkal/kgBB/hari (refeeding syndrome!)

Kebutuhan protein:
  Normal                   : 0,8–1,0 g/kgBB/hari
  Post-op / sakit sedang   : 1,2–1,5 g/kgBB/hari
  Sakit kritis / luka bakar: 1,5–2,0 g/kgBB/hari

Contoh:
  Pria 70 kg post-laparotomi
  Kalori: 70 × 28 = 1.960 kkal/hari (~2.000 kkal/hari)
  Protein: 70 × 1,4 = 98 g/hari (~100 g/hari)
```

---

### G2 — Aturan Puasa Pre-Operatif

#### Panduan ASA/ERAS (Evidence-Based)

```
Cairan bening (air putih, teh, jus bening tanpa ampas):
  Boleh sampai 2 jam sebelum induksi anestesi

Susu formula bayi / ASI:
  4 jam sebelum (susu formula) / 4 jam sebelum (ASI)

Makanan ringan (roti tawar, biskuit):
  6 jam sebelum

Makanan berat (nasi, daging berlemak, goreng-gorengan):
  8 jam sebelum

Obat-obatan rutin:
  Boleh diminum dengan air putih minimal sampai 2–4 jam sebelum
  Pengecualian: antikoagulan dan beberapa obat spesifik → konsultasi anestesi
```

> [!tip] ERAS: Pre-operative Carbohydrate Loading
> Dalam protokol ERAS, pasien diberikan minuman karbohidrat (karbohidrat murni 12,5%, ~400 ml) 2–3 jam sebelum operasi → mengurangi resistensi insulin post-op → mempercepat pemulihan. Belum semua RS menerapkan, tapi ini evidence-based.

---

### G3 — Nutrisi Enteral vs Parenteral

#### Enteral Selalu Lebih Baik dari Parenteral (Bila Usus Berfungsi)

```
Manfaat enteral dibanding parenteral:
  Mempertahankan integritas mukosa usus (cegah bacterial translocation)
  Lebih fisiologis (hormone enteral tetap bekerja)
  Lebih murah
  Risiko infeksi lebih rendah (TPN terkait infeksi kateter, CLABSI)
  Mempercepat pemulihan fungsi GI

Mulai enteral feeding:
  Post-op GIT: dalam 6–24 jam post-op (ERAS protocol) bila tidak ada kontraindikasi
  ICU: dalam 24–48 jam pertama masuk ICU

Kontraindikasi enteral:
  Ileus berat, obstruksi usus aktif
  Perforasi GIT belum direpair
  Iskemia mesenterik aktif
  Fistula enterik high-output tanpa akses distal
```

#### Formula Enteral: Pilihan Dasar

```
Standard polymeric (orang dewasa sakit umum):
  1 kkal/ml, protein moderat
  Contoh: Peptamen, Ensure, Nutrison

High protein (pasien bedah, luka bakar, ICU):
  1–1,5 kkal/ml, protein tinggi (> 20% kalori dari protein)

Semi-elemental / elemental:
  Protein terhidrolisis → untuk malabsorpsi, fistula, Crohn's
  Lebih mahal

Cara pemberian:
  NGT atau NJ (nasojejenal) untuk pasien sadar
  PEG (percutaneous endoscopic gastrostomy) untuk jangka panjang > 4 minggu
  Kecepatan awal: 20–30 ml/jam → naikkan tiap 8–12 jam sampai target
  Target kalori tercapai dalam 48–72 jam
```

---

### G4 — Interpretasi Albumin & Protein

```
Albumin serum (g/dL):
  Normal           : 3,5–5,0 g/dL
  Malnutrisi ringan: 3,0–3,5 g/dL (risiko komplikasi post-op mulai naik)
  Malnutrisi sedang: 2,5–3,0 g/dL (risiko tinggi)
  Malnutrisi berat : < 2,5 g/dL (sangat berisiko → optimasi nutrisi pre-op bila elektif)

Prealbumin (transthyretin):
  Lebih sensitif dari albumin untuk perubahan akut (half-life 2 hari vs albumin 20 hari)
  Normal: 15–35 mg/dL
  < 10 mg/dL → deplesi protein berat
  Berguna untuk monitoring respons terapi nutrisi

Penting: albumin bukan hanya marker nutrisi!
  Turun pada: inflamasi akut (CRP naik → albumin turun karena redistribusi)
  Turun pada: kebocoran kapiler (edema, luka bakar, sepsis) → bukan malnutrisi
  Interpretasi selalu dalam konteks klinis
```

---

## 🔬 SEKSI H — LAB & INTERPRETASI CEPAT

---

### H1 — Analisis Gas Darah (ABG): 4 Langkah Sistematis

> [!abstract] Analogi: ABG adalah "Foto Metabolisme Tubuh Saat Ini"
> ABG memberikan gambaran lengkap tentang keseimbangan asam-basa dan oksigenasi jaringan dalam satu pengambilan darah. Belajar membacanya secara sistematik — jangan langsung lompat ke kesimpulan.

#### Nilai Normal ABG

```
pH          : 7,35–7,45
PaCO₂       : 35–45 mmHg
PaO₂        : 80–100 mmHg (pada FiO₂ 21%)
HCO₃⁻       : 22–26 mEq/L
BE          : -2 sampai +2 mEq/L
SaO₂        : > 95%
Laktat      : < 2 mmol/L
```

#### 4 Langkah Membaca ABG

**LANGKAH 1: Tentukan status asam-basa dari pH**
```
pH < 7,35 → ASIDOSIS
pH > 7,45 → ALKALOSIS
pH 7,35–7,45 → Normal atau terkompensasi
```

**LANGKAH 2: Tentukan penyebab primer (respiratorik atau metabolik?)**
```
Asidosis respiratorik   : PaCO₂ > 45 (CO₂ tertahan)
Alkalosis respiratorik  : PaCO₂ < 35 (CO₂ dibuang terlalu banyak)
Asidosis metabolik      : HCO₃ < 22 (atau BE < -2)
Alkalosis metabolik     : HCO₃ > 26 (atau BE > +2)

Aturan: gangguan primer SEARAH dengan pH
  pH rendah + CO₂ tinggi = asidosis respiratorik
  pH rendah + HCO₃ rendah = asidosis metabolik
  pH tinggi + CO₂ rendah = alkalosis respiratorik
  pH tinggi + HCO₃ tinggi = alkalosis metabolik
```

**LANGKAH 3: Cek kompensasi**
```
Asidosis metabolik → kompensasi: hiperventilasi → PaCO₂ turun
  Formula kompensasi: PaCO₂ expected = (1,5 × HCO₃) + 8 ± 2 (Winter's formula)
  
Alkalosis metabolik → kompensasi: hipoventilasi → PaCO₂ naik
  Formula: PaCO₂ expected = (0,7 × HCO₃) + 21 ± 2

Asidosis respiratorik akut → kompensasi ginjal lambat (HCO₃ naik 1 per 10 CO₂ naik)
Asidosis respiratorik kronik → kompensasi lebih (HCO₃ naik 3,5 per 10 CO₂ naik)
Alkalosis respiratorik akut → HCO₃ turun 2 per 10 CO₂ turun
Alkalosis respiratorik kronik → HCO₃ turun 5 per 10 CO₂ turun

Bila kompensasi sesuai → gangguan tunggal dengan kompensasi adekuat
Bila kompensasi tidak sesuai → gangguan campuran (mixed disorder)
```

**LANGKAH 4: Evaluasi oksigenasi**
```
PaO₂ < 80 mmHg → hipoksemia
PaO₂ < 60 mmHg → hipoksemia berat → intervensi segera

A-a gradient (Alveolar-arterial gradient):
  PAO₂ = (FiO₂ × 713) − (PaCO₂ ÷ 0,8)
  A-a gradient = PAO₂ − PaO₂
  Normal (usia muda): < 10 mmHg
  Normal (lansia): < (usia × 0,3)
  Tinggi (> 20) → ada masalah pertukaran gas (ARDS, pneumonia, PE)
  Normal → hipoksemia dari hipoventilasi saja (OD opioid, dll)
```

#### Contoh Kasus ABG — Latihan Baca

**Kasus 1:**
> pH 7,28 / PaCO₂ 22 / HCO₃ 10 / BE -15 / PaO₂ 95
>
> Langkah 1: pH 7,28 → ASIDOSIS
> Langkah 2: HCO₃ 10 (rendah) → metabolik; CO₂ 22 (rendah) → kompensasi
> Asidosis metabolik
> Langkah 3: Winter's formula → PaCO₂ expected = (1,5 × 10) + 8 = 23 ± 2
> PaCO₂ aktual 22 → dalam rentang expected → kompensasi adekuat
> Langkah 4: PaO₂ 95 → oksigenasi oke
> **Kesimpulan: Asidosis metabolik terkompensasi. Kemungkinan: DKA, sepsis (laktat), diare berat**

**Kasus 2:**
> pH 7,52 / PaCO₂ 28 / HCO₃ 22 / BE +1 / PaO₂ 88
>
> Langkah 1: pH 7,52 → ALKALOSIS
> Langkah 2: PaCO₂ 28 (rendah) → respiratorik; HCO₃ 22 (normal) → belum ada kompensasi metabolik
> Alkalosis respiratorik akut
> Langkah 4: PaO₂ 88 → sedikit rendah
> **Kesimpulan: Alkalosis respiratorik akut. Kemungkinan: hiperventilasi (nyeri, ansietas, pain), hipoksia ringan yang stimulasi napas, emboli paru awal**

---

### H2 — Interpretasi Elektrolit Cepat

#### Kapan Koreksi Elektrolit Harus Segera (Tidak Bisa Tunggu)

```
SEGERA (dalam 1–4 jam):
  K > 6,5 mEq/L atau ada perubahan EKG → hiperkalemia darurat
  K < 2,5 mEq/L → risiko aritmia
  Na < 120 mEq/L dengan gejala (kejang, tidak sadar)
  Ca ion < 0,8 mmol/L atau tetani aktif
  Mg < 0,5 mEq/L dengan aritmia atau kejang

CEPAT (dalam 12–24 jam):
  K 2,5–3,0 mEq/L → koreksi IV/oral
  Na 120–130 mEq/L → koreksi lambat
  Ca total < 7,5 mg/dL simtomatis

RUTIN (24–48 jam):
  K 3,0–3,5 mEq/L → oral correction
  Na 130–135 mEq/L asimtomatis → cari penyebab, koreksi perlahan
```

---

### H3 — Koagulasi: Interpretasi & Kapan Butuh FFP/Platelet

```
PT/INR:
  Normal: PT 11–13 detik / INR 0,8–1,2
  INR 1,5–2,0: koagulasi sedikit terganggu (perhatikan)
  INR > 2,0: koagulasi terganggu signifikan → FFP bila perdarahan atau pre-operasi
  INR > 1,5 pada pasien perdarahan aktif → FFP 10–15 ml/kgBB IV

aPTT:
  Normal: 25–35 detik
  > 1,5× normal → defisiensi jalur intrinsik atau heparin
  Monitoring heparin: target 1,5–2,5× control aPTT

Fibrinogen:
  Normal: 200–400 mg/dL
  < 150 mg/dL → risiko perdarahan
  < 100 mg/dL dengan perdarahan → cryoprecipitate (10 unit → naik ~100 mg/dL)

Platelet (Trombosit):
  > 100.000/μL → aman untuk hampir semua operasi
  50.000–100.000 → aman untuk operasi minor; perhatikan operasi mayor
  < 50.000 dengan perdarahan aktif → transfusi platelet
  < 20.000 → risiko perdarahan spontan → transfusi profilaktik

Satu unit trombosit (satu kantong apheresis) → naik ~30.000–60.000/μL
```

---

### H4 — Laktat: Interpretasi & Target Clearance

```
Nilai Normal Laktat: < 2 mmol/L

Interpretasi:
  < 2 mmol/L   → normal
  2–4 mmol/L   → hiperlaktatemia (waspada, perburukan mungkin terjadi)
  > 4 mmol/L   → laktat tinggi bermakna → curiga syok termasuk terkompensasi
                  → mulai resusitasi agresif meski TD normal

Laktat sebagai panduan resusitasi (Surviving Sepsis Campaign):
  Ukur laktat awal saat masuk
  Target: laktat clearance > 10% per 2 jam (atau normalisasi dalam 6 jam)
  Bila tidak turun meski hemodinamik membaik → curiga tissue hypoperfusion persisten,
  hepatic failure (metabolisme laktat terganggu), atau mitokondrial disfungsi

Penyebab laktat tinggi non-hipoksik (laktat Type B):
  Metformin toksisitas, thiamine deficiency, keganasan, seizure, hiperaktivitas β-adrenergik
  → laktat tinggi bukan selalu berarti hipoksia jaringan
```

---

### H5 — CBC + Diff: Interpretasi Tren

```
Hemoglobin:
  Nilai penting untuk keputusan transfusi (lihat Seksi A4)
  Ingat: Hb akut segera setelah perdarahan masih normal! → plasma belum terdilusi
  Hb turun bermakna baru terlihat 4–6 jam setelah perdarahan atau setelah resusitasi cairan

Leukosit (WBC):
  Normal: 4.000–10.000/μL
  > 10.000 + shift to left (> 10% bands) → infeksi bakteri aktif
  > 20.000 → infeksi berat / leukemia?
  < 4.000 (leukopenia) → kemoterapi, viral, sepsis berat (consume), aplasia

Neutrofil:
  Dominasi pada infeksi bakteri
  ANC (Absolute Neutrophil Count) < 500 → neutropenia berat → risiko infeksi oportunistik

Trombosit (Platelet):
  Normal: 150.000–400.000/μL
  Turun pada: sepsis (konsumsi), DIC, ITP, HELLP, HIT (heparin-induced thrombocytopenia)
  HIT: trombositopenia + trombus (paradoks) pada pasien heparin → ganti heparin segera!
  Naik pada: reaktif (infeksi, inflamasi kronis, asplenia, defisiensi besi) → jarang perlu intervensi

Eosinofil:
  Naik pada: alergi, parasit, keganasan (eosinofilia)
  Turun pada: stres akut, kortikosteroid (tidak bermakna klinis)
```

---

## 📝 TEMPLATE PROMPT UNTUK MATERI DENGAN KALKULASI

> [!success] Gunakan Ini Saat Membuat File .md Individual yang Melibatkan Kalkulasi

```
Saya Taufiq, koas bedah di RSUD Karsa Husada Batu, FKIK UIN Malang.

Saya melampirkan 4 file masterplan sebagai konteks:
1. [00 - MASTERPLAN UTAMA] — konteks keseluruhan stase
2. [0X - MASTERPLAN STASE] — konteks stase spesifik
3. [09 - MASTERPLAN SUPLEMEN] — topik lintas stase & gap coverage
4. [10 - MASTERPLAN BASIC CALCULATIONS] — rumus dan kalkulasi klinis

Sekarang tolong kerjakan file .md individual:
Kode: [KODE TOPIK] — [NAMA TOPIK]

INSTRUKSI TAMBAHAN UNTUK TOPIK YANG MELIBATKAN KALKULASI:
  Sertakan rumus lengkap yang relevan dari file 10
  Buat minimal 1 contoh kasus kalkukasi dengan angka nyata dari konteks RSUD Karsa Husada Batu
  Sebutkan target parameter monitoring yang spesifik (bukan hanya "monitor vital sign")
  Format rumus dalam code block agar mudah dibaca

Format output tetap 7 bagian standar (Opening Kasus → Checklist)
Output: satu file .md lengkap, Quartz-compatible
```

---

## 📌 STATUS PROGRESS

> [!todo] Update setiap sub-seksi selesai dipelajari/dikembangkan

**Seksi A — Resusitasi & Cairan:**
- [ ] A1 — Klasifikasi Syok & Resusitasi
- [ ] A2 — Cairan Maintenance
- [ ] A3 — Defisit Cairan & Replacement
- [ ] A4 — Transfusi Darah
- [ ] A5 — Koreksi Elektrolit

**Seksi B — Obat-Obatan Darurat:**
- [ ] B1 — Vasopressor & Inotropik Drip
- [ ] B2 — Analgetik IGD
- [ ] B3 — Antibiotik Empirik Bedah
- [ ] B4 — Antikoagulan & Reversal
- [ ] B5 — Obat Emergensi Lainnya

**Seksi C — Monitoring & Interpretasi:**
- [ ] C1 — Tanda Vital Normal per Usia
- [ ] C2 — Oksigenasi & Alat O₂
- [ ] C3 — Urine Output
- [ ] C4 — Skoring Klinis IGD

**Seksi D — Kalkulasi Luka Bakar:**
- [ ] D1 — Rule of Nine & Metode Lain
- [ ] D2 — Formula Baxter Step by Step
- [ ] D3 — Kalkulasi Khusus (Anak & Inhalasi)

**Seksi E — Kalkulasi Ortopedi:**
- [ ] E1 — Estimasi Blood Loss per Fraktur
- [ ] E2 — Traksi: Jenis & Beban
- [ ] E3 — Prinsip Gips & Splint

**Seksi F — Kalkulasi Pediatri:**
- [ ] F1 — Estimasi BB Anak
- [ ] F2 — Ukuran ETT Anak
- [ ] F3 — Resusitasi Cairan Anak
- [ ] F4 — Intraosseous Access

**Seksi G — Nutrisi & Perioperatif:**
- [ ] G1 — Kebutuhan Kalori
- [ ] G2 — Aturan Puasa Pre-op
- [ ] G3 — Enteral vs Parenteral
- [ ] G4 — Interpretasi Albumin

**Seksi H — Lab & Interpretasi Cepat:**
- [ ] H1 — ABG: 4 Langkah
- [ ] H2 — Elektrolit Cepat
- [ ] H3 — Koagulasi
- [ ] H4 — Laktat
- [ ] H5 — CBC + Diff

---

## 🔗 KONEKSI KE MASTERPLAN LAIN

> [!note] Topik di File Ini Memperlengkapi

| Topik Kalkulasi | Masterplan yang Relevan |
|----------------|------------------------|
| Resusitasi syok, vasopressor | [[01 - MASTERPLAN IGD 1\|IGD 1 (1F)]], [[05 - MASTERPLAN IGD 2\|IGD 2 (5B)]] |
| Cairan post-op | [[03 - MASTERPLAN BEDAH DIGESTIF\|Digestif (3F)]], [[07 - MASTERPLAN BEDAH UMUM\|Umum (7F)]] |
| Antibiotik bedah | Semua stase |
| Baxter luka bakar | [[05 - MASTERPLAN IGD 2\|IGD 2 (5E)]], [[06 - MASTERPLAN BEDAH PLASTIK\|Plastik (6D)]] |
| Blood loss ortopedi | [[08 - MASTERPLAN BEDAH ORTOPEDI\|Ortopedi (8B, 8C)]] |
| Kalkulasi pediatri | [[05 - MASTERPLAN IGD 2\|IGD 2 (5D)]] |
| ABG & elektrolit | Semua stase, khusus [[05 - MASTERPLAN IGD 2\|IGD 2 (5B)]], [[02 - MASTERPLAN BEDAH SARAF\|Bedah Saraf (2D)]] |
| Skoring klinis | [[01 - MASTERPLAN IGD 1\|IGD 1 (semua)]], [[03 - MASTERPLAN BEDAH DIGESTIF\|Digestif (3C)]], [[04 - MASTERPLAN BEDAH UROLOGI\|Urologi (4D)]] |

---

*Terakhir diupdate: Juni 2026 · Taufiq · Koas Bedah FKIK UIN Malang · RSUD Karsa Husada Batu*
*Lihat juga: [[00 - MASTERPLAN UTAMA STASE BEDAH|Masterplan Utama]] · [[09 - MASTERPLAN SUPLEMEN|Suplemen 09]] · [[01 - MASTERPLAN IGD 1|IGD 1]] · [[05 - MASTERPLAN IGD 2|IGD 2]]*
