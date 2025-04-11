---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSanitization class. 代表清理和恢复 API。如果您无法以其他方式创建/打开文档，请使用它。
type: docs
weight: 4540
url: /zh/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class

代表清理和恢复 API。如果您无法以其他方式创建/打开文档，请使用它。

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取文档外观正在处理的文档。 |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | 文件保存后，您可以检查对文件所做的操作。 |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | 允许为文档生成新的 xref 和 trailer。 |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | 允许删除 pdf 数据之后的数据。 |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | 允许删除 pdf 数据之前的数据。 |

## Methods

| Name | Description |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | 初始化外观。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | 绑定用于清理的 Pdf 流。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | 绑定用于清理的 Pdf 文件。 |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | 关闭外观。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 处理外观。 |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | 删除旧的 xref 和 trailer，并创建新的 xref 和 trailer。 |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | 恢复文档。使用属性进行自定义。 |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | 将结果 PDF 保存到流。 |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | 将结果 PDF 保存到文件。 |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | 删除最后一个 %%EOF 之后的数据。 |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | 删除 %PDF 之前的数据。 |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)