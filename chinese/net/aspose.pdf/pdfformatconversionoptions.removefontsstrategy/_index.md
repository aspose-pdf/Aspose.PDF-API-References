---
title: Enum PdfFormatConversionOptions.RemoveFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy enum。某些文档在转换为 PDF/A 格式后文件大小较大。为了减小这些文档的文件大小，有必要定义一种移除字体的策略。此枚举声明了可用于优化字体使用的策略。只有在设置了标志 [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) 时，此枚举中的每个策略才有意义。
type: docs
weight: 8400
url: /zh/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy 枚举

某些文档在转换为 PDF/A 格式后文件大小较大。为了减小这些文档的文件大小，有必要定义一种移除字体的策略。此枚举声明了可用于优化字体使用的策略。只有在设置了标志 [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) 时，此枚举中的每个策略才有意义。

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | 该策略会移除文档中所有重复的字体。如果文档中包含一组重复字体，则该组中仅将一种字体嵌入文档。文档中其余的字体将被移除，每个被移除的字体都将由已嵌入的对应字体替代。 |
| RemoveSimilarFontsWithDifferentWidths | `1` | 该策略类似于 RemoveDuplicatedFonts，但它移除的不是完全重复的字体，而是彼此相似且仅在参数 "Widths" 上存在差异的字体。该参数包含指定字体中某些字符的宽度集合。此 "Widths" 集合中的每个宽度值并非字符（glyph）的实际宽度，字符的实际宽度已在字体的二进制数据中定义。"Widths" 集合中的宽度值表示字符的视觉宽度——PDF 查看器软件在显示字符时应使用此宽度，而非字体中定义的实际宽度。更准确地说，规范指出：Acrobat 5.0 及以后版本的查看器会使用存储在字体字典中的字形宽度来覆盖字体程序本身中的字形宽度，从而提高文档显示和打印的一致性。该策略比 RemoveDuplicatedFonts 更有效，但在某些情况下使用该策略理论上可能会损害转换后文档的视觉效果。由于同一字符的声明宽度可能不一致，在字体替换后该字符的宽度会变为新的值——当被移除的字体在文档中被已嵌入的字体替换时，如果字符的视觉宽度发生变化，则显示会不正确，这种差异可能会导致诸如文本重叠等视觉缺陷。但所描述的视觉缺陷是极为罕见的情况，该策略能够更有效地减小文档大小。 |
| SubsetFonts | `2` | 这是减少文档大小最有效的策略。它获取完全嵌入的字体集合，并将其精简为仅包含实际使用的子集。建议将该策略与 RemoveDuplicatedFonts 或 RemoveSimilarFontsWithDifferentWidths 联合使用，以实现多重压缩效果。同时使用所有三个策略没有意义，在这种情况下将不会使用 RemoveSimilarFontsWithDifferentWidths。 |

### 另请参阅

* 类 [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)