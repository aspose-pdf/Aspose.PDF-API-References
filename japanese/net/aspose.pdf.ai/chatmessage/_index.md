---
title: "クラス ChatMessage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.ChatMessage クラス。モデルによって生成されるチャット完了メッセージ"
type: docs
weight: 190
url: /ja/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage class

モデルが生成したチャット完了メッセージ。

```csharp
public class ChatMessage
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | `ChatMessage` クラスの新しいインスタンスを初期化します。 |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | `ChatMessage` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | メッセージの内容を取得または設定します。 |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | 参加者のオプション名を取得または設定します。同じ役割の参加者を区別するためのモデル情報を提供します。 |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | メッセージ作成者の役割を取得または設定します。 |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | このメッセージが応答するツール呼び出しを取得または設定します。 |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | 関数呼び出しなど、モデルによって生成されたツール呼び出しを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | アシスタントメッセージを表す新しい ChatMessage オブジェクトを作成します。 |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | システムメッセージを表す新しい ChatMessage オブジェクトを作成します。 |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | ユーザーメッセージを表す新しい ChatMessage オブジェクトを作成します。 |

### 関連項目

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


