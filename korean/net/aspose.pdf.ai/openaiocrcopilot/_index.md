---
title: "클래스 OpenAIOcrCopilot"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.OpenAIOcrCopilot 클래스. PDF 문서와 이미지에서 텍스트를 추출하는 OCR 기능을 제공합니다. 지원되는 이미지 유형은 PNG(.png), JPEG(.jpeg 및 .jpg), WEBP(.webp), 비애니메이션 GIF(.gif)입니다. OpenAI 클라이언트를 생성하고 옵션을 구성한 뒤 OCR copilot을 사용하는 예시입니다."
type: docs
weight: 980
url: /ko/net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

PDF 문서와 이미지에서 텍스트를 추출하기 위한 OCR 기능을 제공합니다. 지원되는 이미지 유형: PNG(.png), JPEG(.jpeg 및 .jpg), WEBP(.webp), 비애니메이션 GIF(.gif). OpenAI 클라이언트를 생성하고 옵션을 구성한 뒤, OCR 코파일럿을 사용하는 예시 사용법입니다.

```csharp
// AI 클라이언트를 생성합니다.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization(\"org_123\") // 선택적 매개변수를 구성합니다.
    .Build(); // Build

// copilot 옵션을 생성합니다.
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...delegate를 사용하여 생성합니다.
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// 요약 copilot을 생성합니다.
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// 텍스트 인식을 가져옵니다.
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// 추출된 텍스트에 접근합니다.
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | `OpenAIOcrCopilot` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### 또 보기

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


