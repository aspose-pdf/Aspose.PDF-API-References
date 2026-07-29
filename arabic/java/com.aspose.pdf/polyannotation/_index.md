---
title: "PolyAnnotation"
linktitle: "PolyAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة أساسية مجردة للتعليقات المتعددة."
type: docs
weight: 3890
url: /ar/java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.PolyAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class PolyAnnotation extends MarkupAnnotation
```

فئة أساسية مجردة للتعليقات المتعددة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | يحدّث النقاط في Vertices وفقًا لتحويل المصفوفة. |
| [getEndingStyle](#getEndingStyle--) | يحصل على نمط نهاية السطر الثاني. |
| [getIntent](#getIntent--) | يحصل على نية التعليق التوضيحي للمضلع أو الخط المتعدد. |
| [getInteriorColor](#getInteriorColor--) | يحصل على اللون الداخلي المستخدم لملء نهايات خطوط التعليق التوضيحي. |
| [getMeasure](#getMeasure--) | وحدات القياس المحددة لهذا التعليق التوضيحي. |
| [getStartingStyle](#getStartingStyle--) | يحصل على نمط نهاية السطر الأول. |
| [getVertices](#getVertices--) | يحصل على مصفوفة من النقاط التي تمثل الإحداثيات الأفقية والرأسية لكل رأس. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | يضبط نمط نهاية السطر الثاني. |
| [setIntent](#setIntent-com.aspose.pdf.PolyIntent-) | يضبط نية التعليق التوضيحي للمضلع أو الخط المتعدد. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | يضبط اللون الداخلي المستخدم لملء نهايات خطوط التعليق التوضيحي. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | وحدات القياس المحددة لهذا التعليق التوضيحي. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | يضبط نمط نهاية السطر الأول. |
| [setVertices](#setVertices-com.aspose.pdf.Point:A-) | يضبط مصفوفة من النقاط التي تمثل الإحداثيات الأفقية والرأسية لكل رأس. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
يحدّث النقاط في Vertices وفقًا لتحويل المصفوفة.

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

يحصل على نمط نهاية السطر الثاني.

**Returns:**
عنصر LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public PolyIntent getIntent()
```

يحصل على نية التعليق التوضيحي للمضلع أو الخط المتعدد.

**Returns:**
عنصر PolyIntent @see PolyIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

يحصل على اللون الداخلي المستخدم لملء نهايات خطوط التعليق التوضيحي.

**Returns:**
كائن Color

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

وحدات القياس المحددة لهذا التعليق التوضيحي.

**Returns:**
مثال Measure

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

يحصل على نمط نهاية السطر الأول.

**Returns:**
عنصر LineEnding @see LineEnding

### getVertices {#getVertices--}
```
public Point [] getVertices()
```

يحصل على مصفوفة من النقاط التي تمثل الإحداثيات الأفقية والرأسية لكل رأس.

**Returns:**
مصفوفة من قيم Point

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
يضبط نمط نهاية السطر الثاني.

### setIntent {#setIntent-com.aspose.pdf.PolyIntent-}
يضبط نية التعليق التوضيحي للمضلع أو الخط المتعدد.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
يضبط اللون الداخلي المستخدم لملء نهايات خطوط التعليق التوضيحي.

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
وحدات القياس المحددة لهذا التعليق التوضيحي.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
يضبط نمط نهاية السطر الأول.

### setVertices {#setVertices-com.aspose.pdf.Point:A-}
يضبط مصفوفة من النقاط التي تمثل الإحداثيات الأفقية والرأسية لكل رأس.
