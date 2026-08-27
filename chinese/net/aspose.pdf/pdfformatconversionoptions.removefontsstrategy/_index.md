---
title: "枚举 PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy 枚举。一些文档在转换为 PDF/A 格式后体积较大。为了减小这些文档的文件大小，需要定义字体移除策略。此枚举声明了可用于优化字体使用的策略。只有在设置了 OptimizeFileSize 标志时，此枚举中的每个策略才有意义。"
type: docs
weight: 8540
url: /zh/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy enumeration

一些文档在转换为 PDF/A 格式后体积较大。为了减小这些文档的文件大小，需要定义字体移除策略。此枚举声明了可用于优化字体使用的策略。只有在设置了 [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) 标志时，此枚举中的每个策略才有意义。

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | 此策略会移除文档中所有重复的字体。如果文档包含一组重复的字体，则仅在文档中嵌入该组中的一个字体。该组的其他字体将从文档中移除，且每个被移除的字体都会被已嵌入的同类字体替代。 |
| RemoveSimilarFontsWithDifferentWidths | `1` | 此策略类似于 RemoveDuplicatedFonts，但它移除的不是完全重复的字体，而是那些仅在参数 \"Widths\" 上不同、相互之间相似的字体。该参数包含针对字体中指定字符的一组宽度值。此 \"Widths\" 集合中的每个宽度值并非字符（字形）的真实宽度，字符的真实宽度已在字体的二进制数据中定义。\"Widths\" 中的宽度值表示该字符的可视宽度——即 PDF 查看器在显示字符时必须使用的宽度，而非字体中定义的真实宽度。更准确的说明是：Acrobat 5.0 及更高版本的查看器使用存储在字体字典中的字形宽度来覆盖字体程序本身的宽度，从而提升文档的显示和打印一致性。该策略比 RemoveDuplicatedFonts 更有效，但在某些情况下使用此策略可能会理论上损害转换后文档的视觉呈现。出现此缺陷的原因是，同一字符的声明宽度可能不同，在这种情况下，字符的宽度将在字体替换后被改为新的宽度——被移除的字体将在文档中被已嵌入的字体替代。如果字符的可视宽度被更改，显示将不正确，这种差异可能导致视觉缺陷，如文字重叠或其他问题。但上述视觉缺陷极为罕见，此策略能够更有效地减小文档大小。 |
| SubsetFonts | `2` | 这是最有效的减小文档体积的策略。它将完整嵌入的字体集合裁剪为仅使用的子集。建议将此策略与 RemoveDuplicatedFonts 或 RemoveSimilarFontsWithDifferentWidths 结合使用，以实现对文件大小的多重压缩效果。同时使用这三种策略没有意义，在这种情况下将不会使用 RemoveSimilarFontsWithDifferentWidths 策略。 |

### 另请参见

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


