# Stokastik_4_RB
Analisis Perbandingan Kinerja Sistem Antrian M/M/1 dan G/G/1 pada Layanan Kantin Gedung E ITERA

## 👥 Anggota Kelompok
| Nama | NIM |
|------|------|
| Farahanum Afifah Ardiansyah | 122450056 |
| Berliana Enda Putri | 122450065 |
| Khusnun Nisa | 122450078 |
| M. Deriansyah Okutra | 122450101 |

**Program Studi Sains Data**  
**Fakultas Sains, Institut Teknologi Sumatera**

---

## 🎯 Tujuan
- Mengestimasi parameter sistem antrian **M/M/1** dan **G/G/1** berdasarkan data kedatangan dan waktu pelayanan di Kantin Gedung E ITERA.  
- Membandingkan performa kedua model melalui ukuran kinerja seperti *waktu tunggu rata-rata*, *panjang antrian rata-rata*, dan *utilisasi sistem*.

---

## 📊 Hasil Singkat
Penelitian berhasil melakukan estimasi parameter untuk kedua model antrian:

### **1. Model M/M/1**
- Kedatangan ~ Poisson, Pelayanan ~ Eksponensial  
- Laju kedatangan (λ) ≈ **0.63 pelanggan/menit**  
- Laju pelayanan (μ) ≈ **1.12 pelanggan/menit**  
- Waktu tunggu rata-rata: **1.14 menit**  
- Rata-rata pelanggan menunggu: **≈1 orang**  
- Utilisasi sistem: **0.56**

### **2. Model G/G/1**
- Kedatangan ~ Weibull, Pelayanan ~ Lognormal  
- Mencerminkan variabilitas nyata pada kantin  
- Waktu tunggu rata-rata: **2.79 menit**  
- Rata-rata pelanggan menunggu: **≈3 orang**  
- Utilisasi sistem: **0.58**

---

## 📝 Kesimpulan Ringkas
- **M/M/1** memberikan performa yang lebih baik (waktu tunggu & panjang antrian lebih rendah), namun **kurang menggambarkan variasi nyata** pada kedatangan dan pelayanan di kantin.  
- **G/G/1** lebih akurat untuk kondisi sebenarnya karena memperhitungkan variabilitas data, meskipun menghasilkan waktu tunggu yang lebih lama.  
- Pemilihan model antrian yang tepat penting untuk memahami kondisi operasional dan membantu pengambilan keputusan manajemen layanan.

---
