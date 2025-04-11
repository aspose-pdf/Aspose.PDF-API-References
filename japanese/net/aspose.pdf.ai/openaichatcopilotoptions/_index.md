---
title: Class OpenAIChatCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIChatCopilotOptions クラス。OpenAICopilot の設定オプションを表します。
type: docs
weight: 830
url: /ja/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## OpenAIChatCopilotOptions クラス

OpenAICopilot の設定オプションを表します。

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | アシスタントの名前を取得または設定します。 |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | コンテキストバックアップ JSON のファイルパスを取得または設定します。 |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | 処理するドキュメントのコレクションを取得または設定します。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | 実行中に使用できる最大完了トークン数を取得または設定します。 |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | 実行中に使用できる最大プロンプトトークン数を取得または設定します。 |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | アシスタントに使用するモデルを取得または設定します。 |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | バックアップからコンテキストを復元するかどうかを示す値を取得または設定します。 |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | アシスタントのシステム指示を含むテキストファイルのファイルパスを取得または設定します。 |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | モデルに使用するサンプリング温度を取得または設定します。 |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | 核サンプリングのための top-p 値を取得または設定します。 |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | スレッドの切り捨て戦略を取得または設定します。 |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | ベクトルストアが期限切れになるまでの日数を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | `OpenAIChatCopilotOptions` の新しいインスタンスを作成します。 |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | `OpenAIChatCopilotOptions` のインスタンスを作成し、提供されたデリゲートを使用して構成します。 |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | 現在の `OpenAIChatCopilotOptions` を取得します。 |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | チャットコパイロットオプションのアシスタント名を設定します。 |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | チャットコパイロットオプションのコンテキストバックアップ JSON のファイルパスを設定します。 |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | チャットコパイロットオプションのドキュメントコレクションに PDF ドキュメントを追加します。 |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | チャットコパイロットオプションのドキュメントコレクションにドキュメントパスを追加します。 |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | チャットコパイロットオプションのドキュメントコレクションにテキストドキュメントを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | チャットコパイロットオプションのドキュメントコレクションを設定します。 |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | チャットコパイロットオプションのドキュメントコレクションに複数の PDF ドキュメントを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | チャットコパイロットオプションのドキュメントコレクションに複数のドキュメントパスを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | チャットコパイロットオプションのドキュメントコレクションに複数のテキストドキュメントを追加します。 |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | チャットコパイロットオプションの指示を設定します。 |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | チャットコパイロットオプションの最大完了トークンを設定します。 |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | チャットコパイロットオプションの最大プロンプトトークンを設定します。 |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | チャットコパイロットオプションのモデルを設定します。 |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | チャットコパイロットオプションでバックアップからコンテキストを復元するかどうかを設定します。 |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | チャットコパイロットオプションの温度を設定します。 |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | チャットコパイロットオプションの top P 値を設定します。 |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | チャットコパイロットオプションの切り捨て戦略を設定します。 |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | チャットコパイロットオプションのベクトルストアの有効期限の日数を設定します。 |

### 参照

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)