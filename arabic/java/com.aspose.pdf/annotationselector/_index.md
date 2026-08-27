---
title: "AnnotationSelector"
linktitle: "AnnotationSelector"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تُستخدم هذه الفئة لاختيار التعليقات التوضيحية باستخدام فكرة قالب الزائر."
type: docs
weight: 100
url: /ar/java/com.aspose.pdf/annotationselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationSelector

**All Implemented Interfaces:**
IAnnotationVisitor

```
public final class AnnotationSelector extends Object implements IAnnotationVisitor
```

تُستخدم هذه الفئة لاختيار التعليقات التوضيحية باستخدام فكرة قالب الزائر.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [AnnotationSelector](#AnnotationSelector--) | يُهيئ نسخة جديدة من فئة AnnotationSelector. |
| [AnnotationSelector](#AnnotationSelector-com.aspose.pdf.Annotation-) | يُهيئ نسخة جديدة من فئة AnnotationSelector. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSelected](#getSelected--) | قائمة الكائنات المحددة. |
| [visit](#visit-com.aspose.pdf.BleedMarkAnnotation-) | يختار {@code bleedMark} إذا تم تهيئة {@link AnnotationSelector} باستخدام كائن {@link BleedMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.CaretAnnotation-) | اختر تعليقة caret إذا تم تهيئة AnnotationSelector باستخدام كائن CaretAnnotation. |
| [visit](#visit-com.aspose.pdf.CircleAnnotation-) | اختر تعليقة دائرة إذا تم تهيئة AnnotationSelector باستخدام كائن CircleAnnotation. |
| [visit](#visit-com.aspose.pdf.ColorBarAnnotation-) | اختر تعليقة ColorBar إذا تم تهيئة AnnotationSelector باستخدام كائن ColorBar. |
| [visit](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | اختر تعليقة مرفق إذا تم تهيئة AnnotationSelector باستخدام كائن FileAttachmentAnnotation. |
| [visit](#visit-com.aspose.pdf.FreeTextAnnotation-) | اختر تعليقة نص حر إذا تم تهيئة AnnotationSelector باستخدام كائن FreeTextAnnotation. |
| [visit](#visit-com.aspose.pdf.HighlightAnnotation-) | اختر تعليقة مرفق إذا تم تهيئة AnnotationSelector باستخدام كائن FreeTextAnnotation. |
| [visit](#visit-com.aspose.pdf.InkAnnotation-) | اختر تعليقة حبر إذا تم تهيئة AnnotationSelector باستخدام كائن InkAnnotation. |
| [visit](#visit-com.aspose.pdf.LineAnnotation-) | اختر تعليقة خط إذا تم تهيئة AnnotationSelector باستخدام كائن LineAnnotation. |
| [visit](#visit-com.aspose.pdf.LinkAnnotation-) | اختر تعليقة رابط إذا تم تهيئة AnnotationSelector باستخدام كائن LinkAnnotation. |
| [visit](#visit-com.aspose.pdf.MovieAnnotation-) | اختر تعليقة فيديو إذا تم تهيئة AnnotationSelector باستخدام كائن MovieAnnotation. |
| [visit](#visit-com.aspose.pdf.PageInformationAnnotation-) | يختار {@code pageInformation} إذا تم تهيئة {@link AnnotationSelector} باستخدام كائن {@link PageInformationAnnotation}. |
| [visit](#visit-com.aspose.pdf.PDF3DAnnotation-) | اختر تعليقة PDF3D إذا تم تهيئة AnnotationSelector باستخدام كائن PDF3DAnnotation. |
| [visit](#visit-com.aspose.pdf.PolygonAnnotation-) | اختر تعليقة مضلع إذا تم تهيئة AnnotationSelector باستخدام كائن PolygonAnnotation. |
| [visit](#visit-com.aspose.pdf.PolylineAnnotation-) | حدد تعليقة الخط المتعدد إذا تم تهيئة AnnotationSelector بكائن PolylineAnnotation. |
| [visit](#visit-com.aspose.pdf.PopupAnnotation-) | حدد تعليقة منبثقة إذا تم تهيئة AnnotationSelector بكائن PopupAnnotation. |
| [visit](#visit-com.aspose.pdf.RedactionAnnotation-) | حدد تعليقة حذف إذا تم تهيئة AnnotationSelector بكائن RedactAnnotation. |
| [visit](#visit-com.aspose.pdf.RegistrationMarkAnnotation-) | يحدد {@code registrationMark} إذا تم تهيئة {@link AnnotationSelector} بكائن {@link RegistrationMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.RichMediaAnnotation-) | حدد تعليقة RichMedia إذا تم تهيئة AnnotationSelector بكائن RichMedia annotation. |
| [visit](#visit-com.aspose.pdf.ScreenAnnotation-) | حدد تعليقة شاشة إذا تم تهيئة AnnotationSelector بكائن ScreenAnnotation. |
| [visit](#visit-com.aspose.pdf.SquareAnnotation-) | حدد تعليقة مربعة إذا تم تهيئة AnnotationSelector بكائن SquareAnnotation. |
| [visit](#visit-com.aspose.pdf.SquigglyAnnotation-) | حدد تعليقة متعرجة إذا تم تهيئة AnnotationSelector بكائن SquigglyAnnotation. |
| [visit](#visit-com.aspose.pdf.StampAnnotation-) | حدد تعليقة ختم إذا تم تهيئة AnnotationSelector بكائن StampAnnotation. |
| [visit](#visit-com.aspose.pdf.StrikeOutAnnotation-) | حدد تعليقة شطب إذا تم تهيئة AnnotationSelector بكائن StrikeOutAnnotation. |
| [visit](#visit-com.aspose.pdf.TextAnnotation-) | حدد تعليقة نص إذا تم تهيئة AnnotationSelector بكائن TextAnnotation. |
| [visit](#visit-com.aspose.pdf.TrimMarkAnnotation-) | يحدد {@code trimMark} إذا تم تهيئة {@link AnnotationSelector} بكائن {@link TrimMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.UnderlineAnnotation-) | حدد تعليقة تسطير إذا تم تهيئة AnnotationSelector بكائن UnderlineAnnotation. |
| [visit](#visit-com.aspose.pdf.WatermarkAnnotation-) | حدد تعليقة علامة مائية إذا تم تهيئة AnnotationSelector بكائن WatermarkAnnotation. |
| [visit](#visit-com.aspose.pdf.WidgetAnnotation-) | حدد تعليقة عنصر واجهة إذا تم تهيئة AnnotationSelector بكائن WidgetAnnotation. |

### AnnotationSelector {#AnnotationSelector--}
```
public AnnotationSelector()
```

يُهيئ نسخة جديدة من فئة AnnotationSelector.

### AnnotationSelector {#AnnotationSelector-com.aspose.pdf.Annotation-}
يُهيئ نسخة جديدة من فئة AnnotationSelector.

### getSelected {#getSelected--}
```
public List < Annotation > getSelected()
```

قائمة الكائنات المحددة.

**Returns:**
قائمة كائنات Annotation

### visit {#visit-com.aspose.pdf.BleedMarkAnnotation-}
يختار {@code bleedMark} إذا تم تهيئة {@link AnnotationSelector} باستخدام كائن {@link BleedMarkAnnotation}.

### visit {#visit-com.aspose.pdf.CaretAnnotation-}
اختر تعليقة caret إذا تم تهيئة AnnotationSelector باستخدام كائن CaretAnnotation.

### visit {#visit-com.aspose.pdf.CircleAnnotation-}
اختر تعليقة دائرة إذا تم تهيئة AnnotationSelector باستخدام كائن CircleAnnotation.

### visit {#visit-com.aspose.pdf.ColorBarAnnotation-}
اختر تعليقة ColorBar إذا تم تهيئة AnnotationSelector باستخدام كائن ColorBar.

### visit {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
اختر تعليقة مرفق إذا تم تهيئة AnnotationSelector باستخدام كائن FileAttachmentAnnotation.

### visit {#visit-com.aspose.pdf.FreeTextAnnotation-}
اختر تعليقة نص حر إذا تم تهيئة AnnotationSelector باستخدام كائن FreeTextAnnotation.

### visit {#visit-com.aspose.pdf.HighlightAnnotation-}
اختر تعليقة مرفق إذا تم تهيئة AnnotationSelector باستخدام كائن FreeTextAnnotation.

### visit {#visit-com.aspose.pdf.InkAnnotation-}
اختر تعليقة حبر إذا تم تهيئة AnnotationSelector باستخدام كائن InkAnnotation.

### visit {#visit-com.aspose.pdf.LineAnnotation-}
اختر تعليقة خط إذا تم تهيئة AnnotationSelector باستخدام كائن LineAnnotation.

### visit {#visit-com.aspose.pdf.LinkAnnotation-}
اختر تعليقة رابط إذا تم تهيئة AnnotationSelector باستخدام كائن LinkAnnotation.

### visit {#visit-com.aspose.pdf.MovieAnnotation-}
اختر تعليقة فيديو إذا تم تهيئة AnnotationSelector باستخدام كائن MovieAnnotation.

### visit {#visit-com.aspose.pdf.PageInformationAnnotation-}
يختار {@code pageInformation} إذا تم تهيئة {@link AnnotationSelector} باستخدام كائن {@link PageInformationAnnotation}.

### visit {#visit-com.aspose.pdf.PDF3DAnnotation-}
اختر تعليقة PDF3D إذا تم تهيئة AnnotationSelector باستخدام كائن PDF3DAnnotation.

### visit {#visit-com.aspose.pdf.PolygonAnnotation-}
اختر تعليقة مضلع إذا تم تهيئة AnnotationSelector باستخدام كائن PolygonAnnotation.

### visit {#visit-com.aspose.pdf.PolylineAnnotation-}
حدد تعليقة الخط المتعدد إذا تم تهيئة AnnotationSelector بكائن PolylineAnnotation.

### visit {#visit-com.aspose.pdf.PopupAnnotation-}
حدد تعليقة منبثقة إذا تم تهيئة AnnotationSelector بكائن PopupAnnotation.

### visit {#visit-com.aspose.pdf.RedactionAnnotation-}
حدد تعليقة حذف إذا تم تهيئة AnnotationSelector بكائن RedactAnnotation.

### visit {#visit-com.aspose.pdf.RegistrationMarkAnnotation-}
يحدد {@code registrationMark} إذا تم تهيئة {@link AnnotationSelector} بكائن {@link RegistrationMarkAnnotation}.

### visit {#visit-com.aspose.pdf.RichMediaAnnotation-}
حدد تعليقة RichMedia إذا تم تهيئة AnnotationSelector بكائن RichMedia annotation.

### visit {#visit-com.aspose.pdf.ScreenAnnotation-}
حدد تعليقة شاشة إذا تم تهيئة AnnotationSelector بكائن ScreenAnnotation.

### visit {#visit-com.aspose.pdf.SquareAnnotation-}
حدد تعليقة مربعة إذا تم تهيئة AnnotationSelector بكائن SquareAnnotation.

### visit {#visit-com.aspose.pdf.SquigglyAnnotation-}
حدد تعليقة متعرجة إذا تم تهيئة AnnotationSelector بكائن SquigglyAnnotation.

### visit {#visit-com.aspose.pdf.StampAnnotation-}
حدد تعليقة ختم إذا تم تهيئة AnnotationSelector بكائن StampAnnotation.

### visit {#visit-com.aspose.pdf.StrikeOutAnnotation-}
حدد تعليقة شطب إذا تم تهيئة AnnotationSelector بكائن StrikeOutAnnotation.

### visit {#visit-com.aspose.pdf.TextAnnotation-}
حدد تعليقة نص إذا تم تهيئة AnnotationSelector بكائن TextAnnotation.

### visit {#visit-com.aspose.pdf.TrimMarkAnnotation-}
يحدد {@code trimMark} إذا تم تهيئة {@link AnnotationSelector} بكائن {@link TrimMarkAnnotation}.

### visit {#visit-com.aspose.pdf.UnderlineAnnotation-}
حدد تعليقة تسطير إذا تم تهيئة AnnotationSelector بكائن UnderlineAnnotation.

### visit {#visit-com.aspose.pdf.WatermarkAnnotation-}
حدد تعليقة علامة مائية إذا تم تهيئة AnnotationSelector بكائن WatermarkAnnotation.

### visit {#visit-com.aspose.pdf.WidgetAnnotation-}
حدد تعليقة عنصر واجهة إذا تم تهيئة AnnotationSelector بكائن WidgetAnnotation.
