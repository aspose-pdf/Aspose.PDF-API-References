---
title: Class SetColor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetColor クラス。非ストローク操作のための色を設定する sc 演算子のクラスを表します
type: docs
weight: 7630
url: /ja/net/aspose.pdf.operators/setcolor/
---
## SetColor クラス

sc 演算子（非ストローク操作のための色を設定する）を表すクラスです。

```csharp
public class SetColor : BasicSetColorOperator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SetColor](setcolor/#constructor)() | 演算子を初期化します。 |
| [SetColor](setcolor/#constructor_1)(double) | DeviceGray、CalGray、および Indexed カラースペースのストローク演算子の色を設定します。 |
| [SetColor](setcolor/#constructor_4)(double[]) | 色成分を指定することを可能にするコンストラクタです。 |
| [SetColor](setcolor/#constructor_2)(double, double, double) | DeviceRGB、CalRGB、および Lab カラースペースのストローク演算子の色を設定します。 |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | CMYK カラースペースの非ストローク演算子の色を設定します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | 青成分を取得または設定します。 |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | シアン成分を取得または設定します。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 色成分の配列を取得します。 |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | 緑成分を取得または設定します。 |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | グレーの黒成分を取得します。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページ演算子リスト内の演算子インデックスです。 |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | 黒成分を取得または設定します。 |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | マゼンタ成分を取得または設定します。 |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | 赤成分を取得または設定します。 |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | 黄色成分を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | 演算子を処理するためのビジターオブジェクトを受け入れます。 |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | 演算子によって指定された色を返します。 |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | 色の文字列表現を返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 参照

* クラス [BasicSetColorOperator](../basicsetcoloroperator/)
* 名前空間 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* アセンブリ [Aspose.PDF](../../)