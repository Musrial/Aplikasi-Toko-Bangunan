# 🧱 Aplikasi Toko Bangunan

Aplikasi web berbasis React.js dan Express.js yang digunakan untuk mengelola operasional toko bangunan seperti manajemen barang, transaksi pembelian & penjualan, pelanggan, supplier. Dibangun dengan arsitektur RESTful API dan otentikasi JWT.

---

## 🚀 Fitur Utama

- 🔐 Login multi-role (Admin & Kasir)
- 👥 Manajemen pengguna (CRUD user)
- 📦 Barang, kategori, dan jenis barang
- 🧾 Transaksi pembelian dan penjualan
- 📈 Dashboard dan laporan dinamis
- 🧮 Cetak invoice otomatis dengan nomor faktur unik
- 🔒 Otentikasi menggunakan JWT & bcrypt

---

## 🛠️ Teknologi yang Digunakan

| Layer      | Teknologi                      |
|------------|--------------------------------|
| Frontend   | React.js, Vite, Bootstrap      |
| Backend    | Node.js, Express.js            |
| Database   | PostgreSQL                     |
| Auth       | JWT (JSON Web Token)           |
| Hashing    | Bcrypt                         |
| Env Config | dotenv                         |

---

## 📦 Instalasi & Menjalankan Proyek

### 1. Clone Repository

```bash
git clone https://github.com/ferlijunandar/Aplikasi-Toko-Bangunan.git
cd Aplikasi-Toko-Bangunan
```
### 2. Setup Backend

```bash
cd server
npm install
node index
```
-Server berjalan di `http://localhost:5000`
### 3. Setup Frontend
-Buka Terminal Baru lalu jalankan perintah berikut:
```bash
npm install
npm run dev
```
-Aplikasi akan berjalan di `http://localhost:5173`
