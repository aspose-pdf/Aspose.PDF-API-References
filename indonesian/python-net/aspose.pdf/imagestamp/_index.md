---
title: "ImageStamp"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili stempel grafis."
type: docs
weight: 690
url: /id/python-net/aspose.pdf/imagestamp/
---

## ImageStamp class

Mewakili stempel grafis.

Tipe ImageStamp menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| ImageStamp(image) | Menginisialisasi sebuah instance baru dari kelas ImageStamp |
| ImageStamp(file_name) | Menginisialisasi sebuah instance baru dari kelas ImageStamp |
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
| lebar | Mendapatkan atau mengatur lebar gambar. Mengatur properti ini memungkinkan skala gambar secara horizontal. |
| tinggi | Mendapatkan atau mengatur tinggi gambar. Mengatur gambar ini memungkinkan skala gambar secara vertikal. |
| zoom_y | Faktor zoom vertikal stempel. Memungkinkan memperbesar/memperkecil stempel secara vertikal. |
| zoom | Faktor zoom stempel. Memungkinkan memperbesar/memperkecil stempel.<br/>            Harap dicatat bahwa pasangan properti ZoomX dan ZoomY memungkinkan mengatur faktor zoom untuk setiap sumbu secara terpisah. <br/>            Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. <br/>            Jika ZoomX dan ZoomY berbeda maka properti Zoom mengembalikan nilai ZoomX. |
| rotate_angle | Mengambil atau mengatur sudut rotasi stempel dalam derajat.<br/>            Properti ini memungkinkan mengatur sudut rotasi arbitrer. |
| image | Mendapatkan aliran gambar yang digunakan untuk stamping. |
| kualitas | Mendapatkan atau mengatur kualitas stempel gambar dalam persen. Nilai yang valid adalah 0..100%. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| put(page) | Menambahkan stempel grafis pada halaman. |
| set_stamp_id(value) | Mengatur Id stempel. |
| get_stamp_id() | Mengembalikan ID cap. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

