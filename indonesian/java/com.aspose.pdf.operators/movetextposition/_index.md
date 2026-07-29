---
title: "MoveTextPosition"
linktitle: "MoveTextPosition"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator Td (memindahkan posisi teks)."
type: docs
weight: 390
url: /id/java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPosition

```
public class MoveTextPosition extends TextPlaceOperator
```

Kelas yang mewakili operator Td (memindahkan posisi teks).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MoveTextPosition](#MoveTextPosition-double-double-) | Menginisialisasi operator. |
| [MoveTextPosition](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-) | Menginisialisasi operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getX](#getX--) | Koordinat X dari posisi teks. |
| [getY](#getY--) | Koordinat Y dari posisi teks. |
| [setX](#setX-double-) | Koordinat X dari posisi teks. |
| [setY](#setY-double-) | Koordinat Y dari posisi teks. |
| [toString](#toString--) | Mengembalikan representasi teks operator. |

### MoveTextPosition {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```

Menginisialisasi operator.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x |  | Koordinat X dari posisi teks. |
| y |  | Koordinat Y dari posisi teks. |

### MoveTextPosition {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-}
Menginisialisasi operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getX {#getX--}
```
public double getX()
```

Koordinat X dari posisi teks.

**Returns:**
nilai double

### getY {#getY--}
```
public double getY()
```

Koordinat Y dari posisi teks.

**Returns:**
nilai double

### setX {#setX-double-}
```
public void setX(double value)
```

Koordinat X dari posisi teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setY {#setY-double-}
```
public void setY(double value)
```

Koordinat Y dari posisi teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi teks operator.

**Returns:**
Representasi teks dari operator.
