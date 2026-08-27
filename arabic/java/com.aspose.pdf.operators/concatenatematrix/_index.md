---
title: "ConcatenateMatrix"
linktitle: "ConcatenateMatrix"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل عامل cm (دمج المصفوفة مع مصفوفة التحويل الحالية)."
type: docs
weight: 140
url: /ar/java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.ConcatenateMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.ConcatenateMatrix

```
public class ConcatenateMatrix extends Operator
```

فئة تمثّل عامل cm (دمج المصفوفة مع مصفوفة التحويل الحالية).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ConcatenateMatrix](#ConcatenateMatrix-double-double-double-double-double-double-) | منشئ لفئة operator. |
| [ConcatenateMatrix](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-) | منشئ لفئة operator. |
| [ConcatenateMatrix](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | يقوم بتهيئة المشغل باستخدام المصفوفة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getMatrix](#getMatrix--) | معامل المصفوفة للمشغل. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | معامل المصفوفة للمشغل. |
| [toCommand](#toCommand--) | للاستخدام الداخلي فقط! |
| [toString](#toString--) | يرجع تمثيل النص للمشغل. |

### ConcatenateMatrix {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```

منشئ لفئة operator.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a |  | معامل A |
| b |  | معامل B |
| c |  | معامل C |
| d |  | معامل D |
| e |  | معامل E |
| f |  | معامل F |

### ConcatenateMatrix {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-}
منشئ لفئة operator.

### ConcatenateMatrix {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
يقوم بتهيئة المشغل باستخدام المصفوفة.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

معامل المصفوفة للمشغل.

**Returns:**
كائن Matrix

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
معامل المصفوفة للمشغل.

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
تمثيل نصي للتمثيل
