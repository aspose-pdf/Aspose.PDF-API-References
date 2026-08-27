---
title: "الفئة SvgSaveOptions.SvgImageSavingInfo"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo. تمثل هذه الفئة مجموعة من البيانات المتعلقة بحفظ ملفات صور الموارد الخارجية أثناء تحويل PDF إلى HTML."
type: docs
weight: 10440
url: /ar/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo class

تمثل هذه الفئة مجموعة من البيانات المتعلقة بحفظ ملف صورة المورد الخارجي أثناء تحويل PDF إلى HTML.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى شفرة الطريقة المخصصة يمكن استخدامه في الشفرة المخصصة لتحديد كيفية معالجة الملف أو أين يتم حفظه. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | يتم تعيينه بواسطة المحول. يمثل المحتوى الثنائي للملف المحفوظ. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | يجب تعيين هذه العلامة إلى "true" في الشفرة المخصصة إذا لسبب ما يجب معالجة الملف المقترح ليس عبر الشفرة المخصصة بل عبر شفرة المحول نفسها بالطريقة القياسية للمحول. لذلك، تعيينها إلى true يعني أن الشفرة المخصصة لم تعالج الملف المشار إليه ويجب على المحول التعامل معه بنفسه (في كلا الحالتين - للحفظ في مكان ما ولتسمية الملف في الإشارة). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | يمثل نوع الصورة المحفوظة المشار إليها في HTML. يتم تعيينه بواسطة المحول ويمكن استخدامه في الشفرة المخصصة لتحديد ما يجب القيام به. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى شفرة الطريقة المخصصة يمكن استخدامه في الشفرة المخصصة لتحديد كيفية معالجة الملف أو أين يتم حفظه. |

### انظر أيضًا

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


