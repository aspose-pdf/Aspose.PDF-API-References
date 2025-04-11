---
title: Enum HeadingRecognitionStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfToMarkdown.HeadingRecognitionStrategy 枚举。表示头部识别策略的类型
type: docs
weight: 8380
url: /zh/net/aspose.pdf.pdftomarkdown/headingrecognitionstrategy/
---
## HeadingRecognitionStrategy 枚举

表示头部识别策略的类型。

```csharp
public enum HeadingRecognitionStrategy
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Outlines | `0` | 通过轮廓表示头部识别策略。 |
| Heuristic | `1` | 通过启发式规则和字体大小统计表示头部识别策略。 |
| Auto | `2` | 提供自动头部识别策略选择。这是默认选项。如果文档包含书签，将选择轮廓策略，否则选择启发式。 |
| None | `3` | 不识别头部。此选项在复杂格式的文档中可能很有用。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.PdfToMarkdown](../../aspose.pdf.pdftomarkdown/)
* 程序集 [Aspose.PDF](../../)