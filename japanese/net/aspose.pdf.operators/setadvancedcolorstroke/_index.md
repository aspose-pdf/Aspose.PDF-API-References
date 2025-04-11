---
title: Class SetAdvancedColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetAdvancedColorStroke クラス。ストローク操作のための色を設定する SCN 演算子を表すクラス
type: docs
weight: 7570
url: /ja/net/aspose.pdf.operators/setadvancedcolorstroke/
---
## SetAdvancedColorStroke クラス

SCN 演算子（ストローク操作のための色を設定）を表すクラスです。

```csharp
public class SetAdvancedColorStroke : BasicSetColorAndPatternOperator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor)() | 演算子を初期化します。 |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_1)(double) | scn 演算子のコンストラクタ |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_4)(double, string) | scn 演算子のコンストラクタ。 |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_5)(double[], string) | scn 演算子のコンストラクタ。 |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_3)(double, double, double, string) | scn 演算子のコンストラクタ。 |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_2)(double, double, double, double, string) | scn 演算子のコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | 色の赤成分を取得します |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | CMYK 色のシアン成分を取得します。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 色成分の配列を取得します。 |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | 色の緑成分を取得します |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | グレー色の黒成分を取得します。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページ演算子リスト内の演算子インデックス。 |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | CMYK 色の黒成分を取得します。 |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | CMYK 色のマゼンタ成分を取得します。 |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | パターン名を取得します。 |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | 色の赤成分を取得します |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | CMYK 色の黄色成分を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setadvancedcolorstroke/accept/)(IOperatorSelector) | 演算子を処理するためのビジターオブジェクトを受け入れます。 |
| override [getColor](../../aspose.pdf.operators/setadvancedcolorstroke/getcolor/)() | 演算子によって指定された色を返します。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 演算子とそのパラメータのテキストを返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 参照

* クラス [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* 名前空間 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* アセンブリ [Aspose.PDF](../../)