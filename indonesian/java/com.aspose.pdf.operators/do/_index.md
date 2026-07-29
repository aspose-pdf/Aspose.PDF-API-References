---
title: "Do"
linktitle: "Do"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator Do (Panggil XObject)."
type: docs
weight: 180
url: /id/java/com.aspose.pdf.operators/do/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Do, com.aspose.pdf.Operator, com.aspose.pdf.operators.Do

```
public class Do extends Operator
```

Kelas yang mewakili operator Do (Panggil XObject).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Do](#Do--) | Membuat operator Do baru. Digunakan untuk mengambil semua operator Do, yaitu tanpa memeriksa nama argumen mereka. |
| [Do](#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-) | Membuat operator Do baru. Digunakan untuk mengambil semua operator Do, yaitu tanpa memeriksa nama argumen mereka. |
| [Do](#Do-java.lang.String-) | Membuat operator Do baru. Digunakan untuk mengambil semua operator Do, yaitu tanpa memeriksa nama argumen mereka. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getCommandName](#getCommandName--) | Mendapatkan nama perintah |
| [getName](#getName--) | Dapatkan nama argumen XObject dari operator. |
| [setName](#setName-java.lang.String-) | Atur nama argumen XObject dari operator. |
| [toCommand](#toCommand--) | Hanya untuk penggunaan internal! |
| [toString](#toString--) | Mengembalikan representasi teks operator. |

### Do {#Do--}
```
public Do()
```

Membuat operator Do baru. Digunakan untuk mengambil semua operator Do, yaitu tanpa memeriksa nama argumen mereka.

### Do {#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-}
Membuat operator Do baru. Digunakan untuk mengambil semua operator Do, yaitu tanpa memeriksa nama argumen mereka.

### Do {#Do-java.lang.String-}
Membuat operator Do baru. Digunakan untuk mengambil semua operator Do, yaitu tanpa memeriksa nama argumen mereka.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Mendapatkan nama perintah

**Returns:**
nilai String

### getName {#getName--}
```
public String getName()
```

Dapatkan nama argumen XObject dari operator.

**Returns:**
nilai String

### setName {#setName-java.lang.String-}
Atur nama argumen XObject dari operator.

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
