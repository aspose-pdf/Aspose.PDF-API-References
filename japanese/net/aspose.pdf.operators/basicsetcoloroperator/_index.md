---
title: Class BasicSetColorOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.BasicSetColorOperator クラス。色を設定するオペレーターの基本クラス
type: docs
weight: 7160
url: /ja/net/aspose.pdf.operators/basicsetcoloroperator/
---
## BasicSetColorOperator クラス

色を設定するオペレーターの基本クラスです。

```csharp
public abstract class BasicSetColorOperator : SetColorOperator
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | 色の赤成分を取得します |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | CMYK色のシアン成分を取得します。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 色成分の配列を取得します。 |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | 色の緑成分を取得します |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | グレー色の黒成分を取得します。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページオペレーターリスト内のオペレーターインデックス。 |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | CMYK色の黒成分を取得します。 |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | CMYK色のマゼンタ成分を取得します。 |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | 色の赤成分を取得します |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | CMYK色の黄色成分を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | オペレーター処理を提供する訪問者 IOperatorSelector を受け入れます。 |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | オペレーターによって指定された色を返します。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | オペレーターとそのパラメータのテキストを返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 参照

* クラス [SetColorOperator](../setcoloroperator/)
* 名前空間 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* アセンブリ [Aspose.PDF](../../)