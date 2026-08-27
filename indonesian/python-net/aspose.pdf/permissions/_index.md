---
title: "Izin"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Enum ini mewakili izin pengguna untuk PDF."
type: docs
weight: 6560
url: /id/python-net/aspose.pdf/permissions/
---

## Permissions enumeration

Enum ini mewakili izin pengguna untuk PDF.

## Members
| Nama anggota | Deskripsi |
| :- | :- |
| PRINT_DOCUMENT | (Penangani keamanan revisi 2) Mencetak dokumen.<br/>            (Penangani keamanan revisi 3 atau lebih) Mencetak dokumen <br/>            (mungkin tidak pada tingkat kualitas tertinggi, <br/>            tergantung apakah [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/) juga diatur). |
| MODIFY_CONTENT | Memodifikasi isi dokumen dengan operasi lain <br/>            selain yang dikendalikan oleh  [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/), <br/>            [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/), dan 11. |
| EXTRACT_CONTENT | (Penangani keamanan revisi 2) Menyalin atau mengekstrak <br/>            teks dan grafik dari dokumen, termasuk mengekstrak <br/>            teks dan grafik (untuk mendukung aksesibilitas bagi pengguna <br/>            dengan disabilitas atau untuk tujuan lain).<br/>            (Penangani keamanan revisi 3 atau lebih) Menyalin atau mengekstrak <br/>            teks dan grafik dari dokumen dengan operasi <br/>            selain yang dikendalikan oleh [EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/). |
| MODIFY_TEXT_ANNOTATIONS | Menambahkan atau memodifikasi anotasi teks, mengisi bidang formulir interaktif, <br/>            dan, jika [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) juga diatur, membuat atau memodifikasi bidang formulir interaktif <br/>            (termasuk bidang tanda tangan). |
| FILL_FORM | (Penangani keamanan revisi 3 atau lebih) Mengisi bidang formulir interaktif yang ada <br/>            (termasuk bidang tanda tangan), bahkan jika <br/>            [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) tidak diatur. |
| EXTRACT_CONTENT_WITH_DISABILITIES | (Penangani keamanan revisi 3 atau lebih) Mengekstrak teks dan <br/>            grafik (untuk mendukung aksesibilitas bagi pengguna dengan disabilitas <br/>            atau untuk tujuan lain). |
| ASSEMBLE_DOCUMENT | (Penangani keamanan revisi 3 atau lebih) Menyusun dokumen <br/>            (menyisipkan, memutar, atau menghapus halaman serta membuat bookmark atau gambar miniatur <br/>            ), bahkan jika [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) tidak diatur. |
| PRINTING_QUALITY | (Penangani keamanan revisi 3 atau lebih) Mencetak dokumen ke <br/>            representasi yang dapat menghasilkan salinan digital yang setia dari konten PDF <br/>            . Ketika bit ini tidak diatur (dan bit 3 diatur), <br/>            pencetakan dibatasi pada representasi tingkat rendah dari tampilan, <br/>            mungkin dengan kualitas yang menurun. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

