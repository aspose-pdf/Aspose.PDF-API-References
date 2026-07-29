---
title: "الفئة PdfContentEditor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfContentEditor. تمثل فئة لتعديل محتوى ملفات PDF."
type: docs
weight: 4550
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class

يمثل فئة لتحرير محتوى ملف PDF.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor/#constructor)() | المُنشئ لكائن PdfContentEditor. |
| [PdfContentEditor](pdfcontenteditor/#constructor_1)(Document) | يُهيئ كائن `PdfContentEditor` جديد على أساس *المستند*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy/) { get; set; } | مجموعة من المعلمات لعملية استبدال النص. |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions/) { get; set; } | يحصل أو يعيّن خيارات تحرير النص. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions/) { get; set; } | يحصل أو يعيّن خيارات استبدال النص. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions/) { get; set; } | يحصل أو يعيّن خيارات بحث النص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/)(string, string) | يضيف إجراءً إضافيًا لحدث المستند. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment_1)(string, string) | يضيف مرفق مستند بدون توضيح. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment)(Stream, string, string) | يضيف مرفق مستند بدون توضيح. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يُهيئ الواجهة. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_1)(Stream) | يربط تدفق PDF للتحرير. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_2)(string) | يربط ملف PDF للتحرير. |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/)(int) | يغيّر تفضيل العرض. |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close/)() | يغلق المستند المفتوح. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink)(Rectangle, string, int) | ينشئ رابطًا لتشغيل تطبيق في مستند PDF. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_1)(Rectangle, string, int, Color) | ينشئ رابطًا لتشغيل تطبيق في مستند PDF. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | ينشئ رابطًا لتشغيل تطبيق في مستند PDF. |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/)(string, Color, bool, bool, string, string, string) | ينشئ إشارة مرجعية بالإجراء المحدد. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret/)(int, Rectangle, Rectangle, string, string, Color) | ينشئ تعليقة caret. |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/)(Rectangle, int, Color, Enum[]) | ينشئ رابطًا لإجراءات مخصصة في مستند PDF. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_2)(Rectangle, string, string, int, string) | ينشئ تعليقة مرفق ملف. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment)(Rectangle, string, Stream, string, int, string) | ينشئ تعليقة مرفق ملف. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_3)(Rectangle, string, string, int, string, double) | ينشئ تعليقة مرفق ملف. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | ينشئ تعليقة مرفق ملف. |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext/)(Rectangle, string, int) | ينشئ تعليقة نص حر في مستند PDF |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/)(string, Rectangle, int, Color) | ينشئ رابطًا إلى JavaScript في مستند PDF. |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline/)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | ينشئ تعليقة خط. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink)(Rectangle, int, int) | ينشئ رابطًا محليًا في مستند PDF. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_1)(Rectangle, int, int, Color) | ينشئ رابطًا محليًا في مستند PDF. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | ينشئ رابطًا محليًا في مستند PDF. |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup/)(Rectangle, string, int, int, Color) | ينشئ تعليقة توصيف في مستند PDF. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie/)(Rectangle, string, int) | ينشئ تعليقات Movie. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink)(Rectangle, string, int, int) | ينشئ رابطًا إلى صفحة مستند PDF آخر. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | ينشئ رابطًا إلى صفحة مستند PDF آخر. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | ينشئ رابطًا إلى صفحة مستند PDF آخر. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon/)(LineInfo, int, Rectangle, string) | ينشئ تعليقة مضلع. |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline/)(LineInfo, int, Rectangle, string) | ينشئ تعليقة خط متعدد. |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup/)(Rectangle, string, bool, int) | ينشئ تعليقة منبثقة في مستند PDF. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp)(int, Rectangle, string, Color, Stream) | ينشئ تعليقة ختم مطاطي. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_1)(int, Rectangle, string, Color, string) | ينشئ تعليقة ختم مطاطي. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_2)(int, Rectangle, string, string, Color) | ينشئ تعليقة ختم مطاطي. |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound/)(Rectangle, string, string, int, string) | ينشئ تعليقات Sound. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle/)(Rectangle, string, Color, bool, int, int) | ينشئ تعليقة مربع-دائرة. |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext/)(Rectangle, string, string, bool, string, int) | ينشئ تعليقة نص في مستند PDF |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink)(Rectangle, string, int) | ينشئ رابط ويب في مستند PDF. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_1)(Rectangle, string, int, Color) | ينشئ رابط ويب في مستند PDF. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_2)(Rectangle, string, int, Color, Enum[]) | ينشئ رابط ويب في مستند PDF. |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments/)() | يحذف جميع المرفقات في مستند PDF. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage)() | يحذف جميع الصور من مستند PDF. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage_1)(int, int[]) | يحذف الصور المحددة في الصفحة المحددة. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp/)(int, int[]) | يحذف عدة طوابع في الصفحة المحددة حسب فهارس الطوابع. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid)(int) | احذف الطابع حسب المعرف من جميع صفحات المستند. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid_1)(int, int) | يحذف الطابع في الصفحة المحددة حسب معرف الطابع. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids_1)(int[]) | يحذف الطوابع ذات المعرفات المحددة من جميع صفحات المستند. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids)(int, int[]) | يحذف الطوابع في الصفحة المحددة حسب عدة معرفات للطوابع. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve/)(LineInfo, int, Rectangle, string) | ينشئ تعليقا من نوع المنحنى. |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink/)() | يستخرج مجموعة كائنات الرابط الموجودة في مستند PDF. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps/)(int) | يرجع مصفوفة من الطوابع في الصفحة. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference/)() | يرجع تفضيل العرض. |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid/)(int, int) | يخفي الطابع. بعد الإخفاء، يمكن استعادة رؤية الطابع باستخدام طريقة ShowStampById. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp/)(int, int, double, double) | يغيّر موضع الطابع في الصفحة. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid/)(int, int, double, double) | يغيّر موضع الطابع في الصفحة. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/)() | يزيل إجراء الفتح من المستند. هذه العملية مفيدة عند دمج عدة مستندات تستخدم إجراء 'GoTo' صريح عند بدء التشغيل. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage/)(int, int, string) | يستبدل الصورة المحددة في الصفحة المحددة من مستند PDF بصورة أخرى. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_2)(string, string) | يستبدل النص في ملف PDF. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext)(string, int, string) | يستبدل النص في ملف PDF في الصفحة المحددة. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_4)(string, string, int) | يستبدل النص في ملف PDF ويضبط حجم الخط. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_3)(string, string, TextState) | يستبدل النص في ملف PDF باستخدام كائن [`TextState`](../../aspose.pdf.text/textstate/) المحدد. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_1)(string, int, string, TextState) | يستبدل النص في ملف PDF في الصفحة المحددة. يمكن تحديد كائن [`TextState`](../../aspose.pdf.text/textstate/) (عائلة الخط، اللون) للنص المستبدل. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | يحفظ مستند PDF إلى الدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | يحفظ مستند PDF إلى الملف المحدد. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid/)(int, int) | يعرض الطابع الذي تم إخفاؤه بواسطة HiddenStampById. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose/) | نوع حدث المستند. يغلق المستند. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen/) | نوع حدث المستند. يفتح المستند. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted/) | نوع حدث المستند. ينفذ إجراءً بعد الطباعة. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved/) | نوع حدث المستند. ينفذ إجراءً بعد الحفظ. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint/) | نوع حدث المستند. ينفذ إجراءً قبل الطباعة. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave/) | نوع حدث المستند. تنفيذ إجراء قبل الحفظ. |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


