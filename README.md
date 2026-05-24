# PRAKTIKUM KECERDASAN BUATAN - ALGORITMA GENETIKA

Repositori ini berisi implementasi algoritma genetik yang dikerjakan pada Praktikum Kecerdasan Buatan. Program ini bertujuan untuk menyelesaikan permasalahan optimasi menggunakan algoritma genetik.

## Struktur Direktori
- `main.py` : File program utama yang berisi implementasi algoritma genetik
- `InisialisasiPopulasi.py` : File berisi algoritma inisialisasi populasi
- `EvaluasiFitness.py` : File berisi algoritma evaluasi fitness
- `selection.py` : File berisi algoritma seleksi
- `crossover.py` : File berisi algoritma crossover
- `mutation.py` : File berisi algoritma mutasi

## Hasil Perkembangan FItness
![image](/img/Figure_1.png)

Grafik menunjukkan perkembangan nilai fitness pada setiap generasi dalam proses optimasi menggunakan Genetic Algorithm.

- Fitness Tertinggi (biru) cepat mencapai nilai maksimum 60 dan stabil hingga akhir generasi.
- Fitness Rata-rata (merah) berada di kisaran tinggi, menandakan mayoritas individu memiliki solusi yang baik.
- Fitness Terendah (kuning) beberapa kali turun drastis akibat proses mutasi dan eksplorasi populasi.

Hasil ini menunjukkan bahwa algoritma berhasil menemukan solusi optimal dengan konvergensi yang cepat sekaligus tetap menjaga keberagaman populasi selama evolusi berlangsung.

## Cara Menjalankan Program
1. Clone repository

```bash
git clone https://github.com/kmuiii/H1D024053-PraktikumKB-Pertemuan9.git
```
2. Install library yang dibutuhkan

```bash
pip install numpy matplotlib
```
3. Jalankan program

```bash
python main.py
```
