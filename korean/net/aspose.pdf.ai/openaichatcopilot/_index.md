---
title: "클래스 OpenAIChatCopilot"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.OpenAIChatCopilot 클래스. AI 모델을 통해 문서와 상호 작용하기 위한 채팅 코파일럿을 나타냅니다. OpenAI 클라이언트를 생성하고 옵션을 구성한 후 ChatCopilot을 사용하여 사용자 질의와 상호 작용하고 대화 컨텍스트를 관리하는 예시 사용법"
type: docs
weight: 880
url: /ko/net/aspose.pdf.ai/openaichatcopilot/
---
## OpenAIChatCopilot class

AI 모델을 통해 문서와 상호작용하는 채팅 코파일럿을 나타냅니다. OpenAI 클라이언트를 생성하고 옵션을 구성한 뒤, ChatCopilot을 사용하여 사용자 질의와 상호작용하고 대화 컨텍스트를 관리하는 예시 사용법입니다.

```csharp
// AI 클라이언트를 생성합니다.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// copilot 옵션을 생성합니다.
var options = OpenAIChatCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...create using delegate.
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument("DocumentInputPath") // Attach documents using .WithDocument(s) methods allows to add text, pdf and paths to documents.
    .WithContextBackupJsonPath("PathToContextBackup") // Supply context backup to resume the conversation session.
    .WithRestoreContextFromBackup(true); // If set to true, the context 

// 요약 copilot을 생성합니다.
var chatCopilot = AICopilotFactory.CreateChatCopilot(openAiClient, options);

// 사용자 질의에 대한 응답을 가져옵니다.
string copilotResponse1 = await chatCopilot.GetResponseAsync("user message");

// 질의 목록에 대한 응답을 가져옵니다.
string copilotResponse2 = await chatCopilot.GetResponseAsync(new List<string>
{
    "message1",
    "message2"
});

// 요약을 PDF 문서로 저장합니다.
await chatCopilot.SaveResponseAsync("message1", "outputPath");

// 지정된 형식으로 요약을 저장합니다.
await chatCopilot.SaveResponseAsync("message1", "outputPath", SaveFormat.DocX);

// 요약을 PDF 문서로 저장합니다.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath");

// 지정된 형식으로 요약을 저장합니다.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath", SaveFormat.DocX);

// 컨텍스트를 저장합니다.
await chatCopilot.SaveContextAsync("outputPath");

// 컨텍스트를 삭제합니다.
await chatCopilot.DeleteContextAsync();
```

```csharp
public class OpenAIChatCopilot : IChatCopilot
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [OpenAIChatCopilot](openaichatcopilot/)(IOpenAIClient, IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | 지정된 클라이언트와 옵션을 사용하여 `OpenAIChatCopilot` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaichatcopilot/hascontext/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/openaichatcopilot/deletecontextasync/)(CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) |  |
| [SaveContextAsync](../../aspose.pdf.ai/openaichatcopilot/savecontextasync/)(string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) |  |

### 또 보기

* interface [IChatCopilot](../ichatcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


