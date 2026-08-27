---
title: "クラス BasicSetColorOperator"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Operators.BasicSetColorOperator クラス。カラー設定演算子の基底クラス"
type: docs
weight: 7300
url: /ja/net/aspose.pdf.operators/basicsetcoloroperator/
---
## BasicSetColorOperator class

set color 演算子の基本クラスです。

```csharp
public abstract class BasicSetColorOperator : SetColorOperator
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | 色の赤成分を取得します |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | CMYK カラーのシアン成分を取得します。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | カラー成分の配列を取得します。 |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | 色の緑成分を取得します |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | グレイカラーの黒成分を取得します。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Page operators list の演算子インデックス。 |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | CMYK カラーの黒成分を取得します。 |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | CMYK カラーのマゼンタ成分を取得します。 |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | 色の赤成分を取得します |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | CMYKカラーの黄色成分を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | 演算子の処理を提供する IOperatorSelector ビジターを受け入れます。 |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | 演算子で指定された色を返します。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 演算子とそのパラメータのテキストを返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 関連項目

* class [SetColorOperator](../setcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


