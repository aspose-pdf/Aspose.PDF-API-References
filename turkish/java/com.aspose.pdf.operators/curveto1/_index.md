---
title: "CurveTo1"
linktitle: "CurveTo1"
second_title: "Aspose.PDF for Java API Referansı"
description: "v operatörünü temsil eden sınıf (eğriyi yola ekler, başlangıç noktası tekrarlanır)."
type: docs
weight: 160
url: /tr/java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo1, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo1

```
public class CurveTo1 extends Operator
```

v operatörünü temsil eden sınıf (eğriyi yola ekler, başlangıç noktası tekrarlanır).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CurveTo1](#CurveTo1-double-double-double-double-) | Eğri operatörünü başlatır. |
| [CurveTo1](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-) | Operatör sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatör seçiciyi kabul eder. |
| [getPoints](#getPoints--) | Eğrinin noktaları. |

### CurveTo1 {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```

Eğri operatörünü başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x2 |  | İkinci noktanın abscisası. |
| y2 |  | İkinci noktanın ordinatı. |
| x3 |  | Üçüncü noktanın abscisası. |
| y3 |  | Üçüncü noktanın ordinatı. |

### CurveTo1 {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-}
Operatör sınıfı için yapıcı.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatör seçiciyi kabul eder.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Eğrinin noktaları.

**Returns:**
Point örneklerinin dizisi
