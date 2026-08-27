---
title: "Class AnnotationSelector"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Annotations.AnnotationSelector class. تُستخدم هذه الفئة لاختيار التعليقات باستخدام فكرة قالب الزائر"
type: docs
weight: 1540
url: /ar/net/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector class

تُستخدم هذه الفئة لاختيار التعليقات التوضيحية باستخدام فكرة نموذج الزائر.

```csharp
public sealed class AnnotationSelector : IAnnotationVisitor
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [AnnotationSelector](annotationselector/#constructor)() | يُنشئ نسخة جديدة من فئة AnnotationSelector. |
| [AnnotationSelector](annotationselector/#constructor_1)(Annotation) | يُنشئ كائنًا جديدًا من `AnnotationSelector`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Selected](../../aspose.pdf.annotations/annotationselector/selected/) { get; } | قائمة الكائنات المحددة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit)(BleedMarkAnnotation) | يختار *bleedMark* إذا تم تهيئة `AnnotationSelector` باستخدام كائن [`BleedMarkAnnotation`](../bleedmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_1)(CaretAnnotation) | يختار تعليقة caret إذا تم تهيئة AnnotationSelector باستخدام كائن CaretAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_2)(CircleAnnotation) | يختار تعليقة دائرة إذا تم تهيئة AnnotationSelector باستخدام كائن CircleAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_3)(ColorBarAnnotation) | يختار تعليقة ColorBar إذا تم تهيئة AnnotationSelector باستخدام كائن ColorBar. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_4)(FileAttachmentAnnotation) | يختار تعليقة مرفق إذا تم تهيئة AnnotationSelector باستخدام كائن FileAttachmentAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_5)(FreeTextAnnotation) | يختار تعليقة نص حر إذا تم تهيئة AnnotationSelector باستخدام كائن FreeTextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_6)(HighlightAnnotation) | يختار تعليقة مرفق إذا تم تهيئة AnnotationSelector باستخدام كائن FreeTextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_7)(InkAnnotation) | يختار تعليقة حبر إذا تم تهيئة AnnotationSelector باستخدام كائن InkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_8)(LineAnnotation) | يختار تعليقة خط إذا تم تهيئة AnnotationSelector باستخدام كائن LineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_9)(LinkAnnotation) | يختار تعليقة رابط إذا تم تهيئة AnnotationSelector باستخدام كائن LinkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_10)(MovieAnnotation) | اختر تعليقة الفيلم إذا تم تهيئة AnnotationSelector باستخدام كائن MovieAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_11)(PageInformationAnnotation) | يختار *pageInformation* إذا تم تهيئة `AnnotationSelector` باستخدام كائن [`PageInformationAnnotation`](../pageinformationannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_12)(PDF3DAnnotation) | اختر تعليقة PDF3D إذا تم تهيئة AnnotationSelector باستخدام كائن PDF3DAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_13)(PolygonAnnotation) | اختر تعليقة المضلع إذا تم تهيئة AnnotationSelector باستخدام كائن PolygonAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_14)(PolylineAnnotation) | اختر تعليقة الخط المتعدد إذا تم تهيئة AnnotationSelector باستخدام كائن PolylineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_15)(PopupAnnotation) | اختر تعليقة النافذة المنبثقة إذا تم تهيئة AnnotationSelector باستخدام كائن PopupAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_16)(RedactionAnnotation) | اختر تعليقة الحذف إذا تم تهيئة AnnotationSelector باستخدام كائن RedactAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_17)(RegistrationMarkAnnotation) | يختار *registrationMark* إذا تم تهيئة `AnnotationSelector` باستخدام كائن [`RegistrationMarkAnnotation`](../registrationmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_18)(RichMediaAnnotation) | اختر تعليقة الفيلم إذا تم تهيئة AnnotationSelector باستخدام كائن RichMedia. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_19)(ScreenAnnotation) | اختر تعليقة الشاشة إذا تم تهيئة AnnotationSelector باستخدام كائن ScreenAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_20)(SquareAnnotation) | اختر تعليقة المربع إذا تم تهيئة AnnotationSelector باستخدام كائن SquareAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_21)(SquigglyAnnotation) | اختر تعليقة المتعرج إذا تم تهيئة AnnotationSelector باستخدام كائن SquigglyAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_22)(StampAnnotation) | اختر تعليقة الختم إذا تم تهيئة AnnotationSelector باستخدام كائن StampAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_23)(StrikeOutAnnotation) | اختر تعليقة الشطب إذا تم تهيئة AnnotationSelector باستخدام كائن StrikeOutAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_24)(TextAnnotation) | اختر تعليقة النص إذا تم تهيئة AnnotationSelector باستخدام كائن TextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_25)(TrimMarkAnnotation) | يختار *trimMark* إذا تم تهيئة `AnnotationSelector` باستخدام كائن [`TrimMarkAnnotation`](../trimmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_26)(UnderlineAnnotation) | اختر تعليقة التسطير إذا تم تهيئة AnnotationSelector باستخدام كائن UnderlineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_27)(WatermarkAnnotation) | اختر تعليقة العلامة المائية إذا تم تهيئة AnnotationSelector باستخدام كائن WatermarkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_28)(WidgetAnnotation) | اختر تعليقة الودجت إذا تم تهيئة AnnotationSelector باستخدام كائن WidgetAnnotation. |

### انظر أيضًا

* interface [IAnnotationVisitor](../iannotationvisitor/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


