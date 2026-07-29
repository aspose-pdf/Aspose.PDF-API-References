---
title: "类 PdfFileSanitization"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfFileSanitization 类。表示消毒和恢复 API。如果您无法以其他方式创建/打开文档，请使用它。"
type: docs
weight: 4660
url: /zh/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class

表示清理和恢复 API。如果无法以其他方式创建/打开文档，请使用它。

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在操作的 document facade。 |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | 文件保存后，您可以检查对文件所做的操作。 |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | 允许为文档生成新的交叉引用表（xref）和尾部。 |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | 允许删除 PDF 数据之后的数据 |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | 允许删除 PDF 数据之前的数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | 初始化 facade。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | 绑定用于消毒的 Pdf 流。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | 绑定一个用于清理的 Pdf 文件。 |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | 关闭 facade。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放 facade。 |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | 删除带有 trailer 的旧 xref，并创建一个新的带有 trailer 的 xref。 |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | 恢复文档。使用属性进行自定义。 |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | 将结果 PDF 保存到流中。 |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | 将结果 PDF 保存到文件中。 |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | 删除最后的 %%EOF 之后的数据。 |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | 删除 %PDF 之前的数据。 |

### 另请参见

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


