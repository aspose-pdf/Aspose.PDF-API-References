---
title: "Row"
linktitle: "Row"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل صفًا في الجدول."
type: docs
weight: 4330
url: /ar/java/com.aspose.pdf/row/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Row

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Row extends Object implements com.aspose.ms.System.ICloneable
```

يمثل صفًا في الجدول.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Row](#Row--) | ينشئ مثيلًا جديدًا من الفئة Row. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone](#deepClone--) | استنساخ الصف. |
| [getBackgroundColor](#getBackgroundColor--) | يحصل على لون الخلفية. |
| [getBorder](#getBorder--) | يحصل على الحد. |
| [getCells](#getCells--) | يحصل على getCells() للصف. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | يحصل على حد الخلية الافتراضي؛ |
| [getDefaultCellPadding](#getDefaultCellPadding--) | يحصل على الهامش الافتراضي للصف getCells() |
| [getDefaultCellTextState](#getDefaultCellTextState--) | يحصل أو يضبط حالة النص الافتراضية للصف getCells() يحصل على حالة النص الافتراضية للصف getCells() |
| [getFixedRowHeight](#getFixedRowHeight--) | يحصل على ارتفاع الصف الثابت - قد يكون للصف ارتفاع ثابت؛ |
| [getMinRowHeight](#getMinRowHeight--) | يحصل على ارتفاع الصف؛ |
| [getVerticalAlignment](#getVerticalAlignment--) | يحصل أو يضبط المحاذاة العمودية. |
| [isInNewPage](#isInNewPage--) | يحصل على ما إذا كان الصف الثابت في صفحة جديدة - يجب طباعة الصفحة التي تحتوي على هذه الخاصية إلى الصفحة التالية الافتراضي false؛ |
| [isRowBroken](#isRowBroken--) | يحصل على ما إذا كان يمكن كسر الصف بين صفحتين |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | يضبط لون الخلفية. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | يضبط الحد. |
| [setCells](#setCells-com.aspose.pdf.Cells-) | يضبط getCells() للصف. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | يضبط حد الخلية الافتراضي؛ |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | يضبط الهامش الافتراضي للصف getCells() |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | يضبط حالة النص الافتراضية للصف getCells() |
| [setFixedRowHeight](#setFixedRowHeight-double-) | يضبط ارتفاع الصف الثابت - قد يكون للصف ارتفاع ثابت؛ |
| [setInNewPage](#setInNewPage-boolean-) | يضبط ما إذا كان يمكن كسر الصف بين صفحتين |
| [setMinRowHeight](#setMinRowHeight-double-) | يضبط ارتفاع الصف؛ |
| [setRowBroken](#setRowBroken-boolean-) | يضبط ما إذا كان يمكن كسر الصف بين صفحتين |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | يحصل أو يضبط المحاذاة العمودية. |

### Row {#Row--}
```
public Row()
```

ينشئ مثيلًا جديدًا من الفئة Row.

### deepClone {#deepClone--}
```
public Object deepClone()
```

استنساخ الصف.

**Returns:**
الكائن المستنسخ

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

يحصل على لون الخلفية.

**Returns:**
قيمة اللون

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

يحصل على الحد.

**Returns:**
قيمة BorderInfo

### getCells {#getCells--}
```
public Cells getCells()
```

يحصل على getCells() للصف.

**Returns:**
قيمة getCells()

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```

يحصل على حد الخلية الافتراضي؛

**Returns:**
قيمة BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```

يحصل على الهامش الافتراضي للصف getCells()

**Returns:**
قيمة MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

يحصل أو يضبط حالة النص الافتراضية للصف getCells() يحصل على حالة النص الافتراضية للصف getCells()

**Returns:**
قيمة TextState

### getFixedRowHeight {#getFixedRowHeight--}
```
public double getFixedRowHeight()
```

يحصل على ارتفاع الصف الثابت - قد يكون للصف ارتفاع ثابت؛

**Returns:**
قيمة double

### getMinRowHeight {#getMinRowHeight--}
```
public double getMinRowHeight()
```

يحصل على ارتفاع الصف؛

**Returns:**
قيمة double

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

يحصل أو يضبط المحاذاة العمودية.

**Returns:**
عنصر VerticalAlignment @see VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

يحصل على ما إذا كان الصف الثابت في صفحة جديدة - يجب طباعة الصفحة التي تحتوي على هذه الخاصية إلى الصفحة التالية الافتراضي false؛

**Returns:**
قيمة منطقية

### isRowBroken {#isRowBroken--}
```
public boolean isRowBroken()
```

يحصل على ما إذا كان يمكن كسر الصف بين صفحتين

**Returns:**
قيمة منطقية

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
يضبط لون الخلفية.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
يضبط الحد.

### setCells {#setCells-com.aspose.pdf.Cells-}
يضبط getCells() للصف.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
يضبط حد الخلية الافتراضي؛

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
يضبط الهامش الافتراضي للصف getCells()

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
يضبط حالة النص الافتراضية للصف getCells()

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public void setFixedRowHeight(double value)
```

يضبط ارتفاع الصف الثابت - قد يكون للصف ارتفاع ثابت؛

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

يضبط ما إذا كان يمكن كسر الصف بين صفحتين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMinRowHeight {#setMinRowHeight-double-}
```
public void setMinRowHeight(double value)
```

يضبط ارتفاع الصف؛

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setRowBroken {#setRowBroken-boolean-}
```
public void setRowBroken(boolean value)
```

يضبط ما إذا كان يمكن كسر الصف بين صفحتين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
يحصل أو يضبط المحاذاة العمودية.
