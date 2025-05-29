# :bookmark: Ujian Tengah Semester - Kelompok 13 :bookmark:

Kami membuat aplikasi sistem manajemen sederhana untuk warung kelontong kecil yang hanya dapat diakses oleh pemilik toko (admin) dan pembeli yang telah terdaftar. Tujuannya adalah untuk membantu pemilik toko dalam mengelola data barang, stok, transaksi, serta memberikan kemudahan kepada pembeli dalam melihat pembelian mereka.

## :beginner: Dosen Pengampu :beginner:
Adi Wahyu Pribadi, S.Si., M.Kom

## :no_good: Anggota Kelompok 3 :no_good:

| No | Nama Anggota            | NPM         |
|----|-------------------------|-------------|
| 1  | Raziy Ibrahim           | 4523210138  |
| 2  | Andhika Pramudya        | 4523210014  |
| 3  | Reza Brema Ginting      | 4523210092  |


## :moneybag: Toko Kelontong Mila :moneybag:

### 1. Aktor dari Toko Kelontong Mila
**:guardsman: Admin :guardsman:**

Admin atau pemilik toko memiliki peran utama dalam mengelola seluruh operasional aplikasi warung kelontong. Tugas utamanya adalah mengelola data barang yang dijual, mulai dari menambahkan barang baru, mengedit informasi barang seperti nama, harga, dan satuan, hingga menghapus barang yang sudah tidak tersedia. Selain itu, admin bertanggung jawab untuk menambahkan stok barang secara berkala agar ketersediaan barang tetap terjaga. Dalam hal transaksi, admin mencatat setiap pembelian yang dilakukan oleh pembeli, menghitung total harga, serta menyimpan detail barang yang dibeli dalam sistem. Admin juga dapat melihat seluruh riwayat transaksi untuk keperluan evaluasi dan pengelolaan usaha.

**:credit_card: Pelanggan :credit_card:**

Pembeli hanya bisa melihat barang yang ia beli saat transaksi (pembelian dilakukan, bentuknya seperti Alfamart dimana pembeli hanya bisa melihat barang yang ia beli)

### 2. Use Case Diagram - Toko Kelontong Mila
   
   ![Untitled](https://github.com/user-attachments/assets/fe73780a-5d6a-4f69-a6da-84fbda814806)
  
### 3. Entitas Utama
   **:gift: Admin :gift:**
| Attribut                | Tipe data   |
|-------------------------|-------------|
| id_admin        | integer  |
| username        | varchar  |
| password         | varchar  |


   **:gift: Barang :gift:**
| Attribut                | Tipe data   |
|-------------------------|-------------|
| id_barang           | integer  |
| nama_barang       | varchar  |
| harga      | integer  |
| stok      | integer  |

### 4. Relasi

   **:gift: Pembelian :gift:**
| Attribut                | Tipe data   |
|-------------------------|-------------|
| id_pembelian              | integer  |
| id_barang        | integer  |
| qty        | integer  |
| tanggal_pembellian      | date  |
| total_harga      | integer  |
| id_admin        | integer  |


   **:gift: Stock :gift:**
| Attribut                | Tipe data   |
|-------------------------|-------------|
| id_stock           | integer  |
| id_barang        | integer  |
| nama_barang       | varchar  |
| stockmasuk      | date  |
| qty        | integer  |
| id_admin        | integer  |

### 5. Class Diagram Toko Kelontong Mila 
![Class Diagram - Toko Kelontong Mila](https://github.com/user-attachments/assets/16d5e144-239d-4cd8-89b3-6f5efa185770)


### 6. ERD Toko Kelontong Mila
![WhatsApp Image 2025-05-29 at 14 02 00](https://github.com/user-attachments/assets/fda10544-aa60-4650-99c7-e083c868660b)



   


### 7. Desain Antarmuka / UI Toko Kelontong Mila
   **:snowflake: WIREFRAME :snowflake:** 
![Image](https://github.com/user-attachments/assets/d90f76e3-c099-4885-a971-b3b6d6bdbe63)

   **:snowflake: MOCKUP :snowflake:**
![Image](https://github.com/user-attachments/assets/9161d15d-738d-4d30-8374-56b9f07b4876)

### 8. Dokumen Fakta Integritas
![image](https://github.com/user-attachments/assets/8e1479f5-deae-41c9-b316-f4f905be1de1)


