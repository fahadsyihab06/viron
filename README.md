# **Viron Programming Language**

**Viron** adalah bahasa pemrograman sederhana yang terinspirasi oleh Bash, dengan sintaksis yang mudah digunakan dan dirancang untuk berbagai keperluan skrip dan otomatisasi.

---

## **Instalasi**

Untuk menjalankan **Viron**, Anda perlu memiliki compiler **GCC** yang sudah terpasang di sistem Anda.

### Langkah-langkah instalasi:

1. **Instalasi untuk termux**
    ```bash
    git clone https://github.com/fahadsyihab06/viron.git
    cd viron
    mv -f viron ../usr/bin
    mv -f viron.nanorc ../usr/share/nano
    cd
    ```
2. **Instalasi untuk Kali Linux, ubuntu, kali debian, dll**
   ```bash
git clone                           https://github.com/fahadsyihab06/viron.git
cd viron
mv -f viron ../usr/bin
mv -f viron.nanorc ../usr/share/nano
cd
    ```

Ini akan menghasilkan program executable bernama `viron`.

---

## **Menjalankan Skrip Viron**

Setelah **Viron** berhasil terinstal, Anda dapat menjalankan skrip **Viron** dengan ekstensi `.vr` menggunakan perintah berikut:

```bash
./viron script.vr
