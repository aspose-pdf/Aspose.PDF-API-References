---
title: Class AssistantCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantCreateRequest 클래스. 어시스턴트를 생성하기 위한 요청 객체
type: docs
weight: 100
url: /ko/net/aspose.pdf.ai/assistantcreaterequest/
---
## AssistantCreateRequest 클래스

어시스턴트를 생성하기 위한 요청 객체입니다.

```csharp
public class AssistantCreateRequest
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [AssistantCreateRequest](assistantcreaterequest/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | 어시스턴트의 설명을 가져오거나 설정합니다. 최대 길이는 512자입니다. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | 어시스턴트가 사용하는 시스템 지침을 가져오거나 설정합니다. 최대 길이는 256,000자입니다. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | 객체에 첨부할 수 있는 16개의 키-값 쌍을 가져오거나 설정합니다. 이는 객체에 대한 추가 정보를 구조화된 형식으로 저장하는 데 유용할 수 있습니다. 키는 최대 64자 길이일 수 있으며 값은 최대 512자 길이일 수 있습니다. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | 사용할 모델의 ID를 가져오거나 설정합니다. 사용 가능한 모든 모델을 보려면 List models API를 사용하거나 모델 개요를 참조하여 설명을 확인할 수 있습니다. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | 어시스턴트의 이름을 가져오거나 설정합니다. 최대 길이는 256자입니다. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | 모델이 출력해야 하는 형식을 가져오거나 설정합니다. GPT-4o, GPT-4 Turbo 및 gpt-3.5-turbo-1106 이후의 모든 GPT-3.5 Turbo 모델과 호환됩니다. { "type": "json_object" }로 설정하면 JSON 모드가 활성화되어 모델이 생성하는 메시지가 유효한 JSON임을 보장합니다. 중요: JSON 모드를 사용할 때는 시스템 또는 사용자 메시지를 통해 모델이 JSON을 생성하도록 지시해야 합니다. 그렇지 않으면 모델이 공백의 끝없는 스트림을 생성할 수 있으며, 이는 생성이 토큰 한도에 도달할 때까지 계속되어 긴 요청이 발생할 수 있습니다. 또한 finish_reason="length"인 경우 메시지 내용이 부분적으로 잘릴 수 있으며, 이는 생성이 max_tokens를 초과했거나 대화가 최대 컨텍스트 길이를 초과했음을 나타냅니다. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | 사용할 샘플링 온도를 가져오거나 설정합니다. 0과 2 사이의 값입니다. 0.8과 같은 높은 값은 출력을 더 무작위로 만들고, 0.2와 같은 낮은 값은 더 집중적이고 결정론적으로 만듭니다. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | 어시스턴트의 도구에서 사용하는 리소스를 가져오거나 설정합니다. 리소스는 도구의 유형에 따라 다릅니다. 예를 들어, code_interpreter 도구는 파일 ID 목록이 필요하고, file_search 도구는 벡터 저장소 ID 목록이 필요합니다. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | 어시스턴트에서 활성화된 도구 목록을 가져오거나 설정합니다. 어시스턴트당 최대 128개의 도구가 있을 수 있습니다. 도구는 code_interpreter, file_search 또는 function 유형일 수 있습니다. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | 온도로 샘플링하는 대안인 nucleus sampling을 가져오거나 설정합니다. 여기서 모델은 top_p 확률 질량을 가진 토큰의 결과를 고려합니다. 따라서 0.1은 상위 10% 확률 질량을 구성하는 토큰만 고려됨을 의미합니다. 일반적으로 이 값을 변경하거나 온도를 변경하는 것을 권장하지만 둘 다는 권장하지 않습니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)