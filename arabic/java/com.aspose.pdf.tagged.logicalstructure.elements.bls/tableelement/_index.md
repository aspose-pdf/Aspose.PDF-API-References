---
title: "TableElement"
linktitle: "TableElement"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل عنصر بنية الجدول في البنية المنطقية."
type: docs
weight: 170
url: /ar/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement

**All Implemented Interfaces:**
IAdjustPosition

```
public final class TableElement extends BLSElement implements IAdjustPosition
```

يمثل عنصر بنية الجدول في البنية المنطقية.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TableElement](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | منشئ للاستخدام الداخلي فقط |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | ضبط الموضع. |
| [createTBody](#createTBody--) | ينشئ {@link TableTHeadElement} ويضيفه إلى الجدول الحالي. |
| [createTFoot](#createTFoot--) | ينشئ {@link TableTFootElement} ويضيفه إلى الجدول الحالي. |
| [createTHead](#createTHead--) | ينشئ {@link TableTHeadElement} ويضيفه إلى الجدول الحالي. |
| [getAlignment](#getAlignment--) | يحصل أو يضبط محاذاة الجدول. |
| [getBackgroundColor](#getBackgroundColor--) | يحصل أو يضبط لون خلفية الجدول. |
| [getBorder](#getBorder--) | يحصل أو يضبط حدود الجدول. |
| [getBroken](#getBroken--) | يحصل أو يضبط كسر عمودي للجدول؛ |
| [getColumnAdjustment](#getColumnAdjustment--) | يحصل أو يضبط تعديل عمود الجدول. |
| [getColumnWidths](#getColumnWidths--) | يحصل على عرض أعمدة الجدول. |
| [getCornerStyle](#getCornerStyle--) | يحصل أو يضبط أنماط زوايا الحدود |
| [getDefaultCellBorder](#getDefaultCellBorder--) | يحصل على حد الخلية الافتراضي. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | يحصل أو يضبط الحشو الافتراضي للخلية. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | يحصل أو يضبط حالة نص الخلية الافتراضية. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | يحصل أو يضبط عرض العمود الافتراضي. |
| [getLeft](#getLeft--) | يحصل أو يضبط إحداثي اليسار للجدول. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | يحصل أو يضبط الحد الأقصى لعدد الأعمدة للجدول. |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | يحصل على عدد الصفوف الأولى المتكررة لعدة صفحات. |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | يحصل على النمط للصفوف المتكررة. |
| [getTable](#getTable--) |  |
| [getTop](#getTop--) | يحصل أو يضبط إحداثي أعلى الجدول. |
| [isBordersIncluded](#isBordersIncluded--) | يحصل أو يضبط تضمين الحدود في عرض الأعمدة. |
| [isBroken](#isBroken--) | يحصل أو يضبط كسر الجدول - سيتم اقتطاعه للصفحة التالية. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | يحصل أو يضبط محاذاة الجدول. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | يحصل أو يضبط لون خلفية الجدول. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | يحصل أو يضبط حدود الجدول. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | يحصل أو يضبط تضمين الحدود في عرض الأعمدة. |
| [setBroken](#setBroken-boolean-) | يحصل أو يضبط كسر الجدول - سيتم اقتطاعه للصفحة التالية. |
| [setBroken](#setBroken-int-) | يحصل أو يضبط كسر عمودي للجدول؛ |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | يحصل أو يضبط تعديل عمود الجدول. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | يحصل على عرض أعمدة الجدول. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | يحصل أو يضبط أنماط زوايا الحدود |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | يحصل على حد الخلية الافتراضي. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | يحصل أو يضبط الحشو الافتراضي للخلية. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | يحصل أو يضبط حالة نص الخلية الافتراضية. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | يحصل أو يضبط عرض العمود الافتراضي. |
| [setLeft](#setLeft-float-) | يحصل أو يضبط إحداثي اليسار للجدول. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | يحصل أو يضبط الحد الأقصى لعدد الأعمدة للجدول. |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | يحصل على عدد الصفوف الأولى المتكررة لعدة صفحات. |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | يحصل على النمط للصفوف المتكررة. |
| [setTop](#setTop-float-) | يحصل أو يضبط إحداثي أعلى الجدول. |

### TableElement {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
منشئ للاستخدام الداخلي فقط

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
ضبط الموضع.

### createTBody {#createTBody--}
```
public final TableTBodyElement createTBody()
```

ينشئ {@link TableTHeadElement} ويضيفه إلى الجدول الحالي.

**Returns:**
تم إنشاء عنصر الهيكل.

### createTFoot {#createTFoot--}
```
public final TableTFootElement createTFoot()
```

ينشئ {@link TableTFootElement} ويضيفه إلى الجدول الحالي.

**Returns:**
تم إنشاء عنصر الهيكل.

### createTHead {#createTHead--}
```
public final TableTHeadElement createTHead()
```

ينشئ {@link TableTHeadElement} ويضيفه إلى الجدول الحالي.

**Returns:**
تم إنشاء عنصر الهيكل.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

يحصل أو يضبط محاذاة الجدول.

**Returns:**
عنصر HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

يحصل أو يضبط لون خلفية الجدول.

**Returns:**
مثيل Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

يحصل أو يضبط حدود الجدول.

**Returns:**
مثيل BorderInfo

### getBroken {#getBroken--}
```
public final int getBroken()
```

يحصل أو يضبط كسر عمودي للجدول؛

**Returns:**
عنصر TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

يحصل أو يضبط تعديل عمود الجدول.

**Returns:**
عنصر ColumnAdjustment

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

يحصل أو يضبط أنماط زوايا الحدود

**Returns:**
عنصر BorderCornerStyle

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

يحصل أو يضبط الحشو الافتراضي للخلية.

**Returns:**
مثيل MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

يحصل أو يضبط حالة نص الخلية الافتراضية.

**Returns:**
مثيل TextState

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

يحصل أو يضبط عرض العمود الافتراضي.

**Returns:**
قيمة سلسلة

### getLeft {#getLeft--}
```
public final float getLeft()
```

يحصل أو يضبط إحداثي اليسار للجدول.

**Returns:**
قيمة عائمة

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

يحصل أو يضبط الحد الأقصى لعدد الأعمدة للجدول.

**Returns:**
قيمة int

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

يحصل على عدد الصفوف الأولى المتكررة لعدة صفحات.

**Returns:**
قيمة int

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

يحصل على النمط للصفوف المتكررة.

**Returns:**
مثيل TextState

### getTable {#getTable--}
```
public final Table getTable()
```



### getTop {#getTop--}
```
public final float getTop()
```

يحصل أو يضبط إحداثي أعلى الجدول.

**Returns:**
قيمة عائمة

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

يحصل أو يضبط تضمين الحدود في عرض الأعمدة.

**Returns:**
قيمة منطقية

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

يحصل أو يضبط كسر الجدول - سيتم اقتطاعه للصفحة التالية.

**Returns:**
قيمة منطقية

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
يحصل أو يضبط محاذاة الجدول.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
يحصل أو يضبط لون خلفية الجدول.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
يحصل أو يضبط حدود الجدول.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

يحصل أو يضبط تضمين الحدود في عرض الأعمدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

يحصل أو يضبط كسر الجدول - سيتم اقتطاعه للصفحة التالية.

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
| قيمة |  | عنصر TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
يحصل أو يضبط تعديل عمود الجدول.

### setColumnWidths {#setColumnWidths-java.lang.String-}
يحصل على عرض أعمدة الجدول.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
يحصل أو يضبط أنماط زوايا الحدود

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
يحصل على حد الخلية الافتراضي.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
يحصل أو يضبط الحشو الافتراضي للخلية.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
يحصل أو يضبط حالة نص الخلية الافتراضية.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
يحصل أو يضبط عرض العمود الافتراضي.

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

يحصل أو يضبط إحداثي اليسار للجدول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

يحصل أو يضبط الحد الأقصى لعدد الأعمدة للجدول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

يحصل على عدد الصفوف الأولى المتكررة لعدة صفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
يحصل على النمط للصفوف المتكررة.

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

يحصل أو يضبط إحداثي أعلى الجدول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |
