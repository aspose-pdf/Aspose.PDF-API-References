---
title: "Graph"
linktitle: "Graph"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل رسمًا بيانيًا - فقرة مولد الرسومات."
type: docs
weight: 70
url: /ar/java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.drawing.Graph, com.aspose.pdf.BaseParagraph, com.aspose.pdf.drawing.Graph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Graph extends BaseParagraph
```

يمثل رسمًا بيانيًا - فقرة مولد الرسومات.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Graph](#Graph--) | للاستخدام الداخلي فقط |
| [Graph](#Graph-double-double-) | يُنشئ مثيلاً جديدًا للفئة {@link Graph}. |
| [Graph](#Graph-float-float-) | يُنشئ مثيلاً جديدًا للفئة {@code Graph}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone](#deepClone--) | استنسخ الرسم البياني. |
| [getBorder](#getBorder--) | يحصل على الحد. |
| [getGraphInfo](#getGraphInfo--) | يحصل على كائن {@code GraphInfo} يُشير إلى معلومات الرسم البياني، مثل اللون وعرض الخط، إلخ. |
| [getHeight](#getHeight--) | يحصل على قيمة عائمة تُشير إلى ارتفاع الرسم البياني. الوحدة هي النقطة. في XML، الوحدة الافتراضية هي النقطة، لكن السنتيمتر والبوصة مدعومان أيضًا. على سبيل المثال، GraphHeight=\"10cm\" أو GraphHeight=\"5inch\". |
| [getLeft](#getLeft--) | يحصل على إحداثي اليسار للجدول. |
| [getShapes](#getShapes--) | يحصل على مجموعة تُشير إلى جميع الأشكال في الرسم البياني. |
| [getTitle](#getTitle--) | يحصل على قيمة نصية تُشير إلى عنوان الرسم البياني. |
| [getTop](#getTop--) | يحصل على إحداثي أعلى الجدول. |
| [getWidth](#getWidth--) | يحصل على قيمة عائمة تُشير إلى عرض الرسم البياني. الوحدة هي النقطة. في XML، الوحدة الافتراضية هي النقطة، لكن السنتيمتر والبوصة مدعومان أيضًا. على سبيل المثال، GraphWidth=\"10cm\" أو GraphWidth=\"5inch\". |
| [isChangePosition](#isChangePosition--) | يحصل على تغيير موضع الحالي بعد معالجة الفقرة. (القيمة الافتراضية true) |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | يضبط الحد. |
| [setChangePosition](#setChangePosition-boolean-) | يضبط تغيير موضع الحالي بعد معالجة الفقرة. (القيمة الافتراضية true) |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | يحصل أو يضبط كائن {@code GraphInfo} يُشير إلى معلومات الرسم البياني، مثل اللون وعرض الخط، إلخ. |
| [setHeight](#setHeight-double-) | يضبط قيمة عائمة تُشير إلى ارتفاع الرسم البياني. الوحدة هي النقطة. في XML، الوحدة الافتراضية هي النقطة، لكن السنتيمتر والبوصة مدعومان أيضًا. على سبيل المثال، GraphHeight=\"10cm\" أو GraphHeight=\"5inch\". |
| [setLeft](#setLeft-double-) | يضبط إحداثي اليسار للجدول. |
| [setShapes](#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-) | يضبط مجموعة تُشير إلى جميع الأشكال في الرسم البياني. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | يضبط قيمة نصية تُشير إلى عنوان الرسم البياني. |
| [setTop](#setTop-double-) | يضبط إحداثي أعلى الجدول. |
| [setWidth](#setWidth-double-) | يضبط قيمة عائمة تُشير إلى عرض الرسم البياني. الوحدة هي النقطة. في XML، الوحدة الافتراضية هي النقطة، لكن السنتيمتر والبوصة مدعومان أيضًا. على سبيل المثال، GraphWidth=\"10cm\" أو GraphWidth=\"5inch\". |

### Graph {#Graph--}
```
public Graph()
```

للاستخدام الداخلي فقط

### Graph {#Graph-double-double-}
```
public Graph(double width, double height)
```

يُنشئ مثيلاً جديدًا للفئة {@link Graph}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | عرض الرسم البياني. |
| الارتفاع |  | ارتفاع الرسم البياني. |

### Graph {#Graph-float-float-}
```
@Deprecated public Graph(float width, float height)
```

يُنشئ مثيلاً جديدًا للفئة {@code Graph}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | عرض الرسم البياني. |
| الارتفاع |  | ارتفاع الرسم البياني. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

استنسخ الرسم البياني.

**Returns:**
الكائن المستنسخ

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

يحصل على الحد.

**Returns:**
BorderInfo عنصر

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

يحصل على كائن {@code GraphInfo} يُشير إلى معلومات الرسم البياني، مثل اللون وعرض الخط، إلخ.

**Returns:**
GraphInfo كائن

### getHeight {#getHeight--}
```
public double getHeight()
```

يحصل على قيمة عائمة تُشير إلى ارتفاع الرسم البياني. الوحدة هي النقطة. في XML، الوحدة الافتراضية هي النقطة، لكن السنتيمتر والبوصة مدعومان أيضًا. على سبيل المثال، GraphHeight=\"10cm\" أو GraphHeight=\"5inch\".

**Returns:**
القيمة التي تشير إلى ارتفاع الرسم البياني.

### getLeft {#getLeft--}
```
public double getLeft()
```

يحصل على إحداثي اليسار للجدول.

**Returns:**
إحداثي اليسار للجدول.

### getShapes {#getShapes--}
```
public final BoundsCheckableList < Shape > getShapes()
```

يحصل على مجموعة تُشير إلى جميع الأشكال في الرسم البياني.

**Returns:**
BoundsCheckableList من الأشكال.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

يحصل على قيمة نصية تُشير إلى عنوان الرسم البياني.

**Returns:**
عنوان الرسم البياني.

### getTop {#getTop--}
```
public double getTop()
```

يحصل على إحداثي أعلى الجدول.

**Returns:**
إحداثي أعلى الجدول.

### getWidth {#getWidth--}
```
public double getWidth()
```

يحصل على قيمة عائمة تُشير إلى عرض الرسم البياني. الوحدة هي النقطة. في XML، الوحدة الافتراضية هي النقطة، لكن السنتيمتر والبوصة مدعومان أيضًا. على سبيل المثال، GraphWidth=\"10cm\" أو GraphWidth=\"5inch\".

**Returns:**
قيمة عائمة تشير إلى عرض الرسم البياني.

### isChangePosition {#isChangePosition--}
```
public boolean isChangePosition()
```

يحصل على تغيير موضع الحالي بعد معالجة الفقرة. (القيمة الافتراضية true)

**Returns:**
قيمة منطقية

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
يضبط الحد.

### setChangePosition {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```

يضبط تغيير موضع الحالي بعد معالجة الفقرة. (القيمة الافتراضية true)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
يحصل أو يضبط كائن {@code GraphInfo} يُشير إلى معلومات الرسم البياني، مثل اللون وعرض الخط، إلخ.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

يضبط قيمة عائمة تُشير إلى ارتفاع الرسم البياني. الوحدة هي النقطة. في XML، الوحدة الافتراضية هي النقطة، لكن السنتيمتر والبوصة مدعومان أيضًا. على سبيل المثال، GraphHeight=\"10cm\" أو GraphHeight=\"5inch\".

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | التي تشير إلى ارتفاع الرسم البياني. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

يضبط إحداثي اليسار للجدول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | إحداثي اليسار للجدول. |

### setShapes {#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-}
يضبط مجموعة تُشير إلى جميع الأشكال في الرسم البياني.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
يضبط قيمة نصية تُشير إلى عنوان الرسم البياني.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

يضبط إحداثي أعلى الجدول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | إحداثي أعلى الجدول. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

يضبط قيمة عائمة تُشير إلى عرض الرسم البياني. الوحدة هي النقطة. في XML، الوحدة الافتراضية هي النقطة، لكن السنتيمتر والبوصة مدعومان أيضًا. على سبيل المثال، GraphWidth=\"10cm\" أو GraphWidth=\"5inch\".

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة تشير إلى عرض الرسم البياني. |
