---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantResponse クラス。モデルを呼び出し、ツールを使用できるアシスタントを表します。
type: docs
weight: 140
url: /ja/net/aspose.pdf.ai/assistantresponse/
---
## AssistantResponse クラス

モデルを呼び出し、ツールを使用できるアシスタントを表します。

```csharp
public class AssistantResponse : BaseResponse
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | アシスタントが作成された時刻の Unix タイムスタンプ（秒単位）を取得または設定します。 |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | アシスタントの説明を取得または設定します。最大長は 512 文字です。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP レスポンスヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | API エンドポイントで参照できる識別子を取得または設定します。 |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | アシスタントが使用するシステム指示を取得または設定します。最大長は 256,000 文字です。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | レスポンスが成功したかどうかを示します。 |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | オブジェクトに添付できる 16 のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに役立ちます。キーは最大 64 文字、値は最大 512 文字です。 |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | 使用するモデルの ID を取得または設定します。利用可能なすべてのモデルを確認するには、List models API を使用するか、モデルの概要を参照してください。 |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | アシスタントの名前を取得または設定します。最大長は 256 文字です。 |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | 常にアシスタントであるオブジェクトタイプを取得または設定します。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラー理由フレーズを取得します。 |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | モデルが出力する必要があるフォーマットを取得または設定します。GPT-4o、GPT-4 Turbo、および gpt-3.5-turbo-1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ "type": "json_object" } に設定すると、モデルが生成するメッセージが有効な JSON であることを保証する JSON モードが有効になります。重要: JSON モードを使用する場合は、システムまたはユーザーメッセージを介してモデルに JSON を生成するよう指示する必要があります。これがないと、モデルはトークン制限に達するまで空白のストリームを生成し続け、長時間実行されているように見える「スタック」したリクエストになります。また、finish_reason="length" の場合、メッセージコンテンツが部分的にカットオフされる可能性があることに注意してください。これは、生成が max_tokens を超えたか、会話が最大コンテキスト長を超えたことを示します。 |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | 使用するサンプリング温度を取得または設定します。範囲は 0 から 2 です。0.8 のような高い値は出力をよりランダムにし、0.2 のような低い値はより集中し、決定論的にします。 |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | アシスタントのツールによって使用されるリソースのセットを取得または設定します。リソースはツールの種類に特有です。たとえば、code_interpreter ツールはファイル ID のリストを必要とし、file_search ツールはベクターストア ID のリストを必要とします。 |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | アシスタントで有効なツールのリストを取得または設定します。アシスタントごとに最大 128 のツールを持つことができます。ツールは code_interpreter、file_search、または function のタイプです。 |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | 温度によるサンプリングの代替手段である、核サンプリングを取得または設定します。モデルは top_p 確率質量を持つトークンの結果を考慮します。したがって、0.1 は上位 10% の確率質量を構成するトークンのみが考慮されることを意味します。一般的には、これまたは温度を変更することをお勧めしますが、両方を変更しないでください。 |

### 参照

* クラス [BaseResponse](../baseresponse/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)