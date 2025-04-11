---
title: Class LlamaSummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaSummaryCopilotOptions クラス。OpenAICopilot の設定オプションを表します。
type: docs
weight: 750
url: /ja/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## LlamaSummaryCopilotOptions クラス

OpenAICopilot の設定オプションを表します。

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | 処理するドキュメントのコレクションを取得または設定します。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | 実行中に使用できる最大の完了トークン数を取得または設定します。 |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | アシスタントに使用するモデルを取得または設定します。 |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | モデルにドキュメントの要約を提供するよう指示するプロンプトを取得または設定します。 |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | アシスタントのシステム指示を含むテキストファイルのファイルパスを取得または設定します。 |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | モデルに使用するサンプリング温度を取得または設定します。 |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | ニュクレウスサンプリングのための top-p 値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | `LlamaSummaryCopilotOptions` の新しいインスタンスを作成します。 |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | `LlamaSummaryCopilotOptions` のインスタンスを作成し、提供されたデリゲートを使用して構成します。 |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | 現在の `LlamaSummaryCopilotOptions` を取得します。 |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | 要約コパイロットオプションのドキュメントコレクションに PDF ドキュメントを追加します。 |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | 要約コパイロットオプションのドキュメントコレクションにドキュメントパスを追加します。 |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | 要約コパイロットオプションのドキュメントコレクションにテキストドキュメントを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 要約コパイロットオプションのドキュメントコレクションを設定します。 |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 要約コパイロットオプションのドキュメントコレクションに複数の PDF ドキュメントを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | 要約コパイロットオプションのドキュメントコレクションに複数のドキュメントパスを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | 要約コパイロットオプションのドキュメントコレクションに複数のテキストドキュメントを追加します。 |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | 要約コパイロットオプションの指示を設定します。 |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | 要約コパイロットオプションの最大完了トークンを設定します。 |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | 要約コパイロットオプションのモデルを設定します。 |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | 要約コパイロットオプションの要約プロンプトを設定します。 |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | 要約コパイロットオプションの温度を設定します。 |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | 要約コパイロットオプションの top P 値を設定します。 |

### 参照

* クラス [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* インターフェース [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)