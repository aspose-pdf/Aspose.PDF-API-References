---
title: "CurveTo2"
linktitle: "CurveTo2"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator y (tambahkan kurva ke jalur, titik akhir direplikasi)."
type: docs
weight: 170
url: /id/java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo2, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo2

```
public class CurveTo2 extends Operator
```

Kelas yang mewakili operator y (tambahkan kurva ke jalur, titik akhir direplikasi).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CurveTo2](#CurveTo2-double-double-double-double-) | Menginisialisasi operator kurva. |
| [CurveTo2](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-) | Konstruktor untuk kelas operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getPoints](#getPoints--) | Titik-titik kurva. |

### CurveTo2 {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```

Menginisialisasi operator kurva.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 |  | Absidis titik kedua. |
| y1 |  | Ordinat titik kedua. |
| x3 |  | Absidis titik ketiga. |
| y3 |  | Ordinat titik ketiga. |

### CurveTo2 {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-}
Konstruktor untuk kelas operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Titik-titik kurva.

**Returns:**
array instance Point
