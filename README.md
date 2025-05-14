# Backend Web Absensi - Node.js + MongoDB

Ini adalah backend dari **Web Absensi** yang dikembangkan selama program magang. Backend ini dibangun menggunakan **Node.js**, **Express.js**, dan **MongoDB** untuk menyimpan serta mengelola data absensi, cuti, dan pengguna secara real-time.

---

## 🔧 Teknologi yang Digunakan

- **Node.js** – Server-side runtime
- **Express.js** – Web framework
- **MongoDB** – Database NoSQL
- **Mongoose** – ODM untuk MongoDB
- **JWT (jsonwebtoken)** – Autentikasi
- **Bcrypt.js** – Enkripsi password
- **dotenv** – Pengelolaan environment variable
- **Cors** – Middleware untuk akses lintas origin

---

## 📁 Struktur Folder

backend/
├── config/ # Konfigurasi koneksi database
│ └── db.js
├── controllers/ # Logika setiap fitur
│ ├── absensi_Controllers.js
│ ├── ajuancuti_Controllers.js
│ ├── auth_Controllers.js
│ ├── export_Controllers.js
│ └── user_Controllers.js
├── middleware/ # Middleware untuk autentikasi
│ └── auth_Middleware.js
├── models/ # Skema MongoDB
│ ├── absensi.js
│ ├── ajuancuti.js
│ ├── export.js
│ └── user.js
├── routes/ # Definisi endpoint API
│ └── index.js
├── .env # Variabel lingkungan
├── index.js # Entry point server
└── package.json


---

## 📦 Instalasi & Menjalankan Server

1. **Clone repositori**
```bash
git clone https://github.com/username/web-absensi-backend.git
cd web-absensi-backend/backend
npm install
```
Proyek backend ini merupakan bagian dari sistem absensi berbasis web yang dikembangkan selama magang dan dapat dikembangkan lebih lanjut.

