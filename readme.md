# Analisis Pola Perjalanan Penumpang Transjakarta

Notebook ini berisi analisis data transaksi elektronik Transjakarta untuk mengidentifikasi pola perjalanan penumpang, segmentasi pengguna, serta insight untuk peningkatan efisiensi dan kualitas layanan.

## Isi Analisis

- **Data Preview & Cleaning:**  
  Menampilkan data mentah, pengecekan duplikat, dan pembersihan data.

- **Feature Engineering:**  
  Konversi waktu ke datetime, ekstraksi fitur hari, jam, dan umur, serta perhitungan durasi perjalanan.

- **Analisis Pola Perjalanan:**

  - Distribusi perjalanan berdasarkan waktu (hari & jam)
  - Perbandingan durasi weekday vs weekend (uji T-Test)
  - Analisis durasi antar koridor (ANOVA)
  - Segmentasi pengguna berdasarkan usia dan gender

- **Aspek Finansial:**

  - Distribusi biaya perjalanan (gratis vs berbayar)
  - Analisis rute termurah & termahal

- **Insight Demografi & Rekomendasi:**
  - Persebaran halte populer
  - Rekomendasi bus khusus perempuan
  - Identifikasi koridor dengan volume tinggi

## Cara Menjalankan

1. **Persiapkan Data:**  
   Pastikan file `Transjakarta.csv` tersedia di direktori yang sama.

2. **Buka Notebook:**  
   Jalankan `Capstone2_MuhamadRafif_JCDSAH_0208.ipynb` di Jupyter Notebook, Google Colab, atau VS Code.

3. **Instalasi Library:**  
   Pastikan library berikut sudah terpasang:

   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scipy
   - folium

   Instalasi (jika diperlukan):

   ```sh
   pip install pandas numpy matplotlib seaborn scipy folium
   ```

4. **Jalankan Sel Notebook:**  
   Eksekusi sel secara berurutan untuk mereproduksi seluruh analisis dan visualisasi.

## Output

- Visualisasi pola perjalanan, segmentasi pengguna, dan distribusi biaya.
- File peta interaktif:
  - `map_out_halte_populer.html`
  - `map_tapin_halte_populer.html`

## Struktur File

- `Capstone2_MuhamadRafif_JCDSAH_0208.ipynb` — Notebook utama analisis
- `Transjakarta.csv` — Dataset transaksi elektronik Transjakarta
- `map_out_halte_populer.html` — Peta halte tap-out populer
- `map_tapin_halte_populer.html` — Peta halte tap-in populer

## Catatan

- Notebook ini menggunakan data fiktif/anonim untuk keperluan analisis.
- Insight dan rekomendasi dapat digunakan sebagai dasar pengambilan keputusan bisnis oleh Transjakarta.

---

**Penulis:**  
Muhamad Rafif Al Hafizh
