---
title: "MovieAnnotation"
linktitle: "MovieAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل تعليقًا مرئيًا يحتوي على رسومات متحركة وصوت يُعرض على شاشة الكمبيوتر ومن خلال السماعات. عندما يتم تنشيط التعليق، the."
type: docs
weight: 3090
url: /ar/java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MovieAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class MovieAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

يمثل توضيح فيلم يحتوي على رسومات متحركة وصوت يتم عرضه على شاشة الكمبيوتر ومن خلال السماعات. عند تفعيل التوضيح، يتم تشغيل الفيلم.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | منشئ للاستخدام مع Generator. |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | ينشئ تعليقًا صوتيًا جديدًا على الصفحة المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل كائن الزائر لمعالجة التعليق. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getAspect](#getAspect--) | يحصل أو يضبط عرض وارتفاع صندوق حدود الفيلم، بوحدات البكسل. |
| [getFile](#getFile--) | يحصل على مواصفة ملف تحدد ملف فيلم ذاتي الوصف. |
| [getPoster](#getPoster--) | يحصل أو يضبط علامة أو تدفق يحدد ما إذا كان سيتم عرض صورة الملصق التي تمثل الفيلم وكيفية عرضها. إذا كان صحيحًا، سيتم جلب صورة الملصق من ملف الفيلم؛ إذا كان خاطئًا، لن يتم عرض أي ملصق. |
| [getRotate](#getRotate--) | يحصل أو يضبط عدد الدرجات التي سيُدوَّر بها الفيلم باتجاه عقارب الساعة بالنسبة للصفحة. يجب أن تكون القيمة مضاعفًا للـ 90. |
| [getTitle](#getTitle--) | يحصل على عنوان تعليق الفيلم. |
| [setAspect](#setAspect-com.aspose.pdf.Point-) | يحصل أو يضبط عرض وارتفاع صندوق حدود الفيلم، بوحدات البكسل. |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | يضبط مواصفة ملف تحدد ملف فيلم ذاتي الوصف. |
| [setPoster](#setPoster-boolean-) | يحصل أو يضبط علامة أو تدفق يحدد ما إذا كان سيتم عرض صورة الملصق التي تمثل الفيلم وكيفية عرضها. إذا كان صحيحًا، سيتم جلب صورة الملصق من ملف الفيلم؛ إذا كان خاطئًا، لن يتم عرض أي ملصق. |
| [setRotate](#setRotate-int-) | يحصل أو يضبط عدد الدرجات التي سيُدوَّر بها الفيلم باتجاه عقارب الساعة بالنسبة للصفحة. يجب أن تكون القيمة مضاعفًا للـ 90. |
| [setTitle](#setTitle-java.lang.String-) | يضبط عنوان تعليق الفيلم. |

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
منشئ للاستخدام مع Generator.

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
ينشئ تعليقًا صوتيًا جديدًا على الصفحة المحددة.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل كائن الزائر لمعالجة التعليق.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
عنصر AnnotationType كقيمة int @see AnnotationType

### getAspect {#getAspect--}
```
public final Point getAspect()
```

يحصل أو يضبط عرض وارتفاع صندوق حدود الفيلم، بوحدات البكسل.

**Returns:**
مثيل Point

### getFile {#getFile--}
```
public FileSpecification getFile()
```

يحصل على مواصفة ملف تحدد ملف فيلم ذاتي الوصف.

**Returns:**
قيمة FileSpecification

### getPoster {#getPoster--}
```
public final boolean getPoster()
```

يحصل أو يضبط علامة أو تدفق يحدد ما إذا كان سيتم عرض صورة الملصق التي تمثل الفيلم وكيفية عرضها. إذا كان صحيحًا، سيتم جلب صورة الملصق من ملف الفيلم؛ إذا كان خاطئًا، لن يتم عرض أي ملصق.

**Returns:**
قيمة منطقية

### getRotate {#getRotate--}
```
public final int getRotate()
```

يحصل أو يضبط عدد الدرجات التي سيُدوَّر بها الفيلم باتجاه عقارب الساعة بالنسبة للصفحة. يجب أن تكون القيمة مضاعفًا للـ 90.

**Returns:**
قيمة int

### getTitle {#getTitle--}
```
public String getTitle()
```

يحصل على عنوان تعليق الفيلم.

**Returns:**
قيمة سلسلة

### setAspect {#setAspect-com.aspose.pdf.Point-}
يحصل أو يضبط عرض وارتفاع صندوق حدود الفيلم، بوحدات البكسل.

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
يضبط مواصفة ملف تحدد ملف فيلم ذاتي الوصف.

### setPoster {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```

يحصل أو يضبط علامة أو تدفق يحدد ما إذا كان سيتم عرض صورة الملصق التي تمثل الفيلم وكيفية عرضها. إذا كان صحيحًا، سيتم جلب صورة الملصق من ملف الفيلم؛ إذا كان خاطئًا، لن يتم عرض أي ملصق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRotate {#setRotate-int-}
```
public final void setRotate(int value)
```

يحصل أو يضبط عدد الدرجات التي سيُدوَّر بها الفيلم باتجاه عقارب الساعة بالنسبة للصفحة. يجب أن تكون القيمة مضاعفًا للـ 90.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setTitle {#setTitle-java.lang.String-}
يضبط عنوان تعليق الفيلم.
