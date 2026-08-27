---
title: "枚举 HeadingRecognitionStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.PdfToMarkdown.HeadingRecognitionStrategy 枚举。表示标题识别策略的类型。"
type: docs
weight: 8380
url: /zh/net/aspose.pdf.pdftomarkdown/headingrecognitionstrategy/
---
## HeadingRecognitionStrategy enumeration

表示标题识别策略的类型。

```csharp
public enum HeadingRecognitionStrategy
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Outlines | `0` | 通过大纲方式表示标题识别策略。 |
| Heuristic | `1` | 通过启发式规则和字体大小统计方式表示标题识别策略。 |
| Auto | `2` | 提供自动的标题识别策略选择。这是默认选项。如果文档包含书签，则选择 Outlines 策略，否则选择 Heuristic 策略。 |
| None | `3` | 不识别标题。此选项在格式复杂的文档中可能有用。 |

### 另请参见

* namespace [Aspose.Pdf.PdfToMarkdown](../../aspose.pdf.pdftomarkdown/)
* assembly [Aspose.PDF](../../)


