---
title: "TextMarkupAnnotation"
linktitle: "TextMarkupAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة أساسية مجردة لتعليمات توضيح النص."
type: docs
weight: 5180
url: /ar/java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextMarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

فئة أساسية مجردة لتعليمات توضيح النص.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | يقوم بتحديث QuadPoints وفقًا لتحويل المصفوفة. |
| [getMarkedText](#getMarkedText--) | يحصل على النص تحت التعليق التوضيحي كـ string. |
| [getMarkedTextFragments](#getMarkedTextFragments--) | يحصل على النص تحت التعليق التوضيحي كـ {@code TextFragmentCollection}. |
| [getQuadPoints](#getQuadPoints--) | يحصل على مصفوفة من النقاط التي تحدد إحداثيات n رباعيات. كل رباعية تشمل كلمة أو مجموعة من الكلمات المتجاورة في النص الأساسي للتعليق التوضيحي. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | يضبط مصفوفة من النقاط التي تحدد إحداثيات n رباعيات. كل رباعية تشمل كلمة أو مجموعة من الكلمات المتجاورة في النص الأساسي للتعليق التوضيحي. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
يقوم بتحديث QuadPoints وفقًا لتحويل المصفوفة.

### getMarkedText {#getMarkedText--}
```
public String getMarkedText()
```

يحصل على النص تحت التعليق التوضيحي كـ string.

**Returns:**
سلسلة تحتوي على النص الموجود تحت التعليق التوضيحي.

### getMarkedTextFragments {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```

يحصل على النص تحت التعليق التوضيحي كـ {@code TextFragmentCollection}.

**Returns:**
{@code TextFragmentCollection} يحتوي على {@code TextFragment}s الموجود تحت التعليق التوضيحي.

### getQuadPoints {#getQuadPoints--}
```
public Point [] getQuadPoints()
```

يحصل على مصفوفة من النقاط التي تحدد إحداثيات n رباعيات. كل رباعية تشمل كلمة أو مجموعة من الكلمات المتجاورة في النص الأساسي للتعليق التوضيحي.

**Returns:**
مصفوفة من قيم Point

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
يضبط مصفوفة من النقاط التي تحدد إحداثيات n رباعيات. كل رباعية تشمل كلمة أو مجموعة من الكلمات المتجاورة في النص الأساسي للتعليق التوضيحي.
