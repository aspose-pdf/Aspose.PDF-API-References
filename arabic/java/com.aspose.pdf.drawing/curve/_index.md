---
title: "Curve"
linktitle: "Curve"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل منحنى بيزيه."
type: docs
weight: 30
url: /ar/java/com.aspose.pdf.drawing/curve/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Curve, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Curve

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Curve extends Shape
```

يمثل منحنى بيزيه.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Curve](#Curve--) | للاستخدام الداخلي فقط |
| [Curve](#Curve-float:A-) | يُهيئ نسخة جديدة من الفئة {@code Curve}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | يتحقق مما إذا كان العنصر يتناسب مع أبعاد الحاوية المحددة (شاملاً). |
| [getPositionArray](#getPositionArray--) | يحصل على مصفوفة موضع من نوع float. |
| [setPositionArray](#setPositionArray-float:A-) | يعيّن مصفوفة موضع من نوع float. |

### Curve {#Curve--}
```
public Curve()
```

للاستخدام الداخلي فقط

### Curve {#Curve-float:A-}
```
public Curve(float[] positionArray)
```

يُهيئ نسخة جديدة من الفئة {@code Curve}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| positionArray |  | مصفوفة الموضع لنقاط التحكم في المنحنى. يجب أن تكون هناك أربع نقاط تحكم، لذا يجب أن يكون طول المصفوفة ثمانية. |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

يتحقق مما إذا كان العنصر يتناسب مع أبعاد الحاوية المحددة (شاملاً).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
صحيح إذا كان يتناسب؛ وإلا، خطأ.

### getPositionArray {#getPositionArray--}
```
public float[] getPositionArray()
```

يحصل على مصفوفة موضع من نوع float.

**Returns:**
مصفوفة float[]

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

يعيّن مصفوفة موضع من نوع float.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | مصفوفة float[] |
