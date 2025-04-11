---
title: Class AnnotationSelector
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.AnnotationSelector. تُستخدم هذه الفئة لاختيار التعليقات التوضيحية باستخدام فكرة قالب الزائر
type: docs
weight: 1450
url: /ar/net/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector class

تُستخدم هذه الفئة لاختيار التعليقات التوضيحية باستخدام فكرة قالب الزائر.

```csharp
public sealed class AnnotationSelector : IAnnotationVisitor
```

## Constructors

| Name | Description |
| --- | --- |
| [AnnotationSelector](annotationselector/#constructor)() | يقوم بتهيئة مثيل جديد من فئة AnnotationSelector. |
| [AnnotationSelector](annotationselector/#constructor_1)(Annotation) | يقوم بتهيئة كائن `AnnotationSelector` جديد. |

## Properties

| Name | Description |
| --- | --- |
| [Selected](../../aspose.pdf.annotations/annotationselector/selected/) { get; } | قائمة الكائنات المحددة. |

## Methods

| Name | Description |
| --- | --- |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit)(BleedMarkAnnotation) | يختار *bleedMark* إذا تم تهيئة `AnnotationSelector` باستخدام كائن [`BleedMarkAnnotation`](../bleedmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_1)(CaretAnnotation) | يختار تعليق المؤشر إذا تم تهيئة AnnotationSelector باستخدام كائن CaretAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_2)(CircleAnnotation) | يختار تعليق الدائرة إذا تم تهيئة AnnotationSelector باستخدام كائن CircleAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_3)(ColorBarAnnotation) | يختار تعليق ColorBar إذا تم تهيئة AnnotationSelector باستخدام كائن ColorBar. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_4)(FileAttachmentAnnotation) | يختار تعليق المرفق إذا تم تهيئة AnnotationSelector باستخدام كائن FileAttachmentAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_5)(FreeTextAnnotation) | يختار تعليق النص الحر إذا تم تهيئة AnnotationSelector باستخدام كائن FreeTextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_6)(HighlightAnnotation) | يختار تعليق المرفق إذا تم تهيئة AnnotationSelector باستخدام كائن FreeTextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_7)(InkAnnotation) | يختار تعليق الحبر إذا تم تهيئة AnnotationSelector باستخدام كائن InkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_8)(LineAnnotation) | يختار تعليق الخط إذا تم تهيئة AnnotationSelector باستخدام كائن LineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_9)(LinkAnnotation) | يختار تعليق الرابط إذا تم تهيئة AnnotationSelector باستخدام كائن LinkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_10)(MovieAnnotation) | يختار تعليق الفيلم إذا تم تهيئة AnnotationSelector باستخدام كائن MovieAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_11)(PageInformationAnnotation) | يختار *pageInformation* إذا تم تهيئة `AnnotationSelector` باستخدام كائن [`PageInformationAnnotation`](../pageinformationannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_12)(PDF3DAnnotation) | يختار تعليق PDF3D إذا تم تهيئة AnnotationSelector باستخدام كائن PDF3DAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_13)(PolygonAnnotation) | يختار تعليق المضلع إذا تم تهيئة AnnotationSelector باستخدام كائن PolygonAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_14)(PolylineAnnotation) | يختار تعليق الخط المتعدد إذا تم تهيئة AnnotationSelector باستخدام كائن PolylineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_15)(PopupAnnotation) | يختار تعليق النافذة المنبثقة إذا تم تهيئة AnnotationSelector باستخدام كائن PopupAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_16)(RedactionAnnotation) | يختار تعليق الحذف إذا تم تهيئة AnnotationSelector باستخدام كائن RedactAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_17)(RegistrationMarkAnnotation) | يختار *registrationMark* إذا تم تهيئة `AnnotationSelector` باستخدام كائن [`RegistrationMarkAnnotation`](../registrationmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_18)(RichMediaAnnotation) | يختار تعليق الفيلم إذا تم تهيئة AnnotationSelector باستخدام كائن RichMedia. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_19)(ScreenAnnotation) | يختار تعليق الشاشة إذا تم تهيئة AnnotationSelector باستخدام كائن ScreenAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_20)(SquareAnnotation) | يختار تعليق المربع إذا تم تهيئة AnnotationSelector باستخدام كائن SquareAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_21)(SquigglyAnnotation) | يختار تعليق الموجة المتعرجة إذا تم تهيئة AnnotationSelector باستخدام كائن SquigglyAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_22)(StampAnnotation) | يختار تعليق الطابع إذا تم تهيئة AnnotationSelector باستخدام كائن StampAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_23)(StrikeOutAnnotation) | يختار تعليق الشطب إذا تم تهيئة AnnotationSelector باستخدام كائن StrikeOutAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_24)(TextAnnotation) | يختار تعليق النص إذا تم تهيئة AnnotationSelector باستخدام كائن TextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_25)(TrimMarkAnnotation) | يختار *trimMark* إذا تم تهيئة `AnnotationSelector` باستخدام كائن [`TrimMarkAnnotation`](../trimmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_26)(UnderlineAnnotation) | يختار تعليق التسطير إذا تم تهيئة AnnotationSelector باستخدام كائن UnderlineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_27)(WatermarkAnnotation) | يختار تعليق العلامة المائية إذا تم تهيئة AnnotationSelector باستخدام كائن WatermarkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_28)(WidgetAnnotation) | يختار تعليق الودجت إذا تم تهيئة AnnotationSelector باستخدام كائن WidgetAnnotation. |

### See Also

* interface [IAnnotationVisitor](../iannotationvisitor/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)