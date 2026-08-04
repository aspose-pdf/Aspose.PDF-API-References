---
title: "XYZExplicitDestination"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat (kiri, atas) diposisikan pada sudut kiri atas jendela dan isi halaman diperbesar dengan faktor zoom. Nilai null untuk salah satu parameter kiri, atas, atau zoom menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tidak berubah. Nilai zoom 0 memiliki arti yang sama dengan nilai null."
type: docs
weight: 880
url: /id/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat (kiri, atas) diposisikan pada sudut kiri atas jendela dan isi halaman diperbesar dengan faktor zoom. Nilai null untuk salah satu parameter kiri, atas, atau zoom menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tidak berubah. Nilai zoom 0 memiliki arti yang sama dengan nilai null.

Tipe XYZExplicitDestination menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | Menginisialisasi instance baru dari kelas XYZExplicitDestination |
| XYZExplicitDestination(document, page_number, left, top, zoom) | Menginisialisasi instance baru dari kelas XYZExplicitDestination |
| XYZExplicitDestination(page_number, left, top, zoom) | Menginisialisasi instance baru dari kelas XYZExplicitDestination |
## Properti
| Nama | Deskripsi |
| :- | :- |
| halaman | Mendapatkan objek halaman tujuan |
| page_number | Mendapatkan nomor halaman tujuan |
| left | Mendapatkan koordinat horizontal kiri dari sudut kiri-atas jendela. |
| top | Mendapatkan koordinat vertikal atas dari sudut kiri-atas jendela. |
| zoom | Mendapatkan faktor zoom. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | Buat destintion ke lokasi yang ditentukan pada halaman dengan mempertimbangkan rotasi halaman jika diperlukan. |
| create_destination(page, type, values) | Membuat instance dari kelas turunan ExplicitDestination. |
| create_destination(doc, page_number, type, values) | Membuat instance dari kelas turunan ExplicitDestination. |
| create_destination(page_number, type, values) | Membuat instance dari kelas turunan ExplicitDestination. |
| create_destination_to_upper_left_corner(page, zoom) | Buat destionation ke sudut kiri atas halaman yang ditentukan. |
| create_destination_to_upper_left_corner(page) | Buat destionation ke sudut kiri atas halaman yang ditentukan. |
| to_string() | Mengonversi status objek menjadi nilai string. Contoh: "1 XYZ 100 200 3". |

### Lihat Juga

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

