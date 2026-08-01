---
title: "クラス OpenAIOcrCopilotOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.OpenAIOcrCopilotOptions クラス。OpenAIOcrCopilot の構成オプションを表します。"
type: docs
weight: 990
url: /ja/net/aspose.pdf.ai/openaiocrcopilotoptions/
---
## OpenAIOcrCopilotOptions class

OpenAIOcrCopilot を構成するオプションを表します。

```csharp
public class OpenAIOcrCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IOcrCopilotOptions<OpenAIOcrCopilotOptions>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Detail](../../aspose.pdf.ai/openaiocrcopilotoptions/detail/) { get; set; } | 画像解析の詳細レベルを取得または設定します。 |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | 処理対象のドキュメントコレクションを取得または設定します。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | 実行中に使用できる完了トークンの最大数を取得または設定します。 |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | アシスタントで使用するモデルを取得または設定します。 |
| [Resolution](../../aspose.pdf.ai/openaiocrcopilotoptions/resolution/) { get; set; } | PDF ページを画像に変換する際に使用される解像度を取得または設定します。デフォルト値は 300 dpi です。 |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | アシスタントシステム指示を含むテキストファイルのパスを取得または設定します。 |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | モデルで使用するサンプリング温度を取得または設定します。 |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | 核サンプリングの top-p 値を取得または設定します。 |
| [UserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/userinstructions/) { get; set; } | ユーザープロンプトを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create)() | `OpenAIOcrCopilotOptions` の新しいインスタンスを作成します。 |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create_1)(Action&lt;OpenAIOcrCopilotOptions&gt;) | 提供されたデリゲートを使用して `OpenAIOcrCopilotOptions` のインスタンスを作成し、構成します。 |
| [GetOptions](../../aspose.pdf.ai/openaiocrcopilotoptions/getoptions/)() | 現在の `OpenAIOcrCopilotOptions` を取得します。 |
| [WithDetail](../../aspose.pdf.ai/openaiocrcopilotoptions/withdetail/)(Detail) | 画像解析の詳細レベルを設定します。 |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument)(PdfDocument) | PDF Document を Document コレクションに追加します。 |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument_1)(string) | Document パスを Document コレクションに追加します。 |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Document コレクションを設定します。 |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 複数の PDF Document を Document コレクションに追加します。 |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | 複数の Document パスを Document コレクションに追加します。 |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiocrcopilotoptions/withmaxcompletiontokens/)(int?) | 最大完了トークン数を設定します。 |
| [WithModel](../../aspose.pdf.ai/openaiocrcopilotoptions/withmodel/)(string) | モデルを設定します。 |
| [WithResolution](../../aspose.pdf.ai/openaiocrcopilotoptions/withresolution/)(int) | PDFページを画像に変換する際に使用される解像度を設定します。デフォルト値は300 dpiです。 |
| [WithSystemInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withsysteminstructions/)(string) | OCRコパイロットオプションの指示を設定します。 |
| [WithTemperature](../../aspose.pdf.ai/openaiocrcopilotoptions/withtemperature/)(double?) | 温度を設定します。 |
| [WithTopP](../../aspose.pdf.ai/openaiocrcopilotoptions/withtopp/)(double?) | top P 値を設定します。 |
| [WithUserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withuserinstructions/)(string) | ユーザープロンプトを設定します。 |

### 関連項目

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IOcrCopilotOptions&lt;TOptions&gt;](../iocrcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


