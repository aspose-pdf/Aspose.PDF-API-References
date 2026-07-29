---
title: "Operator"
linktitle: "Operator"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas abstrak yang mewakili operator."
type: docs
weight: 3180
url: /id/java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator

```
public abstract class Operator extends Object
```

Kelas abstrak yang mewakili operator.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Operator](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Hanya untuk penggunaan internal! |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima pengunjung IOperatorSelector yang menyediakan pemrosesan operator. |
| [createFromCommandName](#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Membuat operator berdasarkan nama instance com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand. |
| [equals](#equals-com.aspose.pdf.Operator-) | Membandingkan instance ini dengan objek yang diberikan. |
| [getCommand](#getCommand--) | Mendapatkan perintah |
| [getCommandName](#getCommandName--) | Mendapatkan nama operator. |
| [getIndex](#getIndex--) | Dapatkan indeks Operator dalam daftar operator halaman. |
| [isTextShowOperator](#isTextShowOperator-com.aspose.pdf.Operator-) | Menentukan apakah operator tersebut adalah operator yang bertanggung jawab untuk output teks (Tj, TJ, dll). |
| [setIndex](#setIndex-int-) | Atur indeks Operator dalam daftar operator halaman. |
| [toString](#toString--) | Menerjemahkan perintah dan parameter menjadi representasi string. |
| [valueEquals](#valueEquals-com.aspose.pdf.Operator-) | Membandingkan instance ini dengan objek yang diberikan. |

### Operator {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Hanya untuk penggunaan internal!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima pengunjung IOperatorSelector yang menyediakan pemrosesan operator.

### createFromCommandName {#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Membuat operator berdasarkan nama instance com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand.

### equals {#equals-com.aspose.pdf.Operator-}
Membandingkan instance ini dengan objek yang diberikan.

### getCommand {#getCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand getCommand()
```

Mendapatkan perintah

**Returns:**
objek ICommand

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Mendapatkan nama operator.

**Returns:**
nilai String

### getIndex {#getIndex--}
```
public int getIndex()
```

Dapatkan indeks Operator dalam daftar operator halaman.

**Returns:**
nilai int

### isTextShowOperator {#isTextShowOperator-com.aspose.pdf.Operator-}
Menentukan apakah operator tersebut adalah operator yang bertanggung jawab untuk output teks (Tj, TJ, dll).

### setIndex {#setIndex-int-}
```
public void setIndex(int value)
```

Atur indeks Operator dalam daftar operator halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### toString {#toString--}
```
public String toString()
```

Menerjemahkan perintah dan parameter menjadi representasi string.

**Returns:**
teks Operator

### valueEquals {#valueEquals-com.aspose.pdf.Operator-}
Membandingkan instance ini dengan objek yang diberikan.
