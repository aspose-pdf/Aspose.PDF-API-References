---
title: "Shape"
linktitle: "Shape"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل شكلًا - كائن الرسومات الأساسي."
type: docs
weight: 130
url: /ar/java/com.aspose.pdf.drawing/shape/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public abstract class Shape extends Object implements IBoundsCheckableItem
```

يمثل شكلًا - كائن الرسومات الأساسي.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Shape](#Shape--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | يتحقق مما إذا كان العنصر يتناسب مع أبعاد الحاوية المحددة (شاملاً). |
| [getGraphInfo](#getGraphInfo--) | يحصل على الكائن الذي يشير إلى معلومات الرسم البياني، مثل اللون، عرض الخط، إلخ. |
| [getText](#getText--) | يحصل أو يضبط نصًا للشكل |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | يضبط الكائن الذي يشير إلى معلومات الرسم البياني، مثل اللون، عرض الخط، إلخ. |
| [setText](#setText-com.aspose.pdf.TextFragment-) | يحصل أو يضبط نصًا للشكل |

### Shape {#Shape--}
```
public Shape()
```



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

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

يحصل على الكائن الذي يشير إلى معلومات الرسم البياني، مثل اللون، عرض الخط، إلخ.

**Returns:**
الكائن الذي يشير إلى معلومات الرسم البياني.

### getText {#getText--}
```
public TextFragment getText()
```

يحصل أو يضبط نصًا للشكل

**Returns:**
TextFragment كائن

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
يضبط الكائن الذي يشير إلى معلومات الرسم البياني، مثل اللون، عرض الخط، إلخ.

### setText {#setText-com.aspose.pdf.TextFragment-}
يحصل أو يضبط نصًا للشكل
