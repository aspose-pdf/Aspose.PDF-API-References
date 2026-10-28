---
title: "IChatCopilot.SaveResponseAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IChatCopilot 메서드. 주어진 메시지에 대한 응답을 PDF 파일에 비동기적으로 저장합니다."
type: docs
weight: 40
url: /ko/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

주어진 메시지에 대한 응답을 PDF 파일에 비동기적으로 저장합니다.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | String | 응답이 저장되는 입력 메시지. |
| outputFileName | String | 응답을 저장할 출력 PDF 파일의 이름. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항). |

### 반환 값

비동기 작업을 나타내는 Task.

### 또 보기

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

주어진 메시지에 대한 응답을 지정된 형식의 파일에 비동기적으로 저장합니다.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | String | 응답이 저장되는 입력 메시지. |
| outputFileName | String | 응답을 저장할 출력 파일의 이름. |
| saveFormat | SaveFormat | 응답을 저장할 형식입니다 (지정하지 않으면 PDF). |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항). |

### 반환 값

비동기 작업을 나타내는 Task.

### 또 보기

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

주어진 메시지 목록에 대한 응답을 PDF 파일에 비동기적으로 저장합니다.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| messages | List`1 | 응답이 저장되는 입력 메시지 목록입니다. |
| outputFileName | String | 응답을 저장할 출력 PDF 파일의 이름입니다. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항). |

### 반환 값

비동기 작업을 나타내는 Task.

### 또 보기

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

주어진 메시지 목록에 대한 응답을 지정된 형식의 파일에 비동기적으로 저장합니다.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| messages | List`1 | 응답이 저장되는 입력 메시지 목록입니다. |
| outputFileName | String | 응답을 저장할 출력 파일의 이름입니다. |
| saveFormat | SaveFormat | 응답을 저장할 형식입니다 (지정하지 않으면 PDF). |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항). |

### 반환 값

비동기 작업을 나타내는 Task.

### 또 보기

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


