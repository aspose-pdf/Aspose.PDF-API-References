---
title: "جدول"
linktitle: "جدول"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل جدولًا يمكن إضافته إلى الصفحة."
type: docs
weight: 4790
url: /ar/java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Table, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Table

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Table extends BaseParagraph
```

يمثل جدولًا يمكن إضافته إلى الصفحة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Table](#Table--) | البناء الافتراضي |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone](#deepClone--) | / * / * يستورد مصفوفة أحادية البعد من البيانات إلى الجدول. الاستيراد يضع خلية واحدة لكل عنصر من عناصر المصفوفة و / * يبدأ من الصف والعمود المحددين في المعلمات. أثناء الاستيراد، إذا تم اكتشاف أن الصفوف اللازمة / * لا تزال غائبة (أي أن جدول الهدف صغير جدًا لاستيعاب جميع البيانات)، سيتم إنشاء الصفوف اللازمة / * / * |
| [drawRoundedRectangle](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-) | أضف عوامل للمستطيل. |
| [getAlignment](#getAlignment--) | يحصل على محاذاة الجدول. |
| [getBackgroundColor](#getBackgroundColor--) | يحصل على لون خلفية الجدول |
| [getBorder](#getBorder--) | يحصل على الحد. |
| [getBreakText](#getBreakText--) | يحصل على نص الفاصل للجدول |
| [getBroken](#getBroken--) | يحصل أو يضبط كسر عمودي للجدول؛ |
| [getColumnAdjustment](#getColumnAdjustment--) | يحصل على تعديل أعمدة الجدول. |
| [getColumnWidth](#getColumnWidth-java.lang.String-) | احصل على عرض العمود |
| [getColumnWidths](#getColumnWidths--) | يحصل على عرض أعمدة الجدول. |
| [getCornerStyle](#getCornerStyle--) | يحصل على أنماط زوايا الحدود |
| [getDefaultCellBorder](#getDefaultCellBorder--) | يحصل على حد الخلية الافتراضي؛ |
| [getDefaultCellPadding](#getDefaultCellPadding--) | يحصل على الحشو الافتراضي للخلية. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | يحصل على حالة نص الخلية الافتراضية. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | يحصل على حد الخلية الافتراضي؛ |
| [getHeight](#getHeight--) | احصل على الارتفاع. |
| [getHeight](#getHeight-com.aspose.pdf.Page-) | احصل على الارتفاع. |
| [getLeft](#getLeft--) | يحصل على إحداثي اليسار للجدول. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | يحصل أو يضبط الحد الأقصى لعدد الأعمدة للجدول |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | يحصل على عدد الصفوف الأولى المتكررة لعدة صفحات |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | يحصل على النمط للصفوف المتكررة |
| [getRows](#getRows--) | يحصل على صفوف الجدول. |
| [getTop](#getTop--) | يحصل على إحداثي أعلى الجدول. |
| [getWidth](#getWidth--) | احصل على العرض. |
| [isBordersIncluded](#isBordersIncluded--) | يحصل على تضمين الحدود في عرض الأعمدة. |
| [isBroken](#isBroken--) | يحصل على أن الجدول مكسور - سيتم قطعه للصفحة التالية. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | يضبط محاذاة الجدول. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | يضبط لون خلفية الجدول |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | يضبط الحد. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | يضبط تضمين الحدود في عرض الأعمدة. |
| [setBreakText](#setBreakText-com.aspose.pdf.TextFragment-) | يضبط نص الفاصل للجدول |
| [setBroken](#setBroken-boolean-) | يضبط أن الجدول مكسور - سيتم قطعه للصفحة التالية. |
| [setBroken](#setBroken-int-) | يحصل أو يضبط كسر عمودي للجدول؛ |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | يضبط تعديل أعمدة الجدول. |
| [setColumnTextState](#setColumnTextState-int-com.aspose.pdf.TextState-) | اضبط الارتفاع. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | يحصل على عرض أعمدة الجدول. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | يحصل أو يضبط أنماط زوايا الحدود |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | يحصل على حد الخلية الافتراضي؛ |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | يضبط الحشو الافتراضي للخلية. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | يضبط حالة النص الافتراضية للخلية. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | يحصل على حد الخلية الافتراضي؛ |
| [setLeft](#setLeft-float-) | يضبط إحداثي اليسار للجدول. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | يحصل أو يضبط الحد الأقصى لعدد الأعمدة للجدول |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | يحصل على عدد الصفوف الأولى المتكررة لعدة صفحات |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | يحصل على النمط للصفوف المتكررة |
| [setTop](#setTop-float-) | يضبط إحداثي أعلى الجدول. |

### Table {#Table--}
```
public Table()
```

البناء الافتراضي

### deepClone {#deepClone--}
```
public Object deepClone()
```

/ * / * يستورد مصفوفة أحادية البعد من البيانات إلى الجدول. الاستيراد يضع خلية واحدة لكل عنصر من عناصر المصفوفة و / * يبدأ من الصف والعمود المحددين في المعلمات. أثناء الاستيراد، إذا تم اكتشاف أن الصفوف اللازمة / * لا تزال غائبة (أي أن جدول الهدف صغير جدًا لاستيعاب جميع البيانات)، سيتم إنشاء الصفوف اللازمة / * / *

**Returns:**
الكائن المستنسخ

### drawRoundedRectangle {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-}
أضف عوامل للمستطيل.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

يحصل على محاذاة الجدول.

**Returns:**
قيمة HorizontalAlignment @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

يحصل على لون خلفية الجدول

**Returns:**
كائن Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

يحصل على الحد.

**Returns:**
كائن BorderInfo

### getBreakText {#getBreakText--}
```
public final TextFragment getBreakText()
```

يحصل على نص الفاصل للجدول

**Returns:**
TextFragment كائن

### getBroken {#getBroken--}
```
public final int getBroken()
```

يحصل أو يضبط كسر عمودي للجدول؛

**Returns:**
قيمة TableBroken @see TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

يحصل على تعديل أعمدة الجدول.

**Returns:**
قيمة ColumnAdjustment @see ColumnAdjustment

### getColumnWidth {#getColumnWidth-java.lang.String-}
احصل على عرض العمود

### getColumnWidths {#getColumnWidths--}
```
public final String getColumnWidths()
```

يحصل على عرض أعمدة الجدول.

**Returns:**
قيمة سلسلة

### getCornerStyle {#getCornerStyle--}
```
public final BorderCornerStyle getCornerStyle()
```

يحصل على أنماط زوايا الحدود

**Returns:**
قيمة BorderCornerStyle @see BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

يحصل على حد الخلية الافتراضي؛

**Returns:**
كائن BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

يحصل على الحشو الافتراضي للخلية.

**Returns:**
كائن MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

يحصل على حالة نص الخلية الافتراضية.

**Returns:**
قيمة TextState

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

يحصل على حد الخلية الافتراضي؛

**Returns:**
كائن String

### getHeight {#getHeight--}
```
public double getHeight()
```

احصل على الارتفاع.

**Returns:**
ارتفاع الجدول

### getHeight {#getHeight-com.aspose.pdf.Page-}
احصل على الارتفاع.

**Returns:**
ارتفاع الجدول

### getLeft {#getLeft--}
```
public final float getLeft()
```

يحصل على إحداثي اليسار للجدول.

**Returns:**
قيمة عائمة

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

يحصل أو يضبط الحد الأقصى لعدد الأعمدة للجدول

**Returns:**
قيمة int

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

يحصل على عدد الصفوف الأولى المتكررة لعدة صفحات

**Returns:**
قيمة int

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

يحصل على النمط للصفوف المتكررة

**Returns:**
كائن TextState

### getRows {#getRows--}
```
public final Rows getRows()
```

يحصل على صفوف الجدول.

**Returns:**
كائن Rows

### getTop {#getTop--}
```
public final float getTop()
```

يحصل على إحداثي أعلى الجدول.

**Returns:**
قيمة عائمة

### getWidth {#getWidth--}
```
public double getWidth()
```

احصل على العرض.

**Returns:**
عرض الجدول

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

يحصل على تضمين الحدود في عرض الأعمدة.

**Returns:**
قيمة منطقية

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

يحصل على أن الجدول مكسور - سيتم قطعه للصفحة التالية.

**Returns:**
قيمة منطقية

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
يضبط محاذاة الجدول.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
يضبط لون خلفية الجدول

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
يضبط الحد.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

يضبط تضمين الحدود في عرض الأعمدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setBreakText {#setBreakText-com.aspose.pdf.TextFragment-}
يضبط نص الفاصل للجدول

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

يضبط أن الجدول مكسور - سيتم قطعه للصفحة التالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

يحصل أو يضبط كسر عمودي للجدول؛

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة TableBroken @see TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
يضبط تعديل أعمدة الجدول.

### setColumnTextState {#setColumnTextState-int-com.aspose.pdf.TextState-}
اضبط الارتفاع.

### setColumnWidths {#setColumnWidths-java.lang.String-}
يحصل على عرض أعمدة الجدول.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
يحصل أو يضبط أنماط زوايا الحدود

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
يحصل على حد الخلية الافتراضي؛

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
يضبط الحشو الافتراضي للخلية.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
يضبط حالة النص الافتراضية للخلية.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
يحصل على حد الخلية الافتراضي؛

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

يضبط إحداثي اليسار للجدول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

يحصل أو يضبط الحد الأقصى لعدد الأعمدة للجدول

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

يحصل على عدد الصفوف الأولى المتكررة لعدة صفحات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
يحصل على النمط للصفوف المتكررة

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

يضبط إحداثي أعلى الجدول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |
