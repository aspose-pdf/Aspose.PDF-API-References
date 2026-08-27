---
title: "MoveTo"
linktitle: "MoveTo"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili {@code operators.m} (memindahkan ke dan memulai subpath baru)."
type: docs
weight: 410
url: /id/java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.MoveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.MoveTo

```
public class MoveTo extends Operator
```

Kelas yang mewakili {@code operators.m} (memindahkan ke dan memulai subpath baru).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MoveTo](#MoveTo-double-double-) | Menginisialisasi {@code Operator.m} (move to) operator baru. |
| [MoveTo](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getX](#getX--) | Koordinat X |
| [getY](#getY--) | Koordinat Y |
| [setX](#setX-double-) | Koordinat X |
| [setY](#setY-double-) | Koordinat Y |
| [toString](#toString--) | Mengembalikan representasi teks dari operator. |

### MoveTo {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```

Menginisialisasi {@code Operator.m} (move to) operator baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x |  | Koordinat x. |
| y |  | Koordinat y. |

### MoveTo {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getX {#getX--}
```
public double getX()
```

Koordinat X

**Returns:**
nilai double

### getY {#getY--}
```
public double getY()
```

Koordinat Y

**Returns:**
nilai double

### setX {#setX-double-}
```
public void setX(double value)
```

Koordinat X

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setY {#setY-double-}
```
public void setY(double value)
```

Koordinat Y

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
