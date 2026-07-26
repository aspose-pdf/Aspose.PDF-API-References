---
title: "FileParams"
linktitle: "FileParams"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mendefinisikan kamus parameter file tersemat yang harus berisi informasi tambahan khusus file."
type: docs
weight: 1490
url: /id/java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileParams

```
public final class FileParams extends Object
```

Mendefinisikan kamus parameter file tersemat yang harus berisi informasi tambahan khusus file.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FileParams](#FileParams-com.aspose.pdf.FileSpecification-) | Konstruktor untuk kelas FileParams. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCheckSum](#getCheckSum--) | String 16-byte yang merupakan checksum dari byte file tersemat yang tidak terkompresi. Checksum dihitung dengan menerapkan algoritma MD5 standar pada byte aliran file tersemat. |
| [getCreationDate](#getCreationDate--) | Dapatkan tanggal dan waktu saat file tersemat dibuat. |
| [getModDate](#getModDate--) | Dapatkan tanggal dan waktu saat file tersemat terakhir dimodifikasi. |
| [getSize](#getSize--) | Ukuran file tersemat yang tidak terkompresi, dalam byte. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Atur tanggal dan waktu saat file tersemat dibuat. |
| [setModDate](#setModDate-java.util.Date-) | Atur tanggal dan waktu saat file tersemat terakhir dimodifikasi. |

### FileParams {#FileParams-com.aspose.pdf.FileSpecification-}
Konstruktor untuk kelas FileParams.

### getCheckSum {#getCheckSum--}
```
public String getCheckSum()
```

String 16-byte yang merupakan checksum dari byte file tersemat yang tidak terkompresi. Checksum dihitung dengan menerapkan algoritma MD5 standar pada byte aliran file tersemat.

**Returns:**
nilai String

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Dapatkan tanggal dan waktu saat file tersemat dibuat.

**Returns:**
Objek Date

### getModDate {#getModDate--}
```
public Date getModDate()
```

Dapatkan tanggal dan waktu saat file tersemat terakhir dimodifikasi.

**Returns:**
Objek Date

### getSize {#getSize--}
```
public int getSize()
```

Ukuran file tersemat yang tidak terkompresi, dalam byte.

**Returns:**
nilai int

### setCreationDate {#setCreationDate-java.util.Date-}
Atur tanggal dan waktu saat file tersemat dibuat.

### setModDate {#setModDate-java.util.Date-}
Atur tanggal dan waktu saat file tersemat terakhir dimodifikasi.
