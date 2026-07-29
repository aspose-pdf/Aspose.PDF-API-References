---
title: "ConcatenateMatrix"
linktitle: "ConcatenateMatrix"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "cm 演算子 (concatenate matrix to current transformation matrix) を表すクラス。"
type: docs
weight: 140
url: /ja/java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.ConcatenateMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.ConcatenateMatrix

```
public class ConcatenateMatrix extends Operator
```

cm 演算子 (concatenate matrix to current transformation matrix) を表すクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ConcatenateMatrix](#ConcatenateMatrix-double-double-double-double-double-double-) | 演算子クラスのコンストラクタです。 |
| [ConcatenateMatrix](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-) | 演算子クラスのコンストラクタです。 |
| [ConcatenateMatrix](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | 演算子を行列で初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getMatrix](#getMatrix--) | 演算子の行列引数です。 |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | 演算子の行列引数です。 |
| [toCommand](#toCommand--) | 内部使用のみ！ |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### ConcatenateMatrix {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```

演算子クラスのコンストラクタです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a |  | A 係数 |
| b |  | B 係数 |
| c |  | C 係数 |
| d |  | D 係数 |
| e |  | E 係数 |
| f |  | F 係数 |

### ConcatenateMatrix {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-}
演算子クラスのコンストラクタです。

### ConcatenateMatrix {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
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

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

内部使用のみ！

**Returns:**
ICommand 値 ICommand オブジェクト

### toString {#toString--}
```
public String toString()
```

演算子のテキスト表現を返します。

**Returns:**
表現のテキスト表現
