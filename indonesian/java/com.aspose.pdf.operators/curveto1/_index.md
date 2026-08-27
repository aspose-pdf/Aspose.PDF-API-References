---
title: "CurveTo1"
linktitle: "CurveTo1"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator v (tambahkan kurva ke jalur, titik awal direplikasi)."
type: docs
weight: 160
url: /id/java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo1, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo1

```
public class CurveTo1 extends Operator
```

Kelas yang mewakili operator v (tambahkan kurva ke jalur, titik awal direplikasi).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CurveTo1](#CurveTo1-double-double-double-double-) | Menginisialisasi operator kurva. |
| [CurveTo1](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-) | Konstruktor untuk kelas operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima pemilih operator. |
| [getPoints](#getPoints--) | Titik-titik kurva. |

### CurveTo1 {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```

Menginisialisasi operator kurva.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x2 |  | Absidis titik kedua. |
| y2 |  | Ordinat titik kedua. |
| x3 |  | Absidis titik ketiga. |
| y3 |  | Ordinat titik ketiga. |

### CurveTo1 {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-}
Konstruktor untuk kelas operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima pemilih operator.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Titik-titik kurva.

**Returns:**
array instance Point
