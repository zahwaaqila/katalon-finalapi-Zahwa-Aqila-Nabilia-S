# katalon-finalapi-Zahwa-Aqila-Nabilia-Setiawan
Final project API Testing 

# Dokumentasi Pengujian API

Dokumentasi ini menyediakan informasi mengenai prosedur pengujian API untuk aplikasi kami. Pengujian diorganisir dalam tiga koleksi test suite utama: `auth`, `booking`, dan `ping`.

##  Test Suite COllection

### 1. Auth

#### Test Case: Buat Token
- **Deskripsi:** Memverifikasi kemampuan untuk membuat token untuk autentikasi.
- **Langkah-langkah:**
  1. Kirim permintaan ke endpoint autentikasi dengan kredensial yang valid.
  2. Pastikan bahwa token berhasil dibuat.

### 2. Booking

#### Test Case 1: CreateBooking
- **Deskripsi:** Menguji fungsionalitas untuk membuat pemesanan baru.
- **Langkah-langkah:**
  1. Kirim permintaan ke endpoint pembuatan pemesanan dengan data yang valid.
  2. Pastikan bahwa pemesanan baru berhasil dibuat.
  3. Simpan ID pemesanan ke dalam variabel global untuk referensi di masa mendatang.

#### Test Case 2: GetBooking
- **Deskripsi:** Memverifikasi kemampuan untuk mengambil detail pemesanan.
- **Langkah-langkah:**
  1. Kirim permintaan ke endpoint untuk mendapatkan detail pemesanan menggunakan ID pemesanan yang disimpan.
  2. Pastikan bahwa detail pemesanan yang benar berhasil diambil.

#### Test Case 3: GetBookingId
- **Deskripsi:** Menguji fungsionalitas untuk mendapatkan pemesanan tertentu berdasarkan ID.
- **Langkah-langkah:**
  1. Kirim permintaan ke endpoint untuk mendapatkan detail pemesanan menggunakan ID pemesanan yang disimpan.
  2. Pastikan bahwa detail pemesanan yang benar berhasil diambil.

#### Test Case 4: UpdateBooking
- **Deskripsi:** Memverifikasi kemampuan untuk memperbarui informasi pemesanan.
- **Langkah-langkah:**
  1. Kirim permintaan ke endpoint untuk memperbarui detail pemesanan menggunakan ID pemesanan yang disimpan.
  2. Pastikan bahwa informasi pemesanan berhasil diperbarui.

#### Test Case 5: PartialUpdateBooking
- **Deskripsi:** Menguji fungsionalitas untuk memperbarui sebagian informasi pemesanan.
- **Langkah-langkah:**
  1. Kirim permintaan ke endpoint untuk memperbarui sebagian detail pemesanan menggunakan ID pemesanan yang disimpan.
  2. Pastikan bahwa informasi pemesanan yang ditentukan berhasil diperbarui.

#### Test Case 6: DeleteBooking
- **Deskripsi:** Memverifikasi kemampuan untuk menghapus pemesanan.
- **Langkah-langkah:**
  1. Kirim permintaan ke endpoint untuk menghapus pemesanan menggunakan ID pemesanan yang disimpan.
  2. Pastikan bahwa pemesanan berhasil dihapus.

### 3. Ping

#### Test Case: HealthCheck
- **Deskripsi:** Menguji endpoint pemeriksaan kesehatan untuk memastikan API berfungsi dengan baik.
- **Langkah-langkah:**
  1. Kirim permintaan ke endpoint pemeriksaan kesehatan.
  2. Pastikan bahwa respons yang berhasil diterima.

## Variabel Global

- `booking_id`: Menyimpan ID pemesanan terakhir yang dibuat untuk referensi dalam pengujian selanjutnya.
- `baseURL`: URL dasar untuk permintaan API.
  
## Detail Repositori Git
- **URL Repositori:**
  - https://github.com/zahwaaqila/katalon-finalapi-Zahwa-Aqila-Nabilia-Setiawan.git

- **Detail Commit:**
  - Beberapa commit dengan pesan commit yang jelas.

## Rekaman Video
- **Berkas Rekaman:**
  - https://drive.google.com/drive/folders/1Xkwb_M1kl6gffaMOULiW4nYzvq-jLNRb?usp=sharing

