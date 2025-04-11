---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateChatCompletionChunkResponse クラス。提供された入力に基づいてモデルによって返されるチャット完了応答のストリーミングチャンクを表します。
type: docs
weight: 250
url: /ja/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse クラス

提供された入力に基づいてモデルによって返されるチャット完了応答のストリーミングチャンクを表します。

```csharp
public class CreateChatCompletionChunkResponse
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | チャット完了の選択肢のリストを取得または設定します。nが1より大きい場合、1つ以上の要素を含むことができます。ストリームオプションを設定した場合、最後のチャンクは空であることもあります: {"include_usage": true}。 |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | チャット完了が作成されたときのUnixタイムスタンプ（秒単位）を取得または設定します。各チャンクは同じタイムスタンプを持ちます。 |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | チャット完了の一意の識別子を取得または設定します。各チャンクは同じIDを持ちます。 |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | 完了を生成するためのモデルを取得または設定します。 |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | 常に chat.completion.chunk であるオブジェクトタイプを取得または設定します。 |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | モデルが実行されるバックエンド構成を表すフィンガープリントを取得または設定します。決定論に影響を与える可能性のあるバックエンドの変更が行われたときを理解するために、シードリクエストパラメータと組み合わせて使用できます。 |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | リクエストで stream_options: {"include_usage": true} を設定したときにのみ存在するオプションのフィールドを取得または設定します。存在する場合、最後のチャンクを除いて、全体のリクエストのトークン使用統計を含むnull値を持ちます。 |

### 参照

* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)