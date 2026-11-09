# Praktikum Analisis dan Visualisasi Data

Repository ini berisi hasil belajar Analisis dan Visualisasi Data, terdiri dari **latihan individu** dan **proyek kelompok**.

**Pemilik repository:** Janeeta Samahat Nowa, XI RPL 7

---

## 📂 Isi Repository

| Nama | Jenis | Keterangan |
|------|-------|------------|
| `Latihan_Praktikum_Analisis_dan_Visualisasi_Data.ipynb` | Individu | EDA dan visualisasi data penjualan Nusantara Mart |
| `Proyek_Kelompok/` | Kelompok | Analisis lagu viral: *What Makes a Song Go Viral?* |

---

## 1. 🛒 Latihan Individu: Penjualan Nusantara Mart

Latihan analisis data eksploratif (EDA) dan visualisasi data penjualan produk **Nusantara Mart** menggunakan Python, Pandas, Matplotlib, dan Seaborn.

### Data

Data transaksi penjualan (`penjualan_nusantaramart.csv`) dengan kolom:

- `order_id`, `tanggal`, `kategori_produk`, `nama_produk`, `wilayah`
- `jumlah`, `harga_satuan`, `total`, `metode_pembayaran`, `rating_pelanggan`

### Ringkasan Hasil

1. **Penjualan per kategori:** Fashion dan Elektronik menyumbang total penjualan tertinggi, sedangkan Makanan & Minuman paling rendah.
2. **Tren bulanan:** Penjualan naik bertahap dari Januari dan mencapai puncak pada Mei 2026, lalu turun tajam di Juni.
3. **Outlier:** Ada transaksi bernilai tinggi pada kategori Elektronik, Olahraga, dan Kesehatan. Ini diduga pembelian grosir atau pengadaan khusus.
4. **Kepuasan pelanggan:** Rating sangat positif, mayoritas berada di kisaran 4,0 sampai 5,0.

---

## 2. 🎵 Proyek Kelompok: What Makes a Song Go Viral?

Studi kasus Data Analyst untuk platform musik fiktif **NusaSound**. Tujuannya mencari pola lagu yang berhasil menarik banyak pendengar, mulai dari genre, tahun rilis, sampai karakteristik audio.

**Dataset:** `viral_songs.csv`, berisi 10.000 lagu dengan 17 kolom (rilis 2010 sampai 2025). Dataset ini bersifat **sintetis**, jadi hasilnya cocok untuk latihan analisis tetapi tidak mewakili perilaku pendengar sebenarnya.

**Yang dikerjakan:** pemeriksaan kualitas data, ringkasan statistik, lima visualisasi (bar chart, line chart, scatter plot, histogram, boxplot), deteksi outlier dengan metode IQR, dashboard ringkas, dan rekomendasi bisnis.

### Temuan Utama

- **Genre:** Latin punya tingkat viral dan total streams tertinggi (64,66%). Pop dan Hip-Hop menyusul dengan lebih dari 61%, sedangkan Classical paling rendah (1,21%).
- **Tahun rilis:** Rata-rata streams naik-turun dan tidak menunjukkan tren yang stabil. Nilai tertinggi ada pada lagu rilisan 2023.
- **Fitur audio:** Danceability berhubungan positif dengan streams, tetapi lemah, sehingga tidak bisa jadi satu-satunya patokan.
- **Sebaran streams:** Sangat miring ke kanan. Rata-rata sekitar 2,42 juta, sedangkan median hanya 329 ribu, dan terdapat 1.399 lagu yang tergolong outlier.

### Rekomendasi Singkat

Genre Latin, Pop, dan Hip-Hop layak diberi ruang uji lebih besar pada playlist rekomendasi. Keputusan sebaiknya memakai median dan distribusi streams, bukan hanya rata-rata, dan perlu divalidasi dengan data streaming nyata.

### Anggota Kelompok

| No | Nama | No. Absen |
|----|------|-----------|
| 1 | Ananda Putra Prawira | 6 |
| 2 | Janeeta Samahat Nowa | 21 |
| 3 | Revantyo Hafiz Prasetyawan | 31 |
| 4 | Sepvaldi Firmandah Ramadhan | 32 |

---
