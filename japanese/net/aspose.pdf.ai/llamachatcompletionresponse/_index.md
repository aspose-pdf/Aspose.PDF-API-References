---
title: "クラス LlamaChatCompletionResponse"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.LlamaChatCompletionResponse クラス。提供された入力に基づいてモデルが返すチャット完了レスポンスを表します。"
type: docs
weight: 740
url: /ja/net/aspose.pdf.ai/llamachatcompletionresponse/
---
## LlamaChatCompletionResponse class

提供された入力に基づき、モデルが返すチャット完了レスポンスを表します。

```csharp
public class LlamaChatCompletionResponse : BaseResponse
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [LlamaChatCompletionResponse](llamachatcompletionresponse/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Choices](../../aspose.pdf.ai/llamachatcompletionresponse/choices/) { get; set; } | チャット完了の選択肢のリストを取得または設定します。n が 1 より大きい場合、複数になる可能性があります。 |
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | チャット完了が作成された時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | チャット完了の一意の識別子を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | チャット完了に使用されるモデルを取得または設定します。 |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | オブジェクトのタイプを取得または設定します。このタイプは常に chat.completion です。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラーの理由フレーズを取得します。 |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | モデルが実行されるバックエンド構成を表すフィンガープリントを取得または設定します。 |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | 完了リクエストの使用統計情報を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | 最初の選択肢の文字列表現を返します。 |

### 関連項目

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


