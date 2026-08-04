---
title: "PdfPageStamp"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas mewakili stempel yang menggunakan halaman PDF sebagai stempel."
type: docs
weight: 1230
url: /id/python-net/aspose.pdf/pdfpagestamp/
---

## PdfPageStamp class

Kelas mewakili stempel yang menggunakan halaman PDF sebagai stempel.

Tipe PdfPageStamp menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfPageStamp(pdf_page) | Menginisialisasi instance baru dari kelas PdfPageStamp |
| PdfPageStamp(file_name, page_index) | Menginisialisasi instance baru dari kelas PdfPageStamp |
| PdfPageStamp(stream, page_index) | Menginisialisasi instance baru dari kelas PdfPageStamp |
## Properti
| Nama | Deskripsi |
| :- | :- |
| background | Mengatur atau mendapatkan nilai bool yang menunjukkan konten dicap sebagai latar belakang.<br/>            Jika nilai true, konten cap diletakkan di bagian bawah.<br/>            Secara default, nilai false, konten cap diletakkan di bagian atas. |
| opasitas | Mendapatkan atau mengatur nilai untuk menunjukkan opasitas cap. Nilainya dari 0.0 hingga 1.0.<br/>            Secara default nilai adalah 1.0. |
| outline_opacity | Mendapatkan atau mengatur nilai untuk menunjukkan opasitas garis luar cap. Nilainya dari 0.0 hingga 1.0.<br/>            Secara default nilai adalah 1.0. |
| outline_width | Mendapatkan atau mengatur nilai lebar garis luar cap.<br/>            Secara default nilai adalah 1.0. |
| rotate | Mengatur atau mengambil rotasi konten stempel sesuai nilai [Rotation](/pdf/python-net/aspose.pdf/rotation/).<br/>            Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan 90 derajat (0, 90, 180, 270 derajat).<br/>            Untuk mengatur sudut arbitrer gunakan properti RotateAngle. <br/>            Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan 90 maka properti Rotate mengembalikan Rotation.None. |
| x_indent | Koordinat stempel horizontal, dimulai dari kiri. |
| y_indent | Koordinat stempel vertikal, dimulai dari bawah. |
| horizontal_alignment | Mengambil atau mengatur perataan Horizontal stempel pada halaman. |
| vertical_alignment | Mengambil atau mengatur perataan vertikal stempel pada halaman. |
| left_margin | Mengambil atau mengatur margin kiri stempel. |
| right_margin | Mengambil atau mengatur margin kanan stempel. |
| bottom_margin | Mengambil atau mengatur margin bawah stempel. |
| top_margin | Mengambil atau mengatur margin atas stempel. |
| zoom_x | Faktor zoom horizontal stempel. Memungkinkan memperbesar/memperkecil stempel secara horizontal. |
| lebar | Lebar yang diinginkan untuk stempel pada halaman. |
| tinggi | Tinggi yang diinginkan untuk stempel pada halaman. |
| zoom_y | Faktor zoom vertikal stempel. Memungkinkan memperbesar/memperkecil stempel secara vertikal. |
| zoom | Faktor zoom stempel. Memungkinkan memperbesar/memperkecil stempel.<br/>            Harap dicatat bahwa pasangan properti ZoomX dan ZoomY memungkinkan mengatur faktor zoom untuk setiap sumbu secara terpisah. <br/>            Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. <br/>            Jika ZoomX dan ZoomY berbeda maka properti Zoom mengembalikan nilai ZoomX. |
| rotate_angle | Mengambil atau mengatur sudut rotasi stempel dalam derajat.<br/>            Properti ini memungkinkan mengatur sudut rotasi arbitrer. |
| pdf_page | Mengambil atau mengatur halaman yang akan digunakan sebagai stempel. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| put(page) | Letakkan stempel pada halaman yang ditentukan. |
| set_stamp_id(value) | Mengatur Id stempel. |
| get_stamp_id() | Mengembalikan ID cap. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

