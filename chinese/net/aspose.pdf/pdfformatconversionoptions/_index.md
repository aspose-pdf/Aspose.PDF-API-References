---
title: "类 PdfFormatConversionOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.PdfFormatConversionOptions 类。表示用于转换 PDF 文档的一组选项。"
type: docs
weight: 8520
url: /zh/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

表示用于转换 PDF 文档的一组选项。

```csharp
public class PdfFormatConversionOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | 构造函数 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | 构造函数 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | 构造函数 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | 构造函数 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | 构造函数 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | 构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | 获取具有默认参数的 PdfFormatConversionOptions 对象 |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | 此标志控制转换后文档中的文本对齐。默认情况下，文档转换不会影响文本对齐，文本保持原样。但在某些情况下，字体替换会导致转换后文档出现文本重叠或多余空格。设置此标志后，将执行特殊的对齐操作。仅应对存在文本重叠或多余空格问题的文档设置此标志，因为使用此标志会降低性能，并且在某些情况下可能会损坏文本内容。 |
| [AutoTaggingSettings](../../aspose.pdf/pdfformatconversionoptions/autotaggingsettings/) { get; set; } | 获取或设置 PDF 格式转换期间的自动标记设置。 |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | 对具有软遮罩的图像的操作。 |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | 对无法转换的对象的操作。 |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | 用于排除多余字体并减小文档文件大小的策略。仅当标志 [`OptimizeFileSize`](./optimizefilesize/) 设置为 true 时此参数才有意义。默认使用 SubsetFonts 和 RemoveDuplicatedFonts 组合策略。 |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | 当无法将某些字体嵌入 PDF 文档时的选项。 |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | PDF 格式。 |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | 获取或设置 icc 配置文件的文件名。如果为 null，则使用默认的 icc 配置文件。 |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | 获取/设置在异步模式下图像流的运行。 |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | 是否启用了低内存转换模式 |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | 获取或设置在转换为 PDF 2.0 时是否将数据从 Info 传递到 Metadata。默认 true。 |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | 用于存储注释的文件路径。 |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | 用于存储注释的流。 |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | 保存用于控制 PDF/A 转换过程的标志，以应对源文档不符合 PDF/A 规范的情况。 |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | 此属性为输出属性。它保存上一次 PDF/A 转换时未在计算机上找到的所有字体（字体名称）。 |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | 获取或设置一个标志，用于启用/禁用特殊转换模式以获得文件大小更小的 PDF/A 文档。当前此标志影响 PDF 文档中使用的字体优化，未来可能还会用于开启对其他数据结构（如图形）的优化。该标志与模式的组合可以显著减小文件大小，但同时也可能显著降低转换性能。 |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | 获取或设置 PDF 格式转换的 [`OutputIntent`](../outputintent/)。 |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | 处理 Unicode 私用区 (PUA) 符号的策略。 |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | 当符号 TrueType 字体拥有多个编码子表时，复制符号字体编码数据的策略。 |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | 对图像遮罩对象的操作 |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | 解决 Unicode 映射问题的规则。可以为 null。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | 文本对齐的策略。仅当标志 [`AlignText`](./aligntext/) 设置为 true 时此参数才有意义。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


