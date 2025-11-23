---
id: purchase-order-transaksi
title: Cara Melakukan Transaksi Purchase Order
sidebar_position: 2
---

## Cara Melakukan Transaksi Purchase Order

Berikut ini akan dijelaskan langkah demi langkah cara melakukan transaksi **Purchase Order** di sistem ERP ADFood. Pada contoh ini, Workspace yang digunakan adalah **Company Branch** dengan nama *Supporting Office Kebagusan Raya*. Pastikan Anda sudah login ke sistem ERP ADFood, kemudian pilih **Workspace** yang sesuai.

1. Buka menu navigasi sidebar di sebelah kiri, pilih modul **Procurement**, lalu klik menu **Purchase Order**. Sistem akan menampilkan halaman **List Purchase Order** seperti pada gambar. Pada halaman ini, Anda dapat melihat daftar transaksi **Purchase Order** yang telah dibuat sebelumnya. Data ditampilkan dalam bentuk tabel (datatable) berisi informasi seperti *Transaction Number, Transaction Date, Vendor, Company Branch, Estimate Delivery Date, Total, Status,* dan *Action*. Untuk membuat transaksi baru, klik tombol **Add Purchase Order**.

![Membuka Menu Purchase Order](image/image.png)

2. Berikut adalah tampilan halaman **Create Purchase Order**, di mana Anda dapat membuat transaksi berdasarkan Purchase Request yang telah dibuat sebelumnya.

![Tampilan Halaman Create Purchase Order](image/image-1.png)

3. Transaksi **Purchase Order** hanya dapat dilakukan dengan mengambil item dari **Purchase Request**. Agar tombol **Get Item From Purchase Request** aktif, Anda harus memilih **Vendor** terlebih dahulu.

![Memilih Vendor Agar Tombol Get Item Aktif](image/image-2.png)

4. Contoh vendor **PT Meat Lover** dipilih, setelah itu tombol **Get Item From Purchase Request** akan aktif.

![Tombol Get Item From Purchase Request Menjadi Aktif](image/image-3.png)

5. Sistem akan menampilkan daftar **Purchase Request** berstatus **Published**. Pilih data yang ingin diproses.

![Daftar Purchase Request Berstatus Published](image/image-4.png)

6. Checklist **Transaction Number**, kemudian klik **Import**.

![Memilih PR untuk Diproses](image/image-5.png)

7. Data dari PR akan otomatis terisi pada halaman PO.

![Data Purchase Request Berhasil Terimport ke PO](image/image-6.png)

8. Isi bagian **Taxes and Charges** jika diperlukan. Klik **Add Row** untuk menambah data.

![Menambah Taxes and Charges](image/image-7.png)

9. Pilih **Type**:  
   - **Actual** → isi **Amount**  
   - **On Net Total** → isi **Rate** (%)

![Mengisi Type Taxes and Charges](image/image-8.png)

10. Pilih **Tax Name** dari dropdown.

![Memilih Tax Name](image/image-9.png)

11. Contoh pengisian:
- Actual → Delivery Charge → Amount: 50.000  
- On Net Total → PPN → Rate: 11  

![Contoh Pengisian Taxes and Charges](image/image-10.png)

Setelah selesai, klik **Save As Draft**.
