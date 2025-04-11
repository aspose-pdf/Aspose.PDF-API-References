---
title: Class RunStepListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunStepListQueryParameters クラス。実行ステップをリストするためのクエリパラメータオブジェクト
type: docs
weight: 1040
url: /ja/net/aspose.pdf.ai/runsteplistqueryparameters/
---
## RunStepListQueryParameters クラス

実行ステップをリストするためのクエリパラメータオブジェクト。

```csharp
public class RunStepListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RunStepListQueryParameters](runsteplistqueryparameters/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | ページネーションに使用するカーソルを取得または設定します。afterはリスト内の位置を定義するオブジェクトIDです。たとえば、リストリクエストを行い、obj_fooで終わる100個のオブジェクトを受け取った場合、次の呼び出しにはafter=obj_fooを含めてリストの次のページを取得できます。 |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | ページネーションに使用するカーソルを取得または設定します。beforeはリスト内の位置を定義するオブジェクトIDです。たとえば、リストリクエストを行い、obj_fooで終わる100個のオブジェクトを受け取った場合、次の呼び出しにはbefore=obj_fooを含めてリストの前のページを取得できます。 |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | 返されるオブジェクトの数の制限を取得または設定します。Limitは1から100の範囲で、デフォルトは20です。 |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | オブジェクトのcreated_atタイムスタンプによるソート順を取得または設定します。ascは昇順、descは降順です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/runsteplistqueryparameters/getqueryparameters/)() | 実行ステップをリストするためのクエリパラメータを取得します。 |

### 参照

* クラス [BaseListQueryParameters](../baselistqueryparameters/)
* インターフェース [IQueryParameters](../iqueryparameters/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)