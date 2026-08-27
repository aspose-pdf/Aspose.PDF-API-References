---
title: "IOpenAIClient.RunAndGetAssistantResponseAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IOpenAIClient 메서드. 지정된 threadId와 runCreateRequest로 어시스턴트를 실행하고 비동기적으로 어시스턴트 응답을 가져옵니다"
type: docs
weight: 410
url: /ko/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/
---
## IOpenAIClient.RunAndGetAssistantResponseAsync method

지정된 threadId와 runCreateRequest를 사용하여 어시스턴트를 실행하고, 비동기적으로 어시스턴트 응답을 가져옵니다.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 스레드의 ID. |
| runCreateRequest | RunCreateRequest | 실행 생성 요청. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항). |

### 반환 값

어시스턴트 응답 문자열을 포함하는 비동기 작업을 나타내는 작업입니다.

### 또 보기

* class [RunCreateRequest](../../runcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


