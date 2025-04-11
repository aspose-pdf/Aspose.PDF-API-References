---
title: Class OpenAISummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAISummaryCopilotOptions クラス。OpenAICopilot の設定オプションを表します。
type: docs
weight: 930
url: /ja/net/aspose.pdf.ai/openaisummarycopilotoptions/
---
## OpenAISummaryCopilotOptions クラス

OpenAICopilot の設定オプションを表します。

```csharp
public class OpenAISummaryCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    ISummaryCopilotOptions<OpenAISummaryCopilotOptions>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/assistantname/) { get; set; } | アシスタントの名前を取得または設定します。 |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | 処理するドキュメントのコレクションを取得または設定します。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | 実行中に使用できる最大の完了トークン数を取得または設定します。 |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | 実行中に使用できる最大のプロンプトトークン数を取得または設定します。 |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | アシスタントに使用するモデルを取得または設定します。 |
| [SummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/summaryprompt/) { get; set; } | モデルにドキュメントの要約を提供するよう指示するプロンプトを取得または設定します。 |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | アシスタントのシステム指示を含むテキストファイルのファイルパスを取得または設定します。 |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | モデルに使用するサンプリング温度を取得または設定します。 |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | 核サンプリングのための top-p 値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create)() | `OpenAISummaryCopilotOptions` の新しいインスタンスを作成します。 |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create_1)(Action&lt;OpenAISummaryCopilotOptions&gt;) | `OpenAISummaryCopilotOptions` のインスタンスを作成し、提供されたデリゲートを使用して構成します。 |
| [GetOptions](../../aspose.pdf.ai/openaisummarycopilotoptions/getoptions/)() | 現在の `OpenAISummaryCopilotOptions` を取得します。 |
| [WithAssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/withassistantname/)(string) | 要約コパイロットオプションのアシスタント名を設定します。 |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | 要約コパイロットオプションのドキュメントコレクションに PDF ドキュメントを追加します。 |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_2)(string) | 要約コパイロットオプションのドキュメントコレクションにドキュメントパスを追加します。 |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | 要約コパイロットオプションのドキュメントコレクションにテキストドキュメントを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 要約コパイロットオプションのドキュメントコレクションを設定します。 |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 要約コパイロットオプションのドキュメントコレクションに複数の PDF ドキュメントを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | 要約コパイロットオプションのドキュメントコレクションに複数のドキュメントパスを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | 要約コパイロットオプションのドキュメントコレクションに複数のテキストドキュメントを追加します。 |
| [WithInstructions](../../aspose.pdf.ai/openaisummarycopilotoptions/withinstructions/)(string) | 要約コパイロットオプションの指示を設定します。 |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxcompletiontokens/)(int?) | 要約コパイロットオプションの最大完了トークンを設定します。 |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxprompttokens/)(int?) | 要約コパイロットオプションの最大プロンプトトークンを設定します。 |
| [WithModel](../../aspose.pdf.ai/openaisummarycopilotoptions/withmodel/)(string) | 要約コパイロットオプションのモデルを設定します。 |
| [WithSummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/withsummaryprompt/)(string) | 要約コパイロットオプションの要約プロンプトを設定します。 |
| [WithTemperature](../../aspose.pdf.ai/openaisummarycopilotoptions/withtemperature/)(double?) | 要約コパイロットオプションの温度を設定します。 |
| [WithTopP](../../aspose.pdf.ai/openaisummarycopilotoptions/withtopp/)(double?) | 要約コパイロットオプションの top P 値を設定します。 |

### 参照

* クラス [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* インターフェース [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)