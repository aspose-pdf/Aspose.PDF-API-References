---
title: "枚举 PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy 枚举。某些 PDF 文档包含属于私有使用区（PUA）的特殊 Unicode 符号，详见 https//en.wikipedia.org/wiki/Private_Use_Areas。此类符号会导致 PDF/A 合规错误，例如“文本映射到 Unicode 私有使用区但不存在 ActualText 条目”。此枚举声明了一组可用于处理 PUA 符号的策略。"
type: docs
weight: 8530
url: /zh/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy enumeration

某些 PDF 文档包含属于私有使用区（PUA）的特殊 Unicode 符号，详见 https://en.wikipedia.org/wiki/Private_Use_Areas。此类符号会导致 PDF/A 合规错误，例如\"Text is mapped to Unicode Private Use Area but no ActualText entry is present\"。此枚举声明了一组可用于处理 PUA 符号的策略。

```csharp
public enum PuaProcessingStrategy
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 禁用 PUA 符号处理。此策略是 PDF/A 文档（符合 Level B）默认使用的。 |
| SurroundPuaTextWithEmptyActualText | `1` | 插入带有 ActualText 条目的标记内容块，内容为空文本。此策略对没有标记内容块的文档效果良好。它是 PDF/A 文档（符合 Level A）默认使用的。 |
| SubstitutePuaSymbols | `2` | 此策略的速度慢于 'SurroundPuaTextWithEmptyActualText'，但它可以消除那些无法通过 SurroundPuaTextWithEmptyActualText 正确处理的文档中的 PUA 合规错误。PUA 符号会被替换为 'space' 符号或特殊的 Unicode（某些 PUA 符号有对应的 Unicode）。替换作用于字体的内部数据 ToUnicode，而不是文档的文本，因此不会影响符号的视觉显示，但会影响符号在复制/粘贴操作系统缓冲区中的呈现。 |

### 另请参见

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


