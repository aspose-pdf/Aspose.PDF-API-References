---
title: "类 PdfAConvertOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.PdfAConvertOptions 类。表示使用 PdfAConverter 插件将 PDF 文档转换为 PDF/A 格式的选项。"
type: docs
weight: 9140
url: /zh/net/aspose.pdf.plugins/pdfaconvertoptions/
---
## PdfAConvertOptions class

表示使用 [`PdfAConverter`](../pdfaconverter/) 插件将 PDF 文档转换为 PDF/A 格式的选项。

```csharp
public sealed class PdfAConvertOptions : PdfAOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfAConvertOptions](pdfaconvertoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | 获取或设置一个值，指示在 PDF/A 转换过程中是否需要额外的手段来保持文本对齐。 |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | 获取或设置对无法转换的对象所采取的操作。 |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | 获取或设置在 PDF/A 转换过程中删除字体以最小化输出文件大小的策略。 |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | 获取处理无法嵌入 Document 的字体的选项。 |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | 获取或设置用于 PDF/A 转换的 ICC（International Color Consortium）配置文件的文件名，以替代默认配置文件。 |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | 获取数据源集合。 |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | 获取或设置一个值，指示在 PDF/A 转换过程中是否启用低内存模式。 |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | 获取或设置日志输出的数据源。 |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | 获取控制 PDF/A 转换的标志，以应对源 PDF Document 不符合 PDF 规范的情况。 |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | 获取或设置一个值，指示是否尝试在 PDF/A 转换过程中减小文件大小。 |
| [Outputs](../../aspose.pdf.plugins/pdfaconvertoptions/outputs/) { get; } | 获取已添加目标（文件或流数据源）的集合，用于保存操作结果。 |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | 获取或设置用于验证或转换的 PDF/A 标准版本。 |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | 获取或设置在 PDF 文档中处理私有使用区（PUA）符号的策略。 |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | 获取或设置在转换带软掩码的图像时所采取的操作。 |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | 获取或设置转换为 PDF/A 格式时对符号字体进行编码的策略。 |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | 获取或设置在 PDF/A 转换过程中处理 ToUnicode CMap 表且未链接到 Unicode 符号的规则。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | 向集合中添加新的数据源。 |
| [AddOutput](../../aspose.pdf.plugins/pdfaconvertoptions/addoutput/)(IDataSource) | 添加新的结果保存目标。 |

### 另请参见

* class [PdfAOptionsBase](../pdfaoptionsbase/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


