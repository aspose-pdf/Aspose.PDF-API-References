---
title: "PKCS7"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili objek PKCS#7 yang sesuai dengan spesifikasi PKCS#7 dalam Internet RFC 2315, <br/>            PKCS #7: Cryptographic Message Syntax, Versi 1.5.<br/>            Digest SHA1 dari rentang byte dokumen dibungkus dalam bidang PKCS#7 SignedData."
type: docs
weight: 190
url: /id/python-net/aspose.pdf.forms/pkcs7/
---

## PKCS7 class

Mewakili objek PKCS#7 yang sesuai dengan spesifikasi PKCS#7 dalam Internet RFC 2315, <br/>            PKCS #7: Cryptographic Message Syntax, Versi 1.5.<br/>            Digest SHA1 dari rentang byte dokumen dibungkus dalam bidang PKCS#7 SignedData.

Tipe PKCS7 menampilkan anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PKCS7() | Menginisialisasi instance baru dari kelas [PKCS7](/pdf/python-net/aspose.pdf.forms/pkcs7/). |
| PKCS7(pfx, password) | Menginisialisasi instance baru dari kelas PKCS7 |
| PKCS7(pfx, password) | Menginisialisasi instance baru dari kelas PKCS7 |
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

