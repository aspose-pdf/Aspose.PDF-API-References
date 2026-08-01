---
title: "클래스 OpenAIImageDescriptionCopilot"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.OpenAIImageDescriptionCopilot 클래스. OpenAICopilot 클래스에 대한 이미지 처리 기능을 제공합니다. ImageDescriptionCopilot 옵션의 OpenAI 클라이언트 구성을 생성하고, 해당 코파일럿을 사용하여 이미지 설명을 생성하고 첨부된 문서에 설명을 추가하는 예시 사용법"
type: docs
weight: 940
url: /ko/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## OpenAIImageDescriptionCopilot class

OpenAICopilot 클래스에 대한 이미지 처리 기능을 제공합니다. OpenAI 클라이언트를 생성하고 ImageDescriptionCopilot 옵션을 구성한 뒤, 코파일럿을 사용하여 이미지 설명을 생성하고 첨부된 문서에 설명을 추가하는 예시 사용법입니다.

```csharp
// AI 클라이언트를 생성합니다.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// copilot 옵션을 생성합니다.
var options = OpenAIImageDescriptionCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...create using delegate.
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument(new PdfDocument // Attach documents.
    {
        Name = "Another_Pdf_with_images",
        Document = new Document(GetInputPath("Pdf_with_images_low_res_bw.pdf"))
    })
    .WithDocument(GetInputPath("Mona_liza.jpg")) // Attach images
    .WithDocument(GetInputPath("Pdf_with_images.pdf")); // Attach document paths.

// 코파일럿을 생성합니다.
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// 이미지 설명을 가져옵니다.
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// 확장 메서드를 사용하여 첨부된 문서에 이미지 설명을 추가합니다.
await copilot.AddPdfImageDescriptionsAsync("DocumentsOutputDirectory");
```

```csharp
public class OpenAIImageDescriptionCopilot : IImageDescriptionCopilot
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | 새 `OpenAIImageDescriptionCopilot` 클래스 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### 또 보기

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


