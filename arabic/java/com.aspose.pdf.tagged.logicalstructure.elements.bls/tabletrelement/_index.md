---
title: "TableTRElement"
linktitle: "TableTRElement"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل عنصر بنية TR في البنية المنطقية للجدول."
type: docs
weight: 240
url: /ar/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement

```
public final class TableTRElement extends TableChildElement
```

يمثل عنصر بنية TR في البنية المنطقية للجدول.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TableTRElement](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | منشئ للاستخدام الداخلي فقط |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [createTD](#createTD--) | ينشئ {@link TableTHElement} ويضيفه إلى الجدول الحالي. |
| [createTH](#createTH--) | ينشئ {@link TableTHElement} ويضيفه إلى الجدول الحالي. |
| [getBackgroundColor](#getBackgroundColor--) | يحصل أو يضبط لون خلفية الصف. |
| [getBorder](#getBorder--) | يحصل أو يضبط حد الصف. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | يحصل على حد الخلية الافتراضي. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | يحصل أو يضبط الهامش الافتراضي لخلايا الصف. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | يحصل أو يضبط حالة النص الافتراضية لخلايا الصف |
| [getFixedRowHeight](#getFixedRowHeight--) | يحصل على ارتفاع الصف الثابت - قد يكون للصف ارتفاع ثابت. |
| [getMinRowHeight](#getMinRowHeight--) | يحصل على ارتفاع الصف. |
| [getVerticalAlignment](#getVerticalAlignment--) | يحصل أو يضبط المحاذاة العمودية. |
| [isInNewPage](#isInNewPage--) | يحصل على ما إذا كان الصف الثابت في صفحة جديدة - يجب طباعة الصفحة التي تحتوي على هذه الخاصية إلى الصفحة التالية. القيمة الافتراضية خاطئة. |
| [isRowBroken](#isRowBroken--) | يحصل على ما إذا كان يمكن كسر الصف بين صفحتين. |
| [preSave](#preSave--) |  |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | يحصل أو يضبط لون خلفية الصف. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | يحصل أو يضبط حد الصف. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | يحصل على حد الخلية الافتراضي. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | يحصل أو يضبط الهامش الافتراضي لخلايا الصف. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | يحصل أو يضبط حالة النص الافتراضية لخلايا الصف |
| [setFixedRowHeight](#setFixedRowHeight-double-) | يحصل على ارتفاع الصف الثابت - قد يكون للصف ارتفاع ثابت. |
| [setInNewPage](#setInNewPage-boolean-) | يحصل على ما إذا كان الصف الثابت في صفحة جديدة - يجب طباعة الصفحة التي تحتوي على هذه الخاصية إلى الصفحة التالية. القيمة الافتراضية خاطئة. |
| [setMinRowHeight](#setMinRowHeight-double-) | يحصل على ارتفاع الصف. |
| [setRowBroken](#setRowBroken-boolean-) | يحصل على ما إذا كان يمكن كسر الصف بين صفحتين. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | يحصل أو يضبط المحاذاة العمودية. |

### TableTRElement {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
منشئ للاستخدام الداخلي فقط

### createTD {#createTD--}
```
public final TableTDElement createTD()
```

ينشئ {@link TableTHElement} ويضيفه إلى الجدول الحالي.

**Returns:**
تم إنشاء عنصر الهيكل.

### createTH {#createTH--}
```
public final TableTHElement createTH()
```

ينشئ {@link TableTHElement} ويضيفه إلى الجدول الحالي.

**Returns:**
تم إنشاء عنصر الهيكل.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

يحصل أو يضبط لون خلفية الصف.

**Returns:**
مثيل Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

يحصل أو يضبط حد الصف.

**Returns:**
مثيل BorderInfo

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

يحصل على حد الخلية الافتراضي.

**Returns:**
مثيل BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

يحصل أو يضبط الهامش الافتراضي لخلايا الصف.

**Returns:**
مثيل MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

يحصل أو يضبط حالة النص الافتراضية لخلايا الصف

**Returns:**
مثيل TextState

### getFixedRowHeight {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```

يحصل على ارتفاع الصف الثابت - قد يكون للصف ارتفاع ثابت.

**Returns:**
قيمة double

### getMinRowHeight {#getMinRowHeight--}
```
public final double getMinRowHeight()
```

يحصل على ارتفاع الصف.

**Returns:**
قيمة double

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

يحصل أو يضبط المحاذاة العمودية.

**Returns:**
عنصر VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public final boolean isInNewPage()
```

يحصل على ما إذا كان الصف الثابت في صفحة جديدة - يجب طباعة الصفحة التي تحتوي على هذه الخاصية إلى الصفحة التالية. القيمة الافتراضية خاطئة.

**Returns:**
قيمة منطقية

### isRowBroken {#isRowBroken--}
```
public final boolean isRowBroken()
```

يحصل على ما إذا كان يمكن كسر الصف بين صفحتين.

**Returns:**
قيمة منطقية

### preSave {#preSave--}
```
public void preSave()
```



### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
يحصل أو يضبط لون خلفية الصف.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
يحصل أو يضبط حد الصف.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
يحصل على حد الخلية الافتراضي.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
يحصل أو يضبط الهامش الافتراضي لخلايا الصف.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
يحصل أو يضبط حالة النص الافتراضية لخلايا الصف

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```

يحصل على ارتفاع الصف الثابت - قد يكون للصف ارتفاع ثابت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setInNewPage {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```

يحصل على ما إذا كان الصف الثابت في صفحة جديدة - يجب طباعة الصفحة التي تحتوي على هذه الخاصية إلى الصفحة التالية. القيمة الافتراضية خاطئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMinRowHeight {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```

يحصل على ارتفاع الصف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setRowBroken {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```

يحصل على ما إذا كان يمكن كسر الصف بين صفحتين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
يحصل أو يضبط المحاذاة العمودية.
