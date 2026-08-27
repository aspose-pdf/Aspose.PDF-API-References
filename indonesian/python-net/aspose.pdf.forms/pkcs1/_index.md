---
title: "PKCS1"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili objek tanda tangan terkait standar PKCS#1.<br/>            Algoritma enkripsi RSA dan metode digest SHA-1 digunakan untuk penandatanganan."
type: docs
weight: 180
url: /id/python-net/aspose.pdf.forms/pkcs1/
---

## PKCS1 class

Mewakili objek tanda tangan terkait standar PKCS#1.<br/>            Algoritma enkripsi RSA dan metode digest SHA-1 digunakan untuk penandatanganan.

Tipe PKCS1 menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PKCS1(image) | Menginisialisasi sebuah instance baru dari kelas PKCS1 |
| PKCS1() | Menginisialisasi instance baru dari kelas [PKCS1](/pdf/python-net/aspose.pdf.forms/pkcs1/). |
| PKCS1(pfx, password) | Menginisialisasi sebuah instance baru dari kelas PKCS1 |
| PKCS1(pfx, password) | Menginisialisasi sebuah instance baru dari kelas PKCS1 |
## Properti
| Nama | Deskripsi |
| :- | :- |
| custom_appearance | Mendapatkan/mengatur tampilan khusus. |
| authority | Nama orang atau otoritas yang menandatangani dokumen. |
| date | Waktu penandatanganan. |
| location | Nama host CPU atau lokasi fisik penandatanganan. |
| reason | Alasan penandatanganan, seperti (Saya setuju). |
| contact_info | Informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan <br/>            untuk memverifikasi tanda tangan, misalnya nomor telepon. |
| byte_range | Array pasangan bilangan bulat (offset byte mulai, panjang dalam byte) <br/>             yang menggambarkan rentang byte yang tepat untuk perhitungan digest. |
| timestamp_settings | Mendapatkan/mengatur pengaturan timestamp. |
| ocsp_settings | Mendapatkan/mengatur pengaturan ocsp. |
| use_ltv | Mendapatkan/mengatur flag validasi ltv. |
| show_properties | Paksa untuk menampilkan/menyembunyikan properti tanda tangan.<br/>            Jika ShowProperties bernilai true, bidang tanda tangan memiliki format penampilan yang telah ditentukan (string untuk merepresentasikan):<br/>            -------------------------------------------<br/>            Ditandatangani secara digital oleh {certificate subject}<br/>            Tanggal: {signature.Date}<br/>            Alasan: {signature.Reason}<br/>            Lokasi: {signature.Location}<br/>            -------------------------------------------<br/>            dimana {X} adalah placeholder untuk nilai X. Tanda tangan juga dapat memiliki gambar, dalam kasus ini string yang terdaftar ditempatkan di atas gambar.<br/>            ShowProperties bernilai true secara default. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| verify() | Verifikasi dokumen terkait tanda tangan ini dan mengembalikan true jika dokumen valid <br/>            atau sebaliknya false. |

### Lihat Juga

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

