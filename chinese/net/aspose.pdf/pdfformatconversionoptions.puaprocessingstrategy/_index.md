---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy 枚举。一些 PDF 文档具有特殊的 Unicode 符号，这些符号属于私人使用区 PUA，详见 https//en.wikipedia.org/wiki/Private_Use_Areas。 这些符号会导致 PDF/A 合规错误，例如“文本映射到 Unicode 私人使用区，但没有 ActualText 条目”。此枚举声明了可以用于处理 PUA 符号的策略。
type: docs
weight: 8390
url: /zh/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy 枚举

一些 PDF 文档具有特殊的 Unicode 符号，这些符号属于私人使用区 (PUA)，详见 https://en.wikipedia.org/wiki/Private_Use_Areas。 这些符号会导致 PDF/A 合规错误，例如“文本映射到 Unicode 私人使用区，但没有 ActualText 条目”。此枚举声明了可以用于处理 PUA 符号的策略。

```csharp
public enum PuaProcessingStrategy
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 禁用 PUA 符号处理。此策略默认用于符合 B 级的 PDF/A 文档。 |
| SurroundPuaTextWithEmptyActualText | `1` | 插入带有 ActualText 条目的标记内容块，该条目包含空文本。此策略对没有标记内容块的文档效果良好。默认用于符合 A 级的 PDF/A 文档。 |
| SubstitutePuaSymbols | `2` | 此策略的工作速度比“SurroundPuaTextWithEmptyActualText”慢，但它可以消除无法通过 SurroundPuaTextWithEmptyActualText 正确处理的文档的 PUA 合规错误。PUA 符号被替换为符号“空格”或特殊 Unicode（某些 PUA 符号具有 Unicode 类似物）。替换应用于文档的文本，而不是字体的内部数据 ToUnicode，因此它不会影响符号的视觉效果，但会影响符号在复制/粘贴操作系统缓冲区中的呈现。 |

### 另请参阅

* 类 [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)