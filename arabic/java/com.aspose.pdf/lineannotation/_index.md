---
title: "LineAnnotation"
linktitle: "LineAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل تعليقات الخط."
type: docs
weight: 2710
url: /ar/java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.LineAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class LineAnnotation extends MarkupAnnotation
```

فئة تمثل تعليقات الخط.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | منشئ للاستخدام مع Generator. |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | ينشئ تعليقة Line جديدة على الصفحة المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل الزائر لمعالجة التعليقات. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | يقوم بتحديث نقطتي البداية والنهاية وفقًا لتحويل المصفوفة. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getCaptionOffset](#getCaptionOffset--) | يحصل على إزاحة نص التسمية من موقعه الطبيعي. |
| [getCaptionPosition](#getCaptionPosition--) | يحصل على موضع تسمية التعليق. |
| [getEnding](#getEnding--) | يحصل على نقطة نهاية الخط. |
| [getEndingStyle](#getEndingStyle--) | يحصل على نمط نهاية الخط لنقطة النهاية. |
| [getIntent](#getIntent--) | يحصل على هدف line annotation. |
| [getInteriorColor](#getInteriorColor--) | يحصل على اللون الداخلي للتعليق. |
| [getLeaderLine](#getLeaderLine--) | يحصل على طول الخط القائد. |
| [getLeaderLineExtension](#getLeaderLineExtension--) | يحصل على طول امتداد الخط القائد. |
| [getLeaderLineOffset](#getLeaderLineOffset--) | يحصل على إزاحة الخط القائد. |
| [getMeasure](#getMeasure--) | وحدات القياس المحددة لهذه التعليقة. |
| [getShowCaption](#getShowCaption--) | يحصل على العلامة المنطقية التي تحدد ما إذا كان يجب عرض المحتوى كتسمية. |
| [getStarting](#getStarting--) | يحصل على نقطة بداية الخط. |
| [getStartingStyle](#getStartingStyle--) | يحصل على نمط نهاية الخط لنقطة بداية الخط. |
| [setCaptionOffset](#setCaptionOffset-com.aspose.pdf.Point-) | يضبط إزاحة نص التسمية من موقعه الطبيعي. |
| [setCaptionPosition](#setCaptionPosition-com.aspose.pdf.CaptionPosition-) | يضبط موضع تسمية التعليق. |
| [setEnding](#setEnding-com.aspose.pdf.Point-) | يضبط نقطة نهاية الخط. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | يضبط نمط النهاية لنقطة النهاية للخط. |
| [setIntent](#setIntent-com.aspose.pdf.LineIntent-) | يضبط هدف line annotation. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | يضبط اللون الداخلي للتعليق. |
| [setLeaderLine](#setLeaderLine-double-) | يضبط طول الخط القائد. |
| [setLeaderLineExtension](#setLeaderLineExtension-double-) | يضبط طول امتداد خط القائد. |
| [setLeaderLineOffset](#setLeaderLineOffset-double-) | يضبط إزاحة خط القائد. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | وحدات القياس المحددة لهذه التعليقة. |
| [setShowCaption](#setShowCaption-boolean-) | يضبط علمًا منطقيًا يحدد ما إذا كان يجب عرض المحتوى كتعليق توضيحي. |
| [setStarting](#setStarting-com.aspose.pdf.Point-) | يضبط نقطة بدء الخط. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | يضبط نمط نهاية الخط لنقطة بدء الخط. |

### LineAnnotation {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
منشئ للاستخدام مع Generator.

### LineAnnotation {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
ينشئ تعليقة Line جديدة على الصفحة المحددة.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل الزائر لمعالجة التعليقات.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
يقوم بتحديث نقطتي البداية والنهاية وفقًا لتحويل المصفوفة.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
عنصر AnnotationType @see AnnotationType

### getCaptionOffset {#getCaptionOffset--}
```
public Point getCaptionOffset()
```

يحصل على إزاحة نص التسمية من موقعه الطبيعي.

**Returns:**
كائن Point

### getCaptionPosition {#getCaptionPosition--}
```
public CaptionPosition getCaptionPosition()
```

يحصل على موضع تسمية التعليق.

**Returns:**
عنصر CaptionPosition @see CaptionPosition

### getEnding {#getEnding--}
```
public Point getEnding()
```

يحصل على نقطة نهاية الخط.

**Returns:**
قيمة النقطة

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

يحصل على نمط نهاية الخط لنقطة النهاية.

**Returns:**
عنصر LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public LineIntent getIntent()
```

يحصل على هدف line annotation.

**Returns:**
عنصر LineIntent @see LineIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

يحصل على اللون الداخلي للتعليق.

**Returns:**
كائن Color

### getLeaderLine {#getLeaderLine--}
```
public double getLeaderLine()
```

يحصل على طول الخط القائد.

**Returns:**
قيمة double

### getLeaderLineExtension {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```

يحصل على طول امتداد الخط القائد.

**Returns:**
قيمة double

### getLeaderLineOffset {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```

يحصل على إزاحة الخط القائد.

**Returns:**
قيمة double

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

وحدات القياس المحددة لهذه التعليقة.

**Returns:**
كائن Measure

### getShowCaption {#getShowCaption--}
```
public boolean getShowCaption()
```

يحصل على العلامة المنطقية التي تحدد ما إذا كان يجب عرض المحتوى كتسمية.

**Returns:**
قيمة منطقية

### getStarting {#getStarting--}
```
public Point getStarting()
```

يحصل على نقطة بداية الخط.

**Returns:**
قيمة النقطة

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

يحصل على نمط نهاية الخط لنقطة بداية الخط.

**Returns:**
عنصر LineEnding @see LineEnding

### setCaptionOffset {#setCaptionOffset-com.aspose.pdf.Point-}
يضبط إزاحة نص التسمية من موقعه الطبيعي.

### setCaptionPosition {#setCaptionPosition-com.aspose.pdf.CaptionPosition-}
يضبط موضع تسمية التعليق.

### setEnding {#setEnding-com.aspose.pdf.Point-}
يضبط نقطة نهاية الخط.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
يضبط نمط النهاية لنقطة النهاية للخط.

### setIntent {#setIntent-com.aspose.pdf.LineIntent-}
يضبط هدف line annotation.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
يضبط اللون الداخلي للتعليق.

### setLeaderLine {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```

يضبط طول الخط القائد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setLeaderLineExtension {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```

يضبط طول امتداد خط القائد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setLeaderLineOffset {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```

يضبط إزاحة خط القائد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
وحدات القياس المحددة لهذه التعليقة.

### setShowCaption {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```

يضبط علمًا منطقيًا يحدد ما إذا كان يجب عرض المحتوى كتعليق توضيحي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setStarting {#setStarting-com.aspose.pdf.Point-}
يضبط نقطة بدء الخط.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
يضبط نمط نهاية الخط لنقطة بدء الخط.
