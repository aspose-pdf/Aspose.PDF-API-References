---
title: "SoundAnnotation"
linktitle: "SoundAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل تعليق صوتي يحتوي على صوت مسجل من ميكروفون الحاسوب أو مستورد من ملف."
type: docs
weight: 4530
url: /ar/java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.SoundAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class SoundAnnotation extends MarkupAnnotation
```

يمثل تعليق صوتي يحتوي على صوت مسجل من ميكروفون الحاسوب أو مستورد من ملف.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | ينشئ تعليقًا صوتيًا جديدًا على الصفحة المحددة. |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | ينشئ تعليقًا صوتيًا جديدًا على الصفحة المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل كائن الزائر لمعالجة التعليق. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getIcon](#getIcon--) | يحصل على أيقونة تُستخدم في عرض التعليق. |
| [getSoundData](#getSoundData--) | يحصل على كائن صوت يحدد الصوت الذي سيتم تشغيله عند تفعيل التعليق. |
| [setIcon](#setIcon-int-) | يضبط أيقونة تُستخدم في عرض التعليق. |

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
ينشئ تعليقًا صوتيًا جديدًا على الصفحة المحددة.

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
ينشئ تعليقًا صوتيًا جديدًا على الصفحة المحددة.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل كائن الزائر لمعالجة التعليق.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
قيمة AnnotationType @see AnnotationType

### getIcon {#getIcon--}
```
public int getIcon()
```

يحصل على أيقونة تُستخدم في عرض التعليق.

**Returns:**
قيمة SoundIcon @see SoundIcon

### getSoundData {#getSoundData--}
```
public SoundData getSoundData()
```

يحصل على كائن صوت يحدد الصوت الذي سيتم تشغيله عند تفعيل التعليق.

**Returns:**
قيمة SoundData

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

يضبط أيقونة تُستخدم في عرض التعليق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة SoundIcon @see SoundIcon |
