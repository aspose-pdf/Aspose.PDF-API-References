---
title: "Stamp"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas yang mewakili stempel."
type: docs
weight: 410
url: /id/python-net/aspose.pdf.facades/stamp/
---

## Stamp class

Kelas yang mewakili stempel.

Tipe Stamp menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| Stamp() | Menginisialisasi instance baru dari kelas Stamp |
## Properti
| Nama | Deskripsi |
| :- | :- |
| stamp_id | Mendapatkan atau mengatur identifier stempel. |
| kualitas | Mendapatkan atau mengatur kualitas stempel gambar dalam persen. Nilai yang valid 0..100%. |
| opasitas | Mendapatkan atau mengatur opasitas stempel. |
| page_number | Mendapatkan atau mengatur nomor halaman. |
| halaman | Mendapatkan atau mengatur array dengan nomor halaman yang akan dipengaruhi oleh stempel. <br/>            Jika Pages = null semua halaman dokumen akan dipengaruhi. |
| rotation | Mendapatkan atau mengatur rotasi stempel dalam derajat. |
| is_background | Mendapatkan atau mengatur status latar belakang. Jika true stempel akan ditempatkan sebagai latar belakang halaman yang disegel.<br/>            Secara default diatur ke false. |
| blending_space | Mendapatkan atau mengatur nilai BlendingColorSpace yang mendefinisikan ruang warna <br/>            yang digunakan untuk melakukan operasi transparansi dan pencampuran pada halaman. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(pdf_file, page_number) | Mengatur file PDF dan nomor halaman yang akan digunakan sebagai stempel. |
| bind_pdf(pdf_stream, page_number) | Mengatur file PDF dan nomor halaman yang akan digunakan sebagai stempel. |
| bind_image(image_file) | Mengatur gambar sebagai stempel. |
| bind_image(image) | Mengatur gambar yang akan digunakan sebagai stempel. |
| bind_logo(formatted_text) | Mengatur teks sebagai stempel. |
| bind_text_state(text_state) | Mengatur keadaan teks dari teks stempel. |
| set_origin(origin_x, origin_y) | Mengatur posisi pada halaman tempat stempel akan ditempatkan. |
| set_image_size(width, height) | Mengatur ukuran stempel gambar. Gambar akan diubah skalanya sesuai dengan nilai yang ditentukan. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

