---
title: "Graph"
linktitle: "Graph"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili grafik - paragraf generator grafis."
type: docs
weight: 70
url: /id/java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.drawing.Graph, com.aspose.pdf.BaseParagraph, com.aspose.pdf.drawing.Graph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Graph extends BaseParagraph
```

Mewakili grafik - paragraf generator grafis.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Graph](#Graph--) | Hanya untuk penggunaan internal |
| [Graph](#Graph-double-double-) | Menginisialisasi instance baru dari kelas {@link Graph}. |
| [Graph](#Graph-float-float-) | Menginisialisasi instance baru dari kelas {@code Graph}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone](#deepClone--) | Klon grafik. |
| [getBorder](#getBorder--) | Mendapatkan border. |
| [getGraphInfo](#getGraphInfo--) | Mendapatkan objek {@code GraphInfo} yang menunjukkan informasi grafik, seperti warna, lebar garis, dll. |
| [getHeight](#getHeight--) | Mendapatkan nilai float yang menunjukkan tinggi grafik. Satuannya adalah point. Dalam XML, satuan default adalah point, tetapi cm dan inch juga didukung. Misalnya, GraphHeight="10cm" atau GraphHeight="5inch". |
| [getLeft](#getLeft--) | Mendapatkan koordinat kiri tabel. |
| [getShapes](#getShapes--) | Mendapatkan koleksi yang menunjukkan semua bentuk dalam grafik. |
| [getTitle](#getTitle--) | Mendapatkan nilai string yang menunjukkan judul grafik. |
| [getTop](#getTop--) | Mendapatkan koordinat atas tabel. |
| [getWidth](#getWidth--) | Mendapatkan nilai float yang menunjukkan lebar grafik. Satuannya adalah point. Dalam XML, satuan default adalah point, tetapi cm dan inch juga didukung. Misalnya, GraphWidth="10cm" atau GraphWidth="5inch". |
| [isChangePosition](#isChangePosition--) | Mendapatkan perubahan posisi saat ini setelah memproses paragraf.(default true) |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Mengatur border. |
| [setChangePosition](#setChangePosition-boolean-) | Mengatur perubahan posisi saat ini setelah memproses paragraf.(default true) |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Mendapatkan atau mengatur objek {@code GraphInfo} yang menunjukkan informasi grafik, seperti warna, lebar garis, dll. |
| [setHeight](#setHeight-double-) | Mengatur nilai float yang menunjukkan tinggi grafik. Satuannya adalah point. Dalam XML, satuan default adalah point, tetapi cm dan inch juga didukung. Misalnya, GraphHeight="10cm" atau GraphHeight="5inch". |
| [setLeft](#setLeft-double-) | Mengatur koordinat kiri tabel. |
| [setShapes](#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-) | Mengatur koleksi yang menunjukkan semua bentuk dalam grafik. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Mengatur nilai string yang menunjukkan judul grafik. |
| [setTop](#setTop-double-) | Mengatur koordinat atas tabel. |
| [setWidth](#setWidth-double-) | Mengatur nilai float yang menunjukkan lebar grafik. Satuannya adalah point. Dalam XML, satuan default adalah point, tetapi cm dan inch juga didukung. Misalnya, GraphWidth="10cm" atau GraphWidth="5inch". |

### Graph {#Graph--}
```
public Graph()
```

Hanya untuk penggunaan internal

### Graph {#Graph-double-double-}
```
public Graph(double width, double height)
```

Menginisialisasi instance baru dari kelas {@link Graph}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar grafik. |
| tinggi |  | Tinggi grafik. |

### Graph {#Graph-float-float-}
```
@Deprecated public Graph(float width, float height)
```

Menginisialisasi instance baru dari kelas {@code Graph}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar grafik. |
| tinggi |  | Tinggi grafik. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klon grafik.

**Returns:**
Objek yang diklon.

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Mendapatkan border.

**Returns:**
elemen BorderInfo

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Mendapatkan objek {@code GraphInfo} yang menunjukkan informasi grafik, seperti warna, lebar garis, dll.

**Returns:**
objek GraphInfo

### getHeight {#getHeight--}
```
public double getHeight()
```

Mendapatkan nilai float yang menunjukkan tinggi grafik. Satuannya adalah point. Dalam XML, satuan default adalah point, tetapi cm dan inch juga didukung. Misalnya, GraphHeight="10cm" atau GraphHeight="5inch".

**Returns:**
nilai yang menunjukkan tinggi grafik.

### getLeft {#getLeft--}
```
public double getLeft()
```

Mendapatkan koordinat kiri tabel.

**Returns:**
koordinat kiri tabel.

### getShapes {#getShapes--}
```
public final BoundsCheckableList < Shape > getShapes()
```

Mendapatkan koleksi yang menunjukkan semua bentuk dalam grafik.

**Returns:**
BoundsCheckableList dari Shapes.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Mendapatkan nilai string yang menunjukkan judul grafik.

**Returns:**
judul grafik.

### getTop {#getTop--}
```
public double getTop()
```

Mendapatkan koordinat atas tabel.

**Returns:**
koordinat atas tabel.

### getWidth {#getWidth--}
```
public double getWidth()
```

Mendapatkan nilai float yang menunjukkan lebar grafik. Satuannya adalah point. Dalam XML, satuan default adalah point, tetapi cm dan inch juga didukung. Misalnya, GraphWidth="10cm" atau GraphWidth="5inch".

**Returns:**
nilai float yang menunjukkan lebar grafik.

### isChangePosition {#isChangePosition--}
```
public boolean isChangePosition()
```

Mendapatkan perubahan posisi saat ini setelah memproses paragraf.(default true)

**Returns:**
nilai boolean

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Mengatur border.

### setChangePosition {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```

Mengatur perubahan posisi saat ini setelah memproses paragraf.(default true)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Mendapatkan atau mengatur objek {@code GraphInfo} yang menunjukkan informasi grafik, seperti warna, lebar garis, dll.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Mengatur nilai float yang menunjukkan tinggi grafik. Satuannya adalah point. Dalam XML, satuan default adalah point, tetapi cm dan inch juga didukung. Misalnya, GraphHeight="10cm" atau GraphHeight="5inch".

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | yang menunjukkan tinggi grafik. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Mengatur koordinat kiri tabel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | koordinat kiri tabel. |

### setShapes {#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-}
Mengatur koleksi yang menunjukkan semua bentuk dalam grafik.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Mengatur nilai string yang menunjukkan judul grafik.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Mengatur koordinat atas tabel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | koordinat atas tabel. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Mengatur nilai float yang menunjukkan lebar grafik. Satuannya adalah point. Dalam XML, satuan default adalah point, tetapi cm dan inch juga didukung. Misalnya, GraphWidth="10cm" atau GraphWidth="5inch".

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float yang menunjukkan lebar grafik. |
