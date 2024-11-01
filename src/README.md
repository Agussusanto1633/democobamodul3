# Kalkulator Hitung Luas Bangun Datar

Proyek ini adalah sebuah aplikasi berbasis Java untuk menghitung luas berbagai bentuk geometri sederhana: persegi, persegi panjang, dan segitiga. Aplikasi ini mengandalkan tiga kelas `persegi`, `persegipanjang`, dan `segitiga`, yang masing-masing bertanggung jawab untuk menghitung luas dari bentuk geometri yang bersangkutan.

## Struktur Proyek

Proyek ini terdiri dari dua file utama:
- `MainR.java` - Berisi menu utama untuk memilih bentuk geometri yang ingin dihitung luasnya.
- `Tugas4R.java` - Berisi metode-metode statis yang digunakan untuk menghitung luas bangun datar.

### Paket `refactor`
- `persegi` - Kelas untuk menghitung luas persegi.
- `persegipanjang` - Kelas untuk menghitung luas persegi panjang.
- `segitiga` - Kelas untuk menghitung luas segitiga.

## Fitur Aplikasi

1. **Menghitung Luas Persegi**
2. **Menghitung Luas Persegi Panjang**
3. **Menghitung Luas Segitiga**

### Menu Utama

Pengguna dapat memilih bentuk geometri yang ingin dihitung luasnya dengan memasukkan nomor yang sesuai di konsol.

### Cara Menggunakan

1. **Jalankan program** - Eksekusi `MainR.java` untuk menampilkan menu utama.
2. **Pilih bentuk geometri** - Masukkan nomor 1, 2, atau 3 untuk memilih bentuk:
    - `1` untuk persegi
    - `2` untuk persegi panjang
    - `3` untuk segitiga
3. **Masukkan dimensi** - Setelah memilih bentuk, pengguna akan diminta untuk memasukkan dimensi yang sesuai.
4. **Hasil** - Program akan menampilkan hasil luas bentuk geometri tersebut.

## Contoh Penggunaan

### Contoh 1: Menghitung Luas Persegi

```plaintext
Selamat datang di Kalkulator hitung luas
1. Hitung Luas Persegi
2. Hitung Luas Persegi Panjang
3. Hitung Luas Segitiga
Pilih No 1-3: 1
Masukkan panjang sisi persegi: 4
Luas Persegi adalah: 16.0 cm²
