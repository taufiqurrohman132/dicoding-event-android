# Dicoding Event App

Aplikasi Android yang menyajikan berbagai event dari API Dicoding dengan fitur lengkap mulai dari navigasi, favorit, pencarian, tema, hingga pengingat harian. Dibangun dengan pendekatan arsitektur modern (MVVM + Repository + Dependency Injection) menggunakan Kotlin.

---

## Cuplikan Layar

<table align="center">
  <tr>
    <td align="center" valign="top">
      <strong>Home</strong><br>
      <img src="https://github.com/user-attachments/assets/00024cd8-20e2-4078-aafc-6c2ba907495c" width="250"/>
    </td>
    <td align="center" valign="top">
      <strong>Detail</strong><br>
      <img src="https://github.com/user-attachments/assets/9f11be57-149e-4d3e-acd4-1ba4be1c5184" width="250"/>
    </td>
    <td align="center" valign="top">
      <strong>Favorit</strong><br>
      <img src="https://github.com/user-attachments/assets/eee1c2c1-5b85-450b-bd89-9f744633b9ab" width="250"/>
    </td>
    <td align="center" valign="top">
      <strong>Notification</strong><br>
      <img src="https://github.com/user-attachments/assets/841ecd13-dcc2-437c-93c8-707b0898ba92" width="250"/>
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td align="center" valign="top">
      <strong>Finished</strong><br>
      <img src="https://github.com/user-attachments/assets/a0800288-86c1-4877-a2b4-c63c765e62df" width="250"/>
    </td>
    <td align="center" valign="top">
      <strong>Upcoming</strong><br>
      <img src="https://github.com/user-attachments/assets/8bfb4a76-422d-4627-a572-a92bd69c0a9c" width="250"/>
    </td>
    <td align="center" valign="top">
      <strong>Search Filter</strong><br>
      <img src="https://github.com/user-attachments/assets/1c8e7a7c-da8a-4c57-ba4a-e7a75e49cd16" width="250"/>
    </td>
    <td align="center" valign="top">
      <strong>Dark Mode</strong><br>
      <img src="https://github.com/user-attachments/assets/2d0b9296-d870-4f15-a153-60477a4f8ae9" width="250"/>
    </td>
  </tr>
</table>

---

## Daftar Fitur

<table>
  <tr>
    <td valign="top" width="50%">
      <ul>
        <li>Bottom Navigation (Aktif, Selesai, Favorit)</li>
        <li>List event dari API</li>
        <li>Halaman detail event</li>
        <li>Tambah/hapus favorit (Room)</li>
        <li>Halaman daftar favorit</li>
        <li>Tema terang/gelap (DataStore)</li>
        <li>Pencarian event</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <ul>
        <li>Home dengan carousel event (opsional)</li>
        <li>Notifikasi harian event terdekat (opsional)</li>
        <li>Arsitektur MVVM + ViewModel</li>
        <li>Repository Pattern</li>
        <li>Data tetap saat rotasi layar</li>
        <li>Indikator loading API</li>
        <li>Error handling koneksi/data</li>
        <li>Inspect Code warning < 10</li>
      </ul>
    </td>
  </tr>
</table>
         
---
         
## Teknologi & Arsitektur

| Komponen | Teknologi |
|---------|-----------|
| Bahasa | Kotlin |
| Arsitektur | MVVM |
| UI | XML + Material 3 |
| API | Retrofit |
| Database | Room |
| Theme Storage | DataStore (Preferences) |
| Dependency Injection | Manual |
| Background Task | WorkManager |
| Lifecycle | ViewModel + LiveData |
| Image Loader | Glide |
| Navigasi | Navigation Component |

---


## 📱 Coba Aplikasi
Kamu bisa langsung mencoba aplikasi ini dengan mengunduh file APK terbaru melalui tombol di bawah:

[ ![Download APK](https://img.shields.io/badge/Download-Latest_APK-green?style=for-the-badge&logo=android) ](https://github.com/taufiqurrohman132/finance-tracker-android/releases/latest)

> **Catatan Instalasi:**
> Karena aplikasi ini didistribusikan secara mandiri (tidak melalui Play Store), Android mungkin akan menampilkan peringatan "Unknown Apps". Pilih **"Install Anyway"** untuk melanjutkan. Aplikasi ini aman dan seluruh kode sumbernya bisa kamu periksa di repository ini.

----
## Cara Menjalankan

1. Clone repo:
 ```bash
 git clone https://github.com/taufiqurrohman132/Apk-DicodingEvent.git
```
