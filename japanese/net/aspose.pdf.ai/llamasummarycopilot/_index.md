---
title: "クラス LlamaSummaryCopilot"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.LlamaSummaryCopilot クラス。AIモデルを使用して文書の要約を取得する機能を提供します。Llama クライアントを作成し、オプションを設定してサマリーコパイロットを使用する例です。注意：このコパイロットは Completion API を使用するため、送信できるテキストの総量はモデルのコンテキストウィンドウで制限されます"
type: docs
weight: 790
url: /ja/net/aspose.pdf.ai/llamasummarycopilot/
---
## LlamaSummaryCopilot class

AI モデルを使用してドキュメントの要約を取得する機能を提供します。Llama クライアントの作成、オプションの設定、要約コパイロットの使用例です。注: このコパイロットは Completion API を使用するため、送信できるテキストの総量はモデルのコンテキストウィンドウで制限されます。

```csharp
// AI クライアントを作成します。
var llamaClient = LlamaClient
   .CreateWithApiKey(ApiKey) // Create Llama client with the API key.
   .Build();

// コパイロットオプションを作成します。
var options = LlamaSummaryCopilotOptions
   .Create() // Create options like this, or...
   //.Create(options => { options.Model = LlamaModels.Llama13BChat; }) // ...デリゲートを使用して作成します。
   .WithTemperature(0.5) // Configure other optional parameters.
   .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
   .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// サマリーコパイロットを作成します。
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(llamaClient, options);

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
public class LlamaSummaryCopilot : ISummaryCopilot
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | `LlamaSummaryCopilot` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/llamasummarycopilot/hascontext/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### 関連項目

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


