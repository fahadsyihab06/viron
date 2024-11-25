# **Viron Programming Language**

**Viron** adalah bahasa pemrograman sederhana yang terinspirasi oleh Bash, dengan sintaksis yang mudah digunakan dan dirancang untuk berbagai keperluan skrip dan otomatisasi.

---

## **Instalasi**

### Langkah-langkah instalasi:

1. **Instalasi untuk termux**
    ```bash
    git clone https://github.com/fahadsyihab06/viron.git
    cd viron
    chmod +x viron
    mv -f viron ../usr/bin
    mv -f viron.nanorc ../usr/share/nano
    cd
    ```
2. **Instalasi untuk Kali Linux, ubuntu, kali debian, dll**
   ```bash
   git clone                           https://github.com/fahadsyihab06/viron.git
   cd viron
   chmod +x viron
   mv -f viron ../usr/bin
   mv -f viron.nanorc ../usr/share/nano
   cd
    ```

Ini akan menghasilkan program executable bernama `viron`.

---

## **Menjalankan Skrip Viron**

Setelah bahasa pemrograman **Viron** berhasil terinstal, Anda dapat menjalankan bahasa pemrograman **Viron** dengan ekstensi `.vr`, untuk memulai coding, kita bisa menggunakan nano.

```bash
nano nama_file.vr
```

## **Opsi Viron**
**Opsi yang Tersedia**

1. *Menampilkan Bantuan:* Untuk melihat bantuan tentang penggunaan program
```bash
./viron --help
```

3. *Menampilkan Versi:* Untuk mengetahui versi dari Viron:
```bash
./viron --version
```

## **Documentasi Sintaks-Sintaks Viron**

**Berikut adalah penjelasan tentang sintaks yang tersedia di dalam Viron:**

*0. Mencetak pesan*
```bash
uniknya cara mencetak pesan bahasa pemrograman viron adalah dengan menuliskan `astaghfirullah` seperti ini

astagfirullah "Hello, World!"
```

*1. Komentar*
```bash
Komentar diawali dengan tanda # dan akan diabaikan saat program dijalankan.

# Ini adalah komentar
cetak "Program berjalan"
```

*2. Variabel*
```bash
Tidak perlu deklarasi tipe variabel, cukup gunakan baca untuk input dan $variabel untuk mengakses nilai variabel.

baca nama
astagfirullah "Halo, $nama!"
```

*3. Tipe Data*
```bash
Tipe data didukung secara otomatis oleh Viron, misalnya string, integer, dan float dapat digunakan langsung.

# Tipe data string
baca nama
astagfirullah "Nama: $nama"

# Tipe data integer
math 10 + 5
```

*4. Input/Output*
```bash
Untuk menerima input dari pengguna, gunakan baca. Untuk menampilkan output, gunakan cetak.

baca nama
astagfirullah "Halo, $nama!"
```

*5. Operator Matematika*
```bash
Gunakan math untuk melakukan operasi matematika.

math 5 + 3
math 10 * 2
```

*6. Pengkondisian*
```bash
Struktur kondisi menggunakan jika.

jika 5 > 3
astagfirullah "Kondisi benar!"
```

*7. Looping*
```bash
Untuk melakukan perulangan, gunakan ulang.

ulang 1 5
```

*8. Fungsi*
```bash
Fungsi dapat digunakan untuk modularitas dan pengorganisasian kode.

fungsi tambah
    math 5 + 5
    astagfirullah "Hasil: 10"
```

*9. Operasi String*
```bash
Melakukan operasi seperti penggabungan string menggunakan tanda +.

baca nama
astagfirullah "Halo, " + $nama
```

*10. Array*
```bash
Array bisa diakses menggunakan indeks.

array nama[0] = "Fahad"
array nama[1] = "Roger"
cetak $nama[0]
```

*11. Redirection dan Pipes*
```bash
Anda dapat melakukan redirection dan pipes untuk menjalankan perintah sistem atau mengalihkan output ke file.

sistem ls > file.txt
sistem cat file.txt | grep "Viron"
```

*12. Komunikasi Sistem*
```bash
Untuk menjalankan perintah sistem atau shell, gunakan sistem.

sistem echo "Ini adalah perintah sistem"
```

*13. Error Handling*
```bash
Jika terjadi error dalam menjalankan perintah, program akan menampilkan pesan kesalahan.

sistem rm tidak_ada_file
```

*14. Modularitas*
```bash
Menggunakan fungsi untuk modularisasi kode yang lebih baik.

fungsi hitung
    math 5 + 5
    cetak "Hasil: 10"
```

*15. Ekspansi Variabel*
```bash
Menggunakan $variabel untuk ekspansi nilai variabel.

baca nama
ekspansi nama
```

*16. Logical Operators*
```bash
Untuk penggunaan operator logika seperti AND, OR:

jika 5 == 5 && 3 == 3
cetak "Semua kondisi benar!"
```

**Contoh Skrip Viron Sederhana**

*Berikut adalah contoh skrip Viron lengkap:*
```bash
# Ini adalah komentar
cetak "Selamat datang di Viron!"

# Variabel
baca nama
cetak "Halo, $nama!"

# Matematika
math 10 + 5
math 20 / 4

# Pengkondisian
jika 10 > 5
cetak "Kondisi benar!"

# Looping
ulang 1 3

# Komunikasi Sistem
sistem echo "Selesai menjalankan script."
```

# Informasi Developer

```Viron dikembangkan oleh:

Nama: Fahad

Versi: 1.0

Tanggal Rilis: [ 25/11/2024 ]
```
# **About !**

Repository GitHub:
https://github.com/fahadsyihab06/viron

SUBSCRIBE!
YouTube: <a href="https://youtube.com/@tc20367?si=WJaTF5lJOftLFyNf">Subscribe YouTube</a> 

Traktir kopi ☕
Saweran: [ https://saweria.co/tc20 ]

