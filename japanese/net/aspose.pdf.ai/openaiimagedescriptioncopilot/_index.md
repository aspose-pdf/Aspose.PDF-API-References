---
title: Class OpenAIImageDescriptionCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIImageDescriptionCopilot クラス。OpenAICopilot クラスのための画像処理機能を提供します。ImageDescriptionCopilot オプションの OpenAI クライアント構成を作成し、コパイロットを使用して画像の説明を生成し、添付されたドキュメントに説明を追加する例を示します。
type: docs
weight: 880
url: /ja/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## OpenAIImageDescriptionCopilot クラス

OpenAICopilot クラスのための画像処理機能を提供します。OpenAI クライアントの作成、ImageDescriptionCopilot オプションの構成、およびコパイロットを使用して画像の説明を生成し、添付されたドキュメントに説明を追加する例を示します。

```csharp
// Create AI client.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Create copilot options.
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

// Create copilot.
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// Get Image descriptions.
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// Use extension method to add image descriptions to attached documents.
await copilot.AddPdfImageDescriptionsAsync("DocumentsOutputDirectory");
```

```csharp
public class OpenAIImageDescriptionCopilot : IImageDescriptionCopilot
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | `OpenAIImageDescriptionCopilot` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### 参照

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)