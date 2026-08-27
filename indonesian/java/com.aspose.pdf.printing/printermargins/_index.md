---
title: "PrinterMargins"
linktitle: "PrinterMargins"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menentukan dimensi margin halaman yang dicetak."
type: docs
weight: 70
url: /id/java/com.aspose.pdf.printing/printermargins/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrinterMargins

```
public class PrinterMargins extends Object
```

Menentukan dimensi margin halaman yang dicetak.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PrinterMargins](#PrinterMargins--) | Menginisialisasi instance baru dari kelas Margins dengan margin lebar 1 inci. |
| [PrinterMargins](#PrinterMargins-int-int-int-int-) | Menginisialisasi instance baru dari kelas Margins dengan margin kiri, kanan, atas, dan bawah yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone](#deepClone--) | Mengambil duplikat objek ini, anggota demi anggota. |
| [equals](#equals-java.lang.Object-) | Membandingkan Margins ini dengan Object yang ditentukan untuk menentukan apakah mereka memiliki dimensi yang sama. (Menimpa Object.Equals(Object).) |
| [getBottom](#getBottom--) | Mendapatkan atau mengatur margin bawah, dalam satuan per seratus inci. |
| [getLeft](#getLeft--) | Mendapatkan atau mengatur lebar margin kiri, dalam satuan per seratus inci. |
| [getRight](#getRight--) | Mendapatkan atau mengatur lebar margin kanan, dalam satuan per seratus inci. |
| [getTop](#getTop--) | Mendapatkan atau mengatur lebar margin atas, dalam satuan per seratus inci. |
| [hashCode](#hashCode--) | Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum dari {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang sama. <li>Tidak <em>diwajibkan</em> bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebisa mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [op_Equality](#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Membandingkan dua Margins untuk menentukan apakah mereka memiliki dimensi yang sama. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Membandingkan dua Margins untuk menentukan apakah mereka memiliki lebar yang tidak sama. |
| [setBottom](#setBottom-int-) | Mendapatkan atau mengatur margin bawah, dalam satuan per seratus inci. |
| [setLeft](#setLeft-int-) | Mendapatkan atau mengatur lebar margin kiri, dalam satuan per seratus inci. |
| [setRight](#setRight-int-) | Mendapatkan atau mengatur lebar margin kanan, dalam satuan per seratus inci. |
| [setTop](#setTop-int-) | Mendapatkan atau mengatur lebar margin atas, dalam satuan per seratus inci. |

### PrinterMargins {#PrinterMargins--}
```
public PrinterMargins()
```

Menginisialisasi instance baru dari kelas Margins dengan margin lebar 1 inci.

### PrinterMargins {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```

Menginisialisasi instance baru dari kelas Margins dengan margin kiri, kanan, atas, dan bawah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kiri |  | nilai int |
| kanan |  | nilai int |
| atas |  | nilai int |
| bawah |  | nilai int |

### deepClone {#deepClone--}
```
public PrinterMargins deepClone()
```

Mengambil duplikat objek ini, anggota demi anggota.

**Returns:**
Objek PrinterMargins

### equals {#equals-java.lang.Object-}
Membandingkan Margins ini dengan Object yang ditentukan untuk menentukan apakah mereka memiliki dimensi yang sama. (Menimpa Object.Equals(Object).)

### getBottom {#getBottom--}
```
public int getBottom()
```

Mendapatkan atau mengatur margin bawah, dalam satuan per seratus inci.

**Returns:**
nilai int

### getLeft {#getLeft--}
```
public int getLeft()
```

Mendapatkan atau mengatur lebar margin kiri, dalam satuan per seratus inci.

**Returns:**
nilai int

### getRight {#getRight--}
```
public int getRight()
```

Mendapatkan atau mengatur lebar margin kanan, dalam satuan per seratus inci.

**Returns:**
nilai int

### getTop {#getTop--}
```
public int getTop()
```

Mendapatkan atau mengatur lebar margin atas, dalam satuan per seratus inci.

**Returns:**
nilai int

### hashCode {#hashCode--}
```
public int hashCode()
```

Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum dari {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang sama. <li>Tidak <em>diwajibkan</em> bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebisa mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
nilai kode hash untuk objek ini. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Membandingkan dua Margins untuk menentukan apakah mereka memiliki dimensi yang sama.

### op_Inequality {#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Membandingkan dua Margins untuk menentukan apakah mereka memiliki lebar yang tidak sama.

### setBottom {#setBottom-int-}
```
public void setBottom(int value)
```

Mendapatkan atau mengatur margin bawah, dalam satuan per seratus inci.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setLeft {#setLeft-int-}
```
public void setLeft(int value)
```

Mendapatkan atau mengatur lebar margin kiri, dalam satuan per seratus inci.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setRight {#setRight-int-}
```
public void setRight(int value)
```

Mendapatkan atau mengatur lebar margin kanan, dalam satuan per seratus inci.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setTop {#setTop-int-}
```
public void setTop(int value)
```

Mendapatkan atau mengatur lebar margin atas, dalam satuan per seratus inci.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
