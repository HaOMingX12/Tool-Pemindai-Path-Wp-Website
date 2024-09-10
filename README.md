![image](https://github.com/user-attachments/assets/2258033b-601d-4c47-b28e-609c2934cbe5)

# **Tool Pemindai Path Wp Website**

## **Deskripsi Tool**

Tool ini dirancang untuk memindai path di situs web untuk mencari file dan direktori tertentu. Tool ini akan mengidentifikasi apakah file atau direktori yang dicari ada, akses ditolak, atau tidak ditemukan, serta mencatat jenis bug dan kemungkinan eksploitasi. Tool ini menggunakan Python dan dapat menangani daftar URL target dari file input.

## **Fitur Utama**

- **Pemindaian Path:** Mencari berbagai path yang relevan di situs web, termasuk file konfigurasi, file sensitif, dan direktori umum.
- **Deteksi Bug:** Mengidentifikasi dan mencatat jenis bug berdasarkan status kode HTTP yang diterima.
- **Penilaian Eksploitasi:** Menyediakan penilaian awal tentang kemungkinan eksploitasi berdasarkan path yang ditemukan.
- **Log Hasil:** Menyimpan hasil pemindaian dalam file log terpisah untuk hasil yang berhasil dan yang gagal.
- **Enkripsi dan Perlindungan:** Tool ini telah dienkripsi menggunakan PyArmor untuk melindungi kode sumber dari modifikasi dan penggunaan yang tidak sah.

## **Cara Menggunakan**

1. **Persiapan:**
   - Pastikan Anda memiliki Python 3.x terinstal di sistem Anda. untuk module nya
   - Install dependensi yang diperlukan dengan perintah berikut:
     ```bash
     pip install requests colorama
     ```

2. **Menyiapkan File Input:**
   - Buat file teks yang berisi daftar URL target, satu URL per baris. Simpan file ini dengan ekstensi `.txt`.

3. **Menjalankan Tool:**
   - Jalankan tool:
     ```bash
     cukup klik dan masukan target
     ```
   - Masukkan nama file yang berisi daftar URL target ketika diminta.

4. **Melihat Hasil:**
   - Hasil pemindaian akan disimpan dalam dua file log:
     - `scan_success.txt` - Menyimpan path yang berhasil ditemukan beserta jenis bug dan kemungkinan eksploitasi.
     - `scan_failure.txt` - Menyimpan path yang tidak berhasil diakses beserta alasan kegagalan.

## **Contoh Hasil**

### **scan_success.txt**


## **Informasi Enkripsi**

Tool ini telah dienkripsi menggunakan **PyArmor** untuk melindungi kode sumber dan mencegah modifikasi yang tidak sah. Jika Anda ingin melakukan perubahan pada kode, Anda perlu menghubungi pengembang untuk mendapatkan versi sumber yang tidak terenkripsi.

## **Sumber dan Kontak**

- **Pengembang:** [HaOMing_X12]
- **Kontak:** [freedomxploitwashere@protonmail.com]
- **Repositori:** [freedomxploit.blogspot.com]

---

**Catatan:** terima kasih telah memakai buatan saya, dan saya harap dapat membantu anda di masa yang akan datang.

