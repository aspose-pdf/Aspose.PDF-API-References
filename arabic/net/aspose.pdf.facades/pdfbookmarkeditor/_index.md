---
title: "الفئة PdfBookmarkEditor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfBookmarkEditor. تمثل فئة للعمل مع إشارات مرجعية لملفات PDF بما في ذلك إنشاء، تعديل، تصدير، استيراد وحذف."
type: docs
weight: 4540
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor class

يمثل فئة للعمل مع إشارات مرجعية لملف PDF تشمل الإنشاء، التعديل، التصدير، الاستيراد والحذف.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | ينشئ كائنًا جديدًا من `PdfBookmarkEditor`. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | ينشئ كائنًا جديدًا من `PdfBookmarkEditor` استنادًا إلى *document*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يُهيئ الواجهة. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | يفرغ Aspose.Pdf.Document المرتبط بواجهة. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | ينشئ إشارة مرجعية للصفحة المحددة. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | ينشئ إشارات مرجعية للصفحات المحددة. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | ينشئ إشارات مرجعية لجميع الصفحات. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | ينشئ الإشارة المرجعية المحددة في PDF Document. يمكن استخدام الطريقة لتكوين تسلسل هرمي للإشارات المرجعية المتداخلة. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | إنشاء إشارات مرجعية لجميع الصفحات باللون والنمط المحددين (عريض، مائل). |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | يحذف جميع الإشارات المرجعية في PDF Document. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | يحذف الإشارة المرجعية في PDF Document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | يصدّر الإشارات المرجعية إلى تدفق XML. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | يصدّر الإشارات المرجعية إلى ملف XML. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | يستخرج الإشارات المرجعية من جميع المستويات في Document. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | يستخرج العناصر الفرعية لbookmark بعنوان مشابه للعنوان في bookmark المحدد. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | يستخرج الإشارات المرجعية من جميع المستويات في Document. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | يستخرج الإشارات المرجعية ذات العنوان المحدد. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | يستورد الإشارات المرجعية إلى Document من ملف XML. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | يستورد الإشارات المرجعية إلى Document من ملف XML. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | يعدّل عنوان bookmark وفقًا للعنوان المحدد للbookmark. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | يحفظ مستند PDF إلى الدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | يحفظ مستند PDF إلى الملف المحدد. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | يصدّر الإشارات المرجعية إلى ملف HTML. |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


