---
title: "الفئة HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo. تمثل هذه الفئة مجموعة من البيانات المتعلقة بحفظ ملفات صور الموارد الخارجية أثناء تحويل PDF إلى HTML"
type: docs
weight: 5770
url: /ar/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

تمثل هذه الفئة مجموعة من البيانات المتعلقة بحفظ ملف صورة المورد الخارجي أثناء تحويل PDF إلى HTML.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى شفرة الطريقة المخصصة يمكن استخدامه في الشفرة المخصصة لتحديد كيفية معالجة الملف أو أين يتم حفظه. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | يتم تعيينه بواسطة المحول. يمثل المحتوى الثنائي للملف المحفوظ. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | يجب تعيين هذه العلامة إلى "true" في الشفرة المخصصة إذا لسبب ما يجب معالجة الملف المقترح ليس عبر الشفرة المخصصة بل عبر شفرة المحول نفسها بالطريقة القياسية للمحول. لذلك، تعيينها إلى true يعني أن الشفرة المخصصة لم تعالج الملف المشار إليه ويجب على المحول التعامل معه بنفسه (في كلا الحالتين - للحفظ في مكان ما ولتسمية الملف في الإشارة). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | يخبر الكود المخصص إلى أي صفحة من مجموعة ملفات HTML المولدة تنتمي الصورة المحفوظة. إذا تم إيقاف تقسيم الصفحات فإن هذه القيمة دائمًا تحتوي على '1' لأنه في هذه الحالة يتم إنشاء صفحة HTML واحدة فقط. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | تمثل نوع الصورة المحفوظة المشار إليها في HTML. يتم تعيينها بواسطة المحول ويمكن استخدامها في الكود المخصص لتحديد ما يجب القيام به |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | يمكن أن تكون الصورة المحفوظة مرتبطة بـ HTML نفسها أو يمكن استخراجها من SVG المدمج في HTML. يمكن لهذه الخاصية إبلاغ الكود المخصص بنوع العنصر الأب للصورة المعالجة. يتم تعيينها بواسطة المحول ويمكن استخدامها في الكود المخصص لتحديد ما يجب القيام به مع تلك الصورة (مثلاً يمكن للكود المخصص أن يقرر أين يتم حفظ الصورة أو كيف يجب الإشارة إليها في محتوى العنصر الأب). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | يخبر الكود المخصص إلى أي صفحة من مستند PDF الأصلي تنتمي الصورة المحفوظة. نظرًا لأنه قد لا يتم حفظ جميع صفحات المستند الأصلي، فإن هذه القيمة تُظهر رقم الصفحة المضيفة في PDF الأصلي. إذا كان رقم الصفحة الأصلية غير معروف لسبب ما، فإنها دائمًا تُعيد '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى شفرة الطريقة المخصصة يمكن استخدامه في الشفرة المخصصة لتحديد كيفية معالجة الملف أو أين يتم حفظه. |

### انظر أيضًا

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


