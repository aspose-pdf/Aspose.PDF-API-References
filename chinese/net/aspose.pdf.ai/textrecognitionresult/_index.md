---
title: "类 TextRecognitionResult"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.TextRecognitionResult 类。表示单个源 Document 的聚合 OCR 结果"
type: docs
weight: 1180
url: /zh/net/aspose.pdf.ai/textrecognitionresult/
---
## TextRecognitionResult class

表示单个源文档的聚合 OCR 结果。

```csharp
public class TextRecognitionResult
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextRecognitionResult](textrecognitionresult/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [OcrDetails](../../aspose.pdf.ai/textrecognitionresult/ocrdetails/) { get; set; } | 一个列表，包含文档中每个页的详细 OCR 结果。对于单图像文件，该列表通常只包含一个 OcrDetail 条目，PageNumber = 1。 |
| [OverallSuccess](../../aspose.pdf.ai/textrecognitionresult/overallsuccess/) { get; set; } | 指示 OCR 是否在此 Document 的所有页中成功。如果 OcrDetails 中的任何 OcrDetail 的 Success 为 false，则为 false。 |
| [SourceIdentifier](../../aspose.pdf.ai/textrecognitionresult/sourceidentifier/) { get; set; } | 源文件的标识符（例如，完整路径或唯一名称）。 |
| [SummaryErrorMessage](../../aspose.pdf.ai/textrecognitionresult/summaryerrormessage/) { get; set; } | 如果 OverallSuccess 为 false，则为合并的错误消息；如果任何页失败，则为摘要。如果 OverallSuccess 为 true，则为 Null。 |
| [TotalUsage](../../aspose.pdf.ai/textrecognitionresult/totalusage/) { get; set; } | 获取或设置处理此文档（所有页面）的总体使用统计信息。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


