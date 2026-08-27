---
title: "PaginationArtifact"
linktitle: "PaginationArtifact"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas dasar abstrak untuk artefak paginasi dalam sebuah dokumen."
type: docs
weight: 3460
url: /id/java/com.aspose.pdf/paginationartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public abstract class PaginationArtifact extends Artifact
```

Mewakili kelas dasar abstrak untuk artefak paginasi dalam sebuah dokumen.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEndPage](#getEndPage--) | Mendapatkan atau mengatur nomor halaman akhir untuk artifact. Nilai harus lebih besar dari atau sama dengan 0. Jika nilai kurang dari 0 diatur, akan disesuaikan menjadi 0. Nilai default 0 berarti tidak ada batas halaman akhir. |
| [getStartPage](#getStartPage--) | Mendapatkan atau mengatur nomor halaman awal untuk artifact. Nilai harus lebih besar dari atau sama dengan 1. Jika nilai kurang dari 1 diatur, akan disesuaikan menjadi 1. |
| [getSubset](#getSubset--) | Mendapatkan atau mengatur subset halaman yang berlaku untuk artifact (mis., semua halaman, halaman genap, halaman ganjil). |
| [setEndPage](#setEndPage-int-) | Mendapatkan atau mengatur nomor halaman akhir untuk artifact. Nilai harus lebih besar dari atau sama dengan 0. Jika nilai kurang dari 0 diatur, akan disesuaikan menjadi 0. Nilai default 0 berarti tidak ada batas halaman akhir. |
| [setStartPage](#setStartPage-int-) | Mendapatkan atau mengatur nomor halaman awal untuk artifact. Nilai harus lebih besar dari atau sama dengan 1. Jika nilai kurang dari 1 diatur, akan disesuaikan menjadi 1. |
| [setSubset](#setSubset-int-) | Mendapatkan atau mengatur subset halaman yang berlaku untuk artifact (mis., semua halaman, halaman genap, halaman ganjil). |

### getEndPage {#getEndPage--}
```
public final int getEndPage()
```

Mendapatkan atau mengatur nomor halaman akhir untuk artifact. Nilai harus lebih besar dari atau sama dengan 0. Jika nilai kurang dari 0 diatur, akan disesuaikan menjadi 0. Nilai default 0 berarti tidak ada batas halaman akhir.

**Returns:**
nilai int

### getStartPage {#getStartPage--}
```
public final int getStartPage()
```

Mendapatkan atau mengatur nomor halaman awal untuk artifact. Nilai harus lebih besar dari atau sama dengan 1. Jika nilai kurang dari 1 diatur, akan disesuaikan menjadi 1.

**Returns:**
nilai int

### getSubset {#getSubset--}
```
public final int getSubset()
```

Mendapatkan atau mengatur subset halaman yang berlaku untuk artifact (mis., semua halaman, halaman genap, halaman ganjil).

**Returns:**
nilai int

### setEndPage {#setEndPage-int-}
```
public final void setEndPage(int value)
```

Mendapatkan atau mengatur nomor halaman akhir untuk artifact. Nilai harus lebih besar dari atau sama dengan 0. Jika nilai kurang dari 0 diatur, akan disesuaikan menjadi 0. Nilai default 0 berarti tidak ada batas halaman akhir.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setStartPage {#setStartPage-int-}
```
public final void setStartPage(int value)
```

Mendapatkan atau mengatur nomor halaman awal untuk artifact. Nilai harus lebih besar dari atau sama dengan 1. Jika nilai kurang dari 1 diatur, akan disesuaikan menjadi 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setSubset {#setSubset-int-}
```
public final void setSubset(int value)
```

Mendapatkan atau mengatur subset halaman yang berlaku untuk artifact (mis., semua halaman, halaman genap, halaman ganjil).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
