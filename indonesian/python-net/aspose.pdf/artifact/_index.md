---
title: "Artifact"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas mewakili objek PDF Artifact."
type: docs
weight: 30
url: /id/python-net/aspose.pdf/artifact/
---

## Artifact class

Kelas mewakili objek PDF Artifact.

Tipe Artifact menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| Artifact(type, sub_type) | Menginisialisasi instance baru dari kelas Artifact |
| Artifact(type, sub_type) | Menginisialisasi instance baru dari kelas Artifact |
## Properti
| Nama | Deskripsi |
| :- | :- |
| custom_type | Mendapatkan nama tipe artifact. Dapat digunakan jika tipe artifact tidak standar. |
| custom_subtype | Mendapatkan nama subtipe artifact. Dapat digunakan jika subtipe artifact bukan subtipe standar. |
| type | Mendapatkan tipe artifact. |
| subtype | Mendapatkan subtipe artifact. Jika artifact memiliki subtipe non-standar, nama subtipe dapat dibaca melalui CustomSubtype. |
| konten | Mendapatkan koleksi operator internal artifact. |
| formulir | Mendapatkan XForm dari artifact (jika XForm digunakan). |
| rectangle | Mendapatkan persegi panjang artifact. |
| position | Mendapatkan atau mengatur posisi artifact.<br/>            Jika properti ini ditentukan, maka margin dan perataan diabaikan. |
| right_margin | Margin kanan artifact. <br/>            Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| left_margin | Margin kiri artifact. <br/>            Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| top_margin | Margin atas artifact. <br/>            Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| bottom_margin | Margin bawah artifact. <br/>            Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| artifact_horizontal_alignment | Perataan horizontal artifact. <br/>            Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| artifact_vertical_alignment | Penjajaran vertikal artefak. <br/>            Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| rotation | Mendapatkan atau mengatur sudut rotasi artefak. |
| text | Mendapatkan teks artefak. |
| image | Mendapatkan gambar artefak (jika ada). |
| opasitas | Mendapatkan atau mengatur opasitas artefak. Nilai yang mungkin berada dalam rentang 0..1. |
| baris | Baris teks multiline artefak. |
| text_state | Status teks untuk teks artefak. |
| is_background | Jika true, Artefak ditempatkan di belakang konten halaman. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| set_image(image_stream) | Mengatur gambar artefak. |
| set_image(image_name) | Mengatur gambar artefak. |
| set_text(formatted_text) | Mengatur teks artefak. |
| set_text_and_state(text, text_state) | Mengatur teks dan properti teks artefak. |
| set_lines_and_state(text, text_state) | Mengatur teks dan properti teks artefak. Memungkinkan untuk menentukan beberapa baris. |
| set_pdf_page(page) | Mengatur halaman PDF yang ditempatkan pada halaman dokumen sebagai artefak. |
| get_value(name) | Mendapatkan nilai khusus artefak. |
| set_value(name, value) | Mengatur nilai khusus artefak. |
| remove_value(name) | Hapus nilai khusus dari artefak. |
| begin_updates() | Mulai pembaruan tertunda. Gunakan fitur ini jika Anda perlu melakukan beberapa perubahan pada artefak yang sama untuk meningkatkan kinerja. <br/>            Biasanya operator artefak diubah kapan saja ketika properti artefak diubah. Hal ini menyebabkan perubahan isi halaman<br/>            setiap kali artefak diubah. Untuk menghindari efek ini, letakkan semua pembaruan artefak di antara panggilan StartUpdates/SaveUpdates.<br/>            Ini memungkinkan mengubah isi halaman hanya sekali. |
| save_updates() | Menyimpan semua pembaruan dalam artefak yang dibuat setelah pemanggilan BeginUpdates(). |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

