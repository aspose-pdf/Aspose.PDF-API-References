---
title: "StampAnnotation"
linktitle: "StampAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل توضيح الختم المطاطي. هذا النوع من التوضيحات يعرض نصًا أو رسومات تهدف إلى الظهور كما لو تم ختمها على الصفحة بختم مطاطي. </p> <hr>."
type: docs
weight: 4630
url: /ar/java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.StampAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class StampAnnotation extends MarkupAnnotation
```

<p> يمثل التعليق التوضيحي للطابع المطاطي. هذا النوع من التعليقات يعرض نصًا أو رسومات تهدف إلى الظهور كما لو تم ختمها على الصفحة بطابع مطاطي. </p> <hr> <pre> المقتطف البرمجي التالي يوضح كيفية إضافة طابعين إلى الصفحة الأولى من مستند PDF. يأتي المستند الإدخالي من inFile ويتم حفظ التغييرات في outFile. الطابع الأول له أيقونة NotForPublicRelease والثاني يأتي بصورة من rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre>

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.IDocument-) | منشئ |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | ينشئ توضيح ختم جديد على الصفحة المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل زائر {@code AnnotationSelector} عند تصفح مجموعة التوضيحات. |
| [clear](#clear--) | مسح المثيلات الثابتة. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getIcon](#getIcon--) | يحصل على أيقونة للختام المطاطي. |
| [getImage](#getImage--) | يحصل على صورة للتعليق. |
| [setBase64SVGImage](#setBase64SVGImage-java.lang.String-) | يضبط صورة SVG للتعليق كسلسلة Base64. |
| [setIcon](#setIcon-com.aspose.pdf.StampIcon-) | يضبط أيقونة للختام المطاطي. |
| [setImage](#setImage-java.io.InputStream-) | يضبط صورة للتعليق. |

### StampAnnotation {#StampAnnotation-com.aspose.pdf.IDocument-}
منشئ

### StampAnnotation {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
ينشئ توضيح ختم جديد على الصفحة المحددة.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل زائر {@code AnnotationSelector} عند تصفح مجموعة التوضيحات.

### clear {#clear--}
```
public static void clear()
```

مسح المثيلات الثابتة.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
عنصر AnnotationType @see AnnotationType

### getIcon {#getIcon--}
```
public StampIcon getIcon()
```

يحصل على أيقونة للختام المطاطي.

**Returns:**
قيمة StampIcon

### getImage {#getImage--}
```
public InputStream getImage()
```

يحصل على صورة للتعليق.

**Returns:**
كائن InputStream

### setBase64SVGImage {#setBase64SVGImage-java.lang.String-}
يضبط صورة SVG للتعليق كسلسلة Base64.

### setIcon {#setIcon-com.aspose.pdf.StampIcon-}
يضبط أيقونة للختام المطاطي.

### setImage {#setImage-java.io.InputStream-}
يضبط صورة للتعليق.
