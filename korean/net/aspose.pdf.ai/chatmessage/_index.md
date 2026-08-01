---
title: "클래스 ChatMessage"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.ChatMessage 클래스. 모델에 의해 생성된 채팅 완료 메시지"
type: docs
weight: 190
url: /ko/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage class

모델이 생성한 채팅 완성 메시지.

```csharp
public class ChatMessage
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | `ChatMessage` 클래스의 새 인스턴스를 초기화합니다. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | `ChatMessage` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | 메시지의 내용을 가져오거나 설정합니다. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | 참가자의 선택적 이름을 가져오거나 설정합니다. 동일 역할의 참가자를 구분하기 위해 모델 정보를 제공합니다. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | 메시지 작성자의 역할을 가져오거나 설정합니다. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | 이 메시지가 응답하는 도구 호출을 가져오거나 설정합니다. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | 함수 호출과 같은 모델에 의해 생성된 도구 호출을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | assistant 메시지를 나타내는 새 ChatMessage 객체를 생성합니다. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | system 메시지를 나타내는 새 ChatMessage 객체를 생성합니다. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | user 메시지를 나타내는 새 ChatMessage 객체를 생성합니다. |

### 또 보기

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


