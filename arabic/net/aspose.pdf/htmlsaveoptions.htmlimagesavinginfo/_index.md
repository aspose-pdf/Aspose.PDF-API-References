---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo class. هذه الفئة تمثل مجموعة من البيانات المتعلقة بحفظ ملفات الصور الخاصة بالموارد الخارجية أثناء تحويل PDF إلى HTML
type: docs
weight: 5640
url: /ar/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

هذه الفئة تمثل مجموعة من البيانات المتعلقة بحفظ ملفات الصور الخاصة بالموارد الخارجية أثناء تحويل PDF إلى HTML.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة. يمكن استخدامه في الكود المخصص لتحديد كيفية المعالجة أو أين يتم حفظ هذا الملف. |

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | يتم تعيينه بواسطة المحول. يمثل المحتوى الثنائي للملف المحفوظ. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | يجب تعيين هذه العلامة إلى "true" في الكود المخصص إذا كان لأسباب معينة يجب معالجة الملف المقترح ليس بواسطة الكود المخصص ولكن بواسطة كود المحول نفسه بالطريقة القياسية للمحول. لذا، تعني تعيينها إلى true أن الكود المخصص لم يعالج الملف المرجعي ويجب على المحول التعامل معه بنفسه (في كلا المعنيين - للحفظ في مكان ما ولتسمية في الملف المرجعي). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | يخبر الكود المخصص إلى أي صفحة من مجموعة صفحات HTML المولدة تنتمي الصورة المحفوظة. إذا تم إيقاف تقسيم الصفحات، فإن هذه القيمة تحتوي دائمًا على '1' لأنه في هذه الحالة يتم إنشاء صفحة HTML واحدة فقط. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | يمثل نوع الصورة المحفوظة المشار إليها في HTML. يتم تعيينه بواسطة المحول ويمكن استخدامه في الكود المخصص لتحديد ما يجب القيام به. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | يمكن أن تنتمي الصورة المحفوظة إلى HTML نفسه أو يمكن استخراجها من SVG المضمن في HTML. يمكن أن تخبر هذه الخاصية الكود المخصص بنوع الوالد للصورة المعالجة. يتم تعيينها بواسطة المحول ويمكن استخدامها في الكود المخصص لتحديد ما يجب القيام به مع تلك الصورة (على سبيل المثال، يمكن أن يقرر الكود المخصص أين يتم حفظ الصورة أو كيف يجب الإشارة إليها في محتوى الوالد). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | يخبر الكود المخصص إلى أي صفحة من مستند PDF الأصلي تنتمي الصورة المحفوظة. نظرًا لأنه من الممكن ألا يتم حفظ جميع صفحات المستند الأصلي، فإن هذه القيمة تخبرنا عن رقم الصفحة المضيفة في PDF الأصلي. إذا كان رقم الصفحة الأصلي غير معروف لسبب ما، فإنه دائمًا ما يرجع '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة. يمكن استخدامه في الكود المخصص لتحديد كيفية المعالجة أو أين يتم حفظ هذا الملف. |

### See Also

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)