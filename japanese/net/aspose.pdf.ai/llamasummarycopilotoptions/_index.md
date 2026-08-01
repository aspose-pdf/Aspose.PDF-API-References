---
title: "クラス LlamaSummaryCopilotOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.LlamaSummaryCopilotOptions クラス。OpenAICopilot の構成オプションを表します。"
type: docs
weight: 800
url: /ja/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## LlamaSummaryCopilotOptions class

OpenAICopilot の設定オプションを表します。

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | 処理対象のドキュメントコレクションを取得または設定します。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | 実行中に使用できる完了トークンの最大数を取得または設定します。 |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | アシスタントで使用するモデルを取得または設定します。 |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | モデルに文書の要約を提供させるためのプロンプトを取得または設定します。 |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | アシスタントシステム指示を含むテキストファイルのパスを取得または設定します。 |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | モデルで使用するサンプリング温度を取得または設定します。 |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | 核サンプリングの top-p 値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | `LlamaSummaryCopilotOptions` の新しいインスタンスを作成します。 |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | 提供されたデリゲートを使用して `LlamaSummaryCopilotOptions` のインスタンスを作成し、構成します。 |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | 現在の `LlamaSummaryCopilotOptions` を取得します。 |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | 要約コパイロットオプションのドキュメントコレクションに PDF ドキュメントを追加します。 |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | 要約コパイロットオプションのドキュメントコレクションにドキュメントパスを追加します。 |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | 要約コパイロットオプションのドキュメントコレクションにテキストドキュメントを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 要約コパイロットオプションのドキュメントコレクションを設定します。 |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 要約コパイロットオプションのドキュメントコレクションに複数の PDF ドキュメントを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | 要約コパイロットオプションのドキュメントコレクションに複数のドキュメントパスを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | 要約コパイロットオプションのドキュメントコレクションに複数のテキストドキュメントを追加します。 |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | 要約コパイロットオプションの指示を設定します。 |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | 要約コパイロットオプションの最大完了トークン数を設定します。 |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | 要約コパイロットオプションのモデルを設定します。 |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | 要約コパイロットオプションの要約プロンプトを設定します。 |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | 要約コパイロットオプションの温度を設定します。 |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | 要約コパイロットオプションの top P 値を設定します。 |

### 関連項目

* class [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


