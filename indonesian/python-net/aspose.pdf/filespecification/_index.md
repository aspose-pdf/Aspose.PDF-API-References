---
title: "FileSpecification"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas yang mewakili file tersemat."
type: docs
weight: 360
url: /id/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

Kelas yang mewakili file tersemat.

Tipe FileSpecification menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| FileSpecification(file) | Menginisialisasi sebuah instance baru dari kelas FileSpecification |
| FileSpecification(stream, name) | Menginisialisasi sebuah instance baru dari kelas FileSpecification |
| FileSpecification(file, description) | Menginisialisasi sebuah instance baru dari kelas FileSpecification |
| FileSpecification(stream, name, description) | Menginisialisasi sebuah instance baru dari kelas FileSpecification |
| FileSpecification(file_name, annot) | Menginisialisasi sebuah instance baru dari kelas FileSpecification |
| FileSpecification() | Buat spesifikasi file kosong baru. |
## Properti
| Nama | Deskripsi |
| :- | :- |
| encoding | Mendapatkan atau mengatur format enkoding.<br/>            Nilai yang mungkin: Zip - file dikompresi dengan ZIP, <br/>            None - file tidak dikompresi. |
| include_contents | Jika true, konten file akan disertakan dalam spesifikasi file. |
| encrypted_payload | Mendapatkan payload terenkripsi. |
| deskripsi | Mendapatkan atau mengatur teks yang terkait dengan spesifikasi file. |
| af_relationship | Hubungan file terkait. |
| stream_contents | Mendapatkan isi file sebagai aliran. <br/>            Isi tidak dimuat ke memori yang memungkinkan mengurangi penggunaan memori.<br/>            Namun aliran ini tidak mendukung penempatan posisi dan properti Length. Jika Anda membutuhkan fitur ini, silakan gunakan properti Contents sebagai gantinya. |
| konten | Mendapatkan atau mengatur isi file. <br/>            Properti ini mengembalikan data yang dimuat ke memori yang dapat menyebabkan pengecualian Out of memory untuk data besar.<br/>            Untuk mengurangi penggunaan memori, silakan gunakan StreamContents. |
| params | Mendapatkan parameter file. |
| mime_type | Mendapatkan subtipe dari file tersemat |
| name | Mendapatkan atau mengatur nama spesifikasi file. |
| unicode_name | Mendapatkan atau mengatur nama unicode spesifikasi file. |
| file_system | Mendapatkan atau mengatur nama sistem file. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| get_value(key) | Mendapatkan parameter khusus aplikasi. |
| set_value(key, value) | Mengatur parameter khusus aplikasi. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

