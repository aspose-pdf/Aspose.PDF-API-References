---
title: Class ChatMessage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ChatMessage 클래스. 모델에 의해 생성된 채팅 완료 메시지
type: docs
weight: 190
url: /ko/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage 클래스

모델에 의해 생성된 채팅 완료 메시지입니다.

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
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | 참가자를 위한 선택적 이름을 가져오거나 설정합니다. 동일한 역할의 참가자를 구별하기 위한 모델 정보를 제공합니다. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | 메시지 작성자의 역할을 가져오거나 설정합니다. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | 이 메시지가 응답하는 도구 호출을 가져오거나 설정합니다. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | 모델에 의해 생성된 도구 호출(예: 함수 호출)을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | 어시스턴트 메시지를 나타내는 새 ChatMessage 객체를 생성합니다. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | 시스템 메시지를 나타내는 새 ChatMessage 객체를 생성합니다. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | 사용자 메시지를 나타내는 새 ChatMessage 객체를 생성합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)