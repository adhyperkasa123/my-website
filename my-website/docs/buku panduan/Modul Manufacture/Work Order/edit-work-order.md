---
id: edit-work-order
title: Mengedit Work Order
sidebar_position: 6
---

# Mengedit Work Order

User dapat melakukan perubahan selama Work Order masih berstatus **Draft**.

---

## 📝 Langkah-Langkah Edit

1. Buka halaman **Work Order List**.
2. Temukan Work Order berstatus Draft.
3. Klik ikon **pencil (Edit)**.

![ikon Edit](image/image-18.png)

Sistem menampilkan halaman edit:

![halaman edit](image/image-17.png)

---

## ✏️ Data yang Bisa Diedit

User bisa mengubah:

- **Start Date**
- **End Date**
- **WIP Warehouse**
- **Project**
- **Qty to Manufacture**

⚠️ **Field yang tidak dapat diubah:**

- Transaction Number  
- Status  
- Posting Date  
- Item  
- Finished Goods Warehouse  

---

# Penyimpanan dari Mode Edit

Pada halaman Edit terdapat dua tombol:

- **Save As Draft**
- **Publish**

---

## 🟦 1. Publish dari Mode Edit

Saat menekan tombol **Publish**, muncul pop-up konfirmasi:

> **Are you sure you want to publish this work order? This action cannot be undone.**

User dapat memilih:

- **Cancel**  
- **Continue**

### Jika memilih **Continue**:

- Status berubah menjadi **Published**
- Data terkunci
- User kembali ke daftar Work Order

![setelah edit](image/image-35.png)

Setelah publish berhasil:

- Muncul notifikasi: **Success — Successfully edited work order.**
- Data ditampilkan di daftar Work Order

![Success](image/image-36.png)

---

## 🟩 2. Save As Draft

Gunakan **Save As Draft** jika user ingin menyimpan tanpa publish.

Setelah ditekan:

- Sistem menampilkan pop-up konfirmasi

![Pop-up Publish Confirmation](image/image-39.png)

- User diarahkan kembali ke daftar Work Order
- Status tetap **Draft**

![Hasil Save as Draft](image/image-40.png)
