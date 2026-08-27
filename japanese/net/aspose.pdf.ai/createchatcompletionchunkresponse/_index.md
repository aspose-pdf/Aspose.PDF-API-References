---
title: "クラス CreateChatCompletionChunkResponse"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.CreateChatCompletionChunkResponse クラス。提供された入力に基づきモデルが返すチャット完了レスポンスのストリーミングチャンクを表します。"
type: docs
weight: 260
url: /ja/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse class

提供された入力に基づき、モデルが返すチャット完了レスポンスのストリーミングチャンクを表します。

```csharp
public class CreateChatCompletionChunkResponse
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | チャット完了の選択肢のリストを取得または設定します。n が 1 より大きい場合、複数の要素を含むことができます。stream_options: {\"include_usage\": true} を設定した場合、最後のチャンクは空になることがあります。 |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | チャット完了が作成された Unix タイムスタンプ（秒）を取得または設定します。各チャンクは同じタイムスタンプを持ちます。 |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | チャット完了の一意の識別子を取得または設定します。各チャンクは同じ ID を持ちます。 |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | 完了を生成するモデルを取得または設定します。 |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | オブジェクトのタイプを取得または設定します。このタイプは常に chat.completion.chunk です。 |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | モデルが実行されるバックエンド構成を表すフィンガープリントを取得または設定します。シードリクエストパラメータと組み合わせて使用し、決定性に影響を与える可能性のあるバックエンドの変更が行われた時期を把握できます。 |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | リクエストで stream_options: {\"include_usage\": true} を設定した場合にのみ存在するオプションフィールドを取得または設定します。存在する場合、最後のチャンクを除き null 値が入ります。最後のチャンクにはリクエスト全体のトークン使用統計が含まれます。 |

### 関連項目

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


