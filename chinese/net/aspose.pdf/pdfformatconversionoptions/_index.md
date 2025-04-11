---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptions 类。表示用于转换 PDF 文档的一组选项
type: docs
weight: 8380
url: /zh/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

表示用于转换 PDF 文档的一组选项

```csharp
public class PdfFormatConversionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | 构造函数 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | 构造函数 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | 构造函数 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | 构造函数 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | 构造函数 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | 构造函数 |

## Properties

| Name | Description |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | 获取具有默认参数的 PdfFormatConversionOptions 对象 |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | 此标志控制转换文档中的文本对齐。默认情况下，文档转换不会影响文本对齐，并保持文本不变。但在某些情况下，字体替换会导致文本重叠或在转换文档中出现额外空格。当设置此标志时，将执行特殊的对齐操作。此标志仅应在文档存在重叠文本或额外文本空格问题时设置，因为使用此标志会降低性能，并且在某些情况下可能会损坏文本内容。 |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | 处理带有软遮罩的图像的操作。 |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | 无法转换的对象的操作 |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | 排除多余字体并减少文档文件大小的策略。此参数仅在标志 [`OptimizeFileSize`](./optimizefilesize/) 设置为 true 时才有意义。默认情况下使用 SubsetFonts 和 RemoveDuplicatedFonts 的组合策略。 |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | 在无法将某些字体嵌入 PDF 文档时的选项。 |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | PDF 格式。 |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | 获取或设置 ICC 配置文件名称的文件名。如果为 null，则使用默认 ICC 配置文件。 |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | 获取/设置图像流的异步模式运行。 |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | 是否启用低内存转换模式 |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | 获取或设置在转换为 PDF 2.0 时是否将数据从 Info 传递到 Metadata。默认值为 true。 |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | 存储注释的文件路径。 |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | 存储注释的流。 |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | 持有标志以控制 PDF/A 转换过程，以防源文档不符合 PDF/A 规范。 |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | 此属性是外部属性。它保存在最后一次 PDF/A 转换中未在计算机上找到的所有字体（字体名称）。 |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | 获取或设置一个标志，该标志启用/禁用特殊转换模式，以获取具有减小文件大小的 PDF/A 文档。现在，此标志影响 PDF 文档中使用的字体的优化，未来可能还会用于切换其他数据结构（如图形）的优化。设置此标志和模式可能会显著减少文件大小，但同时可能会显著降低转换性能。 |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | 获取或设置 PDF 格式转换的 [`OutputIntent`](../outputintent/)。 |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | 处理来自 Unicode 私有使用区 (PUA) 符号的策略。 |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | 如果符号 TrueType 字体具有多个编码子表，则复制符号字体的编码数据的策略。 |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | 图像遮罩对象的操作 |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | 解决 Unicode 映射问题的规则。可以为 null。 |

## Fields

| Name | Description |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | 对齐文本的策略。此参数仅在标志 [`AlignText`](./aligntext/) 设置为 true 时才有意义。 |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)