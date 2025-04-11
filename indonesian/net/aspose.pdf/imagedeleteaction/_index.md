---
title: Enum ImageDeleteAction
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.ImageDeleteAction. Tindakan yang dilakukan dengan objek gambar ketika gambar dihapus dari koleksi. Jika objek gambar dihapus
type: docs
weight: 5870
url: /id/net/aspose.pdf/imagedeleteaction/
---
## Enumerasi ImageDeleteAction

Tindakan yang dilakukan dengan objek gambar ketika gambar dihapus dari koleksi. Jika objek gambar dihapus

```csharp
public enum ImageDeleteAction
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| KeepContents | `0` | Gambar akan dihapus dari koleksi. Jika konten halaman mengandung referensi ke gambar, referensi tersebut tidak akan dihapus. Dokumen mungkin menjadi tidak valid. |
| None | `1` | Gambar akan dihapus dari koleksi dan dari konten halaman, tetapi objek gambar tidak akan dihapus. Ukuran file tidak akan berkurang. |
| ForceDelete | `2` | Gambar akan dihapus dari koleksi dan objek gambar akan dihapus dari dokumen. Jika ada referensi lain pada objek yang sama, dokumen mungkin menjadi rusak. |
| Check | `3` | Gambar akan dihapus dari koleksi dan objek gambar akan dihapus hanya jika tidak ada referensi lain ke gambar dari halaman lain. Ini mungkin memerlukan lebih banyak waktu dibandingkan dengan opsi ForceDelete. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)