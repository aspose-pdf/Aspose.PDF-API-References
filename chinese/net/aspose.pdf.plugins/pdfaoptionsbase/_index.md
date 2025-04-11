---
title: Class PdfAOptionsBase
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAOptionsBase 类。表示 PdfAConverter 插件选项的基类。此类提供用于配置 PDF/A 转换和验证过程的属性和方法。
type: docs
weight: 9010
url: /zh/net/aspose.pdf.plugins/pdfaoptionsbase/
---
## PdfAOptionsBase 类

表示 [`PdfAConverter`](../pdfaconverter/) 插件选项的基类。此类提供用于配置 PDF/A 转换和验证过程的属性和方法。

```csharp
public abstract class PdfAOptionsBase : IPluginOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | 获取或设置一个值，指示在 PDF/A 转换过程中是否需要额外的手段来保持文本对齐。 |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | 获取或设置无法转换的对象应采取的操作。 |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | 获取或设置在 PDF/A 转换过程中移除字体以最小化输出文件大小的策略。 |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | 获取无法嵌入到文档中的字体的处理选项。 |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | 获取或设置用于 PDF/A 转换的 ICC（国际色彩联盟）配置文件的文件名，以替代默认配置文件。 |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | 获取数据源集合 |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | 获取或设置一个值，指示在 PDF/A 转换过程中是否启用低内存模式。 |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | 获取或设置日志输出的数据源。 |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | 获取控制 PDF/A 转换的标志，用于源 PDF 文档不符合 PDF 规范的情况。 |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | 获取或设置一个值，指示是否在 PDF/A 转换过程中尝试减少文件大小。 |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | 获取或设置用于验证或转换的 PDF/A 标准版本。 |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | 获取或设置在 PDF 文档中处理私人使用区（PUA）符号的策略。 |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | 获取或设置在转换带有软遮罩的图像时应采取的操作。 |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | 获取或设置在转换为 PDF/A 格式时对符号字体进行编码的策略。 |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | 获取或设置在 PDF/A 转换过程中处理 ToUnicode CMap 表和未链接到 Unicode 符号的规则。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | 向集合中添加新的数据源 |

### 另请参阅

* 接口 [IPluginOptions](../ipluginoptions/)
* 命名空间 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../)