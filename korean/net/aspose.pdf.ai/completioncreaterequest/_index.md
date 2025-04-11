---
title: Class CompletionCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CompletionCreateRequest 클래스. Create Chat Completion 엔드포인트에 대한 요청을 나타냅니다.
type: docs
weight: 220
url: /ko/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest 클래스

Create Chat Completion 엔드포인트에 대한 요청을 나타냅니다.

```csharp
public class CompletionCreateRequest
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | -2.0과 2.0 사이의 숫자를 가져오거나 설정합니다. 양수 값은 지금까지 텍스트에서의 기존 빈도에 따라 새로운 토큰에 패널티를 부여하여 모델이 동일한 문장을 그대로 반복할 가능성을 줄입니다. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | 완성에서 지정된 토큰이 나타날 가능성을 가져오거나 설정합니다. 토큰 ID로 지정된 토큰을 -100에서 100 사이의 관련 바이어스 값에 매핑하는 JSON 객체를 허용합니다. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | 출력 토큰의 로그 확률을 반환할지 여부를 가져오거나 설정합니다. true인 경우 메시지의 내용에서 반환된 각 출력 토큰의 로그 확률을 반환합니다. |
| [MaxTokens](../../aspose.pdf.ai/completioncreaterequest/maxtokens/) { get; set; } | 완성에서 생성할 최대 토큰 수를 가져오거나 설정합니다. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | 지금까지의 대화를 구성하는 메시지 목록을 가져오거나 설정합니다. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | 사용할 모델의 ID를 가져오거나 설정합니다. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | 각 입력 메시지에 대해 생성할 채팅 완성 선택 수를 가져오거나 설정합니다. 생성된 토큰 수에 따라 요금이 부과됩니다. 비용을 최소화하려면 n을 1로 설정하십시오. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | -2.0과 2.0 사이의 숫자를 가져오거나 설정합니다. 양수 값은 지금까지 텍스트에 나타나는지 여부에 따라 새로운 토큰에 패널티를 부여하여 모델이 새로운 주제에 대해 이야기할 가능성을 높입니다. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | 모델이 출력해야 하는 형식을 지정하는 객체를 가져오거나 설정합니다. GPT-4 Turbo 및 gpt-3.5-turbo-1106보다 최신의 모든 GPT-3.5 Turbo 모델과 호환됩니다. { "type": "json_object" }로 설정하면 모델이 생성하는 메시지가 유효한 JSON임을 보장하는 JSON 모드가 활성화됩니다. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Seed 값을 가져오거나 설정합니다. 이 기능은 베타 상태입니다. 지정된 경우, 시스템은 동일한 시드와 매개변수로 반복 요청 시 동일한 결과를 반환하도록 결정론적으로 샘플링하기 위해 최선을 다합니다. 결정론은 보장되지 않으며, 백엔드의 변경 사항을 모니터링하기 위해 system_fingerprint 응답 매개변수를 참조해야 합니다. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | API가 추가 토큰 생성을 중지할 최대 4개의 시퀀스를 가져오거나 설정합니다. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | 스트리밍을 사용할지 여부를 가져오거나 설정합니다. 설정된 경우, ChatGPT와 같이 부분 메시지 델타가 전송됩니다. 토큰은 사용 가능해짐에 따라 데이터 전용 서버 전송 이벤트로 전송되며, 스트림은 data: [DONE] 메시지로 종료됩니다. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | 사용할 샘플링 온도를 가져오거나 설정합니다. 0과 2 사이의 값입니다. 0.8과 같은 높은 값은 출력을 더 무작위로 만들고, 0.2와 같은 낮은 값은 더 집중적이고 결정론적으로 만듭니다. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | 모델이 호출할 도구를 제어하는 객체를 가져오거나 설정합니다. none은 모델이 도구를 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것 중에서 선택할 수 있음을 의미합니다. required는 모델이 하나 이상의 도구를 호출해야 함을 의미합니다. {"type": "function", "function": {"name": "my_function"}}를 통해 특정 도구를 지정하면 모델이 해당 도구를 호출하도록 강제합니다. 도구가 없을 때 none이 기본값입니다. 도구가 있을 때 auto가 기본값입니다. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | 모델이 호출할 수 있는 도구 목록을 가져오거나 설정합니다. 현재 도구로는 함수만 지원됩니다. 모델이 JSON 입력을 생성할 수 있는 함수 목록을 제공하는 데 사용합니다. 최대 128개의 함수가 지원됩니다. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | 온도를 사용한 샘플링의 대안인 nucleus 샘플링을 가져오거나 설정합니다. 모델은 top_p 확률 질량을 가진 토큰의 결과를 고려합니다. 따라서 0.1은 상위 10% 확률 질량을 구성하는 토큰만 고려됨을 의미합니다. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | OpenAI가 남용을 모니터링하고 감지하는 데 도움이 되는 고유 식별자를 가져오거나 설정합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)