---
title: "클래스 CompletionCreateRequest"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.CompletionCreateRequest 클래스. Create Chat Completion 엔드포인트에 대한 요청을 나타냅니다."
type: docs
weight: 230
url: /ko/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest class

Create Chat Completion 엔드포인트에 대한 요청을 나타냅니다.

```csharp
public class CompletionCreateRequest
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | -2.0에서 2.0 사이의 숫자를 가져오거나 설정합니다. 양수 값은 현재 텍스트에서의 기존 빈도에 따라 새로운 토큰에 페널티를 부여하여 모델이 동일한 문장을 그대로 반복할 가능성을 감소시킵니다. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | 완료에서 지정된 토큰이 나타날 가능성을 가져오거나 설정합니다. 토큰 ID(토크나이저에서 지정)와 -100에서 100 사이의 편향 값을 매핑하는 JSON 객체를 허용합니다. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | 출력 토큰의 로그 확률을 반환할지 여부를 가져오거나 설정합니다. true인 경우, 메시지 내용에 반환된 각 출력 토큰의 로그 확률을 반환합니다. |
| [MaxCompletionTokens](../../aspose.pdf.ai/completioncreaterequest/maxcompletiontokens/) { get; set; } | 완료에서 생성할 최대 토큰 수를 가져오거나 설정합니다. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | 지금까지의 대화를 구성하는 메시지 목록을 가져오거나 설정합니다. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | 사용할 모델의 ID를 가져오거나 설정합니다. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | 각 입력 메시지에 대해 생성할 채팅 완료 선택지 수를 가져오거나 설정합니다. 모든 선택지에서 생성된 토큰 수에 따라 비용이 청구된다는 점에 유의하십시오. 비용을 최소화하려면 n을 1로 유지하십시오. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | -2.0에서 2.0 사이의 숫자를 가져오거나 설정합니다. 양수 값은 현재 텍스트에 나타나는지 여부에 따라 새로운 토큰에 페널티를 부여하여 모델이 새로운 주제에 대해 이야기할 가능성을 높입니다. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | 모델이 출력해야 하는 형식을 지정하는 객체를 가져오거나 설정합니다. GPT-4 Turbo 및 gpt-3.5-turbo-1106 이후의 모든 GPT-3.5 Turbo 모델과 호환됩니다. { "type": "json_object" } 로 설정하면 JSON 모드가 활성화되어 모델이 생성하는 메시지가 유효한 JSON임을 보장합니다. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Seed 값을 가져오거나 설정합니다. 이 기능은 베타 버전입니다. 지정하면 시스템이 결정적으로 샘플링하도록 최선을 다해 동일한 seed와 매개변수로 반복 요청 시 동일한 결과를 반환하도록 합니다. 결정론은 보장되지 않으며, 백엔드 변경을 모니터링하려면 system_fingerprint 응답 매개변수를 참조하십시오. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | API가 추가 토큰 생성을 중지할 최대 4개의 시퀀스를 가져오거나 설정합니다. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | 스트리밍 사용 여부를 가져오거나 설정합니다. 설정하면 ChatGPT와 같이 부분 메시지 델타가 전송됩니다. 토큰은 사용 가능해지는 대로 데이터 전용 서버 전송 이벤트로 전송되며, 스트림은 data: [DONE] 메시지로 종료됩니다. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | 0에서 2 사이의 샘플링 온도를 가져오거나 설정합니다. 0.8과 같은 높은 값은 출력을 더 무작위로 만들고, 0.2와 같은 낮은 값은 더 집중되고 결정적으로 만듭니다. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | 모델이 호출할 도구(있는 경우)를 제어하는 객체를 가져오거나 설정합니다. none은 모델이 도구를 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것을 선택할 수 있음을 의미합니다. required는 모델이 하나 이상의 도구를 반드시 호출해야 함을 의미합니다. {"type": "function", "function": {"name": "my_function"}}와 같이 특정 도구를 지정하면 모델이 해당 도구를 호출하도록 강제합니다. 도구가 없을 때는 none이 기본값이며, 도구가 있을 경우 auto가 기본값입니다. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | 모델이 호출할 수 있는 도구 목록을 가져오거나 설정합니다. 현재 도구로는 함수만 지원됩니다. 이를 사용하여 모델이 JSON 입력을 생성할 수 있는 함수 목록을 제공하십시오. 최대 128개의 함수가 지원됩니다. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | 온도 샘플링의 대안인 핵심 샘플링을 가져오거나 설정합니다. 모델은 top_p 확률 질량을 가진 토큰들의 결과를 고려합니다. 따라서 0.1은 상위 10% 확률 질량을 차지하는 토큰만 고려함을 의미합니다. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | 엔드 유저를 나타내는 고유 식별자를 가져오거나 설정합니다. 이는 OpenAI가 남용을 모니터링하고 감지하는 데 도움이 될 수 있습니다. |

### 또 보기

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


