---
title: "Enum ImageDeleteAction"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.ImageDeleteAction enum. Aksi yang dilakukan pada objek gambar ketika gambar dihapus dari koleksi. Jika objek gambar dihapus"
type: docs
weight: 6000
url: /id/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction enumeration

Aksi yang dilakukan pada objek gambar ketika gambar dihapus dari koleksi. Jika objek gambar dihapus

```csharp
public enum ImageDeleteAction
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| KeepContents | `0` | Gambar akan dihapus dari koleksi. Jika konten Page berisi referensi ke gambar, referensi tersebut tidak akan dihapus. Document mungkin menjadi tidak valid. |
| None | `1` | Gambar akan dihapus dari koleksi dan dari konten halaman, tetapi objek gambar tidak akan dihapus. Ukuran file tidak akan berkurang. |
| ForceDelete | `2` | Gambar akan dihapus dari koleksi dan objek gambar akan dihapus dari dokumen. Jika referensi lain pada objek yang sama ada, dokumen mungkin rusak. |
| Check | `3` | Gambar akan dihapus dari koleksi dan objek gambar akan dihapus hanya jika tidak ada referensi lain ke gambar dari halaman lain. Ini mungkin memerlukan lebih banyak waktu dibandingkan opsi ForceDelete. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


