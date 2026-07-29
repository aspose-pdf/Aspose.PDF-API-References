---
title: "PdfFormatConversionOptions.RemoveFontsStrategy"
linktitle: "PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Aspose.PDF for Java API 参考"
description: "某些文档在转换为 PDF/A 格式后体积较大。为了减小这些文档的文件大小，需要定义一种字体移除策略。这是一个枚举。"
type: docs
weight: 3760
url: /zh/java/com.aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy

```
public static class PdfFormatConversionOptions.RemoveFontsStrategy extends com.aspose.ms.System.Enum
```

某些文档在转换为 PDF/A 格式后体积较大。为减小这些文档的文件大小，需要定义字体移除策略。此枚举声明了可用于优化字体使用的策略。此枚举中的每个策略仅在设置了标志 {@code OptimizeFileSize} 时才有意义。

## 字段

| 字段 | 描述 |
| --- | --- |
| [RemoveDuplicatedFonts](#RemoveDuplicatedFonts) | 此策略会移除文档中所有重复的字体。如果文档包含一组重复的字体，则仅在文档中嵌入该组中的一个字体。该组的其他字体将从文档中移除，每个被移除的字体都会被已嵌入的对应字体替代。 |
| [RemoveSimilarFontsWithDifferentWidths](#RemoveSimilarFontsWithDifferentWidths) | 此策略看起来类似 {@code RemoveDuplicatedFonts}，但它移除的不是完全重复的字体，而是相互之间仅在参数 "Widths" 上不同的相似字体。该参数包含指定字体符号的一组宽度。此 "Widths" 集合中的每个宽度值并非符号（字形）的真实宽度，真实宽度已在字体的二进制数据中定义。"Widths" 集合中的宽度值表示该符号的可视宽度——即 PDF 查看器在显示符号时应使用的宽度，而非字体中定义的真实宽度。更准确地说，规范指出：Acrobat 5.0 及更高版本的查看器使用字体字典中存储的字形宽度来覆盖字体程序本身的宽度，从而提升文档的显示和打印一致性。此策略比 {@code RemoveDuplicatedFonts} 更有效，但在某些情况下使用该策略可能会理论上损害转换后文档的视觉呈现。出现此缺陷的原因是声明的字体宽度在同一符号上可能不同，在这种情况下，符号的宽度将在字体替换后被改为新的宽度——被移除的字体将在文档中被已嵌入的字体替代。如果符号的可视宽度被改变，显示将不正确，这种差异可能导致视觉缺陷，如文字重叠或其他问题。但上述视觉缺陷极为罕见，此策略能够更有效地减小文档大小。 |
| [SubsetFonts](#SubsetFonts) | 这是最有效的减小文档大小的策略。它将完整嵌入的字体集合裁剪为仅使用的子集。建议将此策略与 {@code RemoveDuplicatedFonts} 或 {@code RemoveSimilarFontsWithDifferentWidths} 结合使用，以实现文件大小的多重压缩效果。同时使用这三种策略没有意义，在这种情况下不会使用 {@code RemoveSimilarFontsWithDifferentWidths} 策略。 |

### RemoveDuplicatedFonts {#RemoveDuplicatedFonts}
```
public static final byte RemoveDuplicatedFonts
```

此策略会移除文档中所有重复的字体。如果文档包含一组重复的字体，则仅在文档中嵌入该组中的一个字体。该组的其他字体将从文档中移除，每个被移除的字体都会被已嵌入的对应字体替代。

### RemoveSimilarFontsWithDifferentWidths {#RemoveSimilarFontsWithDifferentWidths}
```
public static final byte RemoveSimilarFontsWithDifferentWidths
```

此策略看起来类似 {@code RemoveDuplicatedFonts}，但它移除的不是完全重复的字体，而是相互之间仅在参数 "Widths" 上不同的相似字体。该参数包含指定字体符号的一组宽度。此 "Widths" 集合中的每个宽度值并非符号（字形）的真实宽度，真实宽度已在字体的二进制数据中定义。"Widths" 集合中的宽度值表示该符号的可视宽度——即 PDF 查看器在显示符号时应使用的宽度，而非字体中定义的真实宽度。更准确地说，规范指出：Acrobat 5.0 及更高版本的查看器使用字体字典中存储的字形宽度来覆盖字体程序本身的宽度，从而提升文档的显示和打印一致性。此策略比 {@code RemoveDuplicatedFonts} 更有效，但在某些情况下使用该策略可能会理论上损害转换后文档的视觉呈现。出现此缺陷的原因是声明的字体宽度在同一符号上可能不同，在这种情况下，符号的宽度将在字体替换后被改为新的宽度——被移除的字体将在文档中被已嵌入的字体替代。如果符号的可视宽度被改变，显示将不正确，这种差异可能导致视觉缺陷，如文字重叠或其他问题。但上述视觉缺陷极为罕见，此策略能够更有效地减小文档大小。

### SubsetFonts {#SubsetFonts}
```
public static final byte SubsetFonts
```

这是最有效的减小文档大小的策略。它将完整嵌入的字体集合裁剪为仅使用的子集。建议将此策略与 {@code RemoveDuplicatedFonts} 或 {@code RemoveSimilarFontsWithDifferentWidths} 结合使用，以实现文件大小的多重压缩效果。同时使用这三种策略没有意义，在这种情况下不会使用 {@code RemoveSimilarFontsWithDifferentWidths} 策略。
