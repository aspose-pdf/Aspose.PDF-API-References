---
title: "IPdfFileEditor.ContentsResizeValue"
linktitle: "IPdfFileEditor.ContentsResizeValue"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "قيمة الهامش أو حجم المحتوى المحددة كنسبة مئوية من وحدات الفضاء الافتراضية. تُستخدم هذه الفئة في ContentsResizeParameters."
type: docs
weight: 310
url: /ar/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

قيمة الهامش أو حجم المحتوى المحددة كنسبة مئوية من وحدات الفضاء الافتراضية. تُستخدم هذه الفئة في ContentsResizeParameters.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [auto](#auto--) | يُهيئ القيمة المحسوبة تلقائيًا. |
| [getValue](#getValue--) | يحصل على القيمة المحددة. استخدم خاصية Unit للحصول على وحدات القيمة. |
| [isPercent](#isPercent--) | يعيد true إذا تم التعبير عن القيمة بالنسب المئوية؛ False إذا تم التعبير عن القيمة بوحدات الافتراضية. |
| [percents](#percents-double-) | يُهيئ القيمة بالنسب المئوية. |
| [setPercentValue](#setPercentValue-double-) | يضبط القيمة بالنسبة المئوية لحجم الصفحة. |
| [setUnitValue](#setUnitValue-double-) | يضبط القيمة بوحدات الفضاء الافتراضية. |
| [units](#units-double-) | يُهيئ القيمة بوحدات الفضاء الافتراضية. |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

يُهيئ القيمة المحسوبة تلقائيًا.

**Returns:**
مثيل قيمة جديد.

### getValue {#getValue--}
```
public final double getValue()
```

يحصل على القيمة المحددة. استخدم خاصية Unit للحصول على وحدات القيمة.

**Returns:**
قيمة double

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

يعيد true إذا تم التعبير عن القيمة بالنسب المئوية؛ False إذا تم التعبير عن القيمة بوحدات الافتراضية.

**Returns:**
قيمة منطقية

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

يُهيئ القيمة بالنسب المئوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | القيمة بالنسبة المئوية. |

**Returns:**
مثيل قيمة جديد.

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

يضبط القيمة بالنسبة المئوية لحجم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

يضبط القيمة بوحدات الفضاء الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

يُهيئ القيمة بوحدات الفضاء الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | القيمة بالوحدات. |

**Returns:**
مثيل قيمة جديد.
