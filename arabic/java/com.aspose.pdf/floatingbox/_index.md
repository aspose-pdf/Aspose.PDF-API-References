---
title: "FloatingBox"
linktitle: "FloatingBox"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل صندوقًا عائمًا في مستند PDF. الصندوق العائم يتم وضعه مخصصًا."
type: docs
weight: 1610
url: /ar/java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FloatingBox, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FloatingBox

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class FloatingBox extends BaseParagraph
```

يمثل صندوقًا عائمًا في مستند PDF. الصندوق العائم يتم وضعه مخصصًا.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FloatingBox](#FloatingBox--) | ينشئ مثيلًا جديدًا من الفئة {@code FloatingBox}. |
| [FloatingBox](#FloatingBox-float-float-) | ينشئ مثيلًا جديدًا من الفئة {@code FloatingBox} بالعرض والارتفاع المحددين. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone](#deepClone--) | ينسخ كائن {@code FloatingBox} جديد. الفقرات داخل الصندوق العائم لا تُنسخ. |
| [getBackgroundColor](#getBackgroundColor--) | يحصل على كائن يشير إلى لون الخلفية للمربع العائم. |
| [getBackgroundImage](#getBackgroundImage--) | يحصل على أو يضبط صورة الخلفية للصفحة (للمولد فقط، لا يتم ملؤها عند قراءة المستند). |
| [getBorder](#getBorder--) | يحصل على كائن يشير إلى معلومات الحدود للمربع العائم. |
| [getColumnInfo](#getColumnInfo--) | يحصل على معلومات العمود |
| [getHeight](#getHeight--) | يحصل على قيمة عائمة تشير إلى ارتفاع المربع العائم. |
| [getLeft](#getLeft--) | يحصل على إحداثي اليسار للجدول. |
| [getPadding](#getPadding--) | يحصل على كائن يشير إلى الحشو للمربع العائم. |
| [getParagraphs](#getParagraphs--) | يحصل على مجموعة تشير إلى جميع الفقرات في الخلية. |
| [getPositioningMode](#getPositioningMode--) | يحدد المتغير لتحديد موقع الـFloatingBox على الصفحة. |
| [getTop](#getTop--) | يحصل على إحداثي أعلى الجدول. |
| [getWidth](#getWidth--) | يحصل على قيمة عائمة تشير إلى عرض المربع العائم. |
| [isNeedRepeating](#isNeedRepeating--) | يحصل على قيمة منطقية تشير إلى ما إذا كان يجب تكرار الفقرة في الصفحة التالية. القيمة الافتراضية هي true. السمة صالحة فقط عندما تكون الفقرة نفسها والكائن الذي يشير إليه ReferenceParagraphID مدرجين في RepeatingRows. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | يضبط كائنًا يشير إلى لون الخلفية للمربع العائم. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | يحصل على أو يضبط صورة الخلفية للصفحة (للمولد فقط، لا يتم ملؤها عند قراءة المستند). |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | يضبط كائنًا يشير إلى معلومات الحدود للمربع العائم. |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | يضبط معلومات العمود |
| [setHeight](#setHeight-double-) | يضبط قيمة عائمة تشير إلى ارتفاع المربع العائم. |
| [setLeft](#setLeft-double-) | يضبط إحداثي اليسار للجدول. |
| [setNeedRepeating](#setNeedRepeating-boolean-) | يضبط قيمة منطقية تشير إلى ما إذا كان يجب تكرار الفقرة في الصفحة التالية. القيمة الافتراضية هي true. السمة صالحة فقط عندما تكون الفقرة نفسها والكائن الذي يشير إليه ReferenceParagraphID مدرجين في RepeatingRows. |
| [setPadding](#setPadding-com.aspose.pdf.MarginInfo-) | يضبط كائنًا يشير إلى الحشو للمربع العائم. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | يضبط مجموعة تشير إلى جميع الفقرات في الخلية. |
| [setPositioningMode](#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-) | يحدد المتغير لتحديد موقع الـFloatingBox على الصفحة. |
| [setTop](#setTop-double-) | يضبط إحداثي أعلى الجدول. |
| [setWidth](#setWidth-double-) | يضبط قيمة عائمة تشير إلى عرض المربع العائم. |

### FloatingBox {#FloatingBox--}
```
public FloatingBox()
```

ينشئ مثيلًا جديدًا من الفئة {@code FloatingBox}.

### FloatingBox {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```

ينشئ مثيلًا جديدًا من الفئة {@code FloatingBox} بالعرض والارتفاع المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | عرض الصندوق. |
| الارتفاع |  | ارتفاع الصندوق. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

ينسخ كائن {@code FloatingBox} جديد. الفقرات داخل الصندوق العائم لا تُنسخ.

**Returns:**
الكائن {@code FloatingBox} الجديد.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

يحصل على كائن يشير إلى لون الخلفية للمربع العائم.

**Returns:**
كائن يشير إلى لون الخلفية.

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

يحصل على أو يضبط صورة الخلفية للصفحة (للمولد فقط، لا يتم ملؤها عند قراءة المستند).

**Returns:**
مثال الصورة

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

يحصل على كائن يشير إلى معلومات الحدود للمربع العائم.

**Returns:**
كائن يشير إلى معلومات الحدود.

### getColumnInfo {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```

يحصل على معلومات العمود

**Returns:**
كائن ColumnInfo

### getHeight {#getHeight--}
```
public double getHeight()
```

يحصل على قيمة عائمة تشير إلى ارتفاع المربع العائم.

**Returns:**
قيمة تشير إلى الارتفاع.

### getLeft {#getLeft--}
```
public double getLeft()
```

يحصل على إحداثي اليسار للجدول.

**Returns:**
إحداثي اليسار للجدول.

### getPadding {#getPadding--}
```
public MarginInfo getPadding()
```

يحصل على كائن يشير إلى الحشو للمربع العائم.

**Returns:**
كائن يشير إلى الحشو.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

يحصل على مجموعة تشير إلى جميع الفقرات في الخلية.

**Returns:**
مجموعة تشير إلى جميع الفقرات.

### getPositioningMode {#getPositioningMode--}
```
public final ParagraphPositioningMode getPositioningMode()
```

يحدد المتغير لتحديد موقع الـFloatingBox على الصفحة.

**Returns:**
عنصر ParagraphPositioningMode

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

يحصل على قيمة عائمة تشير إلى عرض المربع العائم.

**Returns:**
قيمة double

### isNeedRepeating {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```

يحصل على قيمة منطقية تشير إلى ما إذا كان يجب تكرار الفقرة في الصفحة التالية. القيمة الافتراضية هي true. السمة صالحة فقط عندما تكون الفقرة نفسها والكائن الذي يشير إليه ReferenceParagraphID مدرجين في RepeatingRows.

**Returns:**
قيمة منطقية

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
يضبط كائنًا يشير إلى لون الخلفية للمربع العائم.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
يحصل على أو يضبط صورة الخلفية للصفحة (للمولد فقط، لا يتم ملؤها عند قراءة المستند).

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
يضبط كائنًا يشير إلى معلومات الحدود للمربع العائم.

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
يضبط معلومات العمود

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

يضبط قيمة عائمة تشير إلى ارتفاع المربع العائم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة تشير إلى الارتفاع. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

يضبط إحداثي اليسار للجدول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | إحداثي اليسار للجدول. |

### setNeedRepeating {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```

يضبط قيمة منطقية تشير إلى ما إذا كان يجب تكرار الفقرة في الصفحة التالية. القيمة الافتراضية هي true. السمة صالحة فقط عندما تكون الفقرة نفسها والكائن الذي يشير إليه ReferenceParagraphID مدرجين في RepeatingRows.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setPadding {#setPadding-com.aspose.pdf.MarginInfo-}
يضبط كائنًا يشير إلى الحشو للمربع العائم.

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
يضبط مجموعة تشير إلى جميع الفقرات في الخلية.

### setPositioningMode {#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-}
يحدد المتغير لتحديد موقع الـFloatingBox على الصفحة.

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

يضبط قيمة عائمة تشير إلى عرض المربع العائم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |
