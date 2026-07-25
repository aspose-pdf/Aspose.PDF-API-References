---
title: "RichMediaAnnotation"
linktitle: "RichMediaAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تصف RichMediaAnnotation التي تسمح بتضمين بيانات الفيديو/الصوت في مستند PDF."
type: docs
weight: 4260
url: /ar/java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.RichMediaAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class RichMediaAnnotation extends Annotation
```

فئة تصف RichMediaAnnotation التي تسمح بتضمين بيانات الفيديو/الصوت في مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RichMediaAnnotation](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | يُهيئ RichMediaAnnotation. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل الزائر لهذا التعليق التوضيحي. |
| [addCustomData](#addCustomData-java.lang.String-java.io.InputStream-) | أضف بيانات مسماة مخصصة (على سبيل المثال المطلوبة لسكريبت الفلاش). |
| [getActivateOn](#getActivateOn--) | الحدث الذي يُفعّل التطبيق. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getContent](#getContent--) | بيانات محتوى الوسائط الغنية. |
| [getCustomFlashVariables](#getCustomFlashVariables--) | يضبط أو يحصل على متغيرات الفلاش التي تُمرّر إلى المشغل. |
| [getCustomPlayer](#getCustomPlayer--) | يضبط أو يحصل على مشغل فلاش مخصص لتشغيل بيانات الفيديو/الصوت. |
| [getType](#getType--) | يحصل أو يضبط نوع المحتوى. القيم الممكنة: Audio, Video. |
| [setActivateOn](#setActivateOn-int-) | الحدث الذي يُفعّل التطبيق. |
| [setContent](#setContent-java.lang.String-java.io.InputStream-) | حدد تدفق المحتوى. |
| [setCustomFlashVariables](#setCustomFlashVariables-java.lang.String-) | يضبط أو يحصل على متغيرات الفلاش التي تُمرّر إلى المشغل. |
| [setCustomPlayer](#setCustomPlayer-java.io.InputStream-) | يضبط أو يحصل على مشغل فلاش مخصص لتشغيل بيانات الفيديو/الصوت. |
| [setPoster](#setPoster-java.io.InputStream-) | حدد ملصق التعليق التوضيحي. |
| [setType](#setType-int-) | يحصل أو يضبط نوع المحتوى. القيم الممكنة: Audio, Video. |
| [update](#update--) | يقوم بتحديث البيانات بالمعلمات المحددة. |

### RichMediaAnnotation {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
يُهيئ RichMediaAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل الزائر لهذا التعليق التوضيحي.

### addCustomData {#addCustomData-java.lang.String-java.io.InputStream-}
أضف بيانات مسماة مخصصة (على سبيل المثال المطلوبة لسكريبت الفلاش).

### getActivateOn {#getActivateOn--}
```
public int getActivateOn()
```

الحدث الذي يُفعّل التطبيق.

**Returns:**
عنصر ActivationEvent

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
عنصر AnnotationType @see AnnotationType

### getContent {#getContent--}
```
public InputStream getContent()
```

بيانات محتوى الوسائط الغنية.

**Returns:**
كائن InputStream

### getCustomFlashVariables {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```

يضبط أو يحصل على متغيرات الفلاش التي تُمرّر إلى المشغل.

**Returns:**
كائن String

### getCustomPlayer {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```

يضبط أو يحصل على مشغل فلاش مخصص لتشغيل بيانات الفيديو/الصوت.

**Returns:**
كائن InputStream

### getType {#getType--}
```
public int getType()
```

يحصل أو يضبط نوع المحتوى. القيم الممكنة: Audio, Video.

**Returns:**
قيمة ContentType @see ContentType

### setActivateOn {#setActivateOn-int-}
```
public void setActivateOn(int value)
```

الحدث الذي يُفعّل التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر ActivationEvent |

### setContent {#setContent-java.lang.String-java.io.InputStream-}
حدد تدفق المحتوى.

### setCustomFlashVariables {#setCustomFlashVariables-java.lang.String-}
يضبط أو يحصل على متغيرات الفلاش التي تُمرّر إلى المشغل.

### setCustomPlayer {#setCustomPlayer-java.io.InputStream-}
يضبط أو يحصل على مشغل فلاش مخصص لتشغيل بيانات الفيديو/الصوت.

### setPoster {#setPoster-java.io.InputStream-}
حدد ملصق التعليق التوضيحي.

### setType {#setType-int-}
```
public void setType(int value)
```

يحصل أو يضبط نوع المحتوى. القيم الممكنة: Audio, Video.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر ContentType |

### update {#update--}
```
public void update()
```

يقوم بتحديث البيانات بالمعلمات المحددة.
