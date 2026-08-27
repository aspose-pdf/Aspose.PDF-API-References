---
title: "SetColorStroke クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Operators.SetColorStroke クラス。ストロークカラー演算子用に色を設定する SC 演算子を表すクラス"
type: docs
weight: 7820
url: /ja/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke class

SC operator を表すクラス（ストロークカラー演算子のためにカラーを設定）。

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | 演算子を初期化します。 |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | DeviceGray、CalGray、Indexed カラースペースのストローク演算子の色を設定します。 |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | 色成分を設定できるコンストラクタです。 |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | DeviceRGB、CalRGB、Lab カラースペースのストローク演算子の色を設定します。 |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | CMYK カラースペースのストローク演算子の色を設定します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | 青成分を取得または設定します。 |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | シアン成分を取得または設定します。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | カラー成分の配列を取得します。 |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | 緑成分を取得または設定します。 |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | グレイカラーの黒成分を取得します。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Page operators list の演算子インデックス。 |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | 黒成分を取得または設定します。 |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | マゼンタ成分を取得または設定します。 |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | 赤成分を取得または設定します。 |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | 黄成分を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | 演算子を処理するためのビジタオブジェクトを受け入れます。 |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | 演算子で指定された色を返します。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 演算子とそのパラメータのテキストを返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 関連項目

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


