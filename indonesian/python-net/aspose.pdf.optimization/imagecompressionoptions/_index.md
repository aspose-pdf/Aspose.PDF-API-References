---
title: "ImageCompressionOptions"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas berisi sekumpulan opsi untuk kompresi gambar."
type: docs
weight: 10
url: /id/python-net/aspose.pdf.optimization/imagecompressionoptions/
---

## ImageCompressionOptions class

Kelas berisi sekumpulan opsi untuk kompresi gambar.

Tipe ImageCompressionOptions menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| ImageCompressionOptions() | Menginisialisasi sebuah instance baru dari kelas ImageCompressionOptions |
## Properti
| Nama | Deskripsi |
| :- | :- |
| compress_images | Jika flag ini diatur ke true, gambar akan dikompresi dalam dokumen. Tingkat kompresi ditentukan dengan properti ImageQuality. |
| resize_images | Jika flag ini diatur ke true dan CompressImages bernilai true, gambar akan diubah ukurannya jika resolusi gambar lebih besar daripada parameter MaxResolution yang ditentukan. |
| image_quality | Menentukan tingkat kompresi gambar ketika flag CompressIamges digunakan. |
| max_resolution | Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, gambar akan diubah skalanya. |
| version | Versi algoritma kompresi. Nilai yang mungkin adalah: 1. kompresi standar, 2. cepat (kompresi yang ditingkatkan yang lebih cepat daripada standar tetapi mungkin tidak berlaku untuk semua gambar), 3. campuran (kompresi standar diterapkan pada gambar yang tidak dapat dikompresi oleh algoritma yang lebih cepat, ini dapat memberikan kompresi terbaik tetapi lebih lambat daripada algoritma \"fast\". Versi \"Fast\" tidak berlaku untuk mengubah ukuran gambar (metode standar akan digunakan). Default adalah \"Standard\"). |
| encoding | Mendapatkan atau mengatur pengkodean yang digunakan untuk menyimpan gambar. |

### Lihat Juga

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

