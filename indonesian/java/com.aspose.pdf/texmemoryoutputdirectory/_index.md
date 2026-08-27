---
title: "TeXMemoryOutputDirectory"
linktitle: "TeXMemoryOutputDirectory"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mengimplementasikan pengambilan aliran output dari memori. Anda dapat menggunakannya, misalnya, ketika Anda tidak ingin output yang menyertainya (seperti file log) ditulis ke disk tetapi Anda menginginkannya."
type: docs
weight: 4880
url: /id/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TeXMemoryOutputDirectory

**All Implemented Interfaces:**
ITeXInputDirectory, ITeXOutputDirectory, Closeable, AutoCloseable

```
public class TeXMemoryOutputDirectory extends Object implements ITeXOutputDirectory
```

Mengimplementasikan pengambilan aliran output dari memori. Anda dapat menggunakannya, misalnya, ketika Anda tidak ingin output yang menyertainya (seperti file log) ditulis ke disk tetapi ingin membacanya nanti dari memori.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TeXMemoryOutputDirectory](#TeXMemoryOutputDirectory--) | Membuat instance baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [close](#close--) | Membuang instance. @throws IOException Pengecualian IOException dapat dilempar jika terjadi kesalahan I/O. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-) | Mengembalikan aliran untuk dibaca. Tanpa mencari file di subdirektori. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-boolean-) | Mengembalikan aliran untuk dibaca. |
| [getOutputFile](#getOutputFile-java.lang.String-java.lang.String:A-) | Mengembalikan aliran untuk ditulis. |

### TeXMemoryOutputDirectory {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```

Membuat instance baru.

### close {#close--}
```
public void close() throws IOException
```

Membuang instance. @throws IOException Pengecualian IOException dapat dilempar jika terjadi kesalahan I/O.

### getFile {#getFile-java.lang.String-java.lang.String:A-}
Mengembalikan aliran untuk dibaca. Tanpa mencari file di subdirektori.

### getFile {#getFile-java.lang.String-java.lang.String:A-boolean-}
Mengembalikan aliran untuk dibaca.

### getOutputFile {#getOutputFile-java.lang.String-java.lang.String:A-}
Mengembalikan aliran untuk ditulis.
