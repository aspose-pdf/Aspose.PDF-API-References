---
title: "BorderInfo"
linktitle: "BorderInfo"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas ini mewakili batas untuk elemen grafis."
type: docs
weight: 370
url: /id/java/com.aspose.pdf/borderinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BorderInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class BorderInfo extends Object implements com.aspose.ms.System.ICloneable
```

Kelas ini mewakili batas untuk elemen grafis.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BorderInfo](#BorderInfo--) | Menginisialisasi instance baru dari kelas {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-) | Menginisialisasi instance baru dari kelas {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.Color-) | Menginisialisasi instance baru dari kelas {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-) | Menginisialisasi instance baru dari kelas {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-com.aspose.pdf.Color-) | Menginisialisasi instance baru dari kelas {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.GraphInfo-) | Menginisialisasi instance baru dari kelas {@code BorderInfo}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone](#deepClone--) | Mengkloning objek BorderInfo baru. |
| [getBottom](#getBottom--) | Mendapatkan objek yang menunjukkan bagian bawah border. |
| [getLeft](#getLeft--) | Mendapatkan objek {@code GraphInfo} yang menunjukkan sisi kiri border. |
| [getRight](#getRight--) | Mendapatkan objek {@code GraphInfo} yang menunjukkan sisi kanan border. |
| [getRoundedBorderRadius](#getRoundedBorderRadius--) | Mendapatkan radius border yang melengkung. |
| [getTop](#getTop--) | Mendapatkan objek {@code GraphInfo} yang menunjukkan border atas. |
| [setBottom](#setBottom-com.aspose.pdf.GraphInfo-) | Mengatur objek yang menunjukkan bagian bawah border. |
| [setLeft](#setLeft-com.aspose.pdf.GraphInfo-) | Mengatur objek {@code GraphInfo} yang menunjukkan sisi kiri border. |
| [setRight](#setRight-com.aspose.pdf.GraphInfo-) | Mengatur objek {@code GraphInfo} yang menunjukkan sisi kanan border. |
| [setRoundedBorderRadius](#setRoundedBorderRadius-double-) | Mengatur radius border yang melengkung. |
| [setTop](#setTop-com.aspose.pdf.GraphInfo-) | Mengatur objek {@code GraphInfo} yang menunjukkan bagian atas border. |

### BorderInfo {#BorderInfo--}
```
public BorderInfo()
```

Menginisialisasi instance baru dari kelas {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-}
```
public BorderInfo(int borderSide)
```

Menginisialisasi instance baru dari kelas {@code BorderInfo}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| borderSide |  | Menunjukkan info sisi border. Misalnya: (BorderSide.Left \" | BorderSide.Top). |

### BorderInfo {#BorderInfo-int-com.aspose.pdf.Color-}
Menginisialisasi instance baru dari kelas {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-float-}
```
public BorderInfo(int borderSide, float borderWidth)
```

Menginisialisasi instance baru dari kelas {@code BorderInfo}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| borderSide |  | Menunjukkan info sisi border. Misalnya: (BorderSide.Left \" | BorderSide.Top). |
| borderWidth |  | Lebar border. |

### BorderInfo {#BorderInfo-int-float-com.aspose.pdf.Color-}
Menginisialisasi instance baru dari kelas {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-com.aspose.pdf.GraphInfo-}
Menginisialisasi instance baru dari kelas {@code BorderInfo}.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Mengkloning objek BorderInfo baru.

**Returns:**
Objek BorderInfo baru.

### getBottom {#getBottom--}
```
public GraphInfo getBottom()
```

Mendapatkan objek yang menunjukkan bagian bawah border.

**Returns:**
bawah

### getLeft {#getLeft--}
```
public GraphInfo getLeft()
```

Mendapatkan objek {@code GraphInfo} yang menunjukkan sisi kiri border.

**Returns:**
objek yang menunjukkan sisi kiri dari batas.

### getRight {#getRight--}
```
public GraphInfo getRight()
```

Mendapatkan objek {@code GraphInfo} yang menunjukkan sisi kanan border.

**Returns:**
objek yang menunjukkan sisi kanan dari batas.

### getRoundedBorderRadius {#getRoundedBorderRadius--}
```
public double getRoundedBorderRadius()
```

Mendapatkan radius border yang melengkung.

**Returns:**
nilai

### getTop {#getTop--}
```
public GraphInfo getTop()
```

Mendapatkan objek {@code GraphInfo} yang menunjukkan border atas.

**Returns:**
objek yang menunjukkan batas atas

### setBottom {#setBottom-com.aspose.pdf.GraphInfo-}
Mengatur objek yang menunjukkan bagian bawah border.

### setLeft {#setLeft-com.aspose.pdf.GraphInfo-}
Mengatur objek {@code GraphInfo} yang menunjukkan sisi kiri border.

### setRight {#setRight-com.aspose.pdf.GraphInfo-}
Mengatur objek {@code GraphInfo} yang menunjukkan sisi kanan border.

### setRoundedBorderRadius {#setRoundedBorderRadius-double-}
```
public void setRoundedBorderRadius(double value)
```

Mengatur radius border yang melengkung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setTop {#setTop-com.aspose.pdf.GraphInfo-}
Mengatur objek {@code GraphInfo} yang menunjukkan bagian atas border.
