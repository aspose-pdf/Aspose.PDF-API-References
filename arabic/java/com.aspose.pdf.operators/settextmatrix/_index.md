---
title: "SetTextMatrix"
linktitle: "SetTextMatrix"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل معامل Tm (تعيين مصفوفة النص)."
type: docs
weight: 750
url: /ar/java/com.aspose.pdf.operators/settextmatrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.SetTextMatrix

```
public class SetTextMatrix extends TextPlaceOperator
```

فئة تمثل معامل Tm (تعيين مصفوفة النص).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SetTextMatrix](#SetTextMatrix-double-double-double-double-double-double-) | يقوم بتهيئة المشغل. |
| [SetTextMatrix](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-) | يقوم بتهيئة المشغل. |
| [SetTextMatrix](#SetTextMatrix-com.aspose.pdf.Matrix-) | يقوم بتهيئة المشغل باستخدام المصفوفة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getMatrix](#getMatrix--) | معامل المصفوفة للمشغل. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | معامل المصفوفة للمشغل. |
| [toString](#toString--) | يرجع تمثيل النص للمشغل. |

### SetTextMatrix {#SetTextMatrix-double-double-double-double-double-double-}
```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

يقوم بتهيئة المشغل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a |  | معامل A |
| b |  | معامل B |
| c |  | معامل C |
| d |  | معامل D |
| e |  | معامل E |
| f |  | معامل F |

### SetTextMatrix {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-}
يقوم بتهيئة المشغل.

### SetTextMatrix {#SetTextMatrix-com.aspose.pdf.Matrix-}
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

### toString {#toString--}
```
public String toString()
```

يرجع تمثيل النص للمشغل.

**Returns:**
تمثيل النص للمشغل.
