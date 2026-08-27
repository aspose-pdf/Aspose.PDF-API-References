---
title: "SystemFontSource"
linktitle: "SystemFontSource"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili semua font yang terpasang di sistem."
type: docs
weight: 4770
url: /id/java/com.aspose.pdf/systemfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.SystemFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.SystemFontSource

```
public final class SystemFontSource extends FontSource
```

Mewakili semua font yang terpasang di sistem.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SystemFontSource](#SystemFontSource--) | Menginisialisasi instance baru dari kelas. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Periksa apakah objek sumber font sistem sama. |
| [getFontDefinitions](#getFontDefinitions--) | Hanya untuk Internal |
| [hashCode](#hashCode--) | Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum dari {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang sama. <li>Tidak <em>diwajibkan</em> bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebisa mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |

### SystemFontSource {#SystemFontSource--}
```
public SystemFontSource()
```

Menginisialisasi instance baru dari kelas.

### equals {#equals-java.lang.Object-}
Periksa apakah objek sumber font sistem sama.

### getFontDefinitions {#getFontDefinitions--}
```
public com.aspose.font.FontDefinition[] getFontDefinitions()
```

Hanya untuk Internal

**Returns:**
Objek FontDefinition[]

### hashCode {#hashCode--}
```
public int hashCode()
```

Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum dari {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang sama. <li>Tidak <em>diwajibkan</em> bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebisa mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
nilai kode hash untuk objek ini. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
