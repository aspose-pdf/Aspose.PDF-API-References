---
title: Class ThreadMessageCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageCreateRequest 클래스. 스레드 내에서 메시지를 생성하기 위한 요청을 나타냅니다.
type: docs
weight: 1120
url: /ko/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## ThreadMessageCreateRequest 클래스

스레드 내에서 메시지를 생성하기 위한 요청을 나타냅니다.

```csharp
public class ThreadMessageCreateRequest
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | 메시지에 첨부된 파일 목록을 가져오거나 설정합니다. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | 메시지의 내용을 가져오거나 설정합니다. 문자열 또는 내용 부분의 배열일 수 있습니다. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | 객체에 첨부할 수 있는 16개의 키-값 쌍을 가져오거나 설정합니다. 이는 객체에 대한 추가 정보를 구조화된 형식으로 저장하는 데 유용할 수 있습니다. 키는 최대 64자 길이일 수 있으며 값은 최대 512자 길이일 수 있습니다. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | 메시지를 생성하는 엔터티의 역할을 가져오거나 설정합니다. 허용되는 값은 "user", "assistant"입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | 역할이 Assistant로 설정된 새로운 `ThreadMessageCreateRequest`를 생성합니다. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | 역할이 User로 설정된 새로운 `ThreadMessageCreateRequest`를 생성합니다. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | 스레드 메시지 요청의 첨부 파일을 설정합니다. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | 스레드 메시지 요청에 메시지 내용을 추가합니다. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | 스레드 메시지 요청의 메시지 내용을 설정합니다. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | 스레드 메시지 요청의 메타데이터를 설정합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)