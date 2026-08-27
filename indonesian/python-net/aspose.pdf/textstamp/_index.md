---
title: "TextStamp"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili stempel teks."
type: docs
weight: 1550
url: /id/python-net/aspose.pdf/textstamp/
---

## TextStamp class

Mewakili stempel teks.

Tipe TextStamp menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| TextStamp(value) | Menginisialisasi instance baru dari kelas TextStamp |
| TextStamp(value, text_state) | Menginisialisasi instance baru dari kelas TextStamp |
| TextStamp(formatted_text) | Menginisialisasi instance baru dari kelas TextStamp |
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
| draw | Properti ini menentukan bagaimana stempel digambar pada halaman. Jika Draw = true, stempel digambar sebagai operator grafis dan jika draw = false maka stempel digambar sebagai teks. |
| treat_y_indent_as_base_line | Mendefinisikan asal koordinat untuk menempatkan teks.<br/>            Jika TreatYIndentAsBaseLine = true (default ketika Draw = true) nilai YIndent akan diperlakukan sebagai garis dasar teks.<br/>            Jika TreatYIndentAsBaseLine = false (default ketika Draw = false) nilai YIndent akan diperlakukan sebagai bagian bawah (garis turun) teks. |
| word_wrap | Mendefinisikan pembungkus kata. Jika properti ini diatur ke true dan nilai Width ditentukan, teks akan dipisah menjadi beberapa baris agar sesuai dengan lebar yang ditentukan. Nilai default: false. |
| justify | Mendefinisikan perataan teks. Jika properti ini diatur ke true, kedua tepi kiri dan kanan teks akan diratakan. Nilai default: false. |
| scale | Mendefinisikan skala teks. Jika properti ini diatur ke true dan nilai Width ditentukan, teks akan diskalakan agar sesuai dengan lebar yang ditentukan. |
| value | Mendapatkan atau mengatur nilai string yang digunakan sebagai stempel pada halaman. |
| text_state | Mendapatkan properti teks dari stempel. Lihat [text_state](/pdf/python-net/aspose.pdf/textstamp/) untuk detail. |
| text_alignment | Perataan teks di dalam stempel. |
| max_row_width | Tinggi baris maksimum untuk opsi WordWrap. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| put(page) | Menambahkan stempel teks pada halaman. |
| set_stamp_id(value) | Mengatur Id stempel. |
| get_stamp_id() | Mengembalikan ID cap. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

