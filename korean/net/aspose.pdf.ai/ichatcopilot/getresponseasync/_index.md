---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IChatCopilot 메서드. 주어진 메시지에 대한 응답을 비동기적으로 가져옵니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

주어진 메시지에 대한 응답을 비동기적으로 가져옵니다.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | 응답을 요청하는 입력 메시지입니다. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항)입니다. |

### Return Value

응답 문자열을 포함하는 비동기 작업을 나타내는 작업입니다.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

주어진 메시지 목록에 대한 응답을 비동기적으로 가져옵니다.

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | 응답을 요청하는 입력 메시지 목록입니다. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항)입니다. |

### Return Value

응답 문자열을 포함하는 비동기 작업을 나타내는 작업입니다.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)