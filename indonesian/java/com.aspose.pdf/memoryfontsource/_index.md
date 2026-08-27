---
title: "MemoryFontSource"
linktitle: "MemoryFontSource"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili sumber file font tunggal."
type: docs
weight: 3040
url: /id/java/com.aspose.pdf/memoryfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.MemoryFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.MemoryFontSource

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public final class MemoryFontSource extends FontSource implements com.aspose.ms.System.IDisposable, Closeable
```

Mewakili sumber file font tunggal.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MemoryFontSource](#MemoryFontSource-byte:A-) | Menginisialisasi instance baru dari kelas {@code MemoryFontSource}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [close](#close--) | Menutup semua sumber daya yang digunakan oleh dokumen ini. |
| [dispose](#dispose--) | Melepaskan sumber daya internal. Metode ini sudah usang, gunakan close() sebagai gantinya. |
| [equals](#equals-java.lang.Object-) | Periksa apakah objek sumber file font sama. |
| [getFontBytes](#getFontBytes--) | Array byte file font. |
| [hashCode](#hashCode--) | Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum dari {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang sama. <li>Tidak <em>diwajibkan</em> bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebisa mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |

### MemoryFontSource {#MemoryFontSource-byte:A-}
```
public MemoryFontSource(byte[] fontBytes)
```

Menginisialisasi instance baru dari kelas {@code MemoryFontSource}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontBytes |  | Array byte file font. |

### close {#close--}
```
public void close()
```

Menutup semua sumber daya yang digunakan oleh dokumen ini.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Melepaskan sumber daya internal. Metode ini sudah usang, gunakan close() sebagai gantinya.

### equals {#equals-java.lang.Object-}
Periksa apakah objek sumber file font sama.

### getFontBytes {#getFontBytes--}
```
public byte[] getFontBytes()
```

Array byte file font.

**Returns:**
array byte[]

### hashCode {#hashCode--}
```
public int hashCode()
```

Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum dari {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang sama. <li>Tidak <em>diwajibkan</em> bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebisa mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
nilai kode hash untuk objek ini. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
