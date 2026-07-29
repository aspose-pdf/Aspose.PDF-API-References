---
title: "类 PdfBookmarkEditor"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfBookmarkEditor 类。表示用于处理 PDF 文件书签的类，包括创建、修改、导出、导入和删除。"
type: docs
weight: 4540
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor class

表示用于处理 PDF 文件书签的类，包括创建、修改、导出、导入和删除。

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | 初始化新的 `PdfBookmarkEditor` 对象。 |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | 基于 *document* 初始化新的 `PdfBookmarkEditor` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在操作的 document facade。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化 facade。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化 facade。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化 facade。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 释放与外观绑定的 Aspose.Pdf.Document。 |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | 为指定的 page 创建书签。 |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | 为指定的 pages 创建书签。 |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | 为所有 pages 创建书签。 |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | 在 document 中创建指定的书签。此方法可用于形成嵌套书签层次结构。 |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | 为所有 pages 创建书签，使用指定的颜色和样式（粗体、斜体）。 |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | 删除 PDF document 的所有书签。 |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | 删除 PDF document 的书签。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放 facade。 |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | 将书签导出为 XML 流。 |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | 将书签导出为 XML 文件。 |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | 从 document 中提取所有层级的书签。 |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | 提取标题与指定书签相同的书签的子项。 |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | 从 document 中提取所有层级的书签。 |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | 提取具有指定标题的书签。 |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | 从 XML 文件导入书签到 document。 |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | 从 XML 文件导入书签到 document。 |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | 根据指定的书签标题修改书签标题。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | 将 PDF 文档保存到指定的流中。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | 将 PDF 文档保存到指定的文件中。 |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | 将书签导出为 HTML 文件。 |

### 另请参见

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


