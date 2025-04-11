---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo. تمثل هذه الفئة مجموعة من البيانات المتعلقة بحفظ ملفات الصور الخارجية أثناء تحويل PDF إلى HTML
type: docs
weight: 10260
url: /ar/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo class

تمثل هذه الفئة مجموعة من البيانات المتعلقة بحفظ ملف الصورة الخارجية أثناء تحويل PDF إلى HTML.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة. يمكن استخدامه في الكود المخصص لتحديد كيفية المعالجة أو أين يتم حفظ هذا الملف. |

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | يتم تعيينه بواسطة المحول. يمثل المحتوى الثنائي للملف المحفوظ. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | يجب تعيين هذه العلامة إلى "true" في الكود المخصص إذا كان لأسباب معينة يجب معالجة الملف المقترح ليس بواسطة الكود المخصص ولكن بواسطة كود المحول نفسه بالطريقة القياسية للمحول. لذا، تعني تعيينها إلى true أن الكود المخصص لم يعالج الملف المرجعي ويجب على المحول التعامل معه بنفسه (في كلا المعنيين - للحفظ في مكان ما ولتسمية الملف المرجعي). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | يمثل نوع الصورة المحفوظة المشار إليها في HTML. يتم تعيينه بواسطة المحول ويمكن استخدامه في الكود المخصص لتحديد ما يجب القيام به. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة. يمكن استخدامه في الكود المخصص لتحديد كيفية المعالجة أو أين يتم حفظ هذا الملف. |

### See Also

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)