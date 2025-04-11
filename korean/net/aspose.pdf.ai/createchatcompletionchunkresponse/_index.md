---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateChatCompletionChunkResponse 클래스. 제공된 입력을 기반으로 모델에 의해 반환된 채팅 완료 응답의 스트리밍 청크를 나타냅니다.
type: docs
weight: 250
url: /ko/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse 클래스

제공된 입력을 기반으로 모델에 의해 반환된 채팅 완료 응답의 스트리밍 청크를 나타냅니다.

```csharp
public class CreateChatCompletionChunkResponse
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | 채팅 완료 선택 목록을 가져오거나 설정합니다. n이 1보다 크면 여러 요소를 포함할 수 있습니다. stream_options: {"include_usage": true}를 설정하면 마지막 청크에 대해 비어 있을 수도 있습니다. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | 채팅 완료가 생성된 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. 각 청크는 동일한 타임스탬프를 가집니다. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | 채팅 완료에 대한 고유 식별자를 가져오거나 설정합니다. 각 청크는 동일한 ID를 가집니다. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | 완료를 생성할 모델을 가져오거나 설정합니다. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | 항상 chat.completion.chunk인 객체 유형을 가져오거나 설정합니다. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | 모델이 실행되는 백엔드 구성의 지문을 가져오거나 설정합니다. 결정론에 영향을 미칠 수 있는 백엔드 변경 사항이 언제 발생했는지 이해하기 위해 seed 요청 매개변수와 함께 사용할 수 있습니다. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | 요청에서 stream_options: {"include_usage": true}를 설정할 때만 존재하는 선택적 필드를 가져오거나 설정합니다. 존재할 경우, 마지막 청크를 제외하고는 전체 요청에 대한 토큰 사용 통계가 포함된 null 값을 가집니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)