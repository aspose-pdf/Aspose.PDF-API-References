---
title: "FileFontSource"
linktitle: "FileFontSource"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili sumber file font tunggal."
type: docs
weight: 1450
url: /id/java/com.aspose.pdf/filefontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FileFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FileFontSource

```
public final class FileFontSource extends FontSource
```

Mewakili sumber file font tunggal.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FileFontSource](#FileFontSource-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas {@code FileFontSource}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Periksa apakah objek sumber file font sama. |
| [getFilePath](#getFilePath--) | Jalur ke file font. |
| [hashCode](#hashCode--) | Mengembalikan nilai kode hash untuk objek. Metode ini didukung demi manfaat tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum dari {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing dua objek harus menghasilkan hasil integer yang sama. <li>Itu <em>tidak</em> diwajibkan bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing dua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebanyak mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java <span style="font-size:70%"><sup>TM</sup></span>.) |
| [setFilePath](#setFilePath-java.lang.String-) | Jalur ke file font. |

### FileFontSource {#FileFontSource-java.lang.String-}
Menginisialisasi sebuah instance baru dari kelas {@code FileFontSource}.

### equals {#equals-java.lang.Object-}
Periksa apakah objek sumber file font sama.

### getFilePath {#getFilePath--}
```
public String getFilePath()
```

Jalur ke file font.

**Returns:**
nilai String

### hashCode {#hashCode--}
```
public int hashCode()
```

Mengembalikan nilai kode hash untuk objek. Metode ini didukung demi manfaat tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum dari {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing dua objek harus menghasilkan hasil integer yang sama. <li>Itu <em>tidak</em> diwajibkan bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing dua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebanyak mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java <span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
nilai kode hash untuk objek ini. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFilePath {#setFilePath-java.lang.String-}
Jalur ke file font.
