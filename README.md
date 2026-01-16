<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# 📘 Belajar REST API Laravel

Repository ini dibuat sebagai **hasil pembelajaran saya tentang REST API menggunakan Laravel**.  
Di project ini saya mempelajari bagaimana cara membuat API sederhana yang rapi, terstruktur, dan sesuai dengan konsep REST.

Project ini **bukan project production**, melainkan **media belajar** untuk memahami alur backend API.

---

## 🎯 Tujuan Pembelajaran

Melalui project ini saya belajar:

- Konsep dasar REST API
- CRUD (Create, Read, Update, Delete)
- Menggunakan Laravel Eloquent
- Validasi request
- Upload dan hapus file (image)
- Response API yang konsisten
- Error handling (404, 422)
- Pemisahan logic menggunakan Resource

---

## 🧠 Hal yang Dipelajari

### 🔹 REST API
- Menggunakan HTTP Method:
  - `GET` → mengambil data
  - `POST` → menambah data
  - `PUT / PATCH` → mengubah data
  - `DELETE` → menghapus data

---

### 🔹 Laravel Resource
Saya menggunakan `PostResource` untuk:
- Menyamakan format response API
- Mengirim response dengan struktur:
  - `status`
  - `message`
  - `data`

Contoh response:
```json
{
  "status": true,
  "message": "List Data Posts",
  "data": {}
}

