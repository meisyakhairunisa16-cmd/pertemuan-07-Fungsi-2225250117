# Pertemuan 07 - Fungsi Python

**Nama:** [Meisya Khairunisha Priatna]  
**NIM:** [2225250117]  
**Kelas:** [3F]

## Tujuan
Mempelajari fungsi, parameter, return value, dan scope dalam Python untuk membuat program yang modular dan mudah dipahami.

## Struktur Folder
- `latihan/01_salam.py`: Fungsi salam dengan parameter nama dan kelas.
- `latihan/02_luas_persegi_panjang.py`: Menghitung luas persegi panjang.
- `latihan/03_jumlah_n.py`: Menghitung jumlah bilangan 1 sampai n.
- `latihan/04_statistik_sederhana.py`: Mencari nilai minimum, maksimum, dan rata-rata.
- `latihan/05_scope.py`: Memahami local scope dan global scope.
- `praktik/utilitas_matematika.py`: Program menu utilitas matematika.

## Cara Menjalankan
Jalankan file latihan melalui terminal VS Code.

Contoh:
`python latihan/01_salam.py`

Untuk program utama:
`python praktik/utilitas_matematika.py`

## Struktur Fungsi
1. `salam(nama, kelas)` menampilkan salam.
2. `luas_persegi_panjang(p, l)` mengembalikan hasil perkalian panjang dan lebar.
3. `jumlah_n(n)` mengembalikan jumlah bilangan dari 1 sampai n.
4. `statistik(data)` mengembalikan nilai minimum, maksimum, dan rata-rata.
5. `demo(x)` menunjukkan penggunaan variabel lokal.
6. `luas_segitiga(a, t)` mengembalikan luas segitiga.
7. `faktorial(n)` mengembalikan hasil faktorial.
8. `tampilkan_menu()` menampilkan pilihan operasi.
9. `main()` menjalankan menu dan mengatur alur program.

## Hasil Pengujian

| Pengujian | Input | Hasil |
|---|---|---|
| Luas persegi panjang | 8, 5 | 40 |
| Luas segitiga | 10, 6 | 30.0 |
| Jumlah bilangan | 10 | 55 |
| Faktorial | 5 | 120 |
| Faktorial | 0 | 1 |
| Statistik | 70, 80, 65, 90, 75 | Min 65, maks 90, rata-rata 76.0 |

## Refleksi
Penggunaan fungsi membuat program lebih terstruktur karena setiap fungsi memiliki tugas tertentu. Parameter memudahkan penggunaan data yang berbeda, sedangkan return memungkinkan hasil perhitungan digunakan kembali. Pemahaman scope membantu mencegah kesalahan penggunaan variabel.

## Sumber
Bahan Ajar Algoritma dan Pemrograman Pertemuan 07, Tahun Ajaran 2026/2027.