---
title: "Cell"
linktitle: "Cell"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خلية من صف الجدول."
type: docs
weight: 510
url: /ar/java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Cell

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Cell extends Object implements com.aspose.ms.System.ICloneable
```

يمثل خلية من صف الجدول.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Cell](#Cell--) | يُهيئ نسخة جديدة من الفئة Cell. |
| [Cell](#Cell-com.aspose.pdf.Rectangle-) | يُهيئ نسخة جديدة من الفئة Cell. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone](#deepClone--) | استنساخ الخلية. |
| [getAlignment](#getAlignment--) | يحصل على المحاذاة. |
| [getBackgroundColor](#getBackgroundColor--) | يحصل على لون الخلفية. |
| [getBackgroundImage](#getBackgroundImage--) | يحصل على أو يضبط صورة الخلفية |
| [getBackgroundImageFile](#getBackgroundImageFile--) | يحصل على ملف صورة الخلفية. |
| [getBorder](#getBorder--) | يحصل على الحد. |
| [getColSpan](#getColSpan--) | يحصل على أو يضبط امتداد العمود. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | يحصل على حالة نص الخلية الافتراضية. |
| [getMargin](#getMargin--) | يحصل على الحشو. |
| [getParagraphs](#getParagraphs--) | يحصل على النص المنسق للخلية. |
| [getRowSpan](#getRowSpan--) | يحصل على امتداد الصف. |
| [getVerticalAlignment](#getVerticalAlignment--) | يحصل على المحاذاة العمودية. |
| [getWidth](#getWidth--) | يحصل على عرض العمود. |
| [isNoBorder](#isNoBorder--) | يحصل على ما إذا كانت الخلية لها حد. |
| [isOverrideByFragment](#isOverrideByFragment--) | يضبط خاصية TextState للخلية يتم تجاوزها بواسطة خاصية TextState لـ TextFragment. |
| [isWordWrapped](#isWordWrapped--) | يحصل على التفاف الكلمات لنص الخلية. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | يضبط المحاذاة. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | يحصل على أو يضبط لون الخلفية. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | يحصل على أو يضبط صورة الخلفية |
| [setBackgroundImageFile](#setBackgroundImageFile-java.lang.String-) | يضبط ملف صورة الخلفية. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | يضبط الحد. |
| [setColSpan](#setColSpan-int-) | يضبط امتداد العمود. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | يضبط حالة النص الافتراضية للخلية. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | يضبط الحشو. |
| [setNoBorder](#setNoBorder-boolean-) | يضبط وجود حد للخلية. |
| [setOverrideByFragment](#setOverrideByFragment-boolean-) | يضبط خاصية TextState للخلية يتم تجاوزها بواسطة خاصية TextState لـ TextFragment. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | يضبط النص المنسق للخلية. |
| [setRowSpan](#setRowSpan-int-) | يضبط امتداد الصف. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | يضبط المحاذاة العمودية. |
| [setWidth](#setWidth-double-) | يضبط عرض العمود. |
| [setWordWrapped](#setWordWrapped-boolean-) | يضبط التفاف الكلمات لنص الخلية. |

### Cell {#Cell--}
```
public Cell()
```

يُهيئ نسخة جديدة من الفئة Cell.

### Cell {#Cell-com.aspose.pdf.Rectangle-}
يُهيئ نسخة جديدة من الفئة Cell.

### deepClone {#deepClone--}
```
public Object deepClone()
```

استنساخ الخلية.

**Returns:**
الكائن المستنسخ

### getAlignment {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```

يحصل على المحاذاة.

**Returns:**
عنصر HorizontalAlignment @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

يحصل على لون الخلفية.

**Returns:**
كائن Color

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

يحصل على أو يضبط صورة الخلفية

**Returns:**
مثال الصورة

### getBackgroundImageFile {#getBackgroundImageFile--}
```
@Deprecated public String getBackgroundImageFile()
```

يحصل على ملف صورة الخلفية.

**Returns:**
قيمة السلسلة @deprecated تم توسيع الخاصية يرجى استخدام BackgroundImage

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

يحصل على الحد.

**Returns:**
كائن BorderInfo

### getColSpan {#getColSpan--}
```
public int getColSpan()
```

يحصل على أو يضبط امتداد العمود.

**Returns:**
قيمة int

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

يحصل على حالة نص الخلية الافتراضية.

**Returns:**
كائن TextState

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

يحصل على الحشو.

**Returns:**
كائن MarginInfo

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

يحصل على النص المنسق للخلية.

**Returns:**
كائن الفقرات

### getRowSpan {#getRowSpan--}
```
public int getRowSpan()
```

يحصل على امتداد الصف.

**Returns:**
قيمة int

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

يحصل على المحاذاة العمودية.

**Returns:**
عنصر VerticalAlignment @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

يحصل على عرض العمود.

**Returns:**
قيمة double

### isNoBorder {#isNoBorder--}
```
public boolean isNoBorder()
```

يحصل على ما إذا كانت الخلية لها حد.

**Returns:**
قيمة منطقية

### isOverrideByFragment {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```

يضبط خاصية TextState للخلية يتم تجاوزها بواسطة خاصية TextState لـ TextFragment.

**Returns:**
قيمة منطقية

### isWordWrapped {#isWordWrapped--}
```
public boolean isWordWrapped()
```

يحصل على التفاف الكلمات لنص الخلية.

**Returns:**
قيمة منطقية

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
يضبط المحاذاة.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
يحصل على أو يضبط لون الخلفية.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
يحصل على أو يضبط صورة الخلفية

### setBackgroundImageFile {#setBackgroundImageFile-java.lang.String-}
يضبط ملف صورة الخلفية.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
يضبط الحد.

### setColSpan {#setColSpan-int-}
```
public void setColSpan(int value)
```

يضبط امتداد العمود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
يضبط حالة النص الافتراضية للخلية.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
يضبط الحشو.

### setNoBorder {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```

يضبط وجود حد للخلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setOverrideByFragment {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```

يضبط خاصية TextState للخلية يتم تجاوزها بواسطة خاصية TextState لـ TextFragment.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
يضبط النص المنسق للخلية.

### setRowSpan {#setRowSpan-int-}
```
public void setRowSpan(int value)
```

يضبط امتداد الصف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
يضبط المحاذاة العمودية.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

يضبط عرض العمود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setWordWrapped {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```

يضبط التفاف الكلمات لنص الخلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
