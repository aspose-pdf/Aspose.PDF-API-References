---
title: "RunResponse.ToolChoice"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "RunResponse 속성. 모델이 호출하는 도구가 있는지 여부를 가져오거나 설정합니다. none은 모델이 도구를 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 기본값이며 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것을 선택할 수 있음을 의미합니다. required는 모델이 사용자에게 응답하기 전에 하나 이상의 도구를 반드시 호출해야 함을 의미합니다. type file_search 또는 type function과 같이 특정 도구를 지정하고 함수 이름 my_function을 지정하면 모델이 해당 도구를 호출하도록 강제합니다."
type: docs
weight: 230
url: /ko/net/aspose.pdf.ai/runresponse/toolchoice/
---
## RunResponse.ToolChoice property

모델이 호출하는 도구(있는 경우)를 가져오거나 설정합니다. none은 모델이 도구를 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 기본값이며 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것을 선택할 수 있음을 의미합니다. required는 모델이 사용자에게 응답하기 전에 하나 이상의 도구를 반드시 호출해야 함을 의미합니다. {\"type\": \"file_search\"} 또는 {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}}와 같이 특정 도구를 지정하면 모델이 해당 도구를 호출하도록 강제합니다.

```csharp
public string ToolChoice { get; set; }
```

### 또 보기

* class [RunResponse](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


