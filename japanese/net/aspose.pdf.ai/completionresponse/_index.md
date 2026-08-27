---
title: "クラス CompletionResponse"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.CompletionResponse クラス。提供された入力に基づいてモデルが返すチャット完了レスポンスを表します。"
type: docs
weight: 250
url: /ja/net/aspose.pdf.ai/completionresponse/
---
## CompletionResponse class

提供された入力に基づき、モデルが返すチャット完了レスポンスを表します。

```csharp
public class CompletionResponse : BaseResponse
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CompletionResponse](completionresponse/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | チャット完了の選択肢のリストを取得または設定します。n が 1 より大きい場合、複数になる可能性があります。 |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | チャット完了が作成された時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | チャット完了の一意の識別子を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | チャット完了に使用されるモデルを取得または設定します。 |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | オブジェクトのタイプを取得または設定します。このタイプは常に chat.completion です。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラーの理由フレーズを取得します。 |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | モデルが実行されるバックエンド構成を表すフィンガープリントを取得または設定します。シードリクエストパラメータと組み合わせて使用し、決定性に影響を与える可能性のあるバックエンドの変更が行われた時期を把握できます。 |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | 完了リクエストの使用統計情報を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | 最初の選択肢の内容を文字列として返します。 |

### 関連項目

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


