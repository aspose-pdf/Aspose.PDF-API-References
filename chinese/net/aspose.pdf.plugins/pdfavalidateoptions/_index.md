---
title: Class PdfAValidateOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAValidateOptions class. 表示用于验证 PDF 文档的 PDF/A 合规性的选项，使用 PdfAConverter 插件
type: docs
weight: 9030
url: /zh/net/aspose.pdf.plugins/pdfavalidateoptions/
---
## PdfAValidateOptions class

表示用于验证 PDF 文档的 PDF/A 合规性的选项，使用 [`PdfAConverter`](../pdfaconverter/) 插件。

```csharp
public sealed class PdfAValidateOptions : PdfAOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfAValidateOptions](pdfavalidateoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | 获取或设置一个值，指示在 PDF/A 转换过程中是否需要额外的手段来保持文本对齐。 |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | 获取或设置无法转换的对象所采取的操作。 |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | 获取或设置在 PDF/A 转换过程中移除字体以最小化输出文件大小的策略。 |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | 获取处理无法嵌入文档的字体的选项。 |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | 获取或设置用于 PDF/A 转换的 ICC（国际色彩联盟）配置文件的文件名，以替代默认文件。 |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | 获取数据源集合 |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | 获取或设置一个值，指示在 PDF/A 转换过程中是否启用低内存模式。 |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | 获取或设置日志输出的数据源。 |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | 获取控制 PDF/A 转换的标志，以应对源 PDF 文档不符合 PDF 规范的情况。 |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | 获取或设置一个值，指示是否在 PDF/A 转换过程中尝试减少文件大小。 |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | 获取或设置用于验证或转换的 PDF/A 标准版本。 |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | 获取或设置在 PDF 文档中处理私人使用区（PUA）符号的策略。 |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | 获取或设置在转换带有软遮罩的图像时所采取的操作。 |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | 获取或设置在转换为 PDF/A 格式时对符号字体进行编码的策略。 |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | 获取或设置在 PDF/A 转换过程中处理 ToUnicode CMap 表和不链接到 Unicode 符号的规则。 |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | 将新的数据源添加到集合中 |

### See Also

* class [PdfAOptionsBase](../pdfaoptionsbase/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)