---
title: Class SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.SaveOptionsResourceSavingInfo. تمثل هذه الفئة مجموعة من البيانات المتعلقة بحفظ ملفات الموارد الخارجية التي تحدث أثناء تحويل PDF إلى تنسيق آخر مثل HTML
type: docs
weight: 9940
url: /ar/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## SaveOptions.ResourceSavingInfo class

تمثل هذه الفئة مجموعة من البيانات المتعلقة بحفظ ملفات الموارد الخارجية التي تحدث أثناء تحويل PDF إلى تنسيق آخر (مثل HTML)

```csharp
public class ResourceSavingInfo
```

## Properties

| Name | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة. يمكن استخدامه في الكود المخصص لتحديد كيفية المعالجة أو أين يتم حفظ هذا الملف |

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | يتم تعيينه بواسطة المحول. يمثل المحتوى الثنائي للملف المحفوظ. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | يجب تعيين هذه العلامة إلى "true" في الكود المخصص إذا كان لأسباب معينة يجب معالجة الملف المقترح ليس بواسطة الكود المخصص ولكن بواسطة كود المحول نفسه بطريقة قياسية للمحول. لذا، فإن تعيينها إلى true يعني أن الكود المخصص لم يعالج الملف المرجعي ويجب على المحول التعامل معه بنفسه (في كلا المعنيين - للحفظ في مكان ما ولتسمية الملف المرجعي). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة. يمكن استخدامه في الكود المخصص لتحديد كيفية المعالجة أو أين يتم حفظ هذا الملف |

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)