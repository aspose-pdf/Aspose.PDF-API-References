---
title: "インターフェイス IChatCopilot"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.IChatCopilot インターフェイス。AI モデルを介してドキュメントと対話するためのチャットコパイロットを表します。"
type: docs
weight: 490
url: /ja/net/aspose.pdf.ai/ichatcopilot/
---
## IChatCopilot interface

AI モデルを介してドキュメントとやり取りするチャットコパイロットを表します。

```csharp
public interface IChatCopilot : IAICopilot
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | コンテキストを非同期に削除します。 |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | 指定されたメッセージリストに対する応答を非同期に取得します。 |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | 指定されたメッセージに対する応答を非同期に取得します。 |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | コンテキストを JSON ファイルに非同期で保存します。 |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | 指定されたメッセージリストの応答を PDF ファイルに非同期で保存します。 |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | 指定されたメッセージの応答を PDF ファイルに非同期で保存します。 |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | 指定されたメッセージリストの応答を指定フォーマットのファイルに非同期で保存します。 |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | 指定されたメッセージの応答を指定フォーマットのファイルに非同期で保存します。 |

### 関連項目

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


