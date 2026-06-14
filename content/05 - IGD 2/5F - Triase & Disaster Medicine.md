---
title: "5F — Triase & Disaster Medicine"
description: "Sistem triase START, METHANE report, peran koas saat mass casualty incident, dan trauma khusus blast injury"
date: 2026-06-13
tags:
  - koas/bedah-igd-2
  - igd-2/triase
  - disaster-medicine
  - MCI
  - blast-injury
aliases:
  - 5F
  - triase bencana
  - mass casualty incident
---

# 🚦 5F — Triase & Disaster Medicine

> **Lihat juga:** [[05 - MASTERPLAN IGD 2|Masterplan IGD 2]] · [[00 - MASTERPLAN UTAMA STASE BEDAH|Masterplan Utama]] · [[5A - Trauma Multipel & Major Trauma|5A]]

---

## 🏥 1. Opening Kasus

Pukul 19.45, radio IGD tiba-tiba ramai: "Ada kecelakaan bus vs truk di jalan raya arah Malang, perkiraan korban lebih dari 15 orang, beberapa terjepit di dalam bus, ambulans pertama akan tiba dalam 10 menit dengan 3 pasien sekaligus." Kepala IGD langsung menginstruksikan: "Standby semua, ini mass casualty — kosongkan ruang resusitasi, siapkan area tambahan."

Kamu ditunjuk sebagai salah satu petugas yang akan membantu di pintu masuk IGD. Dalam 20 menit berikutnya, pasien berdatangan dalam gelombang — ada yang bisa berjalan sendiri sambil memegang lengannya yang berdarah, ada yang digotong tidak sadarkan diri dengan napas tersengal, ada yang berteriak kesakitan memegang perutnya, dan — yang paling sulit — ada satu pasien yang sudah tidak bernapas sama sekali dengan luka kepala yang sangat parah.

Biasanya, refleks pertamamu adalah lari ke pasien yang paling "terlihat parah" dan berteriak minta bantuan untuk satu pasien itu. Tapi sekarang ada belasan pasien sekaligus, dan tim yang tersedia terbatas. Nah, kamu mau ngapain sekarang?

---

## 🔪 2. Kenapa Ini Penting?

Disaster medicine mengubah cara berpikirmu secara fundamental: di hari biasa, etika kedokteran mengajarkan "tangani yang paling parah dulu, berikan semua sumber daya untuk menyelamatkan satu nyawa." Pada **mass casualty incident (MCI)**, prinsip ini justru bisa membunuh LEBIH BANYAK orang — karena menghabiskan sumber daya terbatas untuk satu pasien yang kemungkinan selamatnya kecil, sementara beberapa pasien lain yang *bisa diselamatkan dengan intervensi minimal* tidak tertangani dan memburuk.

Pasien khas skenario ini di RSUD Karsa Husada Batu: kecelakaan bus/truk di jalan antar-kota, kebakaran pabrik/gudang, atau ledakan tabung gas — situasi yang jumlah korbannya melebihi kapasitas normal IGD.

Yang fatal kalau terlewat:
- **Tidak ada sistem triase** → chaos, semua tim berkumpul di satu pasien sementara pasien lain yang sebenarnya bisa diselamatkan terlantar
- **Tidak melakukan re-triase** → pasien yang awalnya "kuning" memburuk jadi "merah" tapi tidak terdeteksi karena label awal tidak diperbarui
- **Komunikasi tidak terstruktur** ke rumah sakit/komando → bantuan yang datang tidak sesuai kebutuhan riil

Koas yang paham sistem ini bisa langsung berkontribusi sebagai Triage Officer atau Area Officer — peran nyata yang sangat dibutuhkan saat MCI, bukan sekadar penonton.

---

## 📚 3. Dasar yang Harus Kamu Tahu

### Analogi Dulu: "Sekoci Penyelamat dengan Kapasitas Terbatas"

Bayangkan kapal yang sedang tenggelam dengan satu sekoci yang hanya bisa menampung 10 orang, tapi ada 30 orang di air. Petugas sekoci tidak bisa menyelamatkan semua sekaligus — ia harus memilih cepat: siapa yang masih bisa berenang sendiri ke pelampung lain (bisa ditunda), siapa yang tenggelam tapi masih bisa diraih dalam beberapa detik (prioritas utama), dan — yang paling berat secara emosional — siapa yang sudah tidak bergerak sama sekali dan kemungkinan sudah tidak bisa diselamatkan dengan sumber daya yang ada (kategori yang tidak ditangani aktif, demi menyelamatkan yang lain). Ini bukan soal "siapa yang lebih berharga" — ini matematika penyelamatan jumlah maksimal nyawa dengan sumber daya terbatas.

### Sistem Triase START (Simple Triage and Rapid Treatment)

```
Datangi pasien:
  1. Bisa berjalan sendiri? → HIJAU (MINOR) → kumpulkan di area tunggu
  2. Tidak bisa berjalan → lanjut:
     Napas? → Tidak ada setelah reposisi airway → HITAM (DEAD/EXPECTANT)
     Ada → Hitung RR:
       - RR > 30x/menit → MERAH (IMMEDIATE)
       - RR ≤ 30x/menit → cek perfusi (CRT/nadi radial):
         - CRT > 2 detik / nadi radial tidak teraba → MERAH
         - CRT ≤ 2 detik / nadi radial teraba → cek status mental:
           - Tidak bisa ikuti perintah → MERAH
           - Bisa ikuti perintah → KUNING (DELAYED)
```

| Label | Warna | Makna | Prioritas |
|-------|-------|-------|-----------|
| IMMEDIATE | 🔴 Merah | Butuh tindakan segera untuk bertahan hidup | 1 |
| DELAYED | 🟡 Kuning | Cedera signifikan tapi stabil sementara | 2 |
| MINOR | 🟢 Hijau | "Walking wounded" — cedera ringan | 3 |
| EXPECTANT/DEAD | ⚫ Hitam | Tidak survivable dengan sumber daya yang ada | 4 |

> [!warning] Kategori HITAM Paling Sulit Secara Psikologis
> Pasien masih bernapas tapi cedera tidak survivable (kepala hancur, trunk terbelah, luka bakar >90% pada lansia) → HITAM di konteks MCI. Ini KEPUTUSAN MEDIS berdasarkan alokasi sumber daya, bukan penilaian moral terhadap nilai hidup seseorang.

Pada kasus opening: pasien yang bisa berjalan sendiri sambil memegang lengan berdarah → **HIJAU**. Pasien tidak sadar dengan napas tersengal → cek RR dan perfusi → kemungkinan besar **MERAH**. Pasien yang sudah tidak bernapas dengan luka kepala sangat parah → setelah reposisi airway tetap tidak bernapas → **HITAM**.

📸 *Search: `"START triage algorithm flowchart mass casualty"`*

### METHANE Report — Komunikasi Bencana yang Benar

```
M — Major Incident (nyatakan: "Major Incident declared" atau "Standby")
E — Exact Location (koordinat/lokasi tepat)
T — Type of Incident (KLL, ledakan, kebakaran, gempa, dll)
H — Hazards (bahaya: gas beracun, api aktif, bangunan runtuh)
A — Access (rute masuk aman untuk petugas & ambulans)
N — Number of Casualties (perkiraan jumlah + distribusi triase)
E — Emergency Services (siapa sudah ada, siapa dibutuhkan)
```

METHANE diucapkan jelas, TIDAK disingkat saat komunikasi radio — digunakan first responder ke komando medis/IGD penerima.

### Blast Injury — 4 Kategori (untuk kasus ledakan)

1. **Primer**: overpressure wave → cedera organ berongga (timpani, paru, usus) → **blast lung** paling mematikan, tampilan luar bisa normal tapi dalam sudah hancur
2. **Sekunder**: fragmen/shrapnel → luka tembus multipel
3. **Tersier**: tubuh terpental → cedera seperti jatuh dari ketinggian
4. **Kuartener**: panas/kimia/asap → luka bakar, inhalasi, keracunan

📸 *Search: `"blast injury primary secondary tertiary quaternary effects explosion diagram"`*

---

## 🔍 4. Cara Berpikir di Depan Pasien

### Saat Notifikasi MCI Diterima (Sebelum Pasien Datang)

- Pastikan IGD siap: amankan area (keluarkan pasien stabil dari ruang resusitasi), pastikan supply darah/kristaloid/oksigen/troli emergency
- Tunjuk Triage Officer di pintu masuk
- Buka jalur komunikasi dengan bedah + anestesi + ICU
- Catat METHANE report dari first responder bila tersedia

### Saat Pasien Berdatangan — Peran Triage Officer

- Jalankan algoritma START pada SETIAP pasien yang masuk, secepat mungkin (target <60 detik per pasien)
- Beri label triase yang melekat di tubuh pasien (gelang/kartu di tangan/kaki)
- JANGAN terjebak melakukan tindakan lengkap pada satu pasien — tugas triage officer adalah MEMILAH, bukan mengobati
- Arahkan pasien ke area sesuai label (merah → resusitasi, kuning → observasi, hijau → area tunggu, hitam → area terpisah)

### Red Flags Saat MCI

- Kondisi pasien berubah → **re-triase wajib**, label bisa berubah dari kuning ke merah
- Satu tim resusitasi terjebak terlalu lama di satu pasien yang sebenarnya kategori hitam → realokasi sumber daya
- Hazard di lokasi belum dilaporkan via METHANE → bahaya berkelanjutan bagi responder

### Diagnosis Banding pada Trauma Khusus (Blast/Tembak)

- Pasien dari ledakan dengan tampilan luar minimal tapi sesak/hipoksia → curiga **blast lung** (cedera primer) — periksa thoraks dengan seksama meski tidak ada luka eksternal jelas
- Luka tembus abdomen: luka tembak → cenderung laparotomi segera bila ada tanda peritonitis/syok; luka tusuk → selektif (observasi bila stabil tanpa tanda intraperitoneal)

### Pemeriksaan Penunjang

Pada situasi MCI awal, pemeriksaan penunjang **bukan prioritas** — fokus pada triase cepat dan stabilisasi dasar (airway, kontrol perdarahan eksternal). Penunjang dilakukan setelah pasien masuk area resusitasi sesuai prioritas.

---

## 💊 5. Tatalaksana

### Prinsip Saat MCI Berlangsung

> [!success] Peran Koas: Triage Officer atau Area Officer
> Kamu belum jadi team leader, tapi bisa jadi Triage Officer (memilah pasien masuk) atau Area Officer (koordinasi satu area perawatan). Yang terpenting: **jangan panik, ikuti sistem, komunikasi singkat dan jelas**.

- **Satu pasien = satu perawat/dokter** → tidak ada yang memonopoli tim resusitasi untuk satu pasien saat banyak korban menunggu
- Dokumentasi minimal tapi harus ada: label triase melekat di tubuh
- **Re-triase berkelanjutan**: kondisi pasien bisa berubah cepat
- **Surge capacity**: gunakan koridor, lorong, atau area tambahan bila ruang resusitasi penuh

### Tatalaksana Kategori Merah (Immediate)

- Prioritaskan: kontrol airway, kontrol perdarahan eksternal masif (direct pressure/tourniquet), needle decompression bila tension pneumothorax — tindakan CEPAT dan MINIMAL, bukan manajemen lengkap di tempat
- Setelah stabilisasi minimal, pindahkan ke area resusitasi definitif

### Tatalaksana Kategori Kuning (Delayed)

- Observasi berkala, splinting fraktur, analgetik
- Re-evaluasi tanda vital secara periodik — siap re-triase ke merah bila memburuk

### Tatalaksana Kategori Hijau (Minor)

- Area tunggu terpisah, luka ringan ditangani belakangan (jahit, dressing)

### Tatalaksana Kategori Hitam (Expectant)

- Area terpisah, perawatan kenyamanan (comfort care) bila masih bernapas tapi tidak survivable
- Re-evaluasi BILA sumber daya menjadi tersedia (situasi bisa berubah)

### Blast Injury — Pertimbangan Khusus

- Periksa SELURUH tubuh termasuk axila, perineum, leher untuk fragmen/shrapnel (cedera sekunder)
- **Jangan cabut objek penusuk yang masih tertancap** — bisa menyumbat pembuluh darah yang sudah robek, cabut hanya di kamar operasi
- Curiga blast lung pada semua korban ledakan dengan keluhan napas, meski tampilan luar minimal

### Kapan "Konsul" — Eskalasi dalam Konteks MCI

- Update berkala ke komando/konsulen senior: jumlah pasien per kategori (merah/kuning/hijau/hitam), sumber daya yang dibutuhkan (darah, OK, ICU bed)
- METHANE report ke RS rujukan bila perlu transfer

---

## ⚠️ 6. Yang Sering Ditanya Konsulen

❓ *Berapa jumlah pasien per kategori triase sejauh ini?*
✅ Sebutkan jumlah merah/kuning/hijau/hitam secara real-time — ini menentukan alokasi sumber daya (OK, ICU, darah).

❓ *Kenapa pasien ini diberi label hitam padahal masih bernapas?*
✅ Karena cedera dinilai tidak survivable dengan sumber daya yang tersedia saat ini (jelaskan temuan spesifik) — ini bukan "ditinggalkan", tapi alokasi prioritas demi menyelamatkan jumlah maksimal pasien lain yang bisa diselamatkan.

❓ *Apakah ada re-triase yang dilakukan?*
✅ Sebutkan pasien mana yang berubah kategori dan kapan — sistem START membutuhkan re-evaluasi berkelanjutan, tidak statis sejak triase awal.

❓ *METHANE report sudah dikirim ke RS rujukan/komando?*
✅ Sebutkan isi laporannya — terutama jumlah korban dan distribusi triase, serta hazard yang masih ada.

❓ *Pada korban ledakan ini, sudah dicurigai blast lung?*
✅ Periksa thoraks untuk tanda blast lung meski tampilan luar minimal — cedera primer blast bisa sangat berat secara internal tanpa tanda eksternal jelas.

❓ *Kenapa benda yang menancap di pasien ini tidak dicabut?*
✅ Karena bisa menyumbat pembuluh darah yang sudah robek di sekitarnya — pencabutan hanya dilakukan di kamar operasi dengan kontrol perdarahan siap.

❓ *Apa peranmu saat MCI ini?*
✅ Sebutkan peran spesifik (Triage Officer/Area Officer) dan apa yang sudah dilakukan — menunjukkan kamu paham sistem, bukan sekadar membantu tanpa arah.

---

## ✅ 7. Checklist Sebelum Konsul / Visite

- [ ] Sudah paham algoritma START dan bisa menjalankannya pada pasien secara cepat (<60 detik)?
- [ ] Sudah tahu cara memberi label triase yang melekat di tubuh pasien?
- [ ] Sudah memahami konsep re-triase dan kapan label bisa/harus berubah?
- [ ] Sudah tahu isi dan urutan METHANE report?
- [ ] Sudah paham peran Triage Officer vs Area Officer dan kapan masing-masing dibutuhkan?
- [ ] Bila ada kasus blast injury: sudah periksa tanda blast lung dan cedera sekunder (shrapnel) secara menyeluruh?
- [ ] Sudah paham prinsip "jangan cabut benda tertancap di IGD"?
- [ ] Sudah siapkan update jumlah pasien per kategori triase untuk dilaporkan?

---

*Bagian dari [[05 - MASTERPLAN IGD 2|Masterplan IGD 2]] · Taufiq · Koas Bedah FKIK UIN Malang · RSUD Karsa Husada Batu*
