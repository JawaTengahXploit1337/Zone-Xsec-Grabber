# **Zone-Xsec Mass Grabber Tool**

**Deskripsi:**  
Zone-Xsec Grabber adalah alat yang memungkinkan kamu untuk mengekstrak daftar URL dari berbagai halaman web secara otomatis. Dengan memilih antara halaman **Special**, **Archive**, atau **Onhold**, kamu dapat mengambil link utama dari domain tanpa bagian tambahan seperti direktori atau file.

**Fitur:**
- Grab links dari halaman **Special**, **Archive**, dan **Onhold**.
- Mengambil link hanya dari halaman yang dipilih secara otomatis.
- Hasil disimpan dalam file teks yang mudah diakses.

## **Instalasi dan Pengaturan**

### **Langkah-langkah Instalasi:**

1. **Persiapkan Python dan PIP:**
   Pastikan kamu sudah menginstal Python dan pip di sistem kamu. Jika belum, instal Python dari [situs resmi Python](https://www.python.org/downloads/).

   Kamu bisa mengecek apakah Python dan pip sudah terinstal dengan menjalankan perintah berikut di terminal atau command prompt:

   ```bash
   python3 --version
   pip3 --version
   ```

2. **Clone Repository GitHub:**
   Clone repository ini ke direktori lokal kamu dengan menggunakan perintah git:

   ```bash
   git clone https://github.com/username/repository-name.git
   ```

   Gantilah `username/repository-name` dengan username dan nama repositori GitHub kamu.

3. **Instalasi Dependencies:**
   Masuk ke dalam direktori repositori yang telah di-clone dan install dependencies yang dibutuhkan. Untuk itu, kamu harus menginstal `requests` dan `beautifulsoup4` menggunakan pip:

   ```bash
   cd repository-name
   pip3 install -r requirements.txt
   ```

   Jika `requirements.txt` tidak ada, kamu bisa menginstal dependency secara manual:

   ```bash
   pip3 install requests beautifulsoup4
   ```

---

## **Cara Menggunakan Tool:**

1. Jalankan tool dengan perintah berikut:

   ```bash
   python3 zx.py
   ```

2. **Pilih Jenis Halaman:**
   Kamu akan diminta memilih jenis halaman yang ingin digrab:  
   - **1** untuk halaman **Special**
   - **2** untuk halaman **Archive**
   - **3** untuk halaman **Onhold**

3. **Masukkan Jumlah Halaman:**
   Setelah memilih halaman, masukkan jumlah halaman yang ingin digrab. Tool akan mulai mengambil semua link dari halaman yang dipilih, satu per satu.

4. **Proses Grabber:**
   Setelah proses selesai, hasilnya akan disimpan dalam file `grabbed_links.txt` di dalam folder tempat tool dijalankan.

---

## **Contoh Tampilan:**

### Pilih Jenis Halaman:
```
1. Special
2. Archive
3. Onhold
```

### Masukkan Jumlah Halaman:
```
Masukkan jumlah halaman yang akan di-scrape: 3
```

### Output Setelah Proses Selesai:
```
Proses selesai! Semua link berhasil diambil dan disimpan di grabbed_links.txt.
```

---

## **Contributing:**
Jika kamu ingin berkontribusi pada proyek ini, silakan lakukan **fork** pada repositori ini dan buat **pull request** dengan perbaikan atau fitur baru yang ingin kamu tambahkan.

---

## **Lisensi:**
Proyek ini dilisensikan di bawah lisensi MIT. Lihat file [LICENSE](LICENSE) untuk informasi lebih lanjut.
```
