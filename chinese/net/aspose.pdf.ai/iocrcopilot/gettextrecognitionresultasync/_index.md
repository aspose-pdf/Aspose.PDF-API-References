---
title: "IOcrCopilot.GetTextRecognitionResultAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOcrCopilot 方法。异步检索 PDF 文档和图像文件的文本识别结果。支持的图像类型有 PNG .png、JPEG .jpeg 和 .jpg、WEBP .webp、非动画 GIF .gif"
type: docs
weight: 10
url: /zh/net/aspose.pdf.ai/iocrcopilot/gettextrecognitionresultasync/
---
## IOcrCopilot.GetTextRecognitionResultAsync method

异步检索 PDF 文档和图像文件的文本识别结果。支持的图像类型：PNG（.png）、JPEG（.jpeg 和 .jpg）、WEBP（.webp）、非动画 GIF（.gif）。

```csharp
public Task<List<TextRecognitionResult>> GetTextRecognitionResultAsync(
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cancellationToken | Nullable`1 | 用于取消操作的可选取消令牌。 |

### 返回值

表示异步操作的任务。任务结果包含一个 [`TextRecognitionResult`](../../textrecognitionresult/) 列表。

### 另请参见

* class [TextRecognitionResult](../../textrecognitionresult/)
* interface [IOcrCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


