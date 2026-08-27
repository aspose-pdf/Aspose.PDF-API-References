---
title: "DP"
linktitle: "DP"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator DP (menunjuk titik konten yang ditandai)."
type: docs
weight: 190
url: /id/java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.DP, com.aspose.pdf.Operator, com.aspose.pdf.operators.DP

```
public class DP extends Operator
```

Kelas yang mewakili operator DP (menunjuk titik konten yang ditandai).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DP](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-) | Konstruktor untuk kelas operator. |
| [DP](#DP-java.lang.String-) | Menginisialisasi operator. |
| [DP](#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getPropertiesDictionary](#getPropertiesDictionary--) | Mendapatkan kamus properti |
| [getTag](#getTag--) | Mendapatkan tag konten yang ditandai |
| [setPropertiesDictionary](#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-) | Mengatur kamus properti |
| [setTag](#setTag-java.lang.String-) | Mengatur tag konten yang ditandai |
| [toCommand](#toCommand--) | Hanya untuk penggunaan internal! |
| [toString](#toString--) | Mengembalikan representasi teks operator. |

### DP {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-}
Konstruktor untuk kelas operator.

### DP {#DP-java.lang.String-}
Menginisialisasi operator.

### DP {#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getPropertiesDictionary {#getPropertiesDictionary--}
```
public com.aspose.ms.System.Collections.Generic.Dictionary< String ,com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> getPropertiesDictionary()
```

Mendapatkan kamus properti

**Returns:**
nilai IPdfDictionary

### getTag {#getTag--}
```
public String getTag()
```

Mendapatkan tag konten yang ditandai

**Returns:**
nilai String

### setPropertiesDictionary {#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-}
Mengatur kamus properti

### setTag {#setTag-java.lang.String-}
Mengatur tag konten yang ditandai

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Hanya untuk penggunaan internal!

**Returns:**
ICommand nilai objek ICommand

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi teks operator.

**Returns:**
Representasi teks dari operator.
