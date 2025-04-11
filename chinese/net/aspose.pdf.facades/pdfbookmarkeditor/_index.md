---
title: Class PdfBookmarkEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfBookmarkEditor class. 代表一个用于处理PDF文件书签的类，包括创建、修改、导出、导入和删除
type: docs
weight: 4420
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor class

代表一个用于处理PDF文件书签的类，包括创建、修改、导出、导入和删除。

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | 初始化新的 `PdfBookmarkEditor` 对象。 |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | 基于 *document* 初始化新的 `PdfBookmarkEditor` 对象。 |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在处理的文档外观。 |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化外观。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 释放与外观绑定的 Aspose.Pdf.Document。 |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | 为指定页面创建书签。 |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | 为指定页面创建书签。 |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | 为所有页面创建书签。 |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | 在文档中创建指定的书签。该方法可用于形成嵌套书签层次结构。 |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | 为所有页面创建具有指定颜色和样式（粗体、斜体）的书签。 |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | 删除PDF文档的所有书签。 |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | 删除PDF文档的书签。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放外观。 |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | 将书签导出到XML流。 |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | 将书签导出到XML文件。 |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | 从文档中提取所有级别的书签。 |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | 提取具有指定书签标题的书签的子书签。 |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | 从文档中提取所有级别的书签。 |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | 提取具有指定标题的书签。 |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | 从XML文件导入书签到文档。 |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | 从XML文件导入书签到文档。 |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | 根据指定的书签标题修改书签标题。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | 将PDF文档保存到指定流。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | 将PDF文档保存到指定文件。 |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | 将书签导出到HTML文件。 |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)