---
title: "クラス OpenAISummaryCopilot"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.OpenAISummaryCopilot クラス。AI モデルを使用して文書の要約を取得する機能を提供します。OpenAI クライアントを作成し、オプションを構成してサマリーコパイロットを使用する例です。"
type: docs
weight: 1000
url: /ja/net/aspose.pdf.ai/openaisummarycopilot/
---
## OpenAISummaryCopilot class

AI モデルを使用してドキュメントの要約を取得する機能を提供します。OpenAI クライアントの作成、オプションの構成、サマリーコパイロットの使用例です。

```csharp
// AI クライアントを作成します。
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .Build();

// コパイロットオプションを作成します。
var options = OpenAISummaryCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...デリゲートを使用して作成します。
    .WithTemperature(0.5) // Configure other optional parameters.
    .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
    .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// サマリーコパイロットを作成します。
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(openAiClient, options);

// 要約テキストを取得します。
string summaryText = await summaryCopilot.GetSummaryAsync();

// 要約ドキュメントを取得します。
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// ページ情報付きの要約ドキュメントを取得します。
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// 要約を PDF ドキュメントとして保存します。
await summaryCopilot.SaveSummaryAsync("outputPath");

// 指定された形式で要約を保存します。
await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);
```

```csharp
public class OpenAISummaryCopilot : ISummaryCopilot
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [OpenAISummaryCopilot](openaisummarycopilot/)(IOpenAIClient, ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | `OpenAISummaryCopilot` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaisummarycopilot/hascontext/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### 関連項目

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


