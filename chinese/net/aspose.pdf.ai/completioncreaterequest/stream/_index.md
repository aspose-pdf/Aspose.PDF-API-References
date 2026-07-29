---
title: "CompletionCreateRequest.Stream"
second_title: "Aspose.PDF for .NET API 参考"
description: "CompletionCreateRequest 属性。获取或设置是否使用流式传输。如果设置，部分消息增量将像 ChatGPT 那样发送。Token 将作为 dataonly 服务器发送事件在可用时发送，流以 data DONE 消息终止。"
type: docs
weight: 130
url: /zh/net/aspose.pdf.ai/completioncreaterequest/stream/
---
## CompletionCreateRequest.Stream property

获取或设置是否使用流式传输。如果设置，部分消息增量将被发送，类似于 ChatGPT。Token 将以仅数据的服务器发送事件形式在可用时发送，流将在 data: [DONE] 消息时终止。

```csharp
public bool? Stream { get; set; }
```

### 另请参见

* class [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


