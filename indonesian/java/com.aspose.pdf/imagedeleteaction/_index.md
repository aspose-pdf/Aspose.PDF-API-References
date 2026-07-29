---
title: "ImageDeleteAction"
linktitle: "ImageDeleteAction"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Aksi yang dilakukan dengan objek gambar ketika gambar dihapus dari koleksi. Jika objek gambar dihapus"
type: docs
weight: 2290
url: /id/java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.Enum, com.aspose.pdf.ImageDeleteAction

```
public final class ImageDeleteAction extends com.aspose.ms.System.Enum
```

Aksi yang dilakukan dengan objek gambar ketika gambar dihapus dari koleksi. Jika objek gambar dihapus

## Fields

| Field | Deskripsi |
| --- | --- |
| [Check](#Check) | Gambar akan dihapus dari koleksi dan objek gambar akan dihapus hanya jika tidak ada referensi lain ke gambar tersebut dari halaman lain. Ini mungkin memerlukan lebih banyak waktu dibandingkan dengan opsi ForceDelete. |
| [ForceDelete](#ForceDelete) | Gambar akan dihapus dari koleksi dan objek gambar akan dihapus dari dokumen. Jika ada referensi lain pada objek yang sama, dokumen mungkin menjadi rusak. |
| [KeepContents](#KeepContents) | Gambar akan dihapus dari koleksi. Jika konten halaman berisi referensi ke gambar, referensi tersebut tidak akan dihapus. Dokumen mungkin menjadi tidak valid. |
| [None](#None) | Gambar akan dihapus dari koleksi dan dari konten halaman, tetapi objek gambar tidak akan dihapus. Ukuran file tidak akan berkurang. |

### Check {#Check}
```
public static final int Check
```

Gambar akan dihapus dari koleksi dan objek gambar akan dihapus hanya jika tidak ada referensi lain ke gambar tersebut dari halaman lain. Ini mungkin memerlukan lebih banyak waktu dibandingkan dengan opsi ForceDelete.

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```

Gambar akan dihapus dari koleksi dan objek gambar akan dihapus dari dokumen. Jika ada referensi lain pada objek yang sama, dokumen mungkin menjadi rusak.

### KeepContents {#KeepContents}
```
public static final int KeepContents
```

Gambar akan dihapus dari koleksi. Jika konten halaman berisi referensi ke gambar, referensi tersebut tidak akan dihapus. Dokumen mungkin menjadi tidak valid.

### None {#None}
```
public static final int None
```

Gambar akan dihapus dari koleksi dan dari konten halaman, tetapi objek gambar tidak akan dihapus. Ukuran file tidak akan berkurang.
