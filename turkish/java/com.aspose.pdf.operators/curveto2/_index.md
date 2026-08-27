---
title: "CurveTo2"
linktitle: "CurveTo2"
second_title: "Aspose.PDF for Java API Referansı"
description: "y operatörünü temsil eden sınıf (eğriyi yola ekler, son nokta tekrarlanır)."
type: docs
weight: 170
url: /tr/java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo2, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo2

```
public class CurveTo2 extends Operator
```

y operatörünü temsil eden sınıf (eğriyi yola ekler, son nokta tekrarlanır).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CurveTo2](#CurveTo2-double-double-double-double-) | Eğri operatörünü başlatır. |
| [CurveTo2](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-) | Operatör sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getPoints](#getPoints--) | Eğrinin noktaları. |

### CurveTo2 {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```

Eğri operatörünü başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 |  | İkinci noktanın abscisası. |
| y1 |  | İkinci noktanın ordinatı. |
| x3 |  | Üçüncü noktanın abscisası. |
| y3 |  | Üçüncü noktanın ordinatı. |

### CurveTo2 {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-}
Operatör sınıfı için yapıcı.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Eğrinin noktaları.

**Returns:**
Point örneklerinin dizisi
