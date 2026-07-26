---
title: "SetTextMatrix"
linktitle: "SetTextMatrix"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Tm 演算子を表すクラス（テキスト行列を設定）。"
type: docs
weight: 750
url: /ja/java/com.aspose.pdf.operators/settextmatrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.SetTextMatrix

```
public class SetTextMatrix extends TextPlaceOperator
```

Tm 演算子を表すクラス（テキスト行列を設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetTextMatrix](#SetTextMatrix-double-double-double-double-double-double-) | 演算子を初期化します。 |
| [SetTextMatrix](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-) | 演算子を初期化します。 |
| [SetTextMatrix](#SetTextMatrix-com.aspose.pdf.Matrix-) | 演算子を行列で初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getMatrix](#getMatrix--) | 演算子の行列引数です。 |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | 演算子の行列引数です。 |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### SetTextMatrix {#SetTextMatrix-double-double-double-double-double-double-}
```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a |  | A 係数 |
| b |  | B 係数 |
| c |  | C 係数 |
| d |  | D 係数 |
| e |  | E 係数 |
| f |  | F 係数 |

### SetTextMatrix {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-}
演算子を初期化します。

### SetTextMatrix {#SetTextMatrix-com.aspose.pdf.Matrix-}
演算子を行列で初期化します。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

演算子の行列引数です。

**Returns:**
Matrix オブジェクト

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
演算子の行列引数です。

### toString {#toString--}
```
public String toString()
```

演算子のテキスト表現を返します。

**Returns:**
演算子のテキスト表現。
