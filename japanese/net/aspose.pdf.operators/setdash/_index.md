---
title: Class SetDash
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetDash クラス。d 演算子の線のダッシュパターンを設定するクラス
type: docs
weight: 7690
url: /ja/net/aspose.pdf.operators/setdash/
---
## SetDash クラス

d 演算子（線のダッシュパターンを設定する）を表すクラス。

```csharp
public class SetDash : Operator
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SetDash](setdash/)(int[], int) | ダッシュパターン演算子を作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページ演算子リスト内の演算子インデックス。 |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | ダッシュパターン。配列の要素は、交互のダッシュとギャップの長さを指定する数値でなければなりません。要素が1つの配列の場合、ダッシュとギャップの長さは等しくなります。 |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | ダッシュフェーズ。パスをストロークする前に、ダッシュ配列を循環させ、ダッシュとギャップの長さを合計します。累積長さがダッシュフェーズで指定された値に等しくなると、パスのストロークが開始され、その時点からダッシュ配列が循環的に使用されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | 演算子を処理するためのビジターオブジェクトを受け入れます。 |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | 演算子の文字列表現を取得します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 参照

* クラス [Operator](../../aspose.pdf/operator/)
* 名前空間 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* アセンブリ [Aspose.PDF](../../)