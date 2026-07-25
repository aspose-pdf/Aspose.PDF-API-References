---
title: "TableCellElement"
linktitle: "TableCellElement"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة أساسية لعناصر خلايا الجدول (TH و TD) في البنية المنطقية."
type: docs
weight: 150
url: /ar/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class TableCellElement extends TableChildElement implements ITextElement , IAdjustPosition
```

يمثل فئة أساسية لعناصر خلايا الجدول (TH و TD) في البنية المنطقية.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | ضبط الموضع. |
| [getAlignment](#getAlignment--) | يحصل أو يضبط محاذاة الخلية. |
| [getBackgroundColor](#getBackgroundColor--) | يحصل أو يضبط لون خلفية الخلية. |
| [getBorder](#getBorder--) | يحصل أو يضبط حد الخلية. |
| [getCell](#getCell--) |  |
| [getColSpan](#getColSpan--) | يحصل على أو يضبط امتداد العمود. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | يحصل أو يضبط حالة نص الخلية الافتراضية. |
| [getMargin](#getMargin--) | يحصل أو يضبط الحشو. |
| [getRowSpan](#getRowSpan--) | يحصل أو يضبط امتداد الصف. |
| [getStructureTextState](#getStructureTextState--) | يحصل على كائن {@code /Aspose.Pdf.LogicalStructure.StructureTextState} للعنصر الحالي. القيمة: كائن {@code /Aspose.Pdf.LogicalStructure.StructureTextState} للعنصر الحالي. |
| [getVerticalAlignment](#getVerticalAlignment--) | يحصل أو يضبط المحاذاة العمودية. |
| [isNoBorder](#isNoBorder--) | يحصل أو يضبط ما إذا كانت الخلية لها حد. |
| [isWordWrapped](#isWordWrapped--) | يحصل أو يضبط التفاف النص داخل الخلية. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | يحصل أو يضبط محاذاة الخلية. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | يحصل أو يضبط لون خلفية الخلية. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | يحصل أو يضبط حد الخلية. |
| [setColSpan](#setColSpan-int-) | يحصل على أو يضبط امتداد العمود. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | يحصل أو يضبط حالة نص الخلية الافتراضية. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | يحصل أو يضبط الحشو. |
| [setNoBorder](#setNoBorder-boolean-) | يحصل أو يضبط ما إذا كانت الخلية لها حد. |
| [setRowSpan](#setRowSpan-int-) | يحصل أو يضبط امتداد الصف. |
| [setText](#setText-java.lang.String-) | يضيف محتوى النص إلى العنصر النصي الحالي. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | يحصل أو يضبط المحاذاة العمودية. |
| [setWordWrapped](#setWordWrapped-boolean-) | يحصل أو يضبط التفاف النص داخل الخلية. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
ضبط الموضع.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

يحصل أو يضبط محاذاة الخلية.

**Returns:**
عنصر HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

يحصل أو يضبط لون خلفية الخلية.

**Returns:**
مثيل Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

يحصل أو يضبط حد الخلية.

**Returns:**
مثيل BorderInfo

### getCell {#getCell--}
```
public final Cell getCell()
```



### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

يحصل على أو يضبط امتداد العمود.

**Returns:**
قيمة int

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

يحصل أو يضبط حالة نص الخلية الافتراضية.

**Returns:**
مثيل TextState

### getMargin {#getMargin--}
```
public final MarginInfo getMargin()
```

يحصل أو يضبط الحشو.

**Returns:**
مثيل MarginInfo

### getRowSpan {#getRowSpan--}
```
public final int getRowSpan()
```

يحصل أو يضبط امتداد الصف.

**Returns:**
قيمة int

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

يحصل على كائن {@code /Aspose.Pdf.LogicalStructure.StructureTextState} للعنصر الحالي. القيمة: كائن {@code /Aspose.Pdf.LogicalStructure.StructureTextState} للعنصر الحالي.

**Returns:**
مثيل StructureTextState

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

يحصل أو يضبط المحاذاة العمودية.

**Returns:**
عنصر VerticalAlignment

### isNoBorder {#isNoBorder--}
```
public final boolean isNoBorder()
```

يحصل أو يضبط ما إذا كانت الخلية لها حد.

**Returns:**
قيمة منطقية

### isWordWrapped {#isWordWrapped--}
```
public final boolean isWordWrapped()
```

يحصل أو يضبط التفاف النص داخل الخلية.

**Returns:**
قيمة منطقية

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
يحصل أو يضبط محاذاة الخلية.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
يحصل أو يضبط لون خلفية الخلية.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
يحصل أو يضبط حد الخلية.

### setColSpan {#setColSpan-int-}
```
public final void setColSpan(int value)
```

يحصل على أو يضبط امتداد العمود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
يحصل أو يضبط حالة نص الخلية الافتراضية.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
يحصل أو يضبط الحشو.

### setNoBorder {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```

يحصل أو يضبط ما إذا كانت الخلية لها حد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRowSpan {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```

يحصل أو يضبط امتداد الصف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setText {#setText-java.lang.String-}
يضيف محتوى النص إلى العنصر النصي الحالي.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
يحصل أو يضبط المحاذاة العمودية.

### setWordWrapped {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```

يحصل أو يضبط التفاف النص داخل الخلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
