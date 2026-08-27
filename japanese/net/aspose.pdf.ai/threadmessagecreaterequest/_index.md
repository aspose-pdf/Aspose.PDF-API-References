---
title: "クラス ThreadMessageCreateRequest"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.ThreadMessageCreateRequest クラス。スレッド内でメッセージを作成するリクエストを表します。"
type: docs
weight: 1210
url: /ja/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## ThreadMessageCreateRequest class

スレッド内にメッセージを作成するリクエストを表します。

```csharp
public class ThreadMessageCreateRequest
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | メッセージに添付されたファイルのリストを取得または設定します。 |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | メッセージの内容を取得または設定します。文字列またはコンテンツパーツの配列にすることができます。 |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | オブジェクトに添付できる 16 個のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに便利です。キーは最大 64 文字、値は最大 512 文字までです。 |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | メッセージを作成するエンティティのロールを取得または設定します。許可される値は "user"、"assistant" です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | `ThreadMessageCreateRequest` を新規作成し、ロールを Assistant に設定します。 |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | `ThreadMessageCreateRequest` を新規作成し、ロールを User に設定します。 |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | スレッドメッセージリクエストの添付ファイルを設定します。 |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | スレッドメッセージリクエストにメッセージ内容を追加します。 |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | スレッドメッセージリクエストのメッセージ内容を設定します。 |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | スレッドメッセージリクエストのメタデータを設定します。 |

### 関連項目

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


