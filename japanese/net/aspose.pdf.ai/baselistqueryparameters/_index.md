---
title: Class BaseListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.BaseListQueryParameters クラス。オブジェクトをリストするための基本クエリパラメータ
type: docs
weight: 160
url: /ja/net/aspose.pdf.ai/baselistqueryparameters/
---
## BaseListQueryParameters クラス

オブジェクトをリストするための基本クエリパラメータ。

```csharp
public class BaseListQueryParameters
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [BaseListQueryParameters](baselistqueryparameters/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | ページネーションに使用するカーソルを取得または設定します。afterはリスト内の位置を定義するオブジェクトIDです。たとえば、リストリクエストを行い、obj_fooで終わる100個のオブジェクトを受け取った場合、次の呼び出しにはafter=obj_fooを含めてリストの次のページを取得できます。 |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | ページネーションに使用するカーソルを取得または設定します。beforeはリスト内の位置を定義するオブジェクトIDです。たとえば、リストリクエストを行い、obj_fooで終わる100個のオブジェクトを受け取った場合、次の呼び出しにはbefore=obj_fooを含めてリストの前のページを取得できます。 |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | 返されるオブジェクトの数に制限を設定または取得します。Limitは1から100の範囲で、デフォルトは20です。 |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | オブジェクトのcreated_atタイムスタンプによるソート順を取得または設定します。ascは昇順、descは降順です。 |

### 参照

* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)