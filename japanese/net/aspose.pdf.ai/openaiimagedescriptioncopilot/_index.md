---
title: "クラス OpenAIImageDescriptionCopilot"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.OpenAIImageDescriptionCopilot クラス。OpenAICopilot クラスに対する画像処理機能を提供します。ImageDescriptionCopilot オプションの OpenAI クライアント構成を作成し、コパイロットを使用して画像説明を生成し、添付された Document に説明を追加する使用例です。"
type: docs
weight: 940
url: /ja/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## OpenAIImageDescriptionCopilot class

OpenAICopilot クラスの画像処理機能を提供します。OpenAI クライアントの作成、ImageDescriptionCopilot オプションの構成、およびコパイロットを使用して画像の説明を生成し、添付ドキュメントに説明を追加する例です。

```csharp
// AI クライアントを作成します。
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// コパイロットオプションを作成します。
var options = OpenAIImageDescriptionCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...デリゲートを使用して作成します。
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

// コパイロットを作成します。
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// 画像説明を取得します。
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// 拡張メソッドを使用して、添付ドキュメントに画像説明を追加します。
await copilot.AddPdfImageDescriptionsAsync("DocumentsOutputDirectory");
```

```csharp
public class OpenAIImageDescriptionCopilot : IImageDescriptionCopilot
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | 新しい `OpenAIImageDescriptionCopilot` クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### 関連項目

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


