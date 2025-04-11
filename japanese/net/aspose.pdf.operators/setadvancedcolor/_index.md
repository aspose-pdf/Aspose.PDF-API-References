---
title: Class SetAdvancedColor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetAdvancedColor クラス。非ストローク操作のための色を設定する scn オペレーターを表すクラス
type: docs
weight: 7560
url: /ja/net/aspose.pdf.operators/setadvancedcolor/
---
## SetAdvancedColor クラス

scn オペレーター（非ストローク操作のための色を設定）を表すクラスです。

```csharp
public class SetAdvancedColor : BasicSetColorAndPatternOperator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SetAdvancedColor](setadvancedcolor/#constructor)() | オペレーターを初期化します。 |
| [SetAdvancedColor](setadvancedcolor/#constructor_1)(double) | scn オペレーターのコンストラクタ。 |
| [SetAdvancedColor](setadvancedcolor/#constructor_6)(string) | scn オペレーターのコンストラクタ。 |
| [SetAdvancedColor](setadvancedcolor/#constructor_4)(double, string) | scn オペレーターのコンストラクタ。 |
| [SetAdvancedColor](setadvancedcolor/#constructor_5)(double[], string) | scn オペレーターのコンストラクタ。 |
| [SetAdvancedColor](setadvancedcolor/#constructor_3)(double, double, double, string) | scn オペレーターのコンストラクタ。 |
| [SetAdvancedColor](setadvancedcolor/#constructor_2)(double, double, double, double, string) | scn オペレーターのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | 色の赤成分を取得します |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | CMYK 色のシアン成分を取得します。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 色成分の配列を取得します。 |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | 色の緑成分を取得します |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | グレー色の黒成分を取得します。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページオペレーターリスト内のオペレーターインデックス。 |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | CMYK 色の黒成分を取得します。 |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | CMYK 色のマゼンタ成分を取得します。 |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | パターン名を取得します。 |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | 色の赤成分を取得します |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | CMYK 色の黄色成分を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setadvancedcolor/accept/)(IOperatorSelector) | オペレーターを処理するためのビジターオブジェクトを受け入れます。 |
| override [getColor](../../aspose.pdf.operators/setadvancedcolor/getcolor/)() | オペレーターによって指定された色を返します。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | オペレーターとそのパラメータのテキストを返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 参照

* クラス [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* 名前空間 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* アセンブリ [Aspose.PDF](../../)