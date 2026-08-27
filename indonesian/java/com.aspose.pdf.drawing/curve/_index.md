---
title: "Curve"
linktitle: "Curve"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kurva Bezier."
type: docs
weight: 30
url: /id/java/com.aspose.pdf.drawing/curve/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Curve, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Curve

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Curve extends Shape
```

Mewakili kurva Bezier.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Curve](#Curve--) | Hanya untuk penggunaan internal |
| [Curve](#Curve-float:A-) | Menginisialisasi sebuah instance baru dari kelas {@code Curve}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Memeriksa apakah item cocok dengan dimensi kontainer yang diberikan (inklusif). |
| [getPositionArray](#getPositionArray--) | Mendapatkan array posisi float. |
| [setPositionArray](#setPositionArray-float:A-) | Mengatur array posisi float. |

### Curve {#Curve--}
```
public Curve()
```

Hanya untuk penggunaan internal

### Curve {#Curve-float:A-}
```
public Curve(float[] positionArray)
```

Menginisialisasi sebuah instance baru dari kelas {@code Curve}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| positionArray |  | Array posisi dari titik kontrol kurva. Harus ada empat titik kontrol, sehingga panjang array harus delapan. |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Memeriksa apakah item cocok dengan dimensi kontainer yang diberikan (inklusif).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
True jika cocok; jika tidak, false.

### getPositionArray {#getPositionArray--}
```
public float[] getPositionArray()
```

Mendapatkan array posisi float.

**Returns:**
float[] array

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Mengatur array posisi float.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | float[] array |
