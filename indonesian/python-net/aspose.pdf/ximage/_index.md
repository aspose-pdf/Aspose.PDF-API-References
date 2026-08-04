---
title: "XImage"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas yang mewakili X-Object gambar."
type: docs
weight: 1680
url: /id/python-net/aspose.pdf/ximage/
---

## XImage class

Kelas yang mewakili X-Object gambar.

Tipe XImage mengekspos anggota-anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| contains_transparency | Jika gambar mengandung transparansi maka mengembalikan true; sebaliknya, false. |
| grayscaled | Mendapatkan versi gambar yang di-grayscale. |
| filter_type | Mendapatkan tipe filter gambar. |
| lebar | Mendapatkan lebar gambar. |
| tinggi | Mendapatkan tinggi gambar. |
| name | Mendapatkan atau mengatur nama gambar. Harap perhatikan bahwa jika Anda mengubah nama gambar yang memiliki referensi dalam konten halaman, dokumen mungkin menjadi tidak benar. Harap gunakan metode XImage.Rename dalam kasus ini. |
| metadata | Metadata gambar. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| save(stream) | Menyimpan data gambar ke dalam stream sebagai gambar JPEG. |
| save(stream, format) | Menyimpan gambar ke dalam stream dengan format yang diminta. |
| save(stream, resolution) | Menyimpan data gambar ke dalam stream sebagai gambar JPEG dengan resolusi yang ditentukan. |
| save(stream, format, resolution) | Menyimpan gambar ke dalam stream dengan format yang diminta dengan resolusi yang ditentukan. |
| rename(name) | Mengganti nama gambar dan menggantikan semua referensi ke gambar dengan nama baru. |
| get_color_type() | Mengembalikan tipe warna gambar. |
| detect_color_type(bmp) | Mengembalikan tipe warna gambar. |
| is_the_same_object(image) | Mengembalikan true jika kedua gambar merujuk ke objek yang sama. |
| get_name_in_collection() | Mengembalikan nama gambar dalam koleksi ints. |
| to_stream() | Mengembalikan aliran gambar asli. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

