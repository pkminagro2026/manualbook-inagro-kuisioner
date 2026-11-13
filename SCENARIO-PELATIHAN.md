# Skenario Presentasi Pelatihan INAGRO Kuesioner

Buka aplikasi.

Ikuti langkah 1 sampai selesai.

Gunakan data contoh yang tertera pada setiap langkah.

---

## Langkah 1 - Login Super Admin

**Buka**

```text
https://domain-anda
```

**Data utama A**

```text
Email: admin@inagro.test
Password: password
```

**Data cadangan**

| Varian | Email | Password | Role |
|---|---|---|---|
| B | `admin.latihan@example.test` | `Latihan#2026` | Admin |
| C | `operator.latihan@example.test` | `Latihan#2026` | Operator |
| D | `viewer.latihan@example.test` | `Latihan#2026` | Viewer |
| E | `auditor.latihan@example.test` | `Latihan#2026` | Auditor Latihan |

Data B-E dipakai pada Langkah 18 setelah akun dibuat.

**Klik**

```text
Sign in
```

**Hasil**

Dashboard terbuka.

**Lanjut**

Langkah 2.

---

## Langkah 2 - Tunjukkan Dashboard

**Buka**

```text
Dashboard
```

**Data utama A**

Tidak ada input.

**Data cadangan**

Tidak ada input.

**Klik**

Tidak ada klik.

**Hasil**

Kartu Pertanyaan, Kategori, Respons, Rata-rata Skor %, Tren Penyelesaian, Distribusi Opsi, Respons / Bulan, dan Soal Terendah tampil.

**Lanjut**

Langkah 3.

---

## Langkah 3 - Buat Kategori

**Buka**

```text
Master Data > Kategori > New Kategori
```

**Data utama A**

```text
Nama: Kebersihan
Slug: kebersihan
Deskripsi: Penilaian kebersihan area.
Urutan: 5
Aktif: Ya
```

**Data cadangan**

| Varian | Nama | Slug | Deskripsi | Urutan |
|---|---|---|---|---|
| B | Kenyamanan | `kenyamanan` | Penilaian kenyamanan area. | 6 |
| C | Keamanan | `keamanan` | Penilaian keamanan area. | 7 |
| D | Informasi | `informasi` | Penilaian kejelasan informasi. | 8 |
| E | Transportasi | `transportasi` | Penilaian kemudahan transportasi. | 9 |

**Klik**

```text
Create
```

**Hasil**

Kategori Kebersihan tampil di daftar.

**Lanjut**

Langkah 4.

---

## Langkah 4 - Buat Soal

**Buka**

```text
Master Data > Soal > New Soal
```

**Data utama A**

```text
Kategori: Kebersihan
Pertanyaan: Kebersihan Area
Teks bantuan: Nilai kebersihan area yang dikunjungi.
Tipe: Rating
Skala min: 1
Skala max: 7
Wajib dijawab: Ya
Urutan: 1
Aktif: Ya
```

**Data cadangan**

| Varian | Kategori | Pertanyaan | Teks bantuan | Tipe | Skala |
|---|---|---|---|---|---|
| B | Kenyamanan | Kenyamanan Ruang | Nilai kenyamanan area yang dikunjungi. | Rating | 1-7 |
| C | Keamanan | Keamanan Area | Nilai keamanan area yang dikunjungi. | Rating | 1-7 |
| D | Informasi | Kejelasan Informasi | Nilai kejelasan informasi yang diterima. | Rating | 1-7 |
| E | Transportasi | Kemudahan Transportasi | Nilai kemudahan transportasi menuju lokasi. | Rating | 1-7 |

**Klik**

```text
Create
```

**Hasil**

Soal Kebersihan Area tampil di daftar.

**Lanjut**

Langkah 5.

---

## Langkah 5 - Buat Kuesioner

**Buka**

```text
Kuesioner > New Kuesioner
```

**Data utama A**

```text
Judul: Pelatihan INAGRO A
Slug: pelatihan-inagro-a
Deskripsi: Kuesioner latihan operasional jalur A.
Mode: Kategori
Kategori: Pelayanan, Produk, Kepuasan, Kebersihan
Identitas: Nama, Sekolah/Instansi, Tgl Kunjungan - tampil dan wajib
Buka: 2026-11-09 08:00
Tutup: 2026-12-31 23:59
Status: Draft
```

**Data cadangan**

| Varian | Judul | Slug | Mode | Pilihan soal | Jumlah |
|---|---|---|---|---|---|
| B | Pelatihan INAGRO B | `pelatihan-inagro-b` | Custom / Mix | Pelayanan, Produk, Kepuasan; individual Fasilitas Toilet, Fasilitas Meeting Poin, Kenyamanan Ruang | 8 |
| C | Pelatihan INAGRO C | `pelatihan-inagro-c` | Soal Only | Fasilitas Toilet, Fasilitas Meeting Poin, Penjelasan Sales, Pengarahan Tour Guide, Keragaman Permainan Edukasi, Citarasa Katering, Niat Kembali, Keamanan Area | 8 |
| D | Pelatihan INAGRO D | `pelatihan-inagro-d` | Custom / Mix | Informasi, Kepuasan; individual Fasilitas Toilet, Fasilitas Meeting Poin | 4 |
| E | Pelatihan INAGRO E | `pelatihan-inagro-e` | Kategori | Pelayanan, Produk, Kepuasan, Transportasi | 6 |

Jangan pilih kategori Fasilitas secara utuh.

Jangan gunakan soal Fasilitas Wara Wiri.

**Klik**

```text
Create
```

**Hasil**

Kuesioner Pelatihan INAGRO A tampil dengan status Draft dan jumlah soal 6.

**Lanjut**

Langkah 6.

---

## Langkah 6 - Publish

**Buka**

```text
Kuesioner > Pelatihan INAGRO A
```

**Data utama A**

Tidak ada input.

**Data cadangan**

Tidak ada input.

**Klik**

```text
Publish
```

Konfirmasi publish.

**Hasil**

Status menjadi Published.

Snapshot soal terbentuk.

Identitas terkunci.

Tombol Publish hilang.

Tombol QR muncul.

**Lanjut**

Langkah 7.

---

## Langkah 7 - Buka QR

**Buka**

```text
Kuesioner > QR
```

**Data utama A**

Tidak ada input.

**Data cadangan**

Tidak ada input.

**Klik**

```text
Download QR (SVG)
```

Salin tautan `/q/{public_token}`.

Klik Tutup.

**Hasil**

QR tampil.

File SVG dapat dibuka.

Tautan publik tersedia.

**Lanjut**

Langkah 8.

---

## Langkah 8 - Isi Identitas Responden

**Buka**

```text
Tautan publik /q/{public_token}
```

**Data utama A**

```text
Nama: Dewi Lestari
Sekolah/Instansi: SDN 01 Harapan
Tgl Kunjungan: 2026-11-10
```

**Data cadangan**

| Varian | Nama | Sekolah/Instansi | Tgl Kunjungan |
|---|---|---|---|
| B | Raka Pratama | SDN 02 Mekar | 2026-11-11 |
| C | Nabila Putri | SMPN 03 Cahaya | 2026-11-12 |
| D | Fajar Nugraha | SDN 04 Cendana | 2026-11-13 |
| E | Sari Melati | SMPN 05 Bahagia | 2026-11-14 |

**Klik**

```text
Next
```

**Hasil**

Form berpindah ke soal pertama.

**Lanjut**

Langkah 9.

---

## Langkah 9 - Isi Jawaban

**Buka**

```text
Form publik > langkah soal
```

**Data utama A**

```text
Penjelasan Sales: 7
Pengarahan Tour Guide: 7
Keragaman Permainan Edukasi: 7
Citarasa Katering: 7
Niat Kembali: YA
Kebersihan Area: 7
```

**Data cadangan**

| Soal | A | B | C | D | E |
|---|---|---|---|---|---|
| Fasilitas Toilet | - | 6 | 4 | 3 | - |
| Fasilitas Meeting Poin | - | 5 | 3 | 2 | - |
| Penjelasan Sales | 7 | 6 | 5 | - | 5 |
| Pengarahan Tour Guide | 7 | 5 | 4 | - | 6 |
| Keragaman Permainan Edukasi | 7 | 6 | 3 | - | 4 |
| Citarasa Katering | 7 | 7 | 5 | - | 6 |
| Niat Kembali | YA | YA | BELUM TAU | TIDAK | YA |
| Kebersihan Area | 7 | - | - | - | - |
| Kenyamanan Ruang | - | 6 | - | - | - |
| Keamanan Area | - | - | 4 | - | - |
| Kejelasan Informasi | - | - | - | 2 | - |
| Kemudahan Transportasi | - | - | - | - | 5 |

Skor rata-rata:

| Varian | Rata-rata |
|---|---|
| A | 100.00 |
| B | 80.95 |
| C | 50.00 |
| D | 22.22 |
| E | 70.00 |

**Klik**

```text
Next
```

pada setiap langkah.

**Hasil**

Halaman Review tampil.

Validasi tetap berjalan; Next tetap dapat dilanjutkan walaupun soal wajib kosong.

**Lanjut**

Langkah 10.

---

## Langkah 10 - Review dan Submit

**Buka**

```text
Form publik > Review
```

**Data utama A**

Tidak ada input.

**Data cadangan**

Tidak ada input.

**Klik**

```text
Kirim
```

**Hasil**

Jika masih ada soal wajib kosong, Review menampilkan baris merah dan Kirim menampilkan popup daftar isian. Respons belum tersimpan.

Jika semua wajib terisi, halaman sukses tampil dan respons tersimpan dengan status Submitted.

**Lanjut**

Langkah 11.

---

## Langkah 11 - Cek Respons

**Buka**

```text
Respons
```

**Data utama A**

Tidak ada input.

**Data cadangan**

Tidak ada input.

**Klik**

Cari nama responden.

**Hasil**

Respons Dewi Lestari tampil dengan status Submitted.

Skor rata-rata 100.00.

Opsi Niat Kembali YA.

**Lanjut**

Langkah 12.

---

## Langkah 12 - Edit dan Filter

**Buka**

```text
Respons > View
```

**Data utama A**

```text
Nama: Dewi Lestari Revisi
Sekolah/Instansi: SDN 01 Harapan Revisi
```

**Data cadangan**

| Varian | Nama | Sekolah/Instansi | Tgl Kunjungan | Opsi |
|---|---|---|---|---|
| B | Raka Pratama | SDN 02 Mekar | 2026-11-11 | YA |
| C | Nabila Putri | SMPN 03 Cahaya | 2026-11-12 | BELUM TAU |
| D | Fajar Nugraha | SDN 04 Cendana | 2026-11-13 | TIDAK |
| E | Sari Melati | SMPN 05 Bahagia | 2026-11-14 | YA |

**Klik**

```text
Edit
```

```text
Save changes
```

Buka Filter.

Pilih Kuesioner.

Pilih Status Submitted.

Pilih Opsi YA.

Isi Dari dan Sampai.

```text
Apply filters
```

**Hasil**

Nama dan sekolah berubah.

Filter menampilkan respons yang sesuai.

**Lanjut**

Langkah 13.

---

## Langkah 13 - Export

**Buka**

```text
Respons
```

**Data utama A**

```text
Filter Kuesioner: Pelatihan INAGRO A
Filter Status: Submitted
```

**Data cadangan**

| Varian | Kuesioner | Baris wide | Baris Looker |
|---|---|---|---|
| B | Pelatihan INAGRO B | 1 | 8 |
| C | Pelatihan INAGRO C | 1 | 8 |
| D | Pelatihan INAGRO D | 1 | 4 |
| E | Pelatihan INAGRO E | 1 | 6 |

Jika seluruh varian dijalankan: 5 baris wide dan 32 baris Looker.

**Klik**

```text
Export Excel
```

```text
Export Looker
```

**Hasil**

File XLSX wide berisi 1 baris respons dan 6 kolom soal.

File XLSX Looker berisi 6 baris jawaban dan 15 kolom.

**Lanjut**

Langkah 14.

---

## Langkah 14 - Filter Dashboard

**Buka**

```text
Dashboard
```

**Data utama A**

```text
Kuesioner: Pelatihan INAGRO A
Soal: Niat Kembali
Dari: 2026-11-10
Sampai: 2026-11-10
```

**Data cadangan**

| Varian | Kuesioner | Dari | Sampai | Opsi |
|---|---|---|---|---|
| B | Pelatihan INAGRO B | 2026-11-11 | 2026-11-11 | YA |
| C | Pelatihan INAGRO C | 2026-11-12 | 2026-11-12 | BELUM TAU |
| D | Pelatihan INAGRO D | 2026-11-13 | 2026-11-13 | TIDAK |
| E | Pelatihan INAGRO E | 2026-11-14 | 2026-11-14 | YA |

**Klik**

Pilih filter pada widget Distribusi Opsi.

Pilih filter pada widget Respons / Bulan.

Tutup panel filter.

**Hasil**

Distribusi Opsi menampilkan pilihan Niat Kembali jalur A.

Respons / Bulan menampilkan respons bulan berjalan.

**Lanjut**

Langkah 15.

---

## Langkah 15 - Buat Role

**Buka**

```text
Sistem > Role > New Role
```

**Data utama A**

```text
Name: auditor_latihan
Guard Name: web
```

Permission:

```text
ViewAny:QuestionGroup
View:QuestionGroup
ViewAny:Question
View:Question
ViewAny:Questionnaire
View:Questionnaire
ViewAny:Response
View:Response
View:StatsOverview
View:ResponsesPerMonthChart
View:OptionDistributionChart
View:LowestCriteriaTable
```

**Data cadangan**

| Varian | Role | Guard | Keterangan |
|---|---|---|---|
| B | super_admin | web | Role bawaan, bypass penuh |
| C | admin | web | Role bawaan |
| D | operator | web | Role bawaan |
| E | viewer | web | Role bawaan |

Hanya A yang dibuat. B-E adalah role yang sudah ada.

**Klik**

```text
Create
```

**Hasil**

Role Auditor Latihan tampil.

**Lanjut**

Langkah 16.

---

## Langkah 16 - Buat Pengguna A

**Buka**

```text
Sistem > Pengguna > New Pengguna
```

**Data utama A**

```text
Nama: Admin Latihan
Email: admin.latihan@example.test
Password: Latihan#2026
Aktif: Ya
Role: Admin
```

**Data cadangan**

| Varian | Nama | Email | Password | Role | Aktif |
|---|---|---|---|---|---|
| B | Operator Latihan | `operator.latihan@example.test` | `Latihan#2026` | Operator | Ya |
| C | Viewer Latihan | `viewer.latihan@example.test` | `Latihan#2026` | Viewer | Ya |
| D | Auditor Latihan | `auditor.latihan@example.test` | `Latihan#2026` | Auditor Latihan | Ya |
| E | Nonaktif Latihan | `nonaktif.latihan@example.test` | `Latihan#2026` | Viewer | Tidak |

**Klik**

```text
Create
```

**Hasil**

Pengguna Admin Latihan tampil.

**Lanjut**

Langkah 17.

---

## Langkah 17 - Buat Pengguna B

**Buka**

```text
Sistem > Pengguna > New Pengguna
```

**Data utama B**

```text
Nama: Operator Latihan
Email: operator.latihan@example.test
Password: Latihan#2026
Aktif: Ya
Role: Operator
```

**Data cadangan**

| Varian | Nama | Email | Password | Role | Aktif |
|---|---|---|---|---|---|
| C | Viewer Latihan | `viewer.latihan@example.test` | `Latihan#2026` | Viewer | Ya |
| D | Auditor Latihan | `auditor.latihan@example.test` | `Latihan#2026` | Auditor Latihan | Ya |
| E | Nonaktif Latihan | `nonaktif.latihan@example.test` | `Latihan#2026` | Viewer | Tidak |

**Klik**

```text
Create
```

**Hasil**

Pengguna Operator Latihan tampil.

**Lanjut**

Langkah 18.

---

## Langkah 18 - Login Pengguna B

**Buka**

```text
Sign out
```

```text
https://domain-anda
```

**Data utama B**

```text
Email: operator.latihan@example.test
Password: Latihan#2026
```

**Data cadangan**

| Varian | Email | Password | Role |
|---|---|---|---|
| A | `admin@inagro.test` | `password` | Super Admin |
| C | `viewer.latihan@example.test` | `Latihan#2026` | Viewer |
| D | `auditor.latihan@example.test` | `Latihan#2026` | Auditor Latihan |
| E | `nonaktif.latihan@example.test` | `Latihan#2026` | Viewer, nonaktif |

**Klik**

```text
Sign in
```

Buka Respons.

Coba Edit nama/sekolah dan Export.

```text
Sign out
```

**Hasil**

Operator dapat melihat data, mengedit nama/sekolah, dan export.

Operator tidak dapat membuat kuesioner.

Viewer hanya dapat melihat.

Auditor hanya dapat melihat resource dan widget.

Akun nonaktif ditolak.

**Lanjut**

Langkah 19.

---

## Langkah 19 - Selesai

**Buka**

Tidak ada.

**Data utama A**

Tidak ada input.

**Data cadangan**

Tidak ada input.

**Klik**

Tidak ada klik.

**Hasil**

Skenario presentasi selesai.

**Lanjut**

Selesai.
