---
title: "SetCharWidthBoundingBox"
linktitle: "SetCharWidthBoundingBox"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator d1 (mengatur glyph dan kotak pembatas)."
type: docs
weight: 520
url: /id/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidthBoundingBox, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidthBoundingBox

```
public class SetCharWidthBoundingBox extends Operator
```

Kelas yang mewakili operator d1 (mengatur glyph dan kotak pembatas).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | Menginisialisasi operator SetCharWidthBoundingBox. |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-) | Konstruktor untuk kelas operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getLlx](#getLlx--) | Koordinat horizontal kiri-bawah dari persegi pembatas. |
| [getLly](#getLly--) | Koordinat vertikal kiri-bawah dari persegi pembatas. |
| [getUrx](#getUrx--) | Koordinat horizontal kanan-atas dari persegi pembatas. |
| [getUry](#getUry--) | Koordinat vertikal kanan-atas dari persegi pembatas. |
| [getWx](#getWx--) | Pergeseran horizontal glyph. |
| [getWy](#getWy--) | Pergeseran vertikal glyph. |
| [toCommand](#toCommand--) | Hanya untuk penggunaan internal! |
| [toString](#toString--) | Mengembalikan representasi teks operator. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```

Menginisialisasi operator SetCharWidthBoundingBox.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| wx |  | Menunjukkan pergeseran horizontal dalam koordinat glyph. |
| wy |  | Menunjukkan pergeseran vertikal dalam koordinat glyph. Harus 0. |
| llx |  | Menunjukkan koordinat X dari sudut kiri-bawah. |
| lly |  | Menunjukkan koordinat Y dari sudut kiri-bawah. |
| urx |  | Menunjukkan koordinat X dari sudut kanan-atas. |
| ury |  | Menunjukkan koordinat Y dari sudut kanan-atas. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-}
Konstruktor untuk kelas operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getLlx {#getLlx--}
```
public double getLlx()
```

Koordinat horizontal kiri-bawah dari persegi pembatas.

**Returns:**
nilai double

### getLly {#getLly--}
```
public double getLly()
```

Koordinat vertikal kiri-bawah dari persegi pembatas.

**Returns:**
nilai double

### getUrx {#getUrx--}
```
public double getUrx()
```

Koordinat horizontal kanan-atas dari persegi pembatas.

**Returns:**
nilai double

### getUry {#getUry--}
```
public double getUry()
```

Koordinat vertikal kanan-atas dari persegi pembatas.

**Returns:**
nilai double

### getWx {#getWx--}
```
public double getWx()
```

Pergeseran horizontal glyph.

**Returns:**
nilai double

### getWy {#getWy--}
```
public double getWy()
```

Pergeseran vertikal glyph.

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
