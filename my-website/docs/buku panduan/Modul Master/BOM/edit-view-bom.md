---
id: edit-view-bom
title: Mengedit dan Melihat Detail BOM
sidebar_position: 6
---

# Mengelola Bill Of Material (BOM) yang Sudah Tersimpan

Setelah BOM berhasil disimpan dan muncul di halaman **Bill Of Material**, Anda dapat melakukan beberapa tindakan seperti melihat detail BOM, mengedit isi BOM, hingga menghapusnya jika sudah tidak digunakan. Fitur-fitur ini dibuat agar user dapat mengelola BOM dengan mudah dan cepat tanpa perlu membuat ulang.

---

## Mengakses Halaman Daftar BOM

Pada halaman **Bill Of Material**, seluruh daftar BOM akan tampil lengkap beserta statusnya (**Draft** atau **Published**).  
Tersedia beberapa fitur pendukung seperti:

- **Search Bill Of Material Name** → untuk mencari BOM berdasarkan nama  
- **Is Active?** → untuk memfilter apakah BOM tersebut aktif atau tidak

Fitur-fitur ini memudahkan user menemukan BOM yang ingin dikelola tanpa perlu scroll panjang.

---

## Mengubah Status Active

Status **Active / Inactive** digunakan untuk menentukan apakah BOM boleh dipakai dalam proses produksi.

Untuk mengubah status:

- Klik ikon centang biru pada kolom **Active**.  
  ![Ikon Active untuk mengubah status BOM]( image/image-26.png)

Saat tombol ditekan, sistem menampilkan pop-up konfirmasi:

![Pop-up konfirmasi Change Status](image/image-28.png)

Jika Anda menekan **Continue**, sistem akan menampilkan notifikasi:

![Notifikasi berhasil mengubah status](image/image-29.png)

Setelah itu, user diarahkan kembali ke halaman BOM, dan status pada baris yang dipilih akan berubah menjadi tidak aktif.

![Tampilan status BOM setelah berhasil diubah](image/image-30.png)

---

## Melihat Detail BOM

Fitur ini digunakan untuk melihat isi BOM tanpa melakukan perubahan.

1. Cari BOM yang ingin dilihat.
2. Klik ikon **Detail** (ikon mata).  
   ![Ikon Detail untuk melihat informasi BOM](image/image-25.png)

Anda akan diarahkan ke tampilan informasi lengkap BOM.

Pada mode ini:
- **Tidak bisa edit data**
- **Tidak bisa menambah atau menghapus material**
- Hanya untuk melihat informasi saja

Untuk kembali, tekan tombol **Cancel**.

![Tampilan header detail BOM](image/image-31.png)  
![Tampilan material detail BOM](image/image-32.png)

---

## B. Mengedit (Edit) BOM

Fitur Edit digunakan ketika Anda perlu memperbaiki atau mengubah data BOM.

Langkah-langkah:

1. Temukan BOM yang ingin diubah.
2. Klik ikon **Edit** (ikon pensil).
3. Sistem membawa Anda kembali ke halaman pengisian BOM.

Pada halaman edit, user bisa mengubah:
- Bagian **Bill Of Material** seperti BOM Code, Quantity, Project, Currency, Raw Material Based On  
- Catatan tambahan pada BOM  
- Material (menambah material baru, mengubah Qty, atau menghapus material)

Catatan penting:  
Beberapa field pada **Bill Of Material Item** tidak bisa diubah karena mengikuti struktur awal BOM.

![Halaman Edit BOM – bagian header](image/image-34.png)  
![Halaman Edit BOM – bagian material](image/image-33.png)

---

## C. Proses Menyimpan Hasil Edit

Setelah selesai mengedit, terdapat dua pilihan penyimpanan:

### 1. Save As Draft
Gunakan ini jika perubahan masih dalam tahap penyusunan.  
BOM akan tetap berstatus **Draft**.

Notifikasi yang muncul:  
**Success: Bill Of Material Update Successfully**

### 2. Submit
Gunakan jika perubahan sudah final dan siap dipublikasikan.  
Status BOM akan berubah menjadi **Published**.

![Tampilan tombol Save As Draft dan Submit pada halaman BOM](image/image-37.png)

---

## D. Menghapus (Delete) BOM

Gunakan fitur ini untuk menghapus BOM secara permanen.

1. Cari BOM yang ingin dihapus.
2. Klik ikon **Delete** (ikon tempat sampah).  
   ![Ikon Delete untuk menghapus BOM](image/image-35.png)

Sistem akan menampilkan pop-up konfirmasi:

![Pop-up konfirmasi penghapusan BOM](image/image-36-1.png)

Tekan **Continue** jika yakin ingin menghapus.

Setelah berhasil, sistem menampilkan notifikasi:  
**Operation Deleted Successfully**

User akan kembali ke halaman daftar BOM setelah penghapusan selesai.

---
