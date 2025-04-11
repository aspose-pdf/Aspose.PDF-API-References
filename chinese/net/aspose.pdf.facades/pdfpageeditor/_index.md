---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfPageEditor 类。表示一个用于编辑 PDF 文件页面的类，包括旋转页面、缩放页面、移动位置和更改页面大小
type: docs
weight: 4590
url: /zh/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

表示一个用于编辑 PDF 文件页面的类，包括旋转页面、缩放页面、移动位置和更改页面大小。

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | PdfPageEditor 类的构造函数。 |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | PdfPageEditor 类的构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | 获取或设置页面的显示持续时间。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在处理的文档外观。 |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | 获取或设置结果页面上原始 PDF 内容的水平对齐方式，默认值为 AlignmentType.Left。 |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | 一个包含页面编号和旋转角度的哈希表，键表示页面编号，键的值表示旋转角度。 |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | 获取或设置输出文件的页面大小。 |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | 获取或设置要编辑的页面编号。默认情况下，每个页面都会被编辑。 |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | 获取或设置页面的旋转，旋转必须为 0、90、180 或 270。默认值为 0。 |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | 获取或设置过渡效果的持续时间。 |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | 获取或设置在演示文稿中从另一页面移动到此页面时使用的过渡样式。 |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | 获取或设置结果页面上原始 PDF 内容的垂直对齐方式，默认值为 VerticalAlignmentType.Bottom。 |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | 获取或设置缩放系数。值 1.0 对应于 100%。默认值为 1.0。以下示例演示如何更改文档页面的缩放。 |

## Methods

| Name | Description |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | 应用对文档页面所做的更改。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化外观。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 释放与外观绑定的 Aspose.Pdf.Document。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放外观。 |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | 返回文档中指定框的大小。 |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | 返回指定页面的旋转。 |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | 返回页面总数。 |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | 返回指定页面的页面大小。 |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | 将原点从 (0, 0) 移动到指定的点。原点位于左下角，单位为点（1 英寸 = 72 点）。 |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | 将更改后的文档保存到流中。 |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | 将更改后的文档保存到文件中。 |

## Fields

| Name | Description |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | 垂直百叶窗 |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | 垂直百叶窗 |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | 自下而上的擦除 |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | 对角闪烁 |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | 旧页面溶解 |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | 向内框 |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | 左右闪烁 |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | 左右擦除 |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | 向外框 |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | 右左擦除 |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | 向内水平分割 |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | 向外水平分割 |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | 向内垂直分割 |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | 向外垂直分割 |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | 自上而下的闪烁 |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | 自上而下的擦除 |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)