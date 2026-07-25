---
title: "PdfFormatConversionOptions.PuaProcessingStrategy"
linktitle: "PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Aspose.PDF for Java API 参考"
description: "某些 PDF 文档包含属于私有使用区 (PUA) 的特殊 Unicode 符号，详见 https://en.wikipedia.org/wiki/Private_Use_Areas 的描述。这些符号。"
type: docs
weight: 3750
url: /zh/java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy

```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends com.aspose.ms.System.Enum
```

某些 PDF 文档包含属于私用区 (PUA) 的特殊 Unicode 符号，详见 https://en.wikipedia.org/wiki/Private_Use_Areas。此类符号会导致 PDF/A 合规错误，例如 "Text is mapped to Unicode Private Use Area but no ActualText entry is present"。此枚举声明了可用于处理 PUA 符号的策略。

## 字段

| 字段 | 描述 |
| --- | --- |
| [None](#None) | 禁用 PUA 符号处理。此策略默认用于符合 Level B 标准的 PDF/A 文档。 |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | 此策略的运行速度比 'SurroundPuaTextWithEmptyActualText' 慢，但它可以消除无法被 SurroundPuaTextWithEmptyActualText 正确处理的文档中的 PUA 合规错误。PUA 符号会被替换为 'space' 符号或特殊的 Unicode（某些 PUA 符号有 Unicode 对应）。替换不是作用于文档的文本，而是作用于字体的内部数据 ToUnicode，因此不会影响符号的显示，但会影响符号在复制/粘贴操作系统缓冲区中的呈现。 |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | 插入带有 ActualText 条目的标记内容块，该条目包含空文本。此策略对没有标记内容块的文档效果良好。默认用于符合 Level A 标准的 PDF/A 文档。 |

### None {#None}
```
public static final int None
```

禁用 PUA 符号处理。此策略默认用于符合 Level B 标准的 PDF/A 文档。

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```

此策略的运行速度比 'SurroundPuaTextWithEmptyActualText' 慢，但它可以消除无法被 SurroundPuaTextWithEmptyActualText 正确处理的文档中的 PUA 合规错误。PUA 符号会被替换为 'space' 符号或特殊的 Unicode（某些 PUA 符号有 Unicode 对应）。替换不是作用于文档的文本，而是作用于字体的内部数据 ToUnicode，因此不会影响符号的显示，但会影响符号在复制/粘贴操作系统缓冲区中的呈现。

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```

插入带有 ActualText 条目的标记内容块，该条目包含空文本。此策略对没有标记内容块的文档效果良好。默认用于符合 Level A 标准的 PDF/A 文档。
