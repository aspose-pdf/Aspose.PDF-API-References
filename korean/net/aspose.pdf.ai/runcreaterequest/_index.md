---
title: Class RunCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunCreateRequest 클래스. 실행을 생성하기 위한 요청을 나타냅니다.
type: docs
weight: 980
url: /ko/net/aspose.pdf.ai/runcreaterequest/
---
## RunCreateRequest 클래스

실행을 생성하기 위한 요청을 나타냅니다.

```csharp
public class RunCreateRequest
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RunCreateRequest](runcreaterequest/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AdditionalInstructions](../../aspose.pdf.ai/runcreaterequest/additionalinstructions/) { get; set; } | 추가 지침을 가져오거나 설정합니다. 실행을 위한 지침 끝에 추가 지침을 추가합니다. 이는 다른 지침을 무시하지 않고 실행별로 동작을 수정하는 데 유용합니다. |
| [AdditionalMessages](../../aspose.pdf.ai/runcreaterequest/additionalmessages/) { get; set; } | 실행을 생성하기 전에 스레드에 추가 메시지를 가져오거나 설정합니다. |
| [AssistantId](../../aspose.pdf.ai/runcreaterequest/assistantid/) { get; set; } | 이 실행을 실행하는 데 사용할 보조의 ID를 가져오거나 설정합니다. |
| [Instructions](../../aspose.pdf.ai/runcreaterequest/instructions/) { get; set; } | 보조의 지침을 무시하는 지침을 가져오거나 설정합니다. 이는 실행별로 동작을 수정하는 데 유용합니다. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runcreaterequest/maxcompletiontokens/) { get; set; } | 실행 중 사용할 수 있는 최대 완료 토큰 수를 가져오거나 설정합니다. 실행은 여러 턴에 걸쳐 지정된 수의 완료 토큰만 사용하기 위해 최선을 다합니다. 실행이 지정된 완료 토큰 수를 초과하면 실행은 상태가 불완전으로 종료됩니다. 자세한 내용은 incomplete_details를 참조하십시오. |
| [MaxPromptTokens](../../aspose.pdf.ai/runcreaterequest/maxprompttokens/) { get; set; } | 실행 중 사용할 수 있는 최대 프롬프트 토큰 수를 가져오거나 설정합니다. 실행은 여러 턴에 걸쳐 지정된 수의 프롬프트 토큰만 사용하기 위해 최선을 다합니다. 실행이 지정된 프롬프트 토큰 수를 초과하면 실행은 상태가 불완전으로 종료됩니다. 자세한 내용은 incomplete_details를 참조하십시오. |
| [Metadata](../../aspose.pdf.ai/runcreaterequest/metadata/) { get; set; } | 객체에 첨부할 수 있는 16개의 키-값 쌍 집합을 가져오거나 설정합니다. 이는 객체에 대한 추가 정보를 구조화된 형식으로 저장하는 데 유용할 수 있습니다. 키는 최대 64자 길이일 수 있으며 값은 최대 512자 길이일 수 있습니다. |
| [Model](../../aspose.pdf.ai/runcreaterequest/model/) { get; set; } | 이 실행을 실행하는 데 사용할 모델의 ID를 가져오거나 설정합니다. 여기에서 값이 제공되면 보조와 연결된 모델을 무시합니다. 그렇지 않으면 보조와 연결된 모델이 사용됩니다. |
| [ResponseFormat](../../aspose.pdf.ai/runcreaterequest/responseformat/) { get; set; } | 응답 형식을 가져오거나 설정합니다. 모델이 출력해야 하는 형식을 지정합니다. GPT-4o, GPT-4 Turbo 및 gpt-3.5-turbo-1106 이후의 모든 GPT-3.5 Turbo 모델과 호환됩니다. { "type": "json_object" }로 설정하면 JSON 모드가 활성화되어 모델이 생성하는 메시지가 유효한 JSON임을 보장합니다. 중요: JSON 모드를 사용할 때는 시스템 또는 사용자 메시지를 통해 모델이 JSON을 생성하도록 지시해야 합니다. 그렇지 않으면 모델이 공백의 끝없는 스트림을 생성할 수 있으며, 생성이 토큰 한도에 도달할 때까지 계속되어 긴 실행 요청이 발생할 수 있습니다. 또한 finish_reason="length"인 경우 메시지 내용이 부분적으로 잘릴 수 있으며, 이는 생성이 max_tokens를 초과했거나 대화가 최대 컨텍스트 길이를 초과했음을 나타냅니다. |
| [Stream](../../aspose.pdf.ai/runcreaterequest/stream/) { get; set; } | 스트리밍을 사용할지 여부를 가져오거나 설정합니다. true인 경우 실행 중 발생하는 이벤트의 스트림을 서버 전송 이벤트로 반환하며, 실행이 종료 상태에 들어가면 data: [DONE] 메시지로 종료됩니다. |
| [Temperature](../../aspose.pdf.ai/runcreaterequest/temperature/) { get; set; } | 사용할 샘플링 온도를 가져오거나 설정합니다. 0과 2 사이의 값입니다. 0.8과 같은 높은 값은 출력을 더 무작위로 만들고, 0.2와 같은 낮은 값은 더 집중적이고 결정론적으로 만듭니다. |
| [ToolChoice](../../aspose.pdf.ai/runcreaterequest/toolchoice/) { get; set; } | 모델이 호출하는 도구를 가져오거나 설정합니다. none은 모델이 도구를 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 기본값이며 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것 중에서 선택할 수 있음을 의미합니다. required는 모델이 사용자에게 응답하기 전에 하나 이상의 도구를 호출해야 함을 의미합니다. {"type": "file_search"} 또는 {"type": "function", "function": {"name": "my_function"}}와 같은 특정 도구를 지정하면 모델이 해당 도구를 호출하도록 강제합니다. |
| [Tools](../../aspose.pdf.ai/runcreaterequest/tools/) { get; set; } | 이 실행을 위해 보조가 사용할 수 있는 도구를 무시하는 도구를 가져오거나 설정합니다. 이는 실행별로 동작을 수정하는 데 유용합니다. |
| [TopP](../../aspose.pdf.ai/runcreaterequest/topp/) { get; set; } | 온도로 샘플링하는 대안인 nucleus sampling을 가져오거나 설정합니다. 여기서 모델은 top_p 확률 질량을 가진 토큰의 결과를 고려합니다. 따라서 0.1은 상위 10% 확률 질량을 구성하는 토큰만 고려됨을 의미합니다. 일반적으로 이는 온도 또는 TopP를 변경하는 것을 권장하지만 둘 다는 권장하지 않습니다. |
| [TruncationStrategy](../../aspose.pdf.ai/runcreaterequest/truncationstrategy/) { get; set; } | 잘림 전략을 가져오거나 설정합니다. 실행 전에 스레드가 잘리는 방식을 제어합니다. 이를 사용하여 실행의 초기 컨텍스트 창을 제어합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)