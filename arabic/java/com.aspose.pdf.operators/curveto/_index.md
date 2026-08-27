---
title: "CurveTo"
linktitle: "CurveTo"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل عامل c (إضافة منحنى إلى المسار)."
type: docs
weight: 150
url: /ar/java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo

```
public class CurveTo extends Operator
```

فئة تمثّل عامل c (إضافة منحنى إلى المسار).

## الحقول

| حقل | الوصف |
| --- | --- |
| [X1](#X1) | يحصل أو يضبط إحداثي X1. |
| [X2](#X2) | يحصل أو يضبط إحداثي X2. |
| [X3](#X3) | يحصل أو يضبط إحداثي X3. |
| [Y1](#Y1) | يحصل أو يضبط إحداثي Y1. |
| [Y2](#Y2) | يحصل أو يضبط إحداثي Y2. |
| [Y3](#Y3) | يحصل أو يضبط إحداثي Y3. |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [CurveTo](#CurveTo-double-double-double-double-double-double-) | يُهيئ مشغل المنحنى. |
| [CurveTo](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-) | منشئ لفئة operator. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [toCommand](#toCommand--) | للاستخدام الداخلي فقط! |
| [toString](#toString--) | يرجع تمثيل النص للمشغل. |

### X1 {#X1}
```
public double X1
```

يحصل أو يضبط إحداثي X1.

### X2 {#X2}
```
public double X2
```

يحصل أو يضبط إحداثي X2.

### X3 {#X3}
```
public double X3
```

يحصل أو يضبط إحداثي X3.

### Y1 {#Y1}
```
public double Y1
```

يحصل أو يضبط إحداثي Y1.

### Y2 {#Y2}
```
public double Y2
```

يحصل أو يضبط إحداثي Y2.

### Y3 {#Y3}
```
public double Y3
```

يحصل أو يضبط إحداثي Y3.

### CurveTo {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```

يُهيئ مشغل المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x1 |  | الإحداثي السيني للنقطة الأولى. |
| y1 |  | الإحداثي الصادي للنقطة الأولى. |
| x2 |  | الإحداثي السيني للنقطة الثانية. |
| y2 |  | الإحداثي الصادي للنقطة الثانية. |
| x3 |  | الإحداثي السيني للنقطة الثالثة. |
| y3 |  | الإحداثي الصادي للنقطة الثالثة. |

### CurveTo {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-}
منشئ لفئة operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

للاستخدام الداخلي فقط!

**Returns:**
قيمة ICommand كائن ICommand

### toString {#toString--}
```
public String toString()
```

يرجع تمثيل النص للمشغل.

**Returns:**
تمثيل النص للمشغل.
