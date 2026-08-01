---
title: "クラス SetColor"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Operators.SetColor クラス。sc 演算子は非ストローク操作の色を設定するクラスを表します。"
type: docs
weight: 7770
url: /ja/net/aspose.pdf.operators/setcolor/
---
## SetColor class

sc operator を表すクラス（非ストローク操作のためにカラーを設定）。

```csharp
public class SetColor : BasicSetColorOperator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SetColor](setcolor/#constructor)() | 演算子を初期化します。 |
| [SetColor](setcolor/#constructor_1)(double) | DeviceGray、CalGray、Indexed カラースペースのストローク演算子の色を設定します。 |
| [SetColor](setcolor/#constructor_4)(double[]) | 色成分を指定できるコンストラクタです。 |
| [SetColor](setcolor/#constructor_2)(double, double, double) | DeviceRGB、CalRGB、Lab カラースペースのストローク演算子の色を設定します。 |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | CMYK カラースペースの非ストローク演算子の色を設定します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | 青成分を取得または設定します。 |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | シアン成分を取得または設定します。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | カラー成分の配列を取得します。 |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | 緑成分を取得または設定します。 |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | グレイカラーの黒成分を取得します。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Page operators list の演算子インデックス。 |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | 黒成分を取得または設定します。 |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | マゼンタ成分を取得または設定します。 |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | 赤成分を取得または設定します。 |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | 黄成分を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | 演算子を処理するためのビジタオブジェクトを受け入れます。 |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | 演算子で指定された色を返します。 |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | 色の文字列表現を返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 関連項目

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


