---
title: "SetColorSpace"
linktitle: "SetColorSpace"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator cs (mengatur ruang warna untuk operasi non-stroking)."
type: docs
weight: 580
url: /id/java/com.aspose.pdf.operators/setcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpace, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpace

```
public class SetColorSpace extends Operator
```

Kelas yang mewakili operator cs (mengatur ruang warna untuk operasi non-stroking).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetColorSpace](#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-) | Konstruktor untuk kelas operator. |
| [SetColorSpace](#SetColorSpace-java.lang.String-) | Menginisialisasi operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getCommandName](#getCommandName--) | Mendapatkan nama perintah. |
| [getName](#getName--) | Mendapatkan nama ruang warna. |
| [setName](#setName-java.lang.String-) | Mengatur nama ruang warna. |
| [toCommand](#toCommand--) | Hanya untuk penggunaan internal! |

### SetColorSpace {#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-}
Konstruktor untuk kelas operator.

### SetColorSpace {#SetColorSpace-java.lang.String-}
Menginisialisasi operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Mendapatkan nama perintah.

**Returns:**
nilai String

### getName {#getName--}
```
public String getName()
```

Mendapatkan nama ruang warna.

**Returns:**
nilai String

### setName {#setName-java.lang.String-}
Mengatur nama ruang warna.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Hanya untuk penggunaan internal!

**Returns:**
ICommand nilai objek ICommand
