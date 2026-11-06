# DIKEJAR SAWIT: Dokumen Desain

> Endless runner satire gelap + horor atmosferik tentang sawit dan karhutla di Indonesia.
> Pemain mengendalikan **korban**. Dunia di sekitarnya berbicara dengan **suara korporat dan pejabat**.

Status: `✅` = sudah ada di prototipe v0.1 · `⏳` = belum · `❓` = belum diputuskan
Cara memberi masukan: tandai ID dengan ✅ pakai / ❌ buang / ✏️ ubah, atau tambah baris baru.

---

## 0. Keputusan inti

| Aspek | Keputusan |
|---|---|
| Judul | **Dikejar Sawit** |
| Sudut pandang | Korban: warga desa (v0.1), lalu anak sekolah, petani kecil, orangutan |
| Suara satire | Korporat dan pejabat lewat ticker, notifikasi, baliho, layar game over |
| Nada | Satire gelap + horor atmosferik. Horor penuh hanya di ISPU "Berbahaya" |
| Pengejar | Api, asap, buldoser |
| Platform | Web (HTML + Canvas), mobile-first, swipe 4 arah, keyboard, haptic, Web Audio |
| Batasan | Tanpa gore. Tanpa nama perusahaan atau orang nyata. Perusahaan fiktif: **PT Hijau Lestari Abadi Tbk (HLA)** |
| Fakta nyata di game over | **Ya**, dengan sumber (wajib diverifikasi ulang sebelum rilis) |
| Ditunda | Mode Pelaku ("Direktur"), versi 2 |
| Arah visual | **Kabut** (v0.2): siluet datar berlapis, asap abu-kuning, satu warna merah. Moodboard di `design/` |

---

## A. Premis & Identitas
| ID | Elemen | Status |
|---|---|---|
| A1 | Pemain = warga yang kabur dari api, asap, dan ekspansi lahan | ✅ |
| A2 | PT Hijau Lestari Abadi Tbk: nama "hijau" untuk perusak hutan | ✅ |
| A3 | Judul *Dikejar Sawit* | ✅ |
| A4 | Slogan perusahaan: *"Menanam Masa Depan"* | ✅ |
| A5 | Logo daun hijau yang ujungnya terbakar | ⏳ |

## B. Mekanik Inti
| ID | Elemen | Status |
|---|---|---|
| B1 | 3 jalur, swipe kiri/kanan/atas/bawah + keyboard | ✅ |
| B2 | Meteran ISPU naik terus. Di 500, pemain meninggal karena ISPA | ✅ |
| B3 | Endless, tidak bisa dimenangkan | ✅ |
| B4 | Kiri-kanan jalur = sawit monoton dan tunggul terbakar | ✅ |
| B5 | Tersandung dua kali dalam 6 detik = disusul api | ✅ |
| B6 | Hujan sebagai jeda singkat, lalu kemarau tahun berikutnya | ✅ |
| B7 | Kecepatan bertambah seiring waktu | ✅ |

## C. Collectible & Power-up (versi korban)
| ID | Elemen | Status |
|---|---|---|
| C1 | Tandan buah sawit (brondolan): poin "brondolan dipungut". Tiap 15: "memungut brondolan dapat dipidana" | ✅ |
| C2 | 😷 Masker bantuan: ISPU −35. Teks: "1 lembar untuk 1 keluarga" | ✅ |
| C3 | 📄 Dokumen tanah adat: koleksi langka, tidak berguna di hadapan hukum | ⏳ |
| C4 | 🏥 Posko darurat: power-up yang tutup saat didatangi | ⏳ |
| C5 | Satwa yang berlari bersamamu dan bisa diselamatkan | ⏳ |

## D. Rintangan
| ID | Elemen | Aksi | Status |
|---|---|---|---|
| D1 | Kayu tebangan | Lompat (kalau tertabrak, tersandung) | ✅ |
| D2 | Spanduk "ZERO BURNING ✓" melintang | Merunduk | ✅ |
| D3 | Buldoser PT HLA | Pindah jalur (mematikan) | ✅ |
| D3b | Ekskavator PT HLA yang sedang menggali | Pindah jalur (mematikan) | ✅ |
| D4 | Gambut terbakar dari dalam (retakan menyala, berasap) | Lompat (mematikan) | ✅ |
| D5 | Kanal pengering yang dibuat perusahaan | Lompat | ⏳ |
| D6 | Pagar konsesi baru di atas tanah adat | ⏳ | ⏳ |
| D7 | Api loncat yang muncul tiba-tiba di depan | ⏳ | ⏳ |

## E. Momen Gelap
| ID | Elemen | Status |
|---|---|---|
| E1 | Satwa panik di pinggir jalur, suaranya berhenti tiba-tiba | ⏳ |
| E2 | Sekolah dengan anak bermasker, menghilang tertutup asap | ⏳ |
| E3 | Rumah panggung yang "tiba-tiba" jadi area konsesi | ⏳ |
| E4 | Burung jatuh dari langit di level Berbahaya | ⏳ |

## F. Teks, UI & Suara Korporat
| ID | Elemen | Status |
|---|---|---|
| F1 | Ticker berita dengan nada makin absurd per level ISPU | ✅ |
| F2 | Notifikasi ala HP: "Saham HLA naik 3%" | ✅ |
| F3 | Kutipan pejabat fiktif di loading screen | ⏳ |
| F4 | Penghitung hotspot satelit yang tidak pernah turun | ✅ |
| F5 | Tombol "Lari Lagi", tanpa tombol berhenti | ✅ |
| F6 | Laporan CSR: "Kami menanam 12 pohon" | ⏳ |
| F7 | Achievement ironis | ⏳ |

## G. Game Over
| ID | Elemen | Status |
|---|---|---|
| G1 | Teks penyebab kematian (ISPA, buldoser, gambut, spanduk, api) | ✅ |
| G2 | "PT HLA menyampaikan duka cita mendalam dan berkomitmen pada zero burning." | ✅ |
| G3 | Statistik: Jarak · Bibit · Kemarau dilalui · **Tersangka: 0** | ✅ |
| G4 | Satu fakta nyata + sumber | ✅ (verifikasi ulang) |
| G5 | Kamera berbalik ke siluet yang tersisa di asap | ⏳ |

## I. Pengejar
| ID | Elemen | Status |
|---|---|---|
| I1 | Api di belakang pemain, naik saat tersandung | ✅ |
| I2 | Buldoser yang ikut mengejar | ⏳ |
| I3 | Warga & satwa lain yang ikut berlari, satu per satu tumbang dalam asap | ⏳ |

## J. Karhutla
| ID | Elemen | Status |
|---|---|---|
| J1 | Garis api menjalar di samping jalur | ⏳ |
| J2 | Api gambut bawah tanah (= D4) | ✅ |
| J3 | Api loncat (= D7) | ⏳ |
| J4 | Hotspot counter (= F4) | ✅ |
| J5 | Kanal pengering (= D5) | ⏳ |
| J6 | Lapisan warna langit dan kabut per level ISPU | ✅ |
| J7 | Jarak pandang menyusut | ✅ |
| J8 | Matahari jingga lalu merah | ✅ |
| J9 | Nota protes negara tetangga | ✅ (notifikasi) |
| J10 | Pesawat water bombing yang terlambat | ✅ (melintas + notifikasi) |
| J11 | Petugas pemadam dengan alat seadanya | ⏳ |
| J12 | Hujan buatan (TMC): gerimis 2 detik | ⏳ |
| J13 | "Rakor dijadwalkan minggu depan" | ✅ |
| J14 | "Sumber api tidak diketahui" | ✅ |
| J15 | "Lahan terbakar dengan sendirinya" / "oknum warga" | ✅ |
| J16 | Siklus kemarau → hujan → kemarau tahun berikutnya | ✅ |
| J17 | Sekolah diliburkan, penerbangan dibatalkan, saham naik | ✅ |

## K. Tense & Horror
| ID | Elemen | Status |
|---|---|---|
| K1 | Rintangan baru terlihat dari kabut di detik-detik terakhir | ✅ |
| K2 | Siluet manusia di pinggir jalur (hanya ISPU ≥ 300) | ✅ |
| K3 | Langit biru → jingga → merah → gelap | ✅ |
| K4 | Vignette makin pekat, berdenyut dengan detak jantung | ✅ |
| K5 | Bara melayang | ✅ |
| K6 | Retakan merah di tanah gambut | ✅ |
| K7 | Napas makin berat dan cepat | ✅ |
| K8 | Batuk dari arah acak tanpa sumber terlihat | ✅ |
| K9 | Derak api dari belakang | ✅ |
| K10 | Detak jantung di level Berbahaya | ✅ |
| K11 | Pengumuman toa: "warga diimbau tetap di dalam rumah" | ⏳ |
| K12 | Melodi memudar, tinggal dengung | ✅ |
| K13 | Suara burung panik yang berhenti | ✅ (sederhana) |
| K14 | Tokoh menoleh ke belakang ke arah api (kamera belum) | ✅ (sebagian) |
| K16 | Getaran HP saat tersandung / mati | ✅ |
| K18 | Momen sunyi palsu sebelum api loncat | ⏳ |
| K19 | Ticker tetap ceria saat layar paling mengerikan | ✅ |
| K20 | Baliho korporat tersenyum, objek paling jelas dalam kabut | ✅ |
| K21 | Jingle iklan terdistorsi | ⏳ |
| K22 | "Status siaga darurat" muncul setelah game over | ✅ |

---

## Fakta untuk layar game over (G4)

> ⚠️ Angka di bawah ini dikutip dari ingatan atas laporan publik. **Wajib dicek ulang ke sumber aslinya sebelum rilis.**

1. Karhutla 2015 menghanguskan sekitar 2,6 juta hektare lahan. (Bank Dunia, 2016)
2. Kerugian karhutla 2015 diperkirakan US$16,1 miliar, sekitar Rp221 triliun. (Bank Dunia, 2016)
3. Lebih dari 500 ribu orang menderita ISPA selama karhutla 2015. (BNPB, 2015)
4. Sekitar 1,6 juta hektare lahan terbakar pada 2019. (KLHK / SiPongi, 2019)
5. September 2019, langit Muaro Jambi berwarna merah karena asap karhutla. (BMKG, 2019)
6. Gambut yang dikeringkan bisa terbakar di bawah permukaan dan sangat sulit dipadamkan. (BRGM)
