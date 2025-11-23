---
id: definisi-workspace
title: Apa Itu Workspace
sidebar_position: 1
---

# 1. Apa Itu Workspace

## 1.1 Definisi Workspace

**Workspace** pada sistem **ADFood** adalah gambaran dari **struktur organisasi perusahaan** yang menjadi wadah utama untuk mengelola semua **data, proses, dan pengguna (user)** di dalam sistem.

Secara sederhana, Workspace berfungsi sebagai **ruang kerja virtual** yang menampilkan susunan organisasi mulai dari tingkat paling atas (Holding) hingga ke tingkat operasional (Company Branch).

---

###  Struktur Workspace 

Struktur **Workspace** dalam ADFood terdiri dari beberapa tingkatan sebagai berikut:

---

#### **Holding**
- Merupakan **tingkat tertinggi** dalam struktur organisasi.  
- Mewakili **perusahaan induk** yang memiliki satu atau lebih *Subholding* atau *Company*.  
- Fokus utama Holding adalah mengelola dan memantau **laporan keuangan konsolidasi**, yaitu gabungan dari seluruh entitas di bawahnya.  
- Tidak memiliki menu operasional, hanya menyediakan:  
  - **Dashboard**  
  - **Report**  
  yang digunakan untuk analisis dan pelaporan.

---

#### **Subholding**
- Berada di bawah **Holding** sebagai tingkat menengah.  
- Mengelola beberapa **Company** di dalamnya.  
- Sama seperti Holding, Subholding tidak memiliki menu operasional dan hanya menampilkan:  
  - **Dashboard**  
  - **Report**  
- Fungsinya adalah untuk **menggabungkan dan menganalisis data** dari seluruh *Company* yang ada di bawahnya.

---

#### **Company**
- Merupakan **entitas operasional utama** di bawah *Holding* atau *Subholding*.  
- Memiliki menu **operasional (transaksional)**, seperti:  
  - Accounting  
  - Manufacture  
  - Sales  
  - Procurement  
  - dan modul-modul operasional lainnya sesuai kebutuhan perusahaan.  
- Setiap *Company* hanya dapat melihat dan mengelola **data miliknya sendiri**,  
  dan **tidak dapat mengakses data dari Company lain**.

---

#### **Company Branch**
- Adalah **unit atau cabang** dari sebuah *Company*.  
- Memiliki menu **operasional** dan dapat melakukan transaksi sesuai dengan **hak akses** yang diberikan.  
- Seluruh data dan laporan dari *Company Branch* akan **terhubung langsung** dengan *Company induk*,  
  sehingga memudahkan proses pelaporan dan konsolidasi data.
---
# 1.2 Mengelola Workspace

Panduan ini menjelaskan cara menggunakan **Workspace**.  
Setiap pengguna memiliki akun masing-masing dengan hak akses berbeda sesuai **role (perannya)**.  
Dalam contoh ini digunakan akun **Super Admin**, yang memiliki akses penuh untuk mengelola seluruh Workspace.

---