---
title: "IChatCopilot.GetResponseAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IChatCopilot 메서드. 주어진 메시지에 대한 응답을 비동기적으로 가져옵니다."
type: docs
weight: 20
url: /ko/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

주어진 메시지에 대한 응답을 비동기적으로 가져옵니다.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | String | 응답이 요청된 입력 메시지. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항). |

### 반환 값

응답 문자열을 포함하는 비동기 작업을 나타내는 Task.

### 또 보기

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

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| messages | List`1 | 응답이 요청된 입력 메시지들의 목록. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항). |

### 반환 값

응답 문자열을 포함하는 비동기 작업을 나타내는 Task.

### 또 보기

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


