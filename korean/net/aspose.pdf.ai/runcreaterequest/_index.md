---
title: "클래스 RunCreateRequest"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.RunCreateRequest 클래스. 실행을 생성하기 위한 요청을 나타냅니다."
type: docs
weight: 1060
url: /ko/net/aspose.pdf.ai/runcreaterequest/
---
## RunCreateRequest class

런을 생성하기 위한 요청을 나타냅니다.

```csharp
public class RunCreateRequest
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RunCreateRequest](runcreaterequest/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AdditionalInstructions](../../aspose.pdf.ai/runcreaterequest/additionalinstructions/) { get; set; } | 추가 지시사항을 가져오거나 설정합니다. 실행을 위한 지시사항 끝에 추가 지시사항을 추가합니다. 이는 다른 지시사항을 덮어쓰지 않고 실행별로 동작을 수정하는 데 유용합니다. |
| [AdditionalMessages](../../aspose.pdf.ai/runcreaterequest/additionalmessages/) { get; set; } | 실행을 생성하기 전에 스레드에 추가 메시지를 가져오거나 설정합니다. |
| [AssistantId](../../aspose.pdf.ai/runcreaterequest/assistantid/) { get; set; } | 이 런을 실행하는 데 사용할 어시스턴트의 ID를 가져오거나 설정합니다. |
| [Instructions](../../aspose.pdf.ai/runcreaterequest/instructions/) { get; set; } | 어시스턴트의 지시를 재정의하는 지시를 가져오거나 설정합니다. 이는 런별로 동작을 수정하는 데 유용합니다. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runcreaterequest/maxcompletiontokens/) { get; set; } | 실행 중에 사용할 수 있는 최대 완료 토큰 수를 가져오거나 설정합니다. 실행은 여러 턴에 걸쳐 지정된 완료 토큰 수만 사용하도록 최선을 다합니다. 실행이 지정된 완료 토큰 수를 초과하면 상태가 incomplete(불완전)으로 종료됩니다. 자세한 내용은 incomplete_details를 참조하십시오. |
| [MaxPromptTokens](../../aspose.pdf.ai/runcreaterequest/maxprompttokens/) { get; set; } | 실행 중에 사용할 수 있는 최대 프롬프트 토큰 수를 가져오거나 설정합니다. 실행은 여러 턴에 걸쳐 지정된 프롬프트 토큰 수만 사용하도록 최선을 다합니다. 실행이 지정된 프롬프트 토큰 수를 초과하면 상태가 incomplete(불완전)으로 종료됩니다. 자세한 내용은 incomplete_details를 참조하십시오. |
| [Metadata](../../aspose.pdf.ai/runcreaterequest/metadata/) { get; set; } | 객체에 첨부할 수 있는 16개의 키-값 쌍을 가져오거나 설정합니다. 이는 객체에 대한 추가 정보를 구조화된 형식으로 저장하는 데 유용합니다. 키는 최대 64자, 값은 최대 512자까지 가능합니다. |
| [Model](../../aspose.pdf.ai/runcreaterequest/model/) { get; set; } | 이 실행을 수행하는 데 사용할 모델의 ID를 가져오거나 설정합니다. 여기에서 값을 제공하면 어시스턴트에 연결된 모델을 재정의합니다. 제공되지 않으면 어시스턴트에 연결된 모델이 사용됩니다. |
| [ResponseFormat](../../aspose.pdf.ai/runcreaterequest/responseformat/) { get; set; } | 응답 형식을 가져오거나 설정합니다. 모델이 출력해야 하는 형식을 지정합니다. GPT-4o, GPT-4 Turbo 및 gpt-3.5-turbo-1106 이후의 모든 GPT-3.5 Turbo 모델과 호환됩니다. { "type": "json_object" } 로 설정하면 JSON 모드가 활성화되어 모델이 생성하는 메시지가 유효한 JSON임을 보장합니다. 중요: JSON 모드를 사용할 때는 시스템 메시지나 사용자 메시지를 통해 모델에게 직접 JSON을 생성하도록 지시해야 합니다. 이를 수행하지 않으면 모델이 토큰 제한에 도달할 때까지 공백 스트림을 무한히 생성할 수 있어 요청이 오래 실행되고 마치 "멈춘" 것처럼 보일 수 있습니다. 또한 finish_reason="length"인 경우 메시지 내용이 부분적으로 잘릴 수 있는데, 이는 생성이 max_tokens를 초과했거나 대화가 최대 컨텍스트 길이를 초과했음을 나타냅니다. |
| [Stream](../../aspose.pdf.ai/runcreaterequest/stream/) { get; set; } | 스트리밍 사용 여부를 가져오거나 설정합니다. true인 경우 실행 중에 발생하는 이벤트 스트림을 서버 전송 이벤트로 반환하며, 실행이 terminal 상태에 들어가면 data: [DONE] 메시지와 함께 종료됩니다. |
| [Temperature](../../aspose.pdf.ai/runcreaterequest/temperature/) { get; set; } | 0에서 2 사이의 샘플링 온도를 가져오거나 설정합니다. 0.8과 같은 높은 값은 출력을 더 무작위로 만들고, 0.2와 같은 낮은 값은 더 집중되고 결정적으로 만듭니다. |
| [ToolChoice](../../aspose.pdf.ai/runcreaterequest/toolchoice/) { get; set; } | 모델이 호출하는 도구(있는 경우)를 가져오거나 설정합니다. none은 모델이 도구를 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 기본값이며 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것을 선택할 수 있음을 의미합니다. required는 모델이 사용자에게 응답하기 전에 하나 이상의 도구를 반드시 호출해야 함을 의미합니다. {\"type\": \"file_search\"} 또는 {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}}와 같이 특정 도구를 지정하면 모델이 해당 도구를 호출하도록 강제합니다. |
| [Tools](../../aspose.pdf.ai/runcreaterequest/tools/) { get; set; } | 이 실행에 대해 어시스턴트가 사용할 수 있는 도구를 재정의하는 도구를 가져오거나 설정합니다. 이는 실행별로 동작을 수정하는 데 유용합니다. |
| [TopP](../../aspose.pdf.ai/runcreaterequest/topp/) { get; set; } | 온도 샘플링의 대안인 핵심 샘플링을 가져오거나 설정합니다. 모델은 top_p 확률 질량을 가진 토큰 결과를 고려합니다. 따라서 0.1은 상위 10% 확률 질량을 가진 토큰만 고려한다는 의미입니다. 일반적으로 이 값이나 온도 중 하나만 조정하고 둘 다 조정하지 않는 것을 권장합니다. |
| [TruncationStrategy](../../aspose.pdf.ai/runcreaterequest/truncationstrategy/) { get; set; } | 잘라내기 전략을 가져오거나 설정합니다. 실행 전에 스레드가 어떻게 잘라내어질지를 제어합니다. 이를 사용하여 실행의 초기 컨텍스트 윈도우를 제어할 수 있습니다. |

### 또 보기

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


