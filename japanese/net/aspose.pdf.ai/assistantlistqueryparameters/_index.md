---
title: "クラス AssistantListQueryParameters"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.AssistantListQueryParameters クラス。アシスタント一覧取得のためのクエリパラメータオブジェクトを表します"
type: docs
weight: 110
url: /ja/net/aspose.pdf.ai/assistantlistqueryparameters/
---
## AssistantListQueryParameters class

アシスタントの一覧取得用クエリパラメータオブジェクトを表します。

```csharp
public class AssistantListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [AssistantListQueryParameters](assistantlistqueryparameters/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | ページネーションで使用するカーソルを取得または設定します。after はリスト内の位置を示すオブジェクト ID です。例えば、リスト要求を行い 100 個のオブジェクトを受け取り、最後が obj_foo であった場合、次の呼び出しで after=obj_foo を含めることで次のページを取得できます。 |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | ページネーションで使用するカーソルを取得または設定します。before はリスト内の位置を示すオブジェクト ID です。例えば、リスト要求を行い 100 個のオブジェクトを受け取り、最後が obj_foo であった場合、次の呼び出しで before=obj_foo を含めることで前のページを取得できます。 |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | 返されるオブジェクト数の上限を取得または設定します。上限は 1 から 100 の範囲で、デフォルトは 20 です。 |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | オブジェクトの created_at タイムスタンプによるソート順を取得または設定します。asc は昇順、desc は降順を表します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/assistantlistqueryparameters/getqueryparameters/)() | アシスタント一覧取得のクエリパラメータを取得します。 |

### 関連項目

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


