---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetColorStroke クラス。ストロークカラーオペレーターの色を設定する SC オペレーターを表すクラス
type: docs
weight: 7680
url: /ja/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke クラス

ストロークカラーオペレーターの色を設定する SC オペレーターを表すクラスです。

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | オペレーターを初期化します。 |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | DeviceGray、CalGray、および Indexed カラースペースのストロークオペレーターの色を設定します。 |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | 色成分を設定することを可能にするコンストラクタです。 |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | DeviceRGB、CalRGB、および Lab カラースペースのストロークオペレーターの色を設定します。 |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | CMYK カラースペースのストロークオペレーターの色を設定します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | 青成分を取得または設定します。 |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | シアン成分を取得または設定します。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 色成分の配列を取得します。 |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | 緑成分を取得または設定します。 |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | グレーの黒成分を取得します。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページオペレーターリスト内のオペレーターインデックスです。 |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | 黒成分を取得または設定します。 |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | マゼンタ成分を取得または設定します。 |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | 赤成分を取得または設定します。 |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | 黄色成分を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | オペレーターを処理するためにビジターオブジェクトを受け入れます。 |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | オペレーターによって指定された色を返します。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | オペレーターとそのパラメータのテキストを返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 参照

* クラス [BasicSetColorOperator](../basicsetcoloroperator/)
* 名前空間 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* アセンブリ [Aspose.PDF](../../)