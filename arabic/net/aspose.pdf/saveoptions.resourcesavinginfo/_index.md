---
title: "الفئة SaveOptions.ResourceSavingInfo"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.SaveOptionsResourceSavingInfo. تمثل هذه الفئة مجموعة من البيانات المتعلقة بحفظ ملفات الموارد الخارجية التي تحدث أثناء تحويل PDF إلى تنسيق آخر مثل HTML."
type: docs
weight: 10090
url: /ar/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## SaveOptions.ResourceSavingInfo class

هذه الفئة تمثل مجموعة من البيانات المتعلقة بحفظ ملف المورد الخارجي التي تحدث أثناء تحويل PDF إلى تنسيق آخر (مثلاً HTML)

```csharp
public class ResourceSavingInfo
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى شفرة الطريقة المخصصة يمكن استخدامه في الشفرة المخصصة لتحديد كيفية معالجة الملف أو أين يتم حفظه. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | يتم تعيينه بواسطة المحول. يمثل المحتوى الثنائي للملف المحفوظ. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | يجب تعيين هذه العلامة إلى "true" في الشفرة المخصصة إذا لسبب ما يجب معالجة الملف المقترح ليس عبر الشفرة المخصصة بل عبر شفرة المحول نفسها بالطريقة القياسية للمحول. لذلك، تعيينها إلى true يعني أن الشفرة المخصصة لم تعالج الملف المشار إليه ويجب على المحول التعامل معه بنفسه (في كلا الحالتين - للحفظ في مكان ما ولتسمية الملف في الإشارة). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى شفرة الطريقة المخصصة يمكن استخدامه في الشفرة المخصصة لتحديد كيفية معالجة الملف أو أين يتم حفظه. |

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


