---
title: "PdfXmpMetadata"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas untuk manipulasi metadata XMP."
type: docs
weight: 380
url: /id/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

Kelas untuk manipulasi metadata XMP.

Tipe PdfXmpMetadata menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfXmpMetadata() | Konstruktor untuk PdfXmpMetadata. |
| PdfXmpMetadata(document) | Menginisialisasi instance baru dari kelas PdfXmpMetadata |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| kunci | Mengambil kunci dari kamus. |
| nilai | Mengambil koleksi nilai dalam kamus. |
| is_fixed_size | Mengembalikan true jika koleksi memiliki ukuran tetap. |
| is_synchronized | Mengembalikan true jika koleksi disinkronkan. |
| sync_root | Mengambil objek sinkronisasi dari koleksi. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(src_file) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_stream) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_doc) | Mengikat dokumen PDF untuk diedit. |
| save(dest_file) | Menyimpan dokumen PDF ke file yang ditentukan. |
| save(dest_stream) | Menyimpan dokumen PDF ke aliran yang ditentukan. |
| add(key, value) | Menambahkan nilai ke metadata XMP. |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | Menambahkan bidang ekstensi ke metadata. |
| add(key, value) | Menambahkan elemen baru ke objek kamus. |
| add(key, value) | Menambahkan bidang ekstensi ke metadata. |
| remove(key) | Menghapus elemen dengan kunci yang ditentukan. |
| remove(key) | Menghapus kunci dari kamus. |
| contains(key) | Memeriksa apakah kamus berisi kunci yang ditentukan. |
| contains(property) | Memeriksa apakah kamus berisi properti yang ditentukan. |
| get_xmp_metadata() | Dapatkan XmpMetadata dari PDF input dalam format XML. |
| get_xmp_metadata(name) | Dapatkan bagian dari XmpMetadata dari pdf input sesuai dengan nama meta. |
| close() | Melepaskan semua sumber daya yang terkait dengan fasad saat ini. |
| register_namespace_uri(prefix, namespace_uri) | Mendaftarkan URI namespace. |
| get_namespace_uri_by_prefix(prefix) | Mendapatkan URI namespace berdasarkan prefiks. |
| get_prefix_by_namespace_uri(namespace_uri) | Mendapatkan prefiks berdasarkan URI namespace. |
| contains_key(key) | Menentukan apakah kamus ini berisi kunci yang ditentukan. |
| try_get_value(key, value) | Mencoba menemukan kunci dalam kamus dan mengambil nilai jika ditemukan. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

