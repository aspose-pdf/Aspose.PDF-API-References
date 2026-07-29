---
title: "Shape"
linktitle: "Shape"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili bentuk - objek grafis dasar."
type: docs
weight: 130
url: /id/java/com.aspose.pdf.drawing/shape/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public abstract class Shape extends Object implements IBoundsCheckableItem
```

Mewakili bentuk - objek grafis dasar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Shape](#Shape--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Memeriksa apakah item cocok dengan dimensi kontainer yang diberikan (inklusif). |
| [getGraphInfo](#getGraphInfo--) | Mendapatkan objek yang menunjukkan info grafik, seperti warna, lebar garis, dll. |
| [getText](#getText--) | Mendapatkan atau mengatur teks untuk shape |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Mengatur objek yang menunjukkan info grafik, seperti warna, lebar garis, dll. |
| [setText](#setText-com.aspose.pdf.TextFragment-) | Mendapatkan atau mengatur teks untuk shape |

### Shape {#Shape--}
```
public Shape()
```



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

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Mendapatkan objek yang menunjukkan info grafik, seperti warna, lebar garis, dll.

**Returns:**
objek yang menunjukkan info grafik.

### getText {#getText--}
```
public TextFragment getText()
```

Mendapatkan atau mengatur teks untuk shape

**Returns:**
objek TextFragment

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Mengatur objek yang menunjukkan info grafik, seperti warna, lebar garis, dll.

### setText {#setText-com.aspose.pdf.TextFragment-}
Mendapatkan atau mengatur teks untuk shape
