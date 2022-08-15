---
title: PdfContentEditor
second_title: Aspose.PDF لمرجع .NET API
description: يمثل فئة لتحرير محتوى ملف PDF .
type: docs
weight: 2440
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class

يمثل فئة لتحرير محتوى ملف PDF .

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor#constructor)() | مُنشئ الكائن PdfContentEditor. |
| [PdfContentEditor](pdfcontenteditor#constructor_1)(Document) | تهيئة جديد[`PdfContentEditor`](../pdfcontenteditor) كائن على قاعدة*document* . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | الحصول على واجهة المستند التي تعمل عليها. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy) { get; set; } | مجموعة من المعلمات لاستبدال عملية النص |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions) { get; set; } | الحصول على أو تعيين خيارات تحرير النص. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions) { get; set; } | الحصول على أو تعيين خيارات استبدال النص. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions) { get; set; } | الحصول على أو تعيين خيارات البحث عن النص. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction)(string, string) | يضيف إجراءً إضافيًا لحدث المستند. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment#adddocumentattachment_1)(string, string) | إضافة مرفق مستند بدون تعليق توضيحي . |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment#adddocumentattachment)(Stream, string, string) | إضافة مرفق مستند بدون تعليق توضيحي . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | تهيئة الواجهة . |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf#bindpdf_1)(Stream) | يربط دفق PDF للتحرير . |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf#bindpdf_2)(string) | يربط ملف PDF للتحرير . |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference)(int) | يغير تفضيل العرض . |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close)() | إغلاق المستند المفتوح . |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink)(Rectangle, string, int) | إنشاء ارتباط لبدء تشغيل تطبيق في مستند PDF . |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink_1)(Rectangle, string, int, Color) | إنشاء ارتباط لبدء تشغيل تطبيق في مستند PDF . |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | إنشاء ارتباط لبدء تشغيل تطبيق في مستند PDF . |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction)(string, Color, bool, bool, string, string, string) | إنشاء إشارة مرجعية بالإجراء المحدد. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret)(int, Rectangle, Rectangle, string, string, Color) | إنشاء تعليق توضيحي بمؤشر الإقحام . |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink)(Rectangle, int, Color, Enum[]) | إنشاء ارتباط للإجراءات المخصصة في مستند PDF . |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_2)(Rectangle, string, string, int, string) | إنشاء تعليق توضيحي لمرفق الملف . |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment)(Rectangle, string, Stream, string, int, string) | إنشاء تعليق توضيحي لمرفق الملف . |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_3)(Rectangle, string, string, int, string, double) | إنشاء تعليق توضيحي لمرفق الملف . |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | إنشاء تعليق توضيحي لمرفق الملف . |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext)(Rectangle, string, int) | إنشاء تعليق توضيحي نصي مجاني في مستند PDF |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink)(string, Rectangle, int, Color) | ينشئ ارتباطًا بجافا سكريبت في مستند PDF . |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | إنشاء تعليق توضيحي للسطر . |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink)(Rectangle, int, int) | إنشاء ارتباط محلي في مستند PDF . |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink_1)(Rectangle, int, int, Color) | إنشاء ارتباط محلي في مستند PDF . |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | إنشاء ارتباط محلي في مستند PDF . |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup)(Rectangle, string, int, int, Color) | ينشئ تعليقًا توضيحيًا لوثيقة PDF. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie)(Rectangle, string, int) | إنشاء تعليقات توضيحية للفيلم . |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink)(Rectangle, string, int, int) | إنشاء ارتباط إلى صفحة وثيقة PDF أخرى. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | إنشاء ارتباط إلى صفحة وثيقة PDF أخرى. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | إنشاء ارتباط إلى صفحة وثيقة PDF أخرى. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon)(LineInfo, int, Rectangle, string) | لإنشاء تعليق توضيحي على شكل مضلع . |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline)(LineInfo, int, Rectangle, string) | إنشاء تعليق توضيحي متعدد الخطوط . |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup)(Rectangle, string, bool, int) | إنشاء تعليق توضيحي منبثق في مستند PDF . |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp)(int, Rectangle, string, Color, Stream) | ينشئ تعليقًا توضيحيًا بختم مطاطي . |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp_1)(int, Rectangle, string, Color, string) | ينشئ تعليقًا توضيحيًا بختم مطاطي . |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp_2)(int, Rectangle, string, string, Color) | ينشئ تعليقًا توضيحيًا بختم مطاطي . |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound)(Rectangle, string, string, int, string) | إنشاء تعليقات توضيحية صوتية. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle)(Rectangle, string, Color, bool, int, int) | إنشاء تعليق توضيحي على شكل دائرة مربعة . |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext)(Rectangle, string, string, bool, string, int) | إنشاء تعليق توضيحي نصي في مستند PDF |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink)(Rectangle, string, int) | إنشاء ارتباط ويب في مستند PDF . |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink_1)(Rectangle, string, int, Color) | إنشاء ارتباط ويب في مستند PDF . |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink_2)(Rectangle, string, int, Color, Enum[]) | إنشاء ارتباط ويب في مستند PDF . |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments)() | حذف كافة المرفقات في مستند PDF . |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage#deleteimage)() | حذف كافة الصور من مستند PDF . |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage#deleteimage_1)(int, int[]) | حذف الصور المحددة في الصفحة المحددة. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp)(int, int[]) | حذف أختام متعددة على الصفحة المحددة بواسطة فهارس الطوابع. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid#deletestampbyid)(int) | حذف الختم بواسطة المعرف من كافة صفحات المستند. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid#deletestampbyid_1)(int, int) | حذف الختم من الصفحة المحددة بواسطة معرف الطابع. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids#deletestampbyids_1)(int[]) | حذف الأختام ذات المعرفات المحددة من كافة صفحات المستند. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids#deletestampbyids)(int, int[]) | حذف الطوابع على الصفحة المحددة بواسطة معرفات طوابع متعددة. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | التخلص من الواجهة . |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve)(LineInfo, int, Rectangle, string) | إنشاء تعليق توضيحي منحنى . |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink)() | لاستخراج مجموعة مثيلات الارتباط الموجودة في مستند PDF. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps)(int) | إرجاع مصفوفة الطوابع على الصفحة. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference)() | إرجاع تفضيل العرض . |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid)(int, int) | يخفي الطابع. بعد الاختباء ، يمكن استعادة رؤية الختم باستخدام طريقة ShowStampById. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp)(int, int, double, double) | يغير موضع الختم على الصفحة. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid)(int, int, double, double) | يغير موضع الختم على الصفحة. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction)() | يزيل الإجراء المفتوح من المستند. هذه العملية مفيدة عند ربط مستندات متعددة تستخدم إجراء "GoTo" الصريح عند بدء التشغيل. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage)(int, int, string) | يستبدل الصورة المحددة على الصفحة المحددة من مستند PDF بصورة أخرى. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_2)(string, string) | يستبدل النص في ملف PDF . |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext)(string, int, string) | يستبدل النص في ملف PDF بالصفحة المحددة. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_4)(string, string, int) | يستبدل النص في ملف PDF ويعين حجم الخط. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_3)(string, string, TextState) | يستبدل النص في ملف PDF باستخدام المحدد[`TextState`](../../aspose.pdf.text/textstate) الكائن . |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_1)(string, int, string, TextState) | يستبدل النص في ملف PDF بالصفحة المحددة.[`TextState`](../../aspose.pdf.text/textstate) يمكن تحديد الكائن (عائلة الخط ، اللون) لاستبدال النص. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | يحفظ مستند PDF في التدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | يحفظ مستند PDF في الملف المحدد. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid)(int, int) | يظهر الطابع الذي كان مخفيًا بواسطة HiddenStampById. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose) | نوع حدث مستند. يغلق وثيقة. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen) | نوع حدث مستند. يفتح وثيقة. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted) | نوع حدث مستند. تنفيذ إجراء بعد الطباعة. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved) | نوع حدث مستند. تنفيذ إجراء بعد الحفظ. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint) | نوع حدث مستند. تنفيذ إجراء قبل الطباعة. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave) | نوع حدث مستند. تنفيذ إجراء قبل الحفظ. |

### أنظر أيضا

* class [SaveableFacade](../saveablefacade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
