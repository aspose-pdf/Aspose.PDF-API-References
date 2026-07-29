---
title: "LineTo"
linktitle: "LineTo"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator l (menambahkan garis ke jalur)."
type: docs
weight: 380
url: /id/java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.LineTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.LineTo

```
public class LineTo extends Operator
```

Kelas yang mewakili operator l (menambahkan garis ke jalur).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LineTo](#LineTo-double-double-) | Menginisialisasi operator garis. |
| [LineTo](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-) | Konstruktor untuk kelas operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getX](#getX--) | Koordinat X dari titik garis. |
| [getY](#getY--) | Koordinat Y dari titik garis. |
| [setX](#setX-double-) | Koordinat X dari titik garis. |
| [setY](#setY-double-) | Koordinat Y dari titik garis. |
| [toString](#toString--) | Mengembalikan representasi teks dari operator. |

### LineTo {#LineTo-double-double-}
```
public LineTo(double x, double y)
```

Menginisialisasi operator garis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x |  | Koordinat X. |
| y |  | Koordinat Y. |

### LineTo {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-}
Konstruktor untuk kelas operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getX {#getX--}
```
public double getX()
```

Koordinat X dari titik garis.

**Returns:**
nilai double

### getY {#getY--}
```
public double getY()
```

Koordinat Y dari titik garis.

**Returns:**
nilai double

### setX {#setX-double-}
```
public void setX(double value)
```

Koordinat X dari titik garis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setY {#setY-double-}
```
public void setY(double value)
```

Koordinat Y dari titik garis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi teks dari operator.

**Returns:**
Representasi teks dari operator.
