---
title: "ExternalSignature"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Membuat tanda tangan PKCS#7Detached terpisah menggunakan X509Certificate2. Ini mendukung smartcard USB, token tanpa kunci pribadi yang dapat diekspor."
type: docs
weight: 80
url: /id/python-net/aspose.pdf.forms/externalsignature/
---

## ExternalSignature class

Membuat tanda tangan PKCS#7Detached terpisah menggunakan X509Certificate2. Ini mendukung smartcard USB, token tanpa kunci pribadi yang dapat diekspor.

Tipe ExternalSignature menampilkan anggota berikut:
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

