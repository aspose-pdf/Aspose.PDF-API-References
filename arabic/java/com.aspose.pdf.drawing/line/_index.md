---
title: "Line"
linktitle: "Line"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خطًا."
type: docs
weight: 90
url: /ar/java/com.aspose.pdf.drawing/line/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Line, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Line

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Line extends Shape
```

يمثل خطًا.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Line](#Line--) | للاستخدام الداخلي فقط |
| [Line](#Line-float:A-) | يُنشئ مثيلًا جديدًا للفئة {@code Line}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | يتحقق مما إذا كان العنصر يتناسب مع أبعاد الحاوية المحددة (شاملاً). |
| [getPositionArray](#getPositionArray--) | يحصل على الكائن الذي يشير إلى مصفوفة الموضع. المصفوفة مكوّنة من إحداثيات كل نقطة تحكم في الخط. مباشرة. |
| [setPositionArray](#setPositionArray-float:A-) | يضبط الكائن الذي يشير إلى مصفوفة الموضع. المصفوفة مكوّنة من إحداثيات كل نقطة تحكم في الخط. مباشرة. |

### Line {#Line--}
```
public Line()
```

للاستخدام الداخلي فقط

### Line {#Line-float:A-}
```
public Line(float[] positionArray)
```

يُنشئ مثيلًا جديدًا للفئة {@code Line}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| positionArray |  | مصفوفة موضع الخط. |

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

يحصل على الكائن الذي يشير إلى مصفوفة الموضع. المصفوفة مكوّنة من إحداثيات كل نقطة تحكم في الخط. مباشرة.

**Returns:**
التي تشير إلى مصفوفة الموضع.

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

يضبط الكائن الذي يشير إلى مصفوفة الموضع. المصفوفة مكوّنة من إحداثيات كل نقطة تحكم في الخط. مباشرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | التي تشير إلى مصفوفة الموضع. |
