---
title: "ImageDeleteAction"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Aksi yang dilakukan dengan objek gambar ketika gambar dihapus dari koleksi. Jika objek gambar dihapus"
type: docs
weight: 6450
url: /id/python-net/aspose.pdf/imagedeleteaction/
---

## ImageDeleteAction enumeration

Aksi yang dilakukan dengan objek gambar ketika gambar dihapus dari koleksi. Jika objek gambar dihapus

## Members
| Nama anggota | Deskripsi |
| :- | :- |
| KEEP_CONTENTS | Gambar akan dihapus dari koleksi. Jika konten halaman berisi referensi ke gambar, referensi tersebut tidak akan dihapus. Dokumen mungkin menjadi tidak valid. |
| NONE | Gambar akan dihapus dari koleksi dan dari konten halaman, tetapi objek gambar tidak akan dihapus. Ukuran file tidak akan berkurang. |
| FORCE_DELETE | Gambar akan dihapus dari koleksi dan objek gambar akan dihapus dari dokumen. Jika ada referensi lain pada objek yang sama, dokumen mungkin rusak. |
| CHECK | Gambar akan dihapus dari koleksi dan objek gambar akan dihapus hanya jika tidak ada referensi lain ke gambar dari halaman lain. Hal ini mungkin memerlukan lebih banyak waktu dibandingkan opsi ForceDelete. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

