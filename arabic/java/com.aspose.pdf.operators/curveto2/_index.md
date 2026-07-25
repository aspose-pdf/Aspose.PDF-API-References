---
title: "CurveTo2"
linktitle: "CurveTo2"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل عامل y (إضافة منحنى إلى المسار، تكرار النقطة النهائية)."
type: docs
weight: 170
url: /ar/java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo2, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo2

```
public class CurveTo2 extends Operator
```

فئة تمثّل عامل y (إضافة منحنى إلى المسار، تكرار النقطة النهائية).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [CurveTo2](#CurveTo2-double-double-double-double-) | يُهيئ مشغل المنحنى. |
| [CurveTo2](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-) | منشئ لفئة operator. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getPoints](#getPoints--) | نقاط المنحنى. |

### CurveTo2 {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```

يُهيئ مشغل المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x1 |  | الإحداثي السيني للنقطة الثانية. |
| y1 |  | الإحداثي الصادي للنقطة الثانية. |
| x3 |  | الإحداثي السيني للنقطة الثالثة. |
| y3 |  | الإحداثي الصادي للنقطة الثالثة. |

### CurveTo2 {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-}
منشئ لفئة operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

نقاط المنحنى.

**Returns:**
مصفوفة من مثيلات Point
