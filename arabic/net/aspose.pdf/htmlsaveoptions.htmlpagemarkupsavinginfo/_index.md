---
title: "الفئة HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo. إذا كان خاصية SplitToPages من HtmlSaveOptions فسيتم إنشاء عدة ملفات HTML، ملف HTML واحد لكل صفحة محوّلة، أثناء تحويل PDF إلى HTML. تمثل هذه الفئة مجموعة من البيانات المتعلقة بالحفظ المخصص لعلامة صفحة HTML واحدة أثناء تحويل PDF إلى HTML."
type: docs
weight: 5800
url: /ar/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

إذا كانت خاصية SplitToPages من HtmlSaveOptions، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة محوّلة) أثناء تحويل PDF إلى HTML. تمثل هذه الفئة مجموعة من البيانات المتعلقة بالحفظ المخصص لعلامة صفحة HTML واحدة أثناء تحويل PDF إلى HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## الحقول

| الاسم | الوصف |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | يتم تعيينه بواسطة المحول. يمثل HTML المحفوظ كتيار. |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | يجب تعيينه في الشيفرة المخصصة عند الحاجة. يجب ضبط هذه العلامة إلى "true" في الشيفرة المخصصة إذا كان لسبب ما يجب معالجة العلامة html المقدمة ليس بالشيفرة المخصصة بل بشيفرة المحول نفسها بالطريقة القياسية للمحول. وبالتالي، تعيين هذه العلامة في الشيفرة المخصصة يعني أن الشيفرة المخصصة لم تعالج الملف المشار إليه ويجب على المحول التعامل معه بنفسه. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | يتم تعيينه بواسطة المحول. إذا تم ضبط خاصية SplitToPages، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة محوّلة) أثناء عملية التحويل. تحتوي هذه الخاصية على ترتيب ملف صفحة HTML المحفوظة. يمكن استخدام الخاصية في منطق الشيفرة المخصصة لتحديد كيفية معالجة أو مكان حفظ صفحة HTML، وإذا تم إيقاف تقسيم الصفحات فإن هذه القيمة تكون دائمًا "1" لأن الحالة تكون صفحة HTML واحدة كبيرة تُنشأ للمستند الأصلي بالكامل. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | يتم تعيينه بواسطة المحول. إذا تم ضبط خاصية SplitToPages، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة محوّلة) أثناء عملية التحويل. تُخبر هذه الخاصية الشيفرة المخصصة بالصفحة الأصلية في PDF التي تم إنشاء علامة HTML المحفوظة منها. إذا كان رقم الصفحة الأصلية غير معروف لسبب ما أو SplitOnPages=false، فإن هذه الخاصية تحتوي دائمًا على "0" مما يشير إلى أن المحول لا يستطيع توفير رقم الصفحة الأصلي الدقيق لملف علامة HTML المقدم. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى شيفرة الطريقة المخصصة. يمكن استخدامه في الشيفرة المخصصة لتحديد كيفية معالجة المحتوى أو مكان حفظه. |

### انظر أيضًا

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


