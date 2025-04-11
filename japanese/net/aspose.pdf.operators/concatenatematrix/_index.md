---
title: Class ConcatenateMatrix
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.ConcatenateMatrix クラス。現在の変換行列に対して cm 演算子の連結行列を表すクラス
type: docs
weight: 7230
url: /ja/net/aspose.pdf.operators/concatenatematrix/
---
## ConcatenateMatrix クラス

cm 演算子（現在の変換行列に連結行列を追加する）を表すクラスです。

```csharp
public class ConcatenateMatrix : Operator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ConcatenateMatrix](concatenatematrix/#constructor)(Matrix) | 行列によって演算子を初期化します。 |
| [ConcatenateMatrix](concatenatematrix/#constructor_1)(double, double, double, double, double, double) | 演算子を初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページ演算子リスト内の演算子インデックス。 |
| [Matrix](../../aspose.pdf.operators/concatenatematrix/matrix/) { get; set; } | 演算子の行列引数。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/concatenatematrix/accept/)(IOperatorSelector) | 演算子を処理するためのビジターオブジェクトを受け入れます。 |
| override [ToString](../../aspose.pdf.operators/concatenatematrix/tostring/)() | 演算子のテキスト表現を返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 参照

* クラス [Operator](../../aspose.pdf/operator/)
* 名前空間 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* アセンブリ [Aspose.PDF](../../)