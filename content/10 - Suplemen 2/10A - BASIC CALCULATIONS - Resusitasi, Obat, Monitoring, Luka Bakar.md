---
title: "10A — BASIC CALCULATIONS: Resusitasi, Obat Darurat, Monitoring & Luka Bakar"
description: "Kalkulasi klinis terapan untuk IGD & semua stase bedah — Seksi A sampai D: cairan, vasopressor, monitoring, dan formula luka bakar dengan contoh kasus RSUD Karsa Husada Batu"
date: 2026-06-01
tags:
  - kalkulasi
  - basic-calculations
  - resusitasi
  - cairan
  - vasopressor
  - luka-bakar
  - lintas-stase
aliases:
  - kalkulasi cairan
  - rumus resusitasi
  - baxter formula
  - vasopressor drip
  - 10A
---

# 🧮 10A — BASIC CALCULATIONS: Resusitasi, Obat Darurat, Monitoring & Luka Bakar

> **Taufiq · FKIK UIN Malang · RSUD Karsa Husada Batu · 2026**
> *Lihat juga: [[00 - MASTERPLAN UTAMA STASE BEDAH|← Masterplan Utama]] · [[10B - BASIC CALCULATIONS - Ortopedi, Pediatri, Nutrisi, Lab|→ 10B]]*

---

## 🏥 1. Opening Kasus

Jam 23.15. Kamu baru selesai menjahit luka di pojok IGD ketika ambulans masuk membawa dua pasien sekaligus — korban tabrakan beruntun di jalan raya Malang-Batu.

Pasien pertama: pria 45 tahun, pengendara motor. Nadi 128x/menit, tekanan darah 88/60 mmHg, napas 28x/menit, tampak pucat dan berkeringat dingin. Ada luka lecet di dada kiri dan fraktur femur kanan yang jelas terlihat — paha bengkak, deformitas. Dia masih sadar tapi gelisah.

Pasien kedua: wanita 32 tahun, pengendara mobil. Wajah dan leher terkena semburan dari radiator pecah. Kulit wajah tampak merah-merah dan ada bula di leher kanan. Dia mengerang kesakitan. BB dikira sekitar 55 kg.

Perawat IGD menoleh ke kamu: "Dok, yang ini dulu apa yang ini? Cairan berapa cc? Drip vasopressor siap tidak? Luka bakarnya disiram berapa liter?"

Nah, kamu mau ngapain sekarang?

---

## 🔪 2. Kenapa Ini Penting?

Kalkulasi klinis bukan ujian matematika. Ini adalah **perbedaan antara pasien yang hidup dan yang tidak**.

Resusitasi cairan yang kurang → organ hypoperfusi → MODS. Resusitasi yang berlebihan → edema paru pada pasien TBI atau gagal jantung. Vasopressor dengan dosis salah → aritmia atau iskemia mesenteric. Formula Baxter yang dihitung dari waktu tiba di IGD alih-alih waktu kejadian → pasien luka bakar kekurangan cairan 4 jam pertama yang paling kritis.

Yang paling sering salah pada koas:
- Tidak tahu kapan **tekanan nadi menyempit** menandakan sudah Grade II syok (sebelum sistolik turun)
- Menghitung Baxter dari **waktu tiba** bukan **waktu kejadian** → fatal beda
- Tidak tau berapa kecepatan drip norepinefrin → tanya perawat → malu tidak perlu kalau kamu hafal rumusnya
- Koreksi elektrolit terlalu cepat → ODS (osmotic demyelination syndrome) → bisa lebih buruk dari penyakitnya sendiri

File ini adalah **lembar contekan terpusat** yang menjawab semua pertanyaan itu — dengan contoh angka nyata dari IGD RSUD Karsa Husada Batu.

---

## 📚 3. Dasar yang Harus Kamu Tahu

### Prinsip Besar Sebelum Hitung Apapun

Bayangkan tubuh seperti sistem irigasi sawah. Ada sumber air (jantung), saluran besar (pembuluh darah), dan sawah yang butuh air (sel-sel tubuh). Syok terjadi ketika sawah tidak cukup terairi — bisa karena:
- **Sumber airnya kurang** (hipovolemik — perdarahan, dehidrasi)
- **Pompanya rusak** (kardiogenik — infark)
- **Salurannya bocor semua** (distributif — sepsis, anafilaksis)
- **Ada sumbatan di jalur keluar** (obstruktif — tension pneumo, tamponade)

Solusinya beda-beda. Kalau pompa rusak, kamu tidak bisa selesaikan masalah dengan nambah air terus-menerus — justru sawah akan banjir. Bedakan dulu jenisnya sebelum hitung volumenya.

📸 *Search: `"4 types of shock physiology JVP skin temperature comparison table"` — pahami tabel ini sebelum lanjut*

---

## 🔍 4. Cara Berpikir di Depan Pasien

### Alur Kalkulasi di IGD (Urutan Wajib)

```
LANGKAH 1: Kenali jenis syok (lihat JVP, kulit, nadi)
     ↓
LANGKAH 2: Estimasi EBV dan persentase kehilangan
     ↓
LANGKAH 3: Hitung bolus awal dan tentukan cairan
     ↓
LANGKAH 4: Evaluasi respons (HR, TD, UO, laktat)
     ↓
LANGKAH 5: Maintenance + ganti defisit (bila ada)
     ↓
LANGKAH 6: Bila perlu vasopressor → hitung drip
     ↓
LANGKAH 7: Monitor target → titrasi
```

---

## 💊 5. Tatalaksana & Kalkulasi Lengkap

---

### SEKSI A — RESUSITASI & CAIRAN

---

#### A1 — Klasifikasi Syok & Resusitasi Cairan

> [!abstract] Empat Jenis Syok — Bedakan Sebelum Kasih Cairan

| Jenis Syok | Mekanisme | JVP | Kulit | Nadi | Contoh |
|------------|-----------|-----|-------|------|--------|
| **Hipovolemik** | Volume kurang | ↓ | Dingin, lembab, pucat | Lemah, cepat | Perdarahan, dehidrasi |
| **Distributif** | Vasodilatasi masif | ↓/N | Hangat, merah (awal) | Bounding | Sepsis, anafilaksis |
| **Kardiogenik** | Pompa gagal | ↑ | Dingin, lembab | Lemah, cepat | Infark, tamponade |
| **Obstruktif** | Outflow tersumbat | ↑ | Dingin | Lemah | Tension pneumo, PE |

> [!danger] JANGAN kasih cairan masif pada syok kardiogenik atau obstruktif
> Kardiogenik → inotropik. Tension pneumo → needle decompression dulu. Cairan hanya untuk hipovolemik dan distributif.

---

##### ATLS Hemorrhagic Shock Classification

| | **Grade I** | **Grade II** | **Grade III** | **Grade IV** |
|---|-------------|-------------|--------------|-------------|
| **Kehilangan darah** | < 750 ml / < 15% | 750–1500 ml / 15–30% | 1500–2000 ml / 30–40% | > 2000 ml / > 40% |
| **HR** | < 100 | 100–120 | 120–140 | > 140 |
| **TD Sistolik** | Normal | Normal | ↓ | ↓↓ |
| **Tekanan Nadi** | Normal/lebar | **Menyempit ← perhatikan ini!** | Menyempit | Menyempit |
| **RR** | 14–20 | 20–30 | 30–40 | > 35 |
| **Urine Output** | > 30 ml/jam | 20–30 ml/jam | 5–15 ml/jam | < 5 ml/jam |
| **GCS** | Normal | Cemas | Bingung | Letargis |
| **Resusitasi** | Kristaloid ± | Kristaloid | Kristaloid + darah | **Darah segera** |

> [!tip] Kunci: Tekanan Nadi Menyempit = Sudah Grade II
> Tekanan nadi = sistolik − diastolik (normal ~40 mmHg). Saat hipovolemia → vasokonstriksi → diastolik naik → tekanan nadi menyempit. Ini **tanda pertama yang bisa kamu ukur** sebelum sistolik turun. Perhatikan ini di kasus IGD!

---

##### Rumus EBV (Estimated Blood Volume)

```
EBV = Berat Badan (kg) × Faktor Usia

Faktor Usia:
  Neonatus prematur  : 95 ml/kg
  Neonatus aterm     : 85 ml/kg
  Bayi < 1 tahun     : 80 ml/kg
  Anak 1–12 tahun    : 75 ml/kg
  Dewasa pria        : 70 ml/kg
  Dewasa wanita      : 65 ml/kg
```

> [!example] Kasus IGD RSUD Karsa Husada Batu — Pasien 1
> **Situasi:** Pria 45 tahun, 65 kg, fraktur femur kanan tertutup. Nadi 128×/menit, TD 88/60 mmHg, napas 28×/menit, GCS 14.
>
> **EBV** = 65 × 70 = **4.550 ml**
>
> **Tekanan nadi** = 88 − 60 = 28 mmHg → **menyempit** → sudah Grade III
>
> **Estimasi blood loss fraktur femur** = 800–1.500 ml (lihat tabel 10B Seksi E1)
> → Sesuai Grade III (30–40% dari 4.550 = 1.365–1.820 ml)
>
> **Resusitasi awal:** Kristaloid hangat + segera siapkan darah
> - Bolus RL/NaCl 0,9% 1–2 L dalam 15–30 menit
> - Nilai respons: bila HR turun + TD naik → responder
> - Bila tidak respons → transfusi PRBCs segera

---

##### Bolus Cairan Awal

```
DEWASA:
  1–2 Liter RL atau NaCl 0,9% HANGAT dalam 15–30 menit

ANAK:
  20 ml/kgBB RL dalam 20 menit
  Bisa diulang hingga 3× (total 60 ml/kgBB)
```

> [!warning] RL vs NaCl 0,9%?
> Keduanya acceptable. Tapi **NaCl 0,9% volume besar → asidosis hiperkloremik** (klorida berlebih → bikarbonat turun). Lebih aman RL untuk resusitasi besar. **Pengecualian TBI: gunakan NaCl 0,9%** (RL sedikit hipotonik, bisa memperburuk edema serebri).

---

##### Target Resusitasi

```
MAP            : ≥ 65 mmHg  (TBI: ≥ 80 mmHg)
Urine output   : ≥ 0,5 ml/kgBB/jam dewasa  /  ≥ 1 ml/kgBB/jam anak
Laktat serum   : < 2 mmol/L  atau  clearance > 10% per 2 jam
Suhu inti      : > 36°C
```

---

##### Damage Control Resuscitation (DCR) — Trauma Berat

```
HINDARI kristaloid berlebihan → encerkan faktor koagulasi

Rasio komponen darah: PRBCs : FFP : Platelet = 1 : 1 : 1

Tambahan wajib saat MTP (Massive Transfusion Protocol):
  TXA (Tranexamic Acid): 1 gram IV dalam 10 menit
  → WAJIB dalam 3 JAM PERTAMA dari cedera
  → Setelah 3 jam: tidak efektif, bahkan berbahaya

  Kalsium Glukonat 1 gram IV per 4 unit darah
  (sitrat dalam darah donor mengkelasi Ca²⁺ → hipokalsemia → aritmia)
```

---

#### A2 — Cairan Maintenance: Holliday-Segar & 4-2-1 Rule

> [!abstract] Maintenance = "Bayar Tagihan Harian" — Bukan untuk Resusitasi!
> Resusitasi dulu sampai status cairan normal → BARU hitung maintenance. Jangan gabungkan keduanya di fase akut.

##### Holliday-Segar (Kebutuhan Harian)

```
BB 0–10 kg   : 100 ml/kgBB/hari
BB 10–20 kg  : + 50 ml/kgBB/hari (untuk tiap kg di atas 10)
BB > 20 kg   : + 20 ml/kgBB/hari (untuk tiap kg di atas 20)
```

> [!example] Contoh Kasus RSUD Karsa Husada Batu
> **Situasi:** Anak 20 kg post-apendektomi, masih puasa.
>
> 10 kg pertama : 10 × 100 = 1.000 ml
> 10 kg berikut : 10 × 50  = 500 ml
> **Total        : 1.500 ml/hari = 62,5 ml/jam → bulatkan 63 ml/jam**

> **Situasi:** Pria 65 kg post-laparotomi, masih puasa.
>
> 10 kg pertama : 10 × 100 = 1.000 ml
> 10 kg berikut : 10 × 50  = 500 ml
> 45 kg sisanya : 45 × 20  = 900 ml
> **Total        : 2.400 ml/hari = 100 ml/jam**

---

##### 4-2-1 Rule (Kecepatan Drip per Jam — Versi Cepat)

```
BB 0–10 kg   : 4 ml/kgBB/jam
BB 10–20 kg  : + 2 ml/kgBB/jam (tiap kg di atas 10)
BB > 20 kg   : + 1 ml/kgBB/jam (tiap kg di atas 20)
```

> [!example] Cepat hitung: pria 65 kg
> 10 × 4 = 40, plus 10 × 2 = 20, plus 45 × 1 = 45
> **Total: 105 ml/jam** ≈ sama dengan Holliday-Segar

---

##### Cairan Maintenance Standar

| Kondisi Pasien | Pilihan Cairan |
|----------------|---------------|
| Dewasa post-op umum | RL 1.500–2.000 ml/hari atau NaCl 0,9% + KCl 20 mEq/L |
| TBI | NaCl 0,9% — **bukan RL** (RL hipotonik) |
| Anak | RL atau NaCl 0,45% + D5% + KCl |
| Luka bakar hari 1 | RL sesuai Baxter (lihat Seksi D) |

---

#### A3 — Defisit Cairan & Replacement

##### Defisit dari Dehidrasi

```
Defisit Cairan (liter) = BB (kg) × % Dehidrasi × 10

Derajat Dehidrasi:
  Ringan  (3–5%)  : haus, mulut kering, turgor sedikit turun
  Sedang  (6–9%)  : mata cekung, turgor turun, oliguria
  Berat   (≥ 10%) : letargi, tidak produksi air mata, tanda syok
```

> [!example] Kasus IGD — Anak Diare
> **Anak 20 kg, diare 3 hari, mata cekung, rewel** → dehidrasi sedang (8%)
>
> Defisit = 20 × 8% × 10 = **1.600 ml**
> Maintenance = 1.500 ml/hari (dari contoh di atas)
> Ongoing losses = ~500 ml estimasi (diare sisa)
>
> **Total 24 jam = 1.600 + 1.500 + 500 = 3.600 ml**
>
> Pemberian: ½ defisit (800 ml) dalam 8 jam pertama,
> sisanya dalam 16 jam berikutnya, maintenance jalan terus.

---

##### Defisit Puasa Pre-Operatif

```
Defisit Puasa = Maintenance rate (ml/jam) × Lama Puasa (jam)

Cara pemberian (klasik):
  ½ defisit pada jam pertama intraoperatif
  ¼ defisit pada jam kedua
  ¼ defisit pada jam ketiga
  + Maintenance rate + Surgical losses
```

> [!example] Kasus Pre-Operatif
> **Pria 65 kg, maintenance 105 ml/jam, puasa 8 jam**
>
> Defisit puasa = 105 × 8 = **840 ml**
>
> Jam pertama intraop: 420 ml + 105 ml maintenance + third space losses

---

##### Third Space Losses (Intraoperatif)

```
Operasi minor (kulit, superfisial)  : 2–4 ml/kgBB/jam
Operasi medium (thoraks, ortopedi) : 4–6 ml/kgBB/jam
Operasi besar (abdomen terbuka)    : 6–10 ml/kgBB/jam

Total cairan intraoperatif per jam:
= Maintenance + Distribusi defisit puasa + Third space + EBL replacement
```

---

#### A4 — Transfusi Darah

##### Indikasi Transfusi PRBCs

```
Hb < 7 g/dL        → transfusi pasien stabil (TRICC trial)
Hb < 8 g/dL        → pasien PJK atau TBI
Hb < 10 g/dL       → iskemia miokard aktif
Hb berapapun       → syok hemoragik dengan perdarahan aktif
```

> [!tip] Konversi Hb–Hematokrit
> **Hb (g/dL) ≈ Hct (%) ÷ 3**
> Hct 21% ≈ Hb 7 g/dL → sudah indikasi transfusi pasien stabil

---

##### Rumus Volume PRBCs

```
Volume PRBCs (ml) = (Hb target − Hb aktual) × BB (kg) × 3

Atau: rule of thumb sederhana
  1 unit PRBCs ≈ naik Hb 1 g/dL pada pasien 70 kg
  Sesuaikan proporsional untuk BB berbeda
```

> [!example] Kasus Transfusi
> **Pasien wanita 55 kg, Hb 5,8 g/dL, target Hb 9 g/dL**
>
> Volume = (9 − 5,8) × 55 × 3 = 3,2 × 55 × 3 = **528 ml**
>
> 1 unit PRBCs ≈ 250–300 ml → butuh ±2 unit
> Cek Hb 1 jam post-transfusi selesai

---

##### Komponen Darah Lain

| Komponen | Volume/Unit | Indikasi | Efek |
|----------|------------|---------|------|
| **FFP** | 200–250 ml | Koagulopati, reversal warfarin, DIC | Naikkan faktor koagulasi |
| **Trombosit** | 50–70 ml/unit | Plt < 50.000 (perdarahan) | Naik ~5.000–10.000/unit per 70 kg |
| **Cryoprecipitate** | 15–20 ml/unit | Fibrinogen < 1 g/L | 10 unit → naik ~1 g/L fibrinogen |

---

#### A5 — Koreksi Elektrolit

> [!abstract] Elektrolit = "Konduktor Listrik Tubuh"
> Terlalu cepat mengoreksi Na bisa lebih berbahaya dari hiponatremianya sendiri. Terlalu lambat mengoreksi K tinggi bisa hentikan jantung. Tiap elektrolit punya kecepatan koreksi yang tidak boleh dilanggar.

##### Koreksi Natrium (Na)

**Hiponatremia (Na < 135 mEq/L)**

```
Defisit Na = (Na target − Na aktual) × TBW

TBW (Total Body Water):
  Pria dewasa    : BB × 0,6
  Wanita dewasa  : BB × 0,5
  Lansia pria    : BB × 0,5
  Lansia wanita  : BB × 0,45
  Anak           : BB × 0,6–0,7
```

> [!danger] BATAS KECEPATAN KOREKSI Na — MUTLAK
> **Maksimal 8–10 mEq/L per 24 jam**
> Koreksi lebih cepat → **Osmotic Demyelination Syndrome (ODS)** → paralisis, koma, kematian. Tidak bisa dibalik.
>
> **Pengecualian:** hiponatremia simtomatis (kejang aktif) → NaCl 3%, 1–2 ml/kgBB bolus → naikkan Na 1–2 mEq/L untuk stop kejang → lalu kembali koreksi lambat.

> [!example] Kasus Koreksi Na
> **Pria 70 kg, Na = 118 mEq/L, target awal 126 mEq/L (koreksi lambat 8 mEq/24 jam)**
>
> TBW = 70 × 0,6 = 42 L
> Defisit Na = (126 − 118) × 42 = 336 mEq Na
>
> NaCl 0,9% mengandung 154 mEq/L → butuh ~2,2 L dalam 24 jam (di luar maintenance)
> **Cek Na serum tiap 4–6 jam!**

---

**Hipernatremia (Na > 145 mEq/L)**

```
Defisit Air Bebas = TBW × [(Na aktual ÷ 140) − 1]
```

> [!example] Kasus Hipernatremia
> **Wanita 60 kg, Na = 158 mEq/L**
>
> TBW = 60 × 0,5 = 30 L
> Defisit = 30 × [(158 ÷ 140) − 1] = 30 × 0,129 = **3,9 L**
>
> Ganti dengan D5W atau NaCl 0,45%
> Turunkan Na **maksimal 10–12 mEq/L per 24 jam**

---

##### Koreksi Kalium (K)

**Hipokalemia (K < 3,5 mEq/L)**

```
Estimasi defisit K:
  K 3,0–3,5 mEq/L → defisit ~100–200 mEq
  K 2,5–3,0 mEq/L → defisit ~200–400 mEq
  K < 2,5 mEq/L   → defisit > 400 mEq (berat!)

Pemberian KCl IV:
  Via perifer : maksimal 10 mEq/jam (encer dalam 100–250 ml)
  Via CVC    : maksimal 20 mEq/jam + monitoring EKG
  Oral       : 40–80 mEq/hari ÷ 2–4 dosis
```

> [!danger] KCl TIDAK BOLEH IV bolus langsung (undiluted)
> → Cardiac arrest dari hiperkalemia akut!

---

**Hiperkalemia (K > 5,5 mEq/L)**

```
Urutan tatalaksana hiperkalemia DARURAT (K > 6,5 atau ada perubahan EKG):

1. Kalsium Glukonat 10% — 10–20 ml IV pelan (3–5 menit)
   → Stabilisasi membran sel jantung (onset 1–3 menit)
   → TIDAK menurunkan K, hanya melindungi jantung!

2. Insulin 10 unit IV + Dextrose 50% 50 ml
   → Masukkan K ke dalam sel (onset 15–30 menit)

3. Natrium Bikarbonat 50–100 mEq IV
   → Bila ada asidosis (onset 15–30 menit)

4. Salbutamol nebulasi 10–20 mg
   → Masukkan K ke sel via reseptor β₂ (onset 30 menit)

5. Furosemide 40–80 mg IV
   → Buang K lewat urin (perlu fungsi ginjal)

6. Kayexalate oral/enema
   → Buang K lewat GI (lambat, jam-jam)

7. Hemodialisis
   → Bila semua gagal atau GFR sangat rendah
```

---

##### Koreksi Kalsium (Ca)

> [!warning] Koreksi Ca harus memperhitungkan albumin!
> **Ca terkoreksi = Ca terukur + 0,8 × (4 − Albumin pasien)**
>
> Contoh: Ca terukur 7,8 mg/dL, albumin 2,5 g/dL
> Ca terkoreksi = 7,8 + 0,8 × (4 − 2,5) = 7,8 + 1,2 = **9,0 mg/dL → sebenarnya normal!**

```
Hipokalsemia simtomatis (tetani, kejang, Chvostek/Trousseau):
  Kalsium Glukonat 10% — 10–20 ml IV pelan dalam 10 menit
  → Dapat diulang
  → Lanjut infus: 10 ampul (100 ml) dalam 1 L D5W, jalankan 50–100 ml/jam

Hipokalsemia ringan asimtomatis:
  Kalsium karbonat oral 1–3 g/hari + Calcitriol 0,25–0,5 mcg/hari
```

---

### SEKSI B — OBAT-OBATAN DARURAT

---

#### B1 — Vasopressor & Inotropik: Cara Hitung Drip

> [!abstract] Vasopressor = "Pompa Darurat" yang Kamu Kendalikan Per Menit
> Naikkan dosis sedikit → MAP naik. Turunkan sedikit → bisa drop. Ini bukan obat yang bisa ditulis sekali lalu ditinggal. **Kamu harus bisa hitung drip-nya sendiri** — jangan selalu tergantung perawat.

##### Rumus Universal Vasopressor

```
Kecepatan drip (ml/jam) = Dosis (mcg/kgBB/menit) × BB (kg) × 60 ÷ Konsentrasi (mcg/ml)
```

---

##### Norepinefrin (Noradrenalin) — First-Line Septic Shock

```
Konsentrasi standar: 4 mg dalam 250 ml NaCl 0,9% = 16 mcg/ml

Dosis awal  : 0,1–0,2 mcg/kgBB/menit
Titrasi     : naik 0,05–0,1 mcg/kgBB/menit tiap 5–10 menit
Target      : MAP ≥ 65 mmHg
Dosis umum  : 0,01–3 mcg/kgBB/menit
```

> [!example] Kasus: Pasien Sepsis Urosepsis di IGD
> **Pasien 60 kg, MAP 55 mmHg setelah resusitasi 2 L RL → mulai norepinefrin dosis 0,2 mcg/kgBB/menit**
>
> Kecepatan = 0,2 × 60 × 60 ÷ 16 = 720 ÷ 16 = **45 ml/jam**
>
> Setelah 15 menit MAP 62 mmHg, belum target → naikkan ke 0,3 mcg/kgBB/menit:
> = 0,3 × 60 × 60 ÷ 16 = 1.080 ÷ 16 = **67,5 ml/jam → bulatkan 68 ml/jam**

---

##### Dopamin

```
Konsentrasi standar: 200 mg dalam 250 ml = 800 mcg/ml

Efek dosis:
  2–5 mcg/kgBB/menit   : dopaminergik (renal)
  5–10 mcg/kgBB/menit  : β-1 → inotropik + kronotropik
  > 10 mcg/kgBB/menit  : α-1 → vasokonstriksi
```

> [!example] Pasien 60 kg, dosis 5 mcg/kgBB/menit
> = 5 × 60 × 60 ÷ 800 = 18.000 ÷ 800 = **22,5 ml/jam**

---

##### Epinefrin (Adrenalin)

```
Untuk ANAFILAKSIS:
  IM (BUKAN IV): 0,3–0,5 mg larutan 1:1000 di paha anterolateral
  Ulangi tiap 5–15 menit bila perlu → ini OBAT PERTAMA, bukan antihistamin!

Untuk vasopressor ICU:
  Konsentrasi: 1 mg dalam 250 ml = 4 mcg/ml
  Dosis      : 0,01–0,5 mcg/kgBB/menit
  Hitung     : sama seperti norepinefrin
```

---

##### Dobutamin — Inotropik Murni (Syok Kardiogenik)

```
Konsentrasi standar: 250 mg dalam 250 ml = 1.000 mcg/ml

Dosis  : 2,5–20 mcg/kgBB/menit
Efek   : ↑ curah jantung, sedikit vasodilatasi
```

> [!example] Pasien 70 kg, dosis 5 mcg/kgBB/menit
> = 5 × 70 × 60 ÷ 1.000 = 21.000 ÷ 1.000 = **21 ml/jam**

---

##### Ringkasan Pilihan Vasopressor

| Obat | Indikasi Utama | Dosis Awal | Catatan |
|------|---------------|-----------|---------|
| **Norepinefrin** | **Septic shock (first-line)**, neurogenik | 0,1–0,2 mcg/kgBB/menit | Pilihan utama di IGD bedah |
| **Dopamin** | Syok kardiogenik + bradikardia | 5–10 mcg/kgBB/menit | Lebih banyak aritmia dari NE |
| **Epinefrin** | **Anafilaksis (#1!)**, arrest, tambahan refrakter | 0,3–0,5 mg IM (anafilaksis) | **Jangan kasih antihistamin dulu!** |
| **Dobutamin** | Syok kardiogenik curah jantung rendah | 2,5–5 mcg/kgBB/menit | Bisa turunkan tekanan darah |
| **Vasopressin** | Tambahan NE pada septic shock refrakter | 0,03–0,04 U/menit | Dosis tetap, tidak dititrasi |

---

#### B2 — Analgetik di IGD

```
WHO Analgesic Ladder untuk IGD:

RINGAN (VAS 1–3):
  Paracetamol IV 1 gram tiap 6–8 jam (maks 4 gram/hari)
  Ketorolac 15–30 mg IV/IM tiap 6–8 jam (maks 5 hari)

SEDANG (VAS 4–6):
  Paracetamol + Ketorolac
  Tramadol 50–100 mg IV pelan (waspadai mual)

BERAT (VAS 7–10):
  Morfin 0,05–0,1 mg/kgBB IV titrasi tiap 5–10 menit
  Fentanyl 1–2 mcg/kgBB IV (onset 1–2 menit, durasi 30–60 menit)
```

> [!example] Kasus Nyeri Post-Laparotomi
> **Pria 70 kg, post-laparotomi, VAS 8**
>
> Morfin loading: 0,05 × 70 = **3,5 mg IV pelan** → evaluasi 10 menit
> Bila VAS masih > 6 → tambah 2 mg lagi → evaluasi → dst.
> Maintenance: 2–4 mg IV PRN tiap 2–4 jam

---

##### Anestesi Lokal — Dosis Maksimal

```
Lidokain tanpa epinefrin : 3–4 mg/kgBB (maks 300 mg)
Lidokain dengan epinefrin: 7 mg/kgBB  (maks 500 mg)
Bupivakain               : 2,5 mg/kgBB (maks 175 mg)
Ropivakain               : 3 mg/kgBB

JANGAN epinefrin di: jari, hidung, telinga, penis
→ vasokonstriksi → iskemia → nekrosis!
```

> [!example] Kalkulasi dosis untuk hecting
> **Pasien 70 kg, Lidokain 2% tanpa epinefrin**
>
> Dosis maks = 70 × 3 = 210 mg = 10,5 ml larutan 2%
> Untuk luka 5 cm biasanya cukup 3–5 ml → jauh di bawah batas aman

---

##### Nalokson — Antidot Opioid

```
Nalokson: 0,4 mg IV → ulangi tiap 2–3 menit hingga 3× (maks 1,2 mg)
Onset: 1–2 menit. DURASI PENDEK (30–45 menit) → opioid bisa "kembali"
→ Monitor ketat setelah pemberian, siap dosis ulang
```

---

#### B3 — Antibiotik Empirik Bedah

| Kondisi | Patogen Tersangka | Antibiotik Empirik | Dosis |
|---------|-----------------|-------------------|-------|
| **Peritonitis/perforasi GIT** | E. coli, Bacteroides, Enterococcus | Ceftriaxone + Metronidazole | Ceftriaxone 1–2 g/24 jam IV + Metro 500 mg/8 jam IV |
| **Kolesistitis/kolangitis** | E. coli, Klebsiella | Ceftriaxone + Metronidazole | Sama |
| **Kolangitis berat/ICU** | + Pseudomonas | Pip-Tazo atau Meropenem | Pip-Tazo 4,5 g/8 jam atau Meropenem 1 g/8 jam |
| **Urosepsis** | E. coli, Klebsiella | Ceftriaxone atau Cefepime | Ceftriaxone 2 g/24 jam IV |
| **Fraktur terbuka Grade I–II** | S. aureus | Cefazolin | 1–2 g/8 jam, mulai < 1 jam dari injury |
| **Fraktur terbuka Grade III** | + gram negatif | Cefazolin + Gentamisin | Cefazolin + Gentamisin 5 mg/kgBB/24 jam |
| **Fournier's Gangrene** | Polimikrobial + jamur | Meropenem + Metro ± Flukonazol | Meropenem 1 g/8 jam + Metro 500 mg/8 jam |

---

##### Profilaksis Antibiotik Pre-Operatif

```
PRINSIP: satu dosis, 30–60 menit SEBELUM insisi kulit

Operasi bersih (herniorafi, tiroidektomi):
  Cefazolin 1–2 g IV

Operasi bersih-terkontaminasi (kolesistektomi, apendektomi):
  Cefazolin 1–2 g + Metronidazole 500 mg IV

Redose intraoperatif:
  Bila operasi > 3–4 jam ATAU EBL > 1.500 ml → ulangi dosis
```

---

#### B4 — Antikoagulan: Heparin Drip & Reversal

##### UFH (Unfractionated Heparin) Drip

```
Konsentrasi standar: 25.000 unit dalam 250 ml NaCl = 100 unit/ml

Dosis loading   : 80 unit/kgBB IV bolus
Dosis maintenance: 18 unit/kgBB/jam infus kontinu
```

> [!example] Pasien DVT 70 kg
> Loading = 80 × 70 = 5.600 unit → 56 ml larutan (100 unit/ml) bolus
> Maintenance = 18 × 70 = 1.260 unit/jam → 12,6 ml/jam → bulatkan **13 ml/jam**
>
> Target APTT: 60–100 detik (1,5–2,5× normal)
> Cek APTT 6 jam setelah mulai atau perubahan dosis

---

##### LMWH (Enoxaparin)

```
Terapi DVT/PE   : 1 mg/kgBB SC tiap 12 jam
Profilaksis DVT : 0,4 ml SC sekali sehari
```

---

##### Reversal Antikoagulan

```
UFH → Protamin Sulfat
  1 mg protamin netralisir ~100 unit UFH (diberikan 2–3 jam terakhir)
  Maks single dose: 50 mg, berikan IV pelan 10–15 menit

Warfarin → Vitamin K + FFP atau PCC
  Warfarin + perdarahan aktif:
    Vitamin K 10 mg IV pelan + FFP 10–15 ml/kgBB ATAU
    PCC 25–50 unit/kgBB (lebih cepat, volume lebih kecil)

DOAC Dabigatran → Idarucizumab 5 g IV
DOAC Rivaroxaban/Apixaban → Andexanet alfa atau PCC
```

---

#### B5 — Obat Emergensi Lainnya

##### Manitol 20% — untuk TIK Tinggi

```
Dosis    : 0,25–1 g/kgBB IV bolus cepat dalam 10–20 menit
Onset    : 15–30 menit
Durasi   : 4–6 jam
```

> [!example] Pasien TBI dengan tanda herniasi, 60 kg
> Dosis 0,5 g/kgBB = 0,5 × 60 = 30 g Manitol 20%
> Volume = 30 ÷ 0,2 = **150 ml dalam 10–15 menit**
>
> Monitoring:
> - Osmolalitas serum target: 300–320 mOsm/kg
> - Bila > 320 → stop (risiko gagal ginjal)
> - Cek osmolalitas sebelum dosis ulang (tiap 4–6 jam)

---

##### NaCl 3% — Hiperosmolar untuk Edema Serebri

```
Bolus edema serebri : 150–250 ml IV dalam 30 menit
Infus kontinu       : 1–2 ml/kgBB/jam
Target Na serum     : 150–155 mEq/L

Untuk hiponatremia simtomatis:
  1–2 ml/kgBB NaCl 3% dalam 10–20 menit → naikkan Na 1–2 mEq/L → stop kejang
  Lalu koreksi lambat (tidak lebih dari 10 mEq/L per 24 jam total)
```

---

##### Tranexamic Acid (TXA)

```
CRASH-2 protocol (trauma dengan perdarahan):
  1 gram IV dalam 10 menit (bolus pelan)
  Dosis kedua: 1 gram IV dalam 8 jam berikutnya

WAJIB dalam 3 JAM PERTAMA dari cedera
Setelah 3 jam: tidak efektif, mungkin berbahaya

KONTRAINDIKASI: trombosis aktif (DVT, PE, MI), hematuria (sumbat ureter)
```

---

##### Furosemide (Diuretik Loop)

```
Dosis IV dewasa : 20–40 mg pelan; naikkan ke 80–200 mg bila refrakter
Edema paru akut : 40–80 mg IV bolus → evaluasi UO dalam 30–60 menit
Overload cairan : 1 mg/kgBB IV → titrasi ke target UO

Efek samping: hipokalemia, hiponatremia, hipomagnesemia → cek elektrolit
```

---

### SEKSI C — MONITORING & INTERPRETASI

---

#### C1 — Tanda Vital Normal per Usia

> [!info] Jangan Pakai Nilai Normal Dewasa untuk Anak!
> Bayi dengan HR 80 = bradikardia. Anak 2 tahun dengan RR 36 = normal. Salah interpretasi nilai normal per usia bisa menyebabkan over-treatment atau miss diagnosis kritis.

| Usia | HR (bpm) | RR (/mnt) | TD Sistolik (mmHg) | TD Minimal |
|------|---------|-----------|-------------------|-----------|
| Neonatus (0–28 hari) | 100–160 | 40–60 | 60–90 | > 60 |
| Bayi (1–12 bulan) | 100–160 | 30–60 | 70–100 | > 70 |
| Toddler (1–3 tahun) | 90–150 | 24–40 | 80–110 | > 70 + (2 × usia th) |
| Prasekolah (3–5 th) | 80–140 | 22–34 | 80–110 | > 70 + (2 × usia th) |
| Sekolah (6–12 th) | 70–120 | 18–30 | 90–120 | > 80 |
| Remaja (12–18 th) | 60–100 | 12–20 | 100–130 | > 90 |
| Dewasa | 60–100 | 12–20 | 100–140/60–90 | MAP ≥ 65 |

##### Rumus TD Minimal Anak

```
< 1 tahun   : > 70 mmHg
1–10 tahun  : > 70 + (2 × usia dalam tahun) mmHg
> 10 tahun  : > 90 mmHg

Contoh: Anak 5 tahun → minimal = 70 + (2×5) = 80 mmHg
```

---

#### C2 — Oksigenasi: Alat O₂ & Target Saturasi

| Alat | Flow O₂ (L/mnt) | FiO₂ | Indikasi |
|------|----------------|------|---------|
| Nasal Kanul | 1–6 | 24–44% | Hipoksemi ringan |
| Simple Face Mask | 5–10 | 35–60% | Hipoksemi sedang |
| **Non-Rebreather Mask (NRM)** | 10–15 | 60–90% | **Semua pasien kritis → default pertama** |
| Venturi Mask | 2–15 | 24–60% terkontrol | PPOK (FiO₂ diatur ketat) |
| BVM | 10–15 | ~100% | Pasien apnea/butuh ventilasi positif |
| Intubasi + Ventilator | Sesuai setting | 21–100% | GCS ≤ 8, gagal napas |

##### Target SpO₂ per Kondisi

```
Umum/semua kasus darurat   : ≥ 95%
TBI                        : ≥ 95% (hipoksia = cedera sekunder!)
Stroke                     : 94–99%
PPOK eksaserbasi           : 88–92% (jangan menekan drive hipoksik)
Post-cardiac arrest        : 94–96% (hindari hiperoksemia)
Luka bakar + CO poisoning  : 100% NRM (SpO₂ palsu pada CO!)
Neonatus prematur          : 90–95%
```

> [!danger] SpO₂ Normal TIDAK Berarti Oksigenasi Jaringan Normal
> CO poisoning: SpO₂ bisa 99% tapi pasien hipoksia berat → karboksihemoglobin terdeteksi sama seperti oksi-Hb oleh pulse oximeter. Ukur COHb dengan co-oximetry.

---

#### C3 — Urine Output: Target & Interpretasi

```
Target UO:
  Normal / post-op umum          : 0,5 ml/kgBB/jam (≈ 30–50 ml/jam dewasa)
  Resusitasi syok hipovolemik    : 0,5–1,0 ml/kgBB/jam
  Resusitasi luka bakar (Baxter) : 0,5–1,0 ml/kgBB/jam (panduan titrasi!)
  Rhabdomiolisis                 : 1–3 ml/kgBB/jam (paksa flush mioglobin)
  TBI                            : 0,5 ml/kgBB/jam (jangan overload)
  Anak                           : 1 ml/kgBB/jam
  Neonatus                       : 2 ml/kgBB/jam
```

##### Evaluasi Oliguria (< 0,5 ml/kgBB/jam selama ≥ 2 jam)

```
Langkah sistematik:
  1. Cek kateter: tersumbat? terlipat? → flush dulu
  2. Status cairan: dehidrasi? → passive leg raise test
  3. MAP: < 65? → perbaiki perfusi ginjal
  4. Urinalisis: protein, silinder, hematuria → arah AKI
  5. Urea + kreatinin → bedakan pre-renal vs renal vs post-renal

PRE-RENAL (lebih sering):
  Na urin < 20 mEq/L
  FENa < 1%   [FENa = (Na urin × Kr serum) ÷ (Na serum × Kr urin) × 100]
  Respons terhadap cairan

AKI RENAL (tubular necrosis):
  Na urin > 40 mEq/L
  FENa > 2%
  Silinder granular di urinalisis
  Tidak respons cairan
```

---

#### C4 — Skoring Klinis yang Wajib Hafal

##### qSOFA (Sepsis Screening)

```
Skor 1 poin tiap kriteria:
  □ RR ≥ 22/menit
  □ GCS berubah (< 15)
  □ TD sistolik ≤ 100 mmHg

qSOFA ≥ 2 → kemungkinan sepsis → evaluasi SOFA lengkap + mulai resusitasi
```

---

##### Alvarado Score (Apendisitis)

```
M — Migration nyeri ke RLQ          : 1 poin
A — Anoreksia                        : 1 poin
N — Nausea/vomiting                  : 1 poin
T — Tenderness di McBurney           : 2 poin
R — Rebound tenderness               : 1 poin
E — Elevasi suhu > 37,3°C            : 1 poin
L — Leukositosis > 10.000/μL         : 2 poin
S — Shift to left                    : 1 poin
Total                                : 10 poin

≤ 4  → risiko rendah (pertimbangkan pulang/obs)
5–6  → meragukan (USG/CT scan)
≥ 7  → tinggi → apendektomi
```

---

##### Ranson Criteria (Pankreatitis Akut)

```
SAAT MASUK (5 kriteria):
  □ Usia > 55 tahun
  □ Leukosit > 16.000/μL
  □ Glukosa > 200 mg/dL
  □ LDH > 350 IU/L
  □ AST > 250 IU/L

DALAM 48 JAM (6 kriteria):
  □ Ht turun > 10%
  □ BUN naik > 5 mg/dL
  □ Ca serum < 8 mg/dL
  □ PaO₂ < 60 mmHg
  □ Base deficit > 4 mEq/L
  □ Fluid sequestration > 6 L

< 3 poin  : ringan, mortalitas < 1%
3–4 poin  : mortalitas ~15%
5–6 poin  : mortalitas ~40%
> 6 poin  : mortalitas ~100%
```

---

##### Kocher Criteria (Septic Arthritis Anak)

```
□ Demam > 38,5°C              : 1 poin
□ ESR > 40 mm/jam             : 1 poin
□ WBC > 12.000/μL             : 1 poin
□ Non-weight-bearing          : 1 poin
□ CRP > 2 mg/dL               : 1 poin

0 poin   : 0,2% kemungkinan septic arthritis
1 poin   : 3%
2 poin   : 40%
3 poin   : 93%
4–5 poin : > 99% → drainase segera tanpa tunggu konfirmasi lanjut!
```

---

### SEKSI D — KALKULASI LUKA BAKAR

---

#### D1 — Rule of Nine & Metode Lain

> [!abstract] Analogi: Tubuh Dibagi Seperti Pizza
> Tiap "irisan" = 9% luas permukaan tubuh. Jumlahkan irisan yang terkena untuk dapatkan TBSA.

##### Rule of Nine (Dewasa)

```
Kepala + Leher          = 9%
Dada depan              = 9%
Perut depan             = 9%
Punggung atas           = 9%
Punggung bawah          = 9%
Lengan kanan (seluruh)  = 9%
Lengan kiri (seluruh)   = 9%
Paha kanan              = 9%
Tungkai bawah kanan     = 9%
Paha kiri               = 9%
Tungkai bawah kiri      = 9%
Genitalia/Perineum      = 1%
TOTAL                   = 100%
```

> [!warning] Rule of Nine TIDAK Akurat untuk Anak! → Pakai Lund-Browder

##### Koreksi Anak (Lund-Browder Disederhanakan)

| Area | Bayi < 1 th | 5 th | 10 th | Dewasa |
|------|------------|------|-------|--------|
| Kepala | 18% | 13% | 11% | 9% |
| Paha (tiap sisi) | 5,5% | 6,5% | 7,5% | 9% |
| Tungkai bawah (tiap sisi) | 3,5% | 4,5% | 6% | 7% |
| Badan depan | 18% | 18% | 18% | 18% |
| Badan belakang | 18% | 18% | 18% | 18% |

---

##### Palm Method

```
Telapak tangan pasien sendiri (termasuk jari) = 1% TBSA
Berguna untuk luka bakar tidak beraturan (percikan, kontak singkat)
```

> [!tip] PENTING: Jangan masukkan luka bakar derajat I dalam perhitungan TBSA untuk resusitasi!
> Hitung HANYA derajat IIA, IIB, dan III untuk formula Baxter.

---

#### D2 — Derajat Luka Bakar (Kedalaman)

| Derajat | Kedalaman | Tampilan | Nyeri | Penyembuhan |
|---------|-----------|----------|-------|-------------|
| **I** | Epidermis | Merah, kering, tanpa bula | ✅ Ada | Spontan 3–5 hari |
| **IIA** | Dermis papillar | Merah terang, bula, basah | ✅✅ Sangat nyeri | Spontan 7–14 hari |
| **IIB** | Dermis retikuler | Putih/pink pucat, bula besar | Kurang nyeri | Butuh 21–35 hari, sering perlu graft |
| **III** | Seluruh dermis | **Putih/coklat, kering, eschar keras** | **Tidak nyeri!** | **Wajib skin graft** |
| **IV** | Sampai otot/tulang | Hitam, terkarbonikasi | Tidak nyeri | Amputasi/rekonstruksi besar |

> [!tip] Cara Cepat Bedain di Klinis
> - Tusuk jarum → nyeri → masih ada ujung saraf → IIA/IIB
> - Tarik rambut → cabut mudah tanpa nyeri → folikel mati → IIB/III
> - Tekstur: IIA = lembab-merah; IIB = pucat; III = putih keras/coklat kering

---

#### D3 — Formula Baxter (Parkland) — Step by Step

> [!success] Hafal Formula Ini — Wajib Diketahui Semua Koas Bedah

```
FORMULA BAXTER:
Total cairan 24 jam = 4 ml × BB (kg) × % TBSA (derajat II + III)

½ total → diberikan dalam 8 JAM PERTAMA
½ total → diberikan dalam 16 JAM BERIKUTNYA

⚠️ PENTING: 8 jam dihitung dari WAKTU KEJADIAN, bukan waktu tiba di IGD!

Cairan: RINGER LAKTAT (bukan NaCl 0,9%)
```

---

##### Langkah Kalkulasi Step by Step

```
Langkah 1: Tentukan TBSA (hitung HANYA derajat II + III)
Langkah 2: Total = 4 × BB × TBSA
Langkah 3: ½ untuk 8 jam pertama dari waktu kejadian
Langkah 4: Hitung mundur → berapa jam tersisa?
Langkah 5: Kecepatan = ½ total ÷ jam tersisa
Langkah 6: ½ kedua ÷ 16 = kecepatan 16 jam berikutnya
```

---

> [!example] Kasus 1 — Pasien 2 di IGD RSUD Karsa Husada Batu (Datang Segera)
> **Wanita 55 kg, luka bakar semburan radiator. Wajah merah + bula (IIA, 9%) + leher bula besar (IIB, 4,5%) + tangan kanan (IIA, 4,5%). Tiba di IGD 30 menit setelah kejadian.**
>
> **TBSA** = 9 + 4,5 + 4,5 = **18%** (semua derajat II, masuk hitungan)
>
> **Total cairan 24 jam** = 4 × 55 × 18 = **3.960 ml RL**
>
> **½ pertama (8 jam dari kejadian)** = 1.980 ml
> Sudah 30 menit sejak kejadian → sisa 7,5 jam
> **Kecepatan** = 1.980 ÷ 7,5 = **264 ml/jam**
>
> **½ kedua (16 jam berikutnya)** = 1.980 ml
> **Kecepatan** = 1.980 ÷ 16 = **124 ml/jam**
>
> Target UO: 0,5–1 ml/kgBB/jam = **27–55 ml/jam** → ini yang menentukan titrasi, bukan angka kalkulasi saja!

---

> [!example] Kasus 2 — Datang Terlambat (4 Jam Setelah Kejadian)
> **Pria 60 kg, luka bakar minyak goreng, 30% TBSA (IIA + IIB). Tiba di IGD 4 jam setelah kejadian.**
>
> Total = 4 × 60 × 30 = **7.200 ml RL**
>
> ½ pertama = 3.600 ml untuk 8 jam dari kejadian
> Sudah 4 jam → sisa **4 jam** untuk kejar 3.600 ml
> **Kecepatan = 3.600 ÷ 4 = 900 ml/jam** (harus kejar!)
>
> ½ kedua = 3.600 ÷ 16 = **225 ml/jam**
>
> Target UO: 0,5–1 ml/kgBB/jam = **30–60 ml/jam**

---

##### Titrasi Baxter Berdasarkan UO

```
Angka Baxter = STARTING POINT, bukan harga mati!

UO < 0,5 ml/kgBB/jam → percepat cairan (+20% dari rate saat ini)
UO > 1 ml/kgBB/jam  → perlambat cairan (-20% dari rate saat ini)
Re-evaluasi tiap 1–2 jam dan sesuaikan
```

---

##### Hari Kedua dan Seterusnya

```
Hari kedua (24 jam kedua):
  Kristaloid  : ½ dari total hari pertama
  Koloid      : 0,3–0,5 ml/kgBB/% TBSA (albumin 5%, mulai setelah 18–24 jam)
  Dextrose 5% : 500–1.000 ml/hari → ganti insensible water loss

Contoh lanjutan: Pria 60 kg, 30% TBSA
  Hari 1 total: 7.200 ml
  Hari 2 kristaloid: 3.600 ml RL
  Hari 2 koloid: 0,4 × 60 × 30 = 720 ml albumin 5%
```

---

#### D4 — Luka Bakar Inhalasi — Modifikasi Cairan

```
Luka bakar inhalasi → tambah 30–50% dari kalkulasi Baxter standar

Tanda inhalasi yang wajib dicari:
  □ Terbakar di ruang tertutup
  □ Bulu hidung hangus
  □ Sputum jelaga
  □ Suara serak → intubasi segera sebelum edema laring total
  □ Stridor, distress napas
  □ SpO₂ bisa normal palsu (CO poisoning!) → O₂ 100% NRM segera

CO Poisoning:
  T½ COHb dengan O₂ 100% NRM = 60–90 menit
  T½ COHb dengan udara ruang  = 4–5 jam
  → Selalu O₂ 100% NRM sampai COHb < 5%
```

---

#### D5 — Escharotomi: Indikasi & Prinsip

```
Indikasi escharotomi:
  Ekstremitas: full thickness sirkumferensial → tanda kompartemen
    (nadi distal melemah/hilang, parestesia)
  Dada: sirkumferensial → restriksi gerak napas
    (↑ tekanan ventilasi atau ↓ compliance)

Teknik:
  Insisi hanya menembus eschar (bukan sampai fascia seperti fasciotomi)
  Ekstremitas: insisi longitudinal medial DAN lateral
  Dada: insisi midaksilaris bilateral + sambungkan subkostal bila perlu
  Luka terbuka sementara → tutup dengan dressing basah
```

---

## ⚠️ 6. Yang Sering Ditanya Konsulen

> [!question] Pertanyaan Konsulen & Jawabannya

❓ **Pasien ini Grade berapa syoknya? Bagaimana cara menentukan?**
✅ Lihat tekanan nadi (menyempit = sudah Grade II), HR, TD sistolik, RR, GCS, dan UO. Grade I: semua normal, Grade II: HR 100–120 + tekanan nadi menyempit, Grade III: HR 120–140 + TD sistolik turun + GCS bingung, Grade IV: HR > 140 + TD sangat rendah + GCS letargis.

❓ **Berapa bolus cairan pertama yang kamu berikan, dan cairan apa?**
✅ RL atau NaCl 0,9% hangat, 1–2 liter (dewasa) atau 20 ml/kgBB (anak), diberikan dalam 15–30 menit. Evaluasi respons setelah bolus pertama.

❓ **Kapan kamu mulai vasopressor?**
✅ Setelah resusitasi cairan adekuat (2–3 L) tapi MAP masih < 65 mmHg, atau setelah 30 ml/kgBB pada sepsis. Pada syok anafilaksis → epinefrin IM sejak awal bersamaan dengan cairan.

❓ **Kamu buat drip norepinefrin dengan konsentrasi berapa, dan kecepatan berapa?**
✅ Standar: 4 mg dalam 250 ml NaCl 0,9% = 16 mcg/ml. Dosis awal 0,1–0,2 mcg/kgBB/menit. Kecepatan (ml/jam) = dosis × BB × 60 ÷ konsentrasi.

❓ **Berapa target urine output pada pasien luka bakar?**
✅ 0,5–1 ml/kgBB/jam. Ini yang menjadi panduan titrasi Baxter, bukan angka kalkulasinya saja.

❓ **Kamu hitung Baxter dari waktu kapan?**
✅ Dari waktu KEJADIAN, bukan waktu tiba di IGD! Bila pasien datang terlambat, harus kejar ½ volume pertama dalam sisa waktu yang ada sampai 8 jam dari kejadian.

❓ **Kapan kamu boleh koreksi hiponatremia dengan NaCl 3%?**
✅ Hanya pada hiponatremia simtomatis (kejang aktif, GCS turun berat). Dosis: 1–2 ml/kgBB NaCl 3% untuk naikkan Na 1–2 mEq/L dan stop kejang, lalu lanjut koreksi lambat. Maksimal 10 mEq/L per 24 jam total.

❓ **Pasien fibrilasi atrium dengan DVT, bagaimana mulai heparin?**
✅ Loading 80 unit/kgBB IV bolus, lanjut infus 18 unit/kgBB/jam. Cek APTT 6 jam kemudian, target 60–100 detik. Sesuaikan dengan nomogram heparin.

❓ **Kapan TXA harus diberikan dan kapan tidak boleh?**
✅ Harus dalam 3 jam pertama dari cedera trauma, dosis 1 gram IV dalam 10 menit. Setelah 3 jam tidak efektif bahkan berbahaya. Kontraindikasi: trombosis aktif, hematuria (bisa sumbat ureter dengan bekuan).

❓ **Pasien luka bakar 35% TBSA sudah 6 jam, datang dari RS lain, belum dapat cairan. Kamu ngapain pertama?**
✅ Hitung total Baxter (4 × BB × 35%). ½ pertama harusnya diberikan dalam 8 jam dari kejadian, sudah berlalu 6 jam → sisa 2 jam → kecepatan sangat tinggi untuk kejar defisit. Pasang IV line 2 jalur, mulai RL kecepatan tinggi, pasang kateter urin untuk monitor UO tiap jam.

---

## ✅ 7. Checklist Sebelum Konsul / Visite

> [!todo] Checklist Kalkulasi Klinis — Semua Wajib Terjawab

**Resusitasi Syok:**
- [ ] Sudah tentukan jenis syok (hipovolemik/distributif/kardiogenik/obstruktif)?
- [ ] Sudah estimasi EBV dan persentase kehilangan darah?
- [ ] Sudah berikan bolus pertama dan catat waktu pemberian?
- [ ] Sudah evaluasi respons setelah bolus (HR, TD, UO, laktat)?
- [ ] Sudah tentukan target MAP, UO, dan laktat yang akan dimonitor?
- [ ] Bila transfusi: sudah tahu berapa unit dan siapkan darah golongan apa?

**Vasopressor:**
- [ ] Sudah tahu dosis awal norepinefrin/dopamin dalam mcg/kgBB/menit?
- [ ] Sudah bisa hitung kecepatan ml/jam dari dosis dan konsentrasi?
- [ ] Sudah tahu target MAP dan kapan titrasi naik/turun?

**Luka Bakar:**
- [ ] Sudah tentukan derajat tiap area yang terkena?
- [ ] Sudah hitung TBSA dengan benar (derajat I tidak masuk!)?
- [ ] Sudah tahu waktu KEJADIAN (bukan waktu tiba)?
- [ ] Sudah hitung total Baxter dan 2 fase kecepatan drip?
- [ ] Kateter urin sudah terpasang dan UO sudah dicatat per jam?
- [ ] Ada tanda inhalasi? Sudah pasang O₂ 100% NRM?

**Elektrolit:**
- [ ] Bila hiponatremia: sudah hitung TBW dan defisit Na?
- [ ] Sudah tahu batas kecepatan koreksi (maks 10 mEq/L per 24 jam)?
- [ ] Bila hiperkalemia berat: sudah siapkan kalsium glukonat, insulin + dekstrosa, dan pasang monitoring EKG?
- [ ] Bila mau kasih KCl IV: sudah dilute dan kecepatan maksimal sudah benar?

**Antibiotik:**
- [ ] Sudah tentukan kondisi dan pilihan antibiotik empirik yang tepat?
- [ ] Antibiotik profilaksis pre-op sudah diberikan 30–60 menit sebelum insisi?
- [ ] Sudah ambil kultur (darah/urin/pus) SEBELUM memberikan antibiotik?

---

*Terakhir diupdate: Juni 2026 · Taufiq · Koas Bedah FKIK UIN Malang · RSUD Karsa Husada Batu*
*Lihat juga: [[00 - MASTERPLAN UTAMA STASE BEDAH|Masterplan Utama]] · [[10B - BASIC CALCULATIONS - Ortopedi, Pediatri, Nutrisi, Lab|→ 10B: Ortopedi, Pediatri, Nutrisi, Lab]] · [[01 - MASTERPLAN IGD 1|IGD 1]] · [[05 - MASTERPLAN IGD 2|IGD 2]]*
