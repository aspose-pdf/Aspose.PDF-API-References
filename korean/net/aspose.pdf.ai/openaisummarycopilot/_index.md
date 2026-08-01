---
title: "클래스 OpenAISummaryCopilot"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.OpenAISummaryCopilot 클래스. AI 모델을 사용하여 문서 요약을 가져오는 기능을 제공합니다. OpenAI 클라이언트를 생성하고 옵션을 구성한 후 summary copilot을 사용하는 예시"
type: docs
weight: 1000
url: /ko/net/aspose.pdf.ai/openaisummarycopilot/
---
## OpenAISummaryCopilot class

AI 모델을 사용하여 문서 요약을 얻는 기능을 제공합니다. OpenAI 클라이언트를 생성하고 옵션을 구성한 뒤, 요약 코파일럿을 사용하는 예시 사용법입니다.

```csharp
// AI 클라이언트를 생성합니다.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .Build();

// copilot 옵션을 생성합니다.
var options = OpenAISummaryCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...create using delegate.
    .WithTemperature(0.5) // Configure other optional parameters.
    .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
    .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// 요약 copilot을 생성합니다.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(openAiClient, options);

// 요약 텍스트를 가져옵니다.
string summaryText = await summaryCopilot.GetSummaryAsync();

// 요약 문서를 가져옵니다.
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// 페이지 정보가 포함된 요약 문서를 가져옵니다.
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// 요약을 PDF 문서로 저장합니다.
await summaryCopilot.SaveSummaryAsync("outputPath");

// 지정된 형식으로 요약을 저장합니다.
await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);
```

```csharp
public class OpenAISummaryCopilot : ISummaryCopilot
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [OpenAISummaryCopilot](openaisummarycopilot/)(IOpenAIClient, ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | `OpenAISummaryCopilot` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaisummarycopilot/hascontext/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### 또 보기

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


