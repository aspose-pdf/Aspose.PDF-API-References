---
title: Class VectorStoreFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileListQueryParameters クラス。ベクターストアファイルをリストするためのクエリパラメータオブジェクト
type: docs
weight: 1330
url: /ja/net/aspose.pdf.ai/vectorstorefilelistqueryparameters/
---
## VectorStoreFileListQueryParameters クラス

ベクターストアファイルをリストするためのクエリパラメータオブジェクト。

```csharp
public class VectorStoreFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [VectorStoreFileListQueryParameters](vectorstorefilelistqueryparameters/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | ページネーションに使用するカーソルを取得または設定します。afterはリスト内の位置を定義するオブジェクトIDです。たとえば、リストリクエストを行い、obj_fooで終わる100のオブジェクトを受け取った場合、次の呼び出しにはafter=obj_fooを含めてリストの次のページを取得できます。 |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | ページネーションに使用するカーソルを取得または設定します。beforeはリスト内の位置を定義するオブジェクトIDです。たとえば、リストリクエストを行い、obj_fooで終わる100のオブジェクトを受け取った場合、次の呼び出しにはbefore=obj_fooを含めてリストの前のページを取得できます。 |
| [Filter](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/filter/) { get; set; } | ファイルステータスによるフィルタを取得または設定します。in_progress、completed、failed、cancelledのいずれかです。 |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | 返されるオブジェクトの数に制限を取得または設定します。Limitは1から100の範囲で、デフォルトは20です。 |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | オブジェクトのcreated_atタイムスタンプによるソート順を取得または設定します。ascは昇順、descは降順です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/getqueryparameters/)() | ベクターストアファイルをリストするためのクエリパラメータを取得します。 |

### 参照

* クラス [BaseListQueryParameters](../baselistqueryparameters/)
* インターフェース [IQueryParameters](../iqueryparameters/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)