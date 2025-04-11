---
title: Class SetCMYKColor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetCMYKColor クラス。非ストローク操作のために CMYK 色を設定する k 演算子を表すクラス
type: docs
weight: 7580
url: /ja/net/aspose.pdf.operators/setcmykcolor/
---
## SetCMYKColor クラス

k 演算子（非ストローク操作のために CMYK 色を設定）を表すクラスです。

```csharp
public class SetCMYKColor : SetColorOperator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SetCMYKColor](setcmykcolor/)(double, double, double, double) | 演算子を初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [C](../../aspose.pdf.operators/setcmykcolor/c/) { get; set; } | シアン成分を取得または設定します。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページ演算子リスト内の演算子インデックス。 |
| [K](../../aspose.pdf.operators/setcmykcolor/k/) { get; set; } | ブラック成分を取得または設定します。 |
| [M](../../aspose.pdf.operators/setcmykcolor/m/) { get; set; } | マゼンタ成分を取得または設定します。 |
| [Y](../../aspose.pdf.operators/setcmykcolor/y/) { get; set; } | イエロー成分を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcmykcolor/accept/)(IOperatorSelector) | 演算子を処理するために訪問者オブジェクトを受け入れます。 |
| override [getColor](../../aspose.pdf.operators/setcmykcolor/getcolor/)() | 色を返します。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 演算子とそのパラメータのテキストを返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 参照

* クラス [SetColorOperator](../setcoloroperator/)
* 名前空間 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* アセンブリ [Aspose.PDF](../../)