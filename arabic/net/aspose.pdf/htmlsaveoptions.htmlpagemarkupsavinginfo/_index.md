---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo. إذا كانت خاصية SplitToPages من HtmlSaveOptions، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء تحويل PDF إلى HTML. تمثل هذه الفئة مجموعة من البيانات المتعلقة بالحفظ المخصص لعلامة صفحة HTML واحدة أثناء تحويل PDF إلى HTML.
type: docs
weight: 5670
url: /ar/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

إذا كانت خاصية SplitToPages من HtmlSaveOptions، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء تحويل PDF إلى HTML. تمثل هذه الفئة مجموعة من البيانات المتعلقة بالحفظ المخصص لعلامة صفحة HTML واحدة أثناء تحويل PDF إلى HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | يتم تعيينه بواسطة المحول. يمثل HTML المحفوظ كتيار |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | يجب تعيينه في الكود المخصص عند الضرورة. يجب تعيين هذه العلامة إلى "true" في الكود المخصص إذا كان لأسباب معينة يجب معالجة HTML-markup المقدم ليس بواسطة الكود المخصص ولكن بواسطة كود المحول نفسه بطريقة قياسية للمحول. لذا، تعني تعيين هذه العلامة في الكود المخصص أن الكود المخصص لم يعالج الملف المرجعي ويجب على المحول التعامل معه بنفسه |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | يتم تعيينه بواسطة المحول. إذا تم تعيين خاصية SplitToPages، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء التحويل. تحتوي هذه الخاصية على رقم الصفحة المحفوظة من ملف HTML. يمكن استخدام هذه الخاصية في منطق الكود المخصص لتحديد كيفية المعالجة أو أين يتم حفظ صفحة HTML وإذا تم إيقاف تقسيم الصفحات، فإن هذه القيمة تحتوي دائمًا على '1' لأنه في هذه الحالة يتم إنشاء صفحة HTML كبيرة واحدة فقط للمستند المصدر بالكامل. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | يتم تعيينه بواسطة المحول. إذا تم تعيين خاصية SplitToPages، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء التحويل. تخبر هذه الخاصية الكود المخصص من أي صفحة من PDF الأصلي تم إنشاء HTML-markup المحفوظ. إذا كان رقم الصفحة الأصلي لسبب ما غير معروف أو SplitOnPages=false، فإن هذه الخاصية تحتوي دائمًا على '0' مما يشير إلى أن المحول لا يمكنه توفير رقم الصفحة الأصلي الدقيق لملف HTML-markup المقدم. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة. يمكن استخدامه في الكود المخصص لتحديد كيفية المعالجة أو أين يتم حفظ المحتوى |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)