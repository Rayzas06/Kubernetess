# Fullstack Project

## Identitas
- Nama: Raymond Divian Nathaniel
- NIM: 2410511079
- Kelas: B

## Deskripsi
Repository ini berisi proyek fullstack sederhana dengan frontend dan backend terpisah.

## Struktur Folder
- `backend/` - server Node.js
- `frontend/` - aplikasi React
- `klaster/` - file deployment dan service Kubernetes

## Teknologi yang Digunakan
- Backend: Node.js, Express
- Frontend: React, Create React App
- Docker untuk containerization
- Kubernetes untuk deployment (opsional)

## Cara Menjalankan Proyek

### 1. Menjalankan backend
1. Buka terminal di folder `backend`
2. Install dependensi:
   ```bash
   npm install
   ```
3. Jalankan server:
   ```bash
   npm start
   ```

### 2. Menjalankan frontend
1. Buka terminal di folder `frontend`
2. Install dependensi:
   ```bash
   npm install
   ```
3. Jalankan aplikasi React:
   ```bash
   npm start
   ```

### 3. Menggunakan Docker (opsional)
- Backend Dockerfile ada di `backend/Dockerfile`
- Frontend Dockerfile ada di `frontend/Dockerfile`

### 4. Menggunakan Kubernetes (opsional)
File konfigurasi deployment dan service berada di folder `klaster/`.

## Catatan
Pastikan Node.js dan npm sudah terinstall di sistem Anda sebelum menjalankan proyek.
