---
title: "Position"
linktitle: "Position"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili objek posisi"
type: docs
weight: 3940
url: /id/java/com.aspose.pdf/position/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Position

```
public final class Position extends Object
```

Mewakili objek posisi

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Position](#Position-double-double-) | Menginisialisasi sebuah instansi baru dari kelas {@code Position} |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Menentukan apakah objek yang ditentukan sama dengan objek {@code Position} saat ini. |
| [getXIndent](#getXIndent--) | Mendapatkan koordinat X dari objek |
| [getYIndent](#getYIndent--) | Mendapatkan koordinat Y dari objek |
| [hashCode](#hashCode--) | Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum dari {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang sama. <li>Tidak <em>diwajibkan</em> bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebisa mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [setXIndent](#setXIndent-double-) | Mengatur koordinat X dari objek |
| [setYIndent](#setYIndent-double-) | Mengatur koordinat Y dari objek |
| [toString](#toString--) | Mendapatkan representasi string untuk objek {@code Position} saat ini. |

### Position {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```

Menginisialisasi sebuah instansi baru dari kelas {@code Position}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xIndent |  | Nilai koordinat X. |
| yIndent |  | Nilai koordinat Y. |

### equals {#equals-java.lang.Object-}
Menentukan apakah objek yang ditentukan sama dengan objek {@code Position} saat ini.

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Mendapatkan koordinat X dari objek

**Returns:**
nilai double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Mendapatkan koordinat Y dari objek

**Returns:**
nilai double

### hashCode {#hashCode--}
```
public int hashCode()
```

Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum dari {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang sama. <li>Tidak <em>diwajibkan</em> bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebisa mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
nilai kode hash untuk objek ini. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Mengatur koordinat X dari objek

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Mengatur koordinat Y dari objek

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### toString {#toString--}
```
public String toString()
```

Mendapatkan representasi string untuk objek {@code Position} saat ini.

**Returns:**
Representasi string dari objek Position.
