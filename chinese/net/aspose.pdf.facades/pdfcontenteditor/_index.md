---
title: Class PdfContentEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfContentEditor 类。表示一个用于编辑 PDF 文件内容的类
type: docs
weight: 4430
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor 类

表示一个用于编辑 PDF 文件内容的类。

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor/#constructor)() | PdfContentEditor 对象的构造函数。 |
| [PdfContentEditor](pdfcontenteditor/#constructor_1)(Document) | 基于 *document* 初始化新的 `PdfContentEditor` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取文档外观正在处理的文档。 |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy/) { get; set; } | 替换文本操作的一组参数 |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions/) { get; set; } | 获取或设置文本编辑选项。 |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions/) { get; set; } | 获取或设置文本替换选项。 |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions/) { get; set; } | 获取或设置文本搜索选项。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/)(string, string) | 为文档事件添加额外的操作。 |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment_1)(string, string) | 添加没有注释的文档附件。 |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment)(Stream, string, string) | 添加没有注释的文档附件。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_1)(Stream) | 绑定用于编辑的 PDF 流。 |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_2)(string) | 绑定用于编辑的 PDF 文件。 |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/)(int) | 更改视图偏好。 |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close/)() | 关闭已打开的文档。 |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink)(Rectangle, string, int) | 创建一个链接以在 PDF 文档中启动应用程序。 |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_1)(Rectangle, string, int, Color) | 创建一个链接以在 PDF 文档中启动应用程序。 |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | 创建一个链接以在 PDF 文档中启动应用程序。 |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/)(string, Color, bool, bool, string, string, string) | 创建具有指定操作的书签。 |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret/)(int, Rectangle, Rectangle, string, string, Color) | 创建插入符号注释。 |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/)(Rectangle, int, Color, Enum[]) | 创建一个链接以在 PDF 文档中执行自定义操作。 |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_2)(Rectangle, string, string, int, string) | 创建文件附件注释。 |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment)(Rectangle, string, Stream, string, int, string) | 创建文件附件注释。 |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_3)(Rectangle, string, string, int, string, double) | 创建文件附件注释。 |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | 创建文件附件注释。 |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext/)(Rectangle, string, int) | 在 PDF 文档中创建自由文本注释 |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/)(string, Rectangle, int, Color) | 创建一个链接到 PDF 文档中的 JavaScript。 |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline/)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | 创建线条注释。 |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink)(Rectangle, int, int) | 在 PDF 文档中创建本地链接。 |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_1)(Rectangle, int, int, Color) | 在 PDF 文档中创建本地链接。 |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | 在 PDF 文档中创建本地链接。 |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup/)(Rectangle, string, int, int, Color) | 在 PDF 文档中创建标记注释。 |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie/)(Rectangle, string, int) | 创建电影注释。 |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink)(Rectangle, string, int, int) | 创建指向另一个 PDF 文档页面的链接。 |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | 创建指向另一个 PDF 文档页面的链接。 |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | 创建指向另一个 PDF 文档页面的链接。 |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon/)(LineInfo, int, Rectangle, string) | 创建多边形注释。 |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline/)(LineInfo, int, Rectangle, string) | 创建折线注释。 |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup/)(Rectangle, string, bool, int) | 在 PDF 文档中创建弹出注释。 |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp)(int, Rectangle, string, Color, Stream) | 创建橡皮章注释。 |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_1)(int, Rectangle, string, Color, string) | 创建橡皮章注释。 |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_2)(int, Rectangle, string, string, Color) | 创建橡皮章注释。 |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound/)(Rectangle, string, string, int, string) | 创建声音注释。 |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle/)(Rectangle, string, Color, bool, int, int) | 创建方形-圆形注释。 |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext/)(Rectangle, string, string, bool, string, int) | 在 PDF 文档中创建文本注释 |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink)(Rectangle, string, int) | 在 PDF 文档中创建网页链接。 |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_1)(Rectangle, string, int, Color) | 在 PDF 文档中创建网页链接。 |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_2)(Rectangle, string, int, Color, Enum[]) | 在 PDF 文档中创建网页链接。 |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments/)() | 删除 PDF 文档中的所有附件。 |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage)() | 从 PDF 文档中删除所有图像。 |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage_1)(int, int[]) | 删除指定页面上的指定图像。 |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp/)(int, int[]) | 根据印章索引删除指定页面上的多个印章。 |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid)(int) | 从文档的所有页面中按 ID 删除印章。 |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid_1)(int, int) | 根据印章 ID 删除指定页面上的印章。 |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids_1)(int[]) | 从文档的所有页面中删除具有指定 ID 的印章。 |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids)(int, int[]) | 根据多个印章 ID 删除指定页面上的印章。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 处理外观。 |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve/)(LineInfo, int, Rectangle, string) | 创建曲线注释。 |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink/)() | 提取 PDF 文档中包含的链接实例集合。 |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps/)(int) | 返回页面上的印章数组。 |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference/)() | 返回视图偏好。 |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid/)(int, int) | 隐藏印章。隐藏后，可以使用 ShowStampById 方法恢复印章的可见性。 |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp/)(int, int, double, double) | 更改页面上印章的位置。 |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid/)(int, int, double, double) | 更改页面上印章的位置。 |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/)() | 从文档中移除打开操作。此操作在连接多个使用显式“转到”操作启动的文档时非常有用。 |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage/)(int, int, string) | 用另一张图像替换 PDF 文档指定页面上的指定图像。 |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_2)(string, string) | 替换 PDF 文件中的文本。 |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext)(string, int, string) | 替换指定页面上 PDF 文件中的文本。 |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_4)(string, string, int) | 替换 PDF 文件中的文本并设置字体大小。 |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_3)(string, string, TextState) | 使用指定的 [`TextState`](../../aspose.pdf.text/textstate/) 对象替换 PDF 文件中的文本。 |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_1)(string, int, string, TextState) | 替换指定页面上 PDF 文件中的文本。可以指定 [`TextState`](../../aspose.pdf.text/textstate/) 对象（字体系列、颜色）来替换文本。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | 将 PDF 文档保存到指定流。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | 将 PDF 文档保存到指定文件。 |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid/)(int, int) | 显示被 HiddenStampById 隐藏的印章。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose/) | 一种文档事件类型。关闭文档。 |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen/) | 一种文档事件类型。打开文档。 |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted/) | 一种文档事件类型。打印后执行操作。 |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved/) | 一种文档事件类型。保存后执行操作。 |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint/) | 一种文档事件类型。打印前执行操作。 |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave/) | 一种文档事件类型。保存前执行操作。 |

### 另请参阅

* 类 [SaveableFacade](../saveablefacade/)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../)