---
title: "ContentsAppender"
linktitle: "ContentsAppender"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Melakukan modifikasi konten hanya dalam mode APPEND. mode ini memungkinkan menghindari parsing konten yang tidak diperlukan dan berat sebelum perubahan dilakukan pada konten. Ini hanya menambahkan yang baru."
type: docs
weight: 800
url: /id/java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ContentsAppender

```
public class ContentsAppender extends Object
```

Melakukan modifikasi konten hanya dalam mode APPEND. mode ini memungkinkan menghindari parsing konten yang tidak diperlukan dan berat sebelum perubahan dilakukan pada konten. Ini hanya menambahkan operator baru ke akhir atau ke awal konten.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.Page-) | Inisialisasi instance baru dari contents appender dengan halaman terlampir |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.XForm-) | Menginisialisasi instance baru dari contets appender dengan Form XObject. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [appendToBegin](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-) | Menambahkan operator ke akhir konten |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator-) | Menambahkan operator ke akhir konten |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator:A-) | Menambahkan operator ke akhir konten |
| [appendToEnd](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-) | Menambahkan operator ke awal konten |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator-) | Menambahkan operator ke awal konten |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator:A-) | Menambahkan operator ke awal konten |
| [getBeginCode](#getBeginCode--) | String yang berisi operator untuk disisipkan ke awal halaman. |
| [getBeginOperators](#getBeginOperators--) | <p> mengembalikan operator awal </p> |
| [getEndCode](#getEndCode--) | String yang berisi operator untuk ditambahkan ke akhir halaman. |
| [getEndOperators](#getEndOperators--) | <p> mengembalikan operator akhir </p> |
| [resumeUpdate](#resumeUpdate--) | melanjutkan pembaruan dokumen |
| [setBeginCode](#setBeginCode-java.lang.String-) | String yang berisi operator untuk disisipkan ke awal halaman. |
| [setEndCode](#setEndCode-java.lang.String-) | String yang berisi operator untuk disisipkan ke awal halaman. |
| [suppressUpdate](#suppressUpdate--) | Menekan pembaruan data konten. Konten tidak diperbarui sampai ResumeUpdate dipanggil. |
| [updateData](#updateData--) | ini adalah versi baru dari UpdateData, yang menghindari decoding konten yang ada. |
| [updateDataOld](#updateDataOld--) | Harus dipanggil untuk menerapkan perubahan |

### ContentsAppender {#ContentsAppender-com.aspose.pdf.Page-}
Inisialisasi instance baru dari contents appender dengan halaman terlampir

### ContentsAppender {#ContentsAppender-com.aspose.pdf.XForm-}
Menginisialisasi instance baru dari contets appender dengan Form XObject.

### appendToBegin {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-}
Menambahkan operator ke akhir konten

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator-}
Menambahkan operator ke akhir konten

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator:A-}
Menambahkan operator ke akhir konten

### appendToEnd {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-}
Menambahkan operator ke awal konten

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator-}
Menambahkan operator ke awal konten

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator:A-}
Menambahkan operator ke awal konten

### getBeginCode {#getBeginCode--}
```
public String getBeginCode()
```

String yang berisi operator untuk disisipkan ke awal halaman.

**Returns:**
Objek String

### getBeginOperators {#getBeginOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getBeginOperators()
```

<p> mengembalikan operator awal </p>

**Returns:**
objek {@code List<Operator>}

### getEndCode {#getEndCode--}
```
public String getEndCode()
```

String yang berisi operator untuk ditambahkan ke akhir halaman.

**Returns:**
Objek String

### getEndOperators {#getEndOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getEndOperators()
```

<p> mengembalikan operator akhir </p>

**Returns:**
objek {@code List<Operator>}

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

melanjutkan pembaruan dokumen

### setBeginCode {#setBeginCode-java.lang.String-}
String yang berisi operator untuk disisipkan ke awal halaman.

### setEndCode {#setEndCode-java.lang.String-}
String yang berisi operator untuk disisipkan ke awal halaman.

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Menekan pembaruan data konten. Konten tidak diperbarui sampai ResumeUpdate dipanggil.

### updateData {#updateData--}
```
public void updateData()
```

ini adalah versi baru dari UpdateData, yang menghindari decoding konten yang ada.

### updateDataOld {#updateDataOld--}
```
public void updateDataOld()
```

Harus dipanggil untuk menerapkan perubahan
