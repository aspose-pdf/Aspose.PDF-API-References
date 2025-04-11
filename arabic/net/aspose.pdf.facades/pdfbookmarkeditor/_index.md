---
title: Class PdfBookmarkEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfBookmarkEditor class. يمثل فئة للعمل مع إشارات PDF بما في ذلك الإنشاء والتعديل والتصدير والاستيراد والحذف
type: docs
weight: 4420
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor class

يمثل فئة للعمل مع إشارات PDF بما في ذلك الإنشاء والتعديل والتصدير والاستيراد والحذف.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | يقوم بتهيئة كائن `PdfBookmarkEditor` جديد. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | يقوم بتهيئة كائن `PdfBookmarkEditor` جديد بناءً على *المستند*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يعمل عليها. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يقوم بتهيئة الواجهة. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | يقوم بالتخلص من Aspose.Pdf.Document المرتبط بواجهة. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | ينشئ إشارة للصفحة المحددة. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | ينشئ إشارات للصفحات المحددة. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | ينشئ إشارات لجميع الصفحات. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | ينشئ الإشارة المحددة في المستند. يمكن استخدام الطريقة لتشكيل تسلسل هرمي للإشارات المتداخلة. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | ينشئ إشارات لجميع الصفحات مع اللون والنمط المحددين (عريض، مائل). |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | يحذف جميع الإشارات من مستند PDF. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | يحذف الإشارة من مستند PDF. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | يصدر الإشارات إلى تدفق XML. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | يصدر الإشارات إلى ملف XML. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | يستخرج الإشارات من جميع المستويات من المستند. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | يستخرج الأطفال من إشارة بعنوان مشابه للإشارة المحددة. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | يستخرج الإشارات من جميع المستويات من المستند. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | يستخرج الإشارات بالعنوان المحدد. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | يستورد الإشارات إلى المستند من ملف XML. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | يستورد الإشارات إلى المستند من ملف XML. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | يعدل عنوان الإشارة وفقًا لعنوان الإشارة المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | يحفظ مستند PDF إلى التدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | يحفظ مستند PDF إلى الملف المحدد. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | يصدر الإشارات إلى ملف HTML. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)