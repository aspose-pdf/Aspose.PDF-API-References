---
title: "Line"
linktitle: "Line"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili garis."
type: docs
weight: 90
url: /id/java/com.aspose.pdf.drawing/line/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Line, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Line

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Line extends Shape
```

Mewakili garis.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Line](#Line--) | Hanya untuk penggunaan internal |
| [Line](#Line-float:A-) | Menginisialisasi instance baru dari kelas {@code Line}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Memeriksa apakah item cocok dengan dimensi kontainer yang diberikan (inklusif). |
| [getPositionArray](#getPositionArray--) | Mendapatkan objek yang menunjukkan array posisi. Array tersebut terdiri dari koordinat setiap titik kontrol garis secara langsung. |
| [setPositionArray](#setPositionArray-float:A-) | Mengatur objek yang menunjukkan array posisi. Array tersebut terdiri dari koordinat setiap titik kontrol garis secara langsung. |

### Line {#Line--}
```
public Line()
```

Hanya untuk penggunaan internal

### Line {#Line-float:A-}
```
public Line(float[] positionArray)
```

Menginisialisasi instance baru dari kelas {@code Line}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| positionArray |  | Array posisi garis. |

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

Mendapatkan objek yang menunjukkan array posisi. Array tersebut terdiri dari koordinat setiap titik kontrol garis secara langsung.

**Returns:**
yang menunjukkan array posisi.

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Mengatur objek yang menunjukkan array posisi. Array tersebut terdiri dari koordinat setiap titik kontrol garis secara langsung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | yang menunjukkan array posisi. |
