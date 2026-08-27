---
title: "클래스 CreateChatCompletionChunkResponse"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.CreateChatCompletionChunkResponse 클래스. 제공된 입력을 기반으로 모델이 반환한 채팅 완성 응답의 스트리밍 청크를 나타냅니다."
type: docs
weight: 260
url: /ko/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse class

제공된 입력을 기반으로 모델이 반환한 채팅 완성 응답의 스트리밍 청크를 나타냅니다.

```csharp
public class CreateChatCompletionChunkResponse
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | 채팅 완성 선택 항목 목록을 가져오거나 설정합니다. n이 1보다 크면 하나 이상의 요소를 포함할 수 있습니다. stream_options: {"include_usage": true}를 설정한 경우 마지막 청크는 비어 있을 수도 있습니다. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | 채팅 완성이 생성된 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. 각 청크는 동일한 타임스탬프를 가집니다. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | 채팅 완성에 대한 고유 식별자를 가져오거나 설정합니다. 각 청크는 동일한 ID를 가집니다. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | 완성을 생성할 모델을 가져오거나 설정합니다. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | 객체 유형을 가져오거나 설정합니다. 이 값은 항상 chat.completion.chunk입니다. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | 모델이 실행되는 백엔드 구성을 나타내는 지문을 가져오거나 설정합니다. 이는 시드 요청 매개변수와 함께 사용하여 결정성에 영향을 줄 수 있는 백엔드 변경이 언제 발생했는지 이해하는 데 활용될 수 있습니다. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | 요청에서 stream_options: {"include_usage": true}를 설정한 경우에만 존재하는 선택적 필드를 가져오거나 설정합니다. 존재하는 경우 마지막 청크를 제외하고는 null 값을 포함하며, 마지막 청크는 전체 요청에 대한 토큰 사용 통계를 포함합니다. |

### 또 보기

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


