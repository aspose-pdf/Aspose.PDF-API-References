---
title: "类 PdfAOptionsBase"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.PdfAOptionsBase 类。表示 PdfAConverter 插件选项的基类。此类提供用于配置 PDF/A 转换和验证过程的属性和方法。"
type: docs
weight: 9160
url: /zh/net/aspose.pdf.plugins/pdfaoptionsbase/
---
## PdfAOptionsBase class

表示 [`PdfAConverter`](../pdfaconverter/) 插件选项的基类。此类提供用于配置 PDF/A 转换和验证过程的属性和方法。

```csharp
public abstract class PdfAOptionsBase : IPluginOptions
```

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
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | 获取或设置用于验证或转换的 PDF/A 标准版本。 |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | 获取或设置在 PDF 文档中处理私有使用区（PUA）符号的策略。 |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | 获取或设置在转换带软掩码的图像时所采取的操作。 |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | 获取或设置转换为 PDF/A 格式时对符号字体进行编码的策略。 |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | 获取或设置在 PDF/A 转换过程中处理 ToUnicode CMap 表且未链接到 Unicode 符号的规则。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | 向集合中添加新的数据源。 |

### 另请参见

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


