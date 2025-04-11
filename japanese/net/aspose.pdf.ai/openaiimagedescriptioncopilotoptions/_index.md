---
title: Class OpenAIImageDescriptionCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions クラス。OpenAICopilot の設定オプションを表します。
type: docs
weight: 900
url: /ja/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## OpenAIImageDescriptionCopilotOptions クラス

OpenAICopilot の設定オプションを表します。

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | アシスタントの名前を取得または設定します。 |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | 処理するドキュメントのコレクションを取得または設定します。 |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | モデルに画像の説明を提供するよう指示するプロンプトを取得または設定します。 |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | ユーザーによって指定された場合、画像の詳細レベルを取得または設定します。「low」はトークンを少なく使用し、「high」を使用して高解像度を選択できます。設定されていない場合はデフォルトで「auto」になります。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | 実行中に使用される可能性のある最大完了トークン数を取得または設定します。 |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | 実行中に使用される可能性のある最大プロンプトトークン数を取得または設定します。 |
| override [Model](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/model/) { get; set; } | アシスタントに使用するビジョンモデルを取得または設定します。 |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | アシスタントのシステム指示を含むテキストファイルのファイルパスを取得または設定します。 |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | モデルに使用するサンプリング温度を取得または設定します。 |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | 核サンプリングのための top-p 値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | `OpenAIImageDescriptionCopilotOptions` の新しいインスタンスを作成します。 |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | `OpenAIImageDescriptionCopilotOptions` のインスタンスを作成し、提供されたデリゲートを使用して構成します。 |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | 現在の `OpenAIImageDescriptionCopilotOptions` を取得します。 |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | 画像説明コパイロットオプションのアシスタント名を設定します。 |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | 画像説明コパイロットオプションのドキュメントコレクションに PDF ドキュメントを追加します。 |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | 画像説明コパイロットオプションのドキュメントコレクションにドキュメントパスを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 画像説明コパイロットオプションのドキュメントコレクションを設定します。 |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 画像説明コパイロットオプションのドキュメントコレクションに複数の PDF ドキュメントを追加します。 |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | 画像説明コパイロットオプションのドキュメントコレクションに複数のドキュメントパスを追加します。 |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | 画像説明コパイロットオプションのプロンプトを設定します。 |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | 画像の詳細レベルを設定します。 |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | 画像説明コパイロットオプションの指示を設定します。 |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | 画像説明コパイロットオプションの最大完了トークンを設定します。 |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | 画像説明コパイロットオプションの最大プロンプトトークンを設定します。 |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | 画像説明コパイロットオプションのモデルを設定します。 |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | 画像説明コパイロットオプションの温度を設定します。 |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | 画像説明コパイロットオプションの top P 値を設定します。 |

### 参照

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)