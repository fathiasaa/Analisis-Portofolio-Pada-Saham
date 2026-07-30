# Analisis Portofolio Saham - Efficient Frontier

Proyek ini bertujuan untuk menganalisis kinerja portofolio saham dengan menghitung **return**, **risiko (volatilitas)**, dan **rasio Sharpe** dari masing-masing saham. Selain itu, proyek ini menentukan portofolio optimal menggunakan pendekatan **Efficient Frontier**, yaitu portofolio yang memberikan keseimbangan terbaik antara tingkat pengembalian dan risiko.

---
## Tim Proyek

| Anggota Tim | NIM |
|---------------|-------|
| Aliifah       | L0225014 |
| Fathia        | L0225021   |
---

## Dataset
Data yang digunakan berasal dari empat saham dengan kode ticker:
- 035900.KQ
- 041510.KQ
- 173940.KQ
- 122870.KQ

---

## Metodologi
1. **[Simulasi Monte Carlo](ca://s?q=Simulasi_Monte_Carlo_portofolio)**  
   - Membentuk 10.000 kombinasi bobot portofolio secara acak.  
   - Menghitung return dan risiko untuk setiap kombinasi.  

2. **[Perhitungan Return & Risiko](ca://s?q=Perhitungan_return_dan_risiko_portofolio)**  
   - Annual return dihitung dari rata-rata pengembalian.  
   - Volatilitas dihitung sebagai standar deviasi tahunan.  

3. **[Rasio Sharpe](ca://s?q=Rasio_Sharpe_portofolio)**  
   - Digunakan untuk mengukur efisiensi portofolio (return per unit risiko).  

4. **[Efficient Frontier](ca://s?q=Efficient_Frontier_portofolio)**  
   - Menentukan portofolio optimal dengan rasio Sharpe tertinggi.  

---

## Hasil
- **Portofolio Optimal** diperoleh berdasarkan rasio Sharpe tertinggi.  
- Annual Return: **34,78%**  
- Annualized Volatility: **45,45%**  
- Rasio Sharpe: **0,7432**  

**Alokasi dana utama:**
- Saham 035900.KQ → 56,74%  
- Saham 041510.KQ → 43,09%  

> Catatan: Angka di atas merupakan hasil simulasi pada dataset dan parameter tertentu. Nilai dapat berbeda jika dataset, periode waktu, atau jumlah simulasi diubah.

Portofolio ini menunjukkan keseimbangan yang baik antara risiko dan return, sesuai bagi investor dengan profil risiko moderat.

---

## Dokumentasi
- Notebook `.ipynb` berisi langkah analisis lengkap.  

---

## Catatan
Proyek ini dibuat untuk **Tugas Mata Kuliah Dasar Pemograman**.  
Hasil simulasi dapat berbeda jika dataset diperbarui atau jumlah simulasi diubah.
