---
title: "クラス OpenAIOcrCopilot"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.OpenAIOcrCopilot クラス。PDF ドキュメントや画像からテキストを抽出する OCR 機能を提供します。サポートされている画像タイプは PNG（.png）、JPEG（.jpeg、.jpg）、WEBP（.webp）、非アニメーション GIF（.gif）です。OpenAI クライアントを作成し、オプションを構成して OCR コパイロットを使用する例です。"
type: docs
weight: 980
url: /ja/net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

PDF ドキュメントや画像からテキストを抽出する OCR 機能を提供します。サポートされている画像タイプ: PNG (.png)、JPEG (.jpeg および .jpg)、WEBP (.webp)、非アニメーション GIF (.gif)。OpenAI クライアントの作成、オプションの構成、OCR コパイロットの使用例です。

```csharp
// AI クライアントを作成します。
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization("org_123") // オプションパラメータを構成します。
    .Build(); // Build

// コパイロットオプションを作成します。
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...delegate を使用して作成。
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// サマリーコパイロットを作成します。
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// テキスト認識を取得します。
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// 抽出されたテキストにアクセスします。
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | `OpenAIOcrCopilot` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### 関連項目

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


