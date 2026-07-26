---
title: "Titik"
linktitle: "Titik"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili titik dengan koordinat pecahan."
type: docs
weight: 3870
url: /id/java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Point

```
public final class Point extends Object
```

Mewakili titik dengan koordinat pecahan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Point](#Point-double-double-) | Menginisialisasi instance baru dari {@code Point}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [distance](#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Menghitung jarak antara dua titik. |
| [getTrivial](#getTrivial--) | Mendapatkan titik dengan koordinat nol. |
| [getX](#getX--) | Mendapatkan nilai koordinat X. |
| [getY](#getY--) | Mendapatkan nilai koordinat Y. |
| [setX](#setX-double-) | Mengatur nilai koordinat X. |
| [setY](#setY-double-) | Mengatur nilai koordinat Y. |
| [toPoint](#toPoint--) | Mengonversi titik menjadi objek java.awt.geom.Point2D.Float. |
| [toString](#toString--) | Mengembalikan representasi string titik saat ini. |

### Point {#Point-double-double-}
```
public Point(double x, double y)
```

Menginisialisasi instance baru dari {@code Point}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x |  | Nilai koordinat x. |
| y |  | Nilai koordinat y. |

### distance {#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Menghitung jarak antara dua titik.

### getTrivial {#getTrivial--}
```
public static Point getTrivial()
```

Mendapatkan titik dengan koordinat nol.

**Returns:**
Objek Point

### getX {#getX--}
```
public double getX()
```

Mendapatkan nilai koordinat X.

**Returns:**
nilai double

### getY {#getY--}
```
public double getY()
```

Mendapatkan nilai koordinat Y.

**Returns:**
nilai double

### setX {#setX-double-}
```
public void setX(double value)
```

Mengatur nilai koordinat X.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setY {#setY-double-}
```
public void setY(double value)
```

Mengatur nilai koordinat Y.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### toPoint {#toPoint--}
```
public Point2D.Float toPoint()
```

Mengonversi titik menjadi objek java.awt.geom.Point2D.Float.

**Returns:**
Struktur Float.

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi string titik saat ini.

**Returns:**
String, yang mewakili titik saat ini.
