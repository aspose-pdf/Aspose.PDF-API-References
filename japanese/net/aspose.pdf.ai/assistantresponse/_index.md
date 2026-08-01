---
title: "クラス AssistantResponse"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.AssistantResponse クラス。モデルを呼び出し、ツールを使用できるアシスタントを表します。"
type: docs
weight: 140
url: /ja/net/aspose.pdf.ai/assistantresponse/
---
## AssistantResponse class

モデルを呼び出し、ツールを使用できるアシスタントを表します。

```csharp
public class AssistantResponse : BaseResponse
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | アシスタントが作成されたときの Unix タイムスタンプ（秒）を取得または設定します。 |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | アシスタントの説明を取得または設定します。最大長は 512 文字です。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | API エンドポイントで参照できる識別子を取得または設定します。 |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | アシスタントが使用するシステム指示を取得または設定します。最大長は 256,000 文字です。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | オブジェクトに添付できる 16 個のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに便利です。キーは最大 64 文字、値は最大 512 文字までです。 |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | 使用するモデルの ID を取得または設定します。List models API を使用して利用可能なすべてのモデルを確認したり、モデルの概要でそれらの説明を確認したりできます。 |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | アシスタントの名前を取得または設定します。最大長は 256 文字です。 |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | オブジェクトのタイプを取得または設定します。これは常に assistant です。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラーの理由フレーズを取得します。 |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | モデルが出力しなければならない形式を取得または設定します。GPT-4o、GPT-4 Turbo、そして gpt-3.5-turbo-1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ \"type\": \"json_object\" } に設定すると JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合、システムメッセージまたはユーザーメッセージでモデルに JSON を生成するよう指示する必要があります。これを行わないと、モデルはトークン上限に達するまで空白のストリームを無限に生成し続け、長時間実行され「スタックした」ように見えるリクエストになる可能性があります。また、finish_reason=\"length\" の場合、生成が max_tokens を超えた、または会話が最大コンテキスト長を超えたことを示し、メッセージ内容が部分的に切り取られることがあります。 |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | 使用するサンプリング温度（0 から 2 の範囲）を取得または設定します。0.8 のような高い値は出力をよりランダムにし、0.2 のような低い値はより焦点が合い決定的になります。 |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | アシスタントのツールで使用されるリソースのセットを取得または設定します。リソースはツールの種類に固有です。たとえば、code_interpreter ツールはファイル ID のリストが必要で、file_search ツールはベクトルストア ID のリストが必要です。 |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | アシスタントで有効化されたツールのリストを取得または設定します。アシスタントあたり最大 128 個のツールが可能です。ツールは code_interpreter、file_search、または function のタイプです。 |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | 温度によるサンプリングの代替として、トップ確率質量 top_p を考慮する nucleus sampling と呼ばれる手法を取得または設定します。たとえば 0.1 は上位 10% の確率質量を占めるトークンのみが考慮されることを意味します。通常、temperature とこの設定は同時に変更せず、どちらか一方を調整することを推奨します。 |

### 関連項目

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


