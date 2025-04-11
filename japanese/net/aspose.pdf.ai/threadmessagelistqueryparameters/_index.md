---
title: Class ThreadMessageListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageListQueryParameters クラス。スレッドメッセージを一覧表示するためのクエリパラメータオブジェクト
type: docs
weight: 1130
url: /ja/net/aspose.pdf.ai/threadmessagelistqueryparameters/
---
## ThreadMessageListQueryParameters クラス

スレッドメッセージを一覧表示するためのクエリパラメータオブジェクト。

```csharp
public class ThreadMessageListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ThreadMessageListQueryParameters](threadmessagelistqueryparameters/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | ページネーションに使用するカーソルを取得または設定します。afterはリスト内の位置を定義するオブジェクトIDです。たとえば、リストリクエストを行い、obj_fooで終わる100のオブジェクトを受け取った場合、次の呼び出しにはafter=obj_fooを含めてリストの次のページを取得できます。 |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | ページネーションに使用するカーソルを取得または設定します。beforeはリスト内の位置を定義するオブジェクトIDです。たとえば、リストリクエストを行い、obj_fooで終わる100のオブジェクトを受け取った場合、次の呼び出しにはbefore=obj_fooを含めてリストの前のページを取得できます。 |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | 返されるオブジェクトの数に制限を設定または取得します。Limitは1から100の範囲で、デフォルトは20です。 |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | オブジェクトのcreated_atタイムスタンプによるソート順を取得または設定します。ascは昇順、descは降順です。 |
| [RunId](../../aspose.pdf.ai/threadmessagelistqueryparameters/runid/) { get; set; } | 生成したランIDでメッセージをフィルタリングします。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/threadmessagelistqueryparameters/getqueryparameters/)() | スレッドメッセージを一覧表示するためのクエリパラメータを取得します。 |

### 参照

* クラス [BaseListQueryParameters](../baselistqueryparameters/)
* インターフェース [IQueryParameters](../iqueryparameters/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)