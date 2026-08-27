---
title: "BatesNArtifact"
linktitle: "BatesNArtifact"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas menjelaskan artefak Penomoran Bates."
type: docs
weight: 290
url: /id/java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

Kelas menjelaskan artefak Penomoran Bates.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | Menginisialisasi instance baru dari kelas {@link BatesNArtifact}. Konstruktor ini bersifat internal dan membuat instance artefak header dengan nilai default. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | Mendapatkan atau mengatur jumlah digit untuk penomoran Bates. Nilainya harus antara 3 dan 15 inklusif. Jika nilai yang diberikan kurang dari 3, akan disesuaikan menjadi 3. Jika nilai yang diberikan lebih dari 15, akan disesuaikan menjadi 15. Nilai default adalah 6. |
| [getPrefix](#getPrefix--) | Mendapatkan atau mengatur awalan yang akan ditambahkan ke nomor Bates. |
| [getStartNumber](#getStartNumber--) | Mendapatkan atau mengatur nomor awal untuk penomoran Bates. Nilainya harus lebih besar atau sama dengan 1. Jika nilai yang diberikan kurang dari 1, akan disesuaikan menjadi 1. |
| [getSuffix](#getSuffix--) | Mendapatkan atau mengatur akhiran yang akan ditambahkan ke nomor Bates. |
| [setNumberOfDigits](#setNumberOfDigits-int-) | Mendapatkan atau mengatur jumlah digit untuk penomoran Bates. Nilainya harus antara 3 dan 15 inklusif. Jika nilai yang diberikan kurang dari 3, akan disesuaikan menjadi 3. Jika nilai yang diberikan lebih dari 15, akan disesuaikan menjadi 15. Nilai default adalah 6. |
| [setPrefix](#setPrefix-java.lang.String-) | Mendapatkan atau mengatur awalan yang akan ditambahkan ke nomor Bates. |
| [setStartNumber](#setStartNumber-int-) | Mendapatkan atau mengatur nomor awal untuk penomoran Bates. Nilainya harus lebih besar atau sama dengan 1. Jika nilai yang diberikan kurang dari 1, akan disesuaikan menjadi 1. |
| [setSuffix](#setSuffix-java.lang.String-) | Mendapatkan atau mengatur akhiran yang akan ditambahkan ke nomor Bates. |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

Menginisialisasi instance baru dari kelas {@link BatesNArtifact}. Konstruktor ini bersifat internal dan membuat instance artefak header dengan nilai default.

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

Mendapatkan atau mengatur jumlah digit untuk penomoran Bates. Nilainya harus antara 3 dan 15 inklusif. Jika nilai yang diberikan kurang dari 3, akan disesuaikan menjadi 3. Jika nilai yang diberikan lebih dari 15, akan disesuaikan menjadi 15. Nilai default adalah 6.

**Returns:**
nilai int

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

Mendapatkan atau mengatur awalan yang akan ditambahkan ke nomor Bates.

**Returns:**
nilai String

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

Mendapatkan atau mengatur nomor awal untuk penomoran Bates. Nilainya harus lebih besar atau sama dengan 1. Jika nilai yang diberikan kurang dari 1, akan disesuaikan menjadi 1.

**Returns:**
nilai int

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

Mendapatkan atau mengatur akhiran yang akan ditambahkan ke nomor Bates.

**Returns:**
nilai String

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

Mendapatkan atau mengatur jumlah digit untuk penomoran Bates. Nilainya harus antara 3 dan 15 inklusif. Jika nilai yang diberikan kurang dari 3, akan disesuaikan menjadi 3. Jika nilai yang diberikan lebih dari 15, akan disesuaikan menjadi 15. Nilai default adalah 6.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setPrefix {#setPrefix-java.lang.String-}
Mendapatkan atau mengatur awalan yang akan ditambahkan ke nomor Bates.

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

Mendapatkan atau mengatur nomor awal untuk penomoran Bates. Nilainya harus lebih besar atau sama dengan 1. Jika nilai yang diberikan kurang dari 1, akan disesuaikan menjadi 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setSuffix {#setSuffix-java.lang.String-}
Mendapatkan atau mengatur akhiran yang akan ditambahkan ke nomor Bates.
