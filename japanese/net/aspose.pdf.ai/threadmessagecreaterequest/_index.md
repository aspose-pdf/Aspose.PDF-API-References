---
title: Class ThreadMessageCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageCreateRequest クラス。スレッド内にメッセージを作成するためのリクエストを表します
type: docs
weight: 1120
url: /ja/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## ThreadMessageCreateRequest クラス

スレッド内にメッセージを作成するためのリクエストを表します。

```csharp
public class ThreadMessageCreateRequest
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | メッセージに添付されたファイルのリストを取得または設定します。 |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | メッセージの内容を取得または設定します。文字列または内容部分の配列であることができます。 |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | オブジェクトに添付できる16のキーと値のペアのセットを取得または設定します。これは、構造化された形式でオブジェクトに関する追加情報を保存するのに便利です。キーは最大64文字、値は最大512文字までです。 |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | メッセージを作成するエンティティの役割を取得または設定します。許可される値には、「user」、「assistant」が含まれます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | 役割をアシスタントに設定した新しい `ThreadMessageCreateRequest` を作成します。 |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | 役割をユーザーに設定した新しい `ThreadMessageCreateRequest` を作成します。 |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | スレッドメッセージリクエストの添付ファイルを設定します。 |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | スレッドメッセージリクエストにメッセージ内容を追加します。 |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | スレッドメッセージリクエストのメッセージ内容を設定します。 |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | スレッドメッセージリクエストのメタデータを設定します。 |

### 参照

* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)