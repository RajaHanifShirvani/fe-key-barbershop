# 💈 Key Barber

Key Barber adalah platform digital untuk barbershop modern yang mengintegrasikan teknologi **AI Hairstyle Recommendation**. Proyek ini terdiri dari dua bagian utama: Frontend (Next.js) dan Backend (Node.js/Express).

---

## 🚀 Fitur Utama

- **AI Hairstyle Analysis**: Upload foto wajah dan dapatkan rekomendasi gaya rambut yang paling cocok menggunakan AI.
- **Booking & Services**: Lihat daftar layanan potong rambut dan pilih kapster favorit Anda.
- **User Dashboard**: Kelola profil, lihat riwayat transaksi, dan riwayat analisis AI.
- **Admin Management**: Kontrol penuh atas data user, layanan, kapster, dan konfigurasi AI.
- **Secure Authentication**: Mendukung Google OAuth dan sistem login tradisional.

---

## 🛠️ Tech Stack

### Frontend (`fe-key-barbershop`)
- **Framework**: [Next.js 15+ (App Router)](https://nextjs.org/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Fonts**: Playfair Display (Serif) & Inter (Sans-serif)

### Backend (`be-key-barbershop`)
- **Runtime**: [Node.js](https://nodejs.org/)
- **Framework**: [Express.js](https://expressjs.com/)
- **ORM**: [Prisma](https://www.prisma.io/)
- **Database**: MySQL
- **Documentation**: Swagger UI

---

## 📦 Instalasi & Setup

### 1. Clone Repository
```bash
git clone https://github.com/RajaHanifShirvani/Keybarber.git
cd Keybarber
```

### 2. Setup Backend
1. Masuk ke folder backend:
   ```bash
   cd be-key-barbershop
   ```
2. Install dependensi:
   ```bash
   npm install
   ```
3. Konfigurasi `.env`:
   Buat file `.env` dan sesuaikan `DATABASE_URL` serta API Key AI Anda.
4. Jalankan migrasi database:
   ```bash
   npx prisma migrate dev
   ```
5. Jalankan server:
   ```bash
   npm run dev
   ```

### 3. Setup Frontend
1. Masuk ke folder frontend:
   ```bash
   cd fe-key-barbershop
   ```
2. Install dependensi:
   ```bash
   npm install
   ```
3. Jalankan aplikasi:
   ```bash
   npm run dev
   ```

---

## 📂 Struktur Folder

```text
Keybarber/
├── be-key-barbershop/    # Express.js API
│   ├── src/
│   │   ├── controllers/  # Logika bisnis
│   │   ├── routes/       # Endpoint API
│   │   └── prisma/       # Schema database
│   └── server.js         # Entry point backend
└── fe-key-barbershop/    # Next.js Application
    ├── src/
    │   ├── app/          # Routing & Pages
    │   └── components/   # Reusable UI
    └── public/           # Asset statis (images/logo)
```

---

## 📄 Lisensi
Proyek ini dikembangkan untuk kebutuhan mitra Keybarber.

---
*Developed with ❤️ by Keybarber Team*