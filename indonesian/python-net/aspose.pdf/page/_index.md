---
title: "Page"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas yang merepresentasikan halaman dokumen PDF."
type: docs
weight: 1080
url: /id/python-net/aspose.pdf/page/
---

## Page class

Kelas yang merepresentasikan halaman dokumen PDF.

Tipe Page menampilkan anggota-anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| is_add_paragraphs_after_last | Mendapatkan atau mengatur penambahan paragraf setelah paragraf terakhir pada halaman |
| background_image | Mendapatkan atau mengatur gambar latar belakang untuk halaman (hanya untuk generator, tidak diisi saat membaca dokumen). |
| toc_info | Mendapatkan atau mengatur informasi daftar isi. |
| header | Mendapatkan atau mengatur header halaman. |
| lapisan | Mendapatkan atau mengatur koleksi lapisan. |
| footer | Mendapatkan atau mengatur footer halaman. |
| paragraphs | Mendapatkan paragraf. |
| page_info | Mendapatkan atau mengatur info halaman (hanya untuk generator, tidak diisi saat membaca dokumen). |
| rekt | Mendapatkan atau mengatur persegi panjang halaman.<br/>            Untuk mendapatkan: kotak potong halaman dikembalikan jika ditentukan, jika tidak kotak media halaman dikembalikan.<br/>            Untuk mengatur: kotak media halaman selalu diatur.<br/>            Harap perhatikan bahwa properti ini tidak mempertimbangkan rotasi halaman. Untuk mendapatkan persegi panjang halaman dengan mempertimbangkan rotasi, gunakan ActualRect. |
| color_type | Mengatur tipe warna halaman berdasarkan informasi yang diperoleh dari operator SetColor,<br/>            gambar, dan formulir. |
| note_line_style | Mendapatkan atau mengatur gaya garis untuk catatan.(hanya untuk generator, tidak diisi saat membaca dokumen) |
| tab_order | Mendapatkan atau mengatur urutan tab halaman. <br/>            Nilai yang mungkin: Baris, Kolom. Default, Manual |
| durasi | Mendapatkan atau mengatur durasi tampilan halaman. Ini adalah waktu dalam detik yang halaman akan ditampilkan selama presentasi.<br/>            Mengembalikan -1 jika durasi tidak didefinisikan. |
| contents | Mendapatkan koleksi operator dalam aliran konten halaman.<br/>            [OperatorCollection](/pdf/python-net/aspose.pdf/operatorcollection/) |
| grup | Mendapatkan atau mengatur kelas atribut grup yang menentukan atribut grup halaman untuk digunakan dalam model pencitraan transparan. |
| annotations | Mendapatkan koleksi anotasi halaman.<br/>            [annotations](/pdf/python-net/aspose.pdf/page/) |
| resources | Mendapatkan sumber daya halaman. Objek Resources berisi koleksi gambar, formulir, dan font.<br/>            [resources](/pdf/python-net/aspose.pdf/page/) |
| putar | Mendapatkan atau mengatur rotasi halaman. |
| trim_box | Mendapatkan atau mengatur trim box halaman. |
| art_box | Mendapatkan atau mengatur art box halaman. |
| bleed_box | Mendapatkan atau mengatur kotak bleed halaman. |
| crop_box | Mendapatkan atau mengatur kotak crop halaman. |
| media_box | Mendapatkan atau mengatur kotak media halaman. |
| angka | Dapatkan nomor halaman. |
| rotation_matrix | Mendapatkan matriks transformasi untuk halaman. |
| background | Mendapatkan atau mengatur warna latar belakang halaman. |
| watermark | Mendapatkan atau mengatur watermark halaman. |
| artifacts | Mendapatkan koleksi artefak pada halaman. |
| aksi | Mendapatkan koleksi properti halaman. |
| fields_in_tab_order | Mendapatkan daftar objek Field dalam urutan Tab pada halaman ini. |
| user_unit | Mendapatkan atau mengatur nilai UserUnit. Angka positif yang memberikan ukuran satuan ruang pengguna default, dalam kelipatan 1 ⁄ 72 inci.<br/>            Nilai default adalah 1. Silakan set nilai nol atau negatif untuk menghapus entri ini pada halaman. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| send_to(device, output) | Mengirim halaman untuk diproses dengan perangkat halaman yang diberikan. |
| send_to(device, output_file_name) | Mengirim halaman untuk diproses dengan perangkat halaman yang diberikan. |
| accept(visitor) | Menerima objek pengunjung [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) yang menyediakan fungsionalitas untuk bekerja dengan anotasi. |
| accept(visitor) | Menerima objek pengunjung [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) yang menyediakan fungsionalitas untuk bekerja dengan objek teks. |
| accept(visitor) | Menerima objek pengunjung [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) yang menyediakan fungsionalitas untuk bekerja dengan objek penempatan gambar. |
| accept(visitor) | Menerima objek pengunjung [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) yang menyediakan fungsionalitas untuk bekerja dengan objek teks. |
| add_image(image_stream, image_rect) | Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| add_image(hocr, image_stream, image_rect) | Menambahkan gambar yang dapat dicari ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| add_image(image_stream, image_rect, image_width, image_height, save_image_proportions) | Menambahkan gambar pada halaman dan menempatkannya tergantung pada posisi persegi panjang gambar. |
| add_image(image_path, rectangle) | Menambahkan gambar yang dapat dicari ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| is_blank(fill_threshold_factor) | Mendapatkan flag apakah halaman kosong atau tidak. |
| get_page_rect(consider_rotation) | Mengembalikan persegi panjang halaman sesuai dengan CropBox-nya (atau MediaBox jika CropBox null). |
| calculate_content_b_box() | Menghitung nilai bbox - persegi panjang yang berisi konten tanpa margin yang terlihat. |
| rotation_to_int(rotation) | Menerjemahkan anggota enumerasi rotasi menjadi nilai integer. |
| int_to_rotation(rotation) | Menerjemahkan nilai integer menjadi anggota enumerasi rotasi yang sesuai. |
| add_stamp(stamp) | Menempatkan stempel ke halaman. Stempel dapat berupa nomor halaman, gambar, atau teks sederhana, misalnya logo. |
| flatten() | Menghapus semua bidang yang terletak di halaman dan menempatkan nilai mereka sebagai gantinya. |
| set_page_size(width, height) | Mengatur ukuran halaman untuk halaman. |
| make_grayscale() | Mengonversi halaman menjadi skala abu-abu. |
| free_memory() | Menghapus data cache |
| get_notifications() | Mengembalikan notifikasi tentang operasi internal dengan konten halaman. (Saat ini hanya notifikasi tentang peristiwa paragraf dalam skenario penambahan teks yang didukung.) |
| as_byte_array(resolution) | Mengonversi halaman saat ini menjadi bitmap dan kemudian mengembalikan array byte. |
| as_xml() | Mengonversi halaman saat ini menjadi xml dengan encoding utf8. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

