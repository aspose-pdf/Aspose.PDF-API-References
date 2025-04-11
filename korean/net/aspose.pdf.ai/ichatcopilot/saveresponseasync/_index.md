---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IChatCopilot 메서드. 주어진 메시지에 대한 응답을 PDF 파일로 비동기적으로 저장합니다.
type: docs
weight: 40
url: /ko/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

주어진 메시지에 대한 응답을 PDF 파일로 비동기적으로 저장합니다.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | 응답이 저장될 입력 메시지입니다. |
| outputFileName | String | 응답을 저장할 출력 PDF 파일의 이름입니다. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항)입니다. |

### Return Value

비동기 작업을 나타내는 작업입니다.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

주어진 메시지에 대한 응답을 지정된 형식의 파일로 비동기적으로 저장합니다.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | 응답이 저장될 입력 메시지입니다. |
| outputFileName | String | 응답을 저장할 출력 파일의 이름입니다. |
| saveFormat | SaveFormat | 응답을 저장할 형식(PDF가 지정되지 않은 경우)입니다. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항)입니다. |

### Return Value

비동기 작업을 나타내는 작업입니다.

### See Also

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

주어진 메시지 목록에 대한 응답을 PDF 파일로 비동기적으로 저장합니다.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | 응답이 저장될 입력 메시지 목록입니다. |
| outputFileName | String | 응답을 저장할 출력 PDF 파일의 이름입니다. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항)입니다. |

### Return Value

비동기 작업을 나타내는 작업입니다.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

주어진 메시지 목록에 대한 응답을 지정된 형식의 파일로 비동기적으로 저장합니다.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | 응답이 저장될 입력 메시지 목록입니다. |
| outputFileName | String | 응답을 저장할 출력 파일의 이름입니다. |
| saveFormat | SaveFormat | 응답을 저장할 형식(PDF가 지정되지 않은 경우)입니다. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항)입니다. |

### Return Value

비동기 작업을 나타내는 작업입니다.

### See Also

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)