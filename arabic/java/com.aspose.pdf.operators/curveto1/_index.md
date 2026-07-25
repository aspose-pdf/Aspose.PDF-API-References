---
title: "CurveTo1"
linktitle: "CurveTo1"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل عامل v (إضافة منحنى إلى المسار، تكرار النقطة الأولية)."
type: docs
weight: 160
url: /ar/java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo1, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo1

```
public class CurveTo1 extends Operator
```

فئة تمثّل عامل v (إضافة منحنى إلى المسار، تكرار النقطة الأولية).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [CurveTo1](#CurveTo1-double-double-double-double-) | يُهيئ مشغل المنحنى. |
| [CurveTo1](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-) | منشئ لفئة operator. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل محدد المشغل. |
| [getPoints](#getPoints--) | نقاط المنحنى. |

### CurveTo1 {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```

يُهيئ مشغل المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x2 |  | الإحداثي السيني للنقطة الثانية. |
| y2 |  | الإحداثي الصادي للنقطة الثانية. |
| x3 |  | الإحداثي السيني للنقطة الثالثة. |
| y3 |  | الإحداثي الصادي للنقطة الثالثة. |

### CurveTo1 {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-}
منشئ لفئة operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل محدد المشغل.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

نقاط المنحنى.

**Returns:**
مصفوفة من مثيلات Point
