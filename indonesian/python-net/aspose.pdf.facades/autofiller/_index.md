---
title: "AutoFiller"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili kelas untuk menerima data dari basis data atau sumber data lain, mengisi data tersebut ke dalam bidang yang dirancang pada templat pdf dan akhirnya menghasilkan file pdf baru atau aliran.<br/>             Memiliki dua mode masukan file templat: masukan sebagai aliran atau file pdf.<br/>             Memiliki empat jenis mode keluaran: satu aliran gabungan, satu file gabungan, banyak aliran kecil, banyak file kecil.<br/>             Dapat menerima data literal yang terdapat dalam System.Data.DataTable."
type: docs
weight: 20
url: /id/python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

Mewakili kelas untuk menerima data dari basis data atau sumber data lain, mengisi data tersebut ke dalam bidang yang dirancang pada templat pdf dan akhirnya menghasilkan file pdf baru atau aliran.<br/>             Memiliki dua mode masukan file templat: masukan sebagai aliran atau file pdf.<br/>             Memiliki empat jenis mode keluaran: satu aliran gabungan, satu file gabungan, banyak aliran kecil, banyak file kecil.<br/>             Dapat menerima data literal yang terdapat dalam System.Data.DataTable.

Tipe AutoFiller menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| AutoFiller() | Menginisialisasi sebuah instance baru dari kelas AutoFiller |
## Properti
| Nama | Deskripsi |
| :- | :- |
| output_stream | Mendapatkan atau mengatur OutputStream. Salah satu dari empat mode output. Kasus penggunaan klasiknya adalah Response.OutputStream.<br/>            Silakan lihat demo online. |
| output_streams | Mendapatkan atau mengatur banyak Output Streams. Salah satu dari empat mode output. |
| input_stream | Mendapatkan atau mengatur input template stream. Salah satu dari dua mode input. |
| input_file_name | Mendapatkan atau mengatur input template file. Salah satu dari dua mode input. |
| output_file_name | Mendapatkan atau mengatur satu file output besar yang digabungkan. Salah satu dari empat mode output. |
| generating_path | Mendapatkan atau mengatur Generating Path dari file pdf kecil jika banyak file pdf kecil akan dihasilkan. Ini bekerja dengan properti lain [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName.<br/>            Salah satu dari empat mode output. |
| basic_file_name | Mendapatkan atau mengatur basic file name jika banyak file kecil akan dihasilkan. File yang dihasilkan akan berupa "BasicFileName0","BasicFileName1",...<br/>            Ini bekerja dengan properti lain [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| save() | Menyimpan semua pdf. |
| save(dest_file) | Menyimpan semua pdf. |
| save(dest_stream) | Menyimpan semua pdf. |
| bind_pdf(src_file) | Mengikat sebuah file Pdf. |
| bind_pdf(src_stream) | Mengikat sebuah file Pdf. |
| bind_pdf(src_doc) | Mengikat sebuah dokumen Pdf. |
| close() | Menutup objek dan output streams. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

