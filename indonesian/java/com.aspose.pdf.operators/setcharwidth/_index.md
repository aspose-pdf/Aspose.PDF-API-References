---
title: "SetCharWidth"
linktitle: "SetCharWidth"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator d0 (mengatur lebar glyph)."
type: docs
weight: 510
url: /id/java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidth

```
public class SetCharWidth extends Operator
```

Kelas yang mewakili operator d0 (mengatur lebar glyph).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetCharWidth](#SetCharWidth-double-double-) | Konstruktor. |
| [SetCharWidth](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Konstruktor untuk kelas operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getWx](#getWx--) | Perpindahan horizontal koordinat glyph. |
| [getWy](#getWy--) | Perpindahan vertikal koordinat glyph. |
| [toCommand](#toCommand--) | Hanya untuk penggunaan internal! |
| [toString](#toString--) | Mengembalikan representasi teks operator. |

### SetCharWidth {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```

Konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| wx |  | Pergeseran horizontal glyph. |
| wy |  | Pergeseran vertikal glyph. |

### SetCharWidth {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Konstruktor untuk kelas operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getWx {#getWx--}
```
public double getWx()
```

Perpindahan horizontal koordinat glyph.

**Returns:**
nilai double

### getWy {#getWy--}
```
public double getWy()
```

Perpindahan vertikal koordinat glyph.

**Returns:**
nilai double

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
Representasi teks dari representasi
