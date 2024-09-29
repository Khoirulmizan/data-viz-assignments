```
Nama: Khoirul Mizan Abdullah
NIM: 122450010
Kelas: RA
Mata Kuliah: Visualisasi Data dan Informasi
```

# Tugas Viz 3 - Visualisasi Perubahan Populasi di Amerika Serikat (2022-2023)

Program Python ini memvisualisasikan perubahan populasi di Amerika Serikat antara tahun 2022 dan 2023 menggunakan peta choropleth. Program ini menggabungkan data populasi dari file CSV dengan shapefile negara bagian AS untuk menghasilkan representasi geografis perubahan persentase populasi yang jelas dan intuitif.

## Fitur

- **Sumber Data**:
  - Data populasi (`NST-EST2023-ALLDATA.csv`)
  - Shapefile batas negara bagian AS (`cb_2022_us_state_500k.shp`)
  
- **Perhitungan Perubahan Populasi**: Program menghitung persentase perubahan populasi untuk setiap negara bagian antara tahun 2022 dan 2023.

- **Visualisasi Peta Choropleth**:
  - Peta choropleth dihasilkan menggunakan pustaka **Geopandas**.
  - Menampilkan perubahan persentase populasi dengan skala warna.
  - Negara bagian di luar benua AS (Alaska, Hawaii, dan Puerto Rico) dikecualikan untuk tampilan visual yang lebih rapi.

## Persyaratan

- **Pustaka Python**:
  - `geopandas`
  - `pandas`
  - `matplotlib`

## Cara Menjalankan

1. Pastikan semua pustaka yang diperlukan sudah terpasang dengan menjalankan perintah berikut:
    ```bash
    pip install geopandas pandas matplotlib
    ```
2. Letakkan file CSV populasi (`NST-EST2023-ALLDATA.csv`) dan shapefile negara bagian AS (`cb_2022_us_state_500k.shp`) di direktori kerja Anda.
3. Jalankan skrip Python untuk menghasilkan peta yang memvisualisasikan perubahan populasi di seluruh negara bagian AS.

## Hasil

Program ini menghasilkan peta choropleth yang menunjukkan persentase perubahan populasi di negara bagian Amerika Serikat dari tahun 2022 hingga 2023.
