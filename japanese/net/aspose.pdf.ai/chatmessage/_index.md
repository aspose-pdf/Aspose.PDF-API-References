---
title: Class ChatMessage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ChatMessage クラス。モデルによって生成されたチャット完了メッセージ
type: docs
weight: 190
url: /ja/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage クラス

モデルによって生成されたチャット完了メッセージです。

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
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | 参加者のオプションの名前を取得または設定します。同じ役割の参加者を区別するためのモデル情報を提供します。 |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | メッセージの著者の役割を取得または設定します。 |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | このメッセージが応答しているツールコールを取得または設定します。 |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | モデルによって生成されたツールコール（関数呼び出しなど）を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | アシスタントメッセージを表す新しい ChatMessage オブジェクトを作成します。 |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | システムメッセージを表す新しい ChatMessage オブジェクトを作成します。 |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | ユーザーメッセージを表す新しい ChatMessage オブジェクトを作成します。 |

### 参照

* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)