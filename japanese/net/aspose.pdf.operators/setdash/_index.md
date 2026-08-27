---
title: "クラス SetDash"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Operators.SetDash クラス。d 演算子は線の破線パターンを設定することを表すクラスです。"
type: docs
weight: 7830
url: /ja/net/aspose.pdf.operators/setdash/
---
## SetDash class

d operator を表すクラス（線の破線パターンを設定）。

```csharp
public class SetDash : Operator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SetDash](setdash/)(int[], int) | 破線パターン設定演算子を作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Page operators list の演算子インデックス。 |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | 破線パターン。配列の要素は、交互の破線と間隔の長さを指定する数値でなければなりません。要素が1つの場合、破線と間隔の長さは同じになります。 |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | 破線位相。パスのストロークを開始する前に、破線配列を循環させて破線と間隔の長さを合計します。累積長さが破線位相で指定された値に等しくなると、パスのストロークが開始され、以降は破線配列が循環的に使用されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | 演算子を処理するためのビジタオブジェクトを受け入れます。 |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | 演算子の文字列表現を取得します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 関連項目

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


