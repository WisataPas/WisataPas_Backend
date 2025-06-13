# WisataPas : Temukan Tempat Seru dengan Teknologi Rekomendasi Cerdas.

## Coding Camp Powered by DBS Foundation Capstone Project  
**Capstone Team ID** : `CC25-CF197`

---

### 🔗 Akses Backend API (Deployed)  
GitHub Repository:  
[https://github.com/jamaljml18/wisatapas-backend-vercel](https://github.com/jamaljml18/wisatapas-backend-vercel)  
**Base Endpoint**:  
`https://wisatapas-backend-vercel.vercel.app`

![Backend Deployment](https://res.cloudinary.com/diihtbw9h/image/upload/v1/deployBe_gujhmd)

---

### 🤖 Akses Model Machine Learning (Deployed)  
HuggingFace Space:  
[https://huggingface.co/spaces/mjamalm18/fastapi-wisatapas/tree/main](https://huggingface.co/spaces/mjamalm18/fastapi-wisatapas/tree/main)  
**Base Endpoint**:  
`https://mjamalm18-fastapi-wisatapas.hf.space`

![ML Deployment](https://res.cloudinary.com/diihtbw9h/image/upload/v1/deployMl_wsucfn)

---

# 📘 Dokumentasi API WisataPass

Dokumentasi ini mencakup tiga bagian utama:
- Autentikasi & User
- Manajemen Tempat Favorit
- Fitur Utama (Machine Learning)

---

## 🔐 Autentikasi & User

### 1. Login
- **Method**: `POST`  
- **Endpoint**:  
  `https://wisatapas-backend-vercel.vercel.app/api/login`

### 2. Register
- **Method**: `POST`  
- **Endpoint**:  
  `https://wisatapas-backend-vercel.vercel.app/api/register`

### 3. Auth Check ID
- **Method**: `GET`  
- **Endpoint**:  
  `https://wisatapas-backend-vercel.vercel.app/api/auth-check-id`

### 4. Auth Check Nama
- **Method**: `GET`  
- **Endpoint**:  
  `https://wisatapas-backend-vercel.vercel.app/api/auth-check-name`

---

## 📌 Manajemen Tempat Favorit

### 1. Simpan Tempat Favorit
- **Method**: `POST`  
- **Endpoint**:  
  `https://wisatapas-backend-vercel.vercel.app/api/like`

### 2. Hapus Tempat Favorit
- **Method**: `DELETE`  
- **Endpoint**:  
  `https://wisatapas-backend-vercel.vercel.app/api/unlike`

### 3. Load Tempat Favorit User
- **Method**: `GET`  
- **Endpoint**:  
  `https://wisatapas-backend-vercel.vercel.app/api/favorites/{idUser}`

#### Parameter:
- `idUser` (path): ID dari user yang datanya ingin diambil

---

## 🧠 Fitur Utama (Machine Learning)

### 1. Rekomendasi Tempat Wisata
- **Method**: `POST`  
- **Endpoint**:  
  `https://mjamalm18-fastapi-wisatapas.hf.space/recommendations`

### 2. Pencarian Tempat Wisata
- **Method**: `POST`  
- **Endpoint**:  
  `https://mjamalm18-fastapi-wisatapas.hf.space/search`

### 3. Text Generation (Deskripsi Wisata Otomatis)
- **Method**: `POST`  
- **Endpoint**:  
  `https://mjamalm18-fastapi-wisatapas.hf.space/textgen`
