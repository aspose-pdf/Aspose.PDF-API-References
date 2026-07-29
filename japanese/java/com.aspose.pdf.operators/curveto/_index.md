---
title: "CurveTo"
linktitle: "CurveTo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "c 演算子 (append curve to path) を表すクラス。"
type: docs
weight: 150
url: /ja/java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo

```
public class CurveTo extends Operator
```

c 演算子 (append curve to path) を表すクラス。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [X1](#X1) | X1 座標を取得または設定します。 |
| [X2](#X2) | X2 座標を取得または設定します。 |
| [X3](#X3) | X3 座標を取得または設定します。 |
| [Y1](#Y1) | Y1 座標を取得または設定します。 |
| [Y2](#Y2) | Y2 座標を取得または設定します。 |
| [Y3](#Y3) | Y3 座標を取得または設定します。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CurveTo](#CurveTo-double-double-double-double-double-double-) | 曲線演算子を初期化します。 |
| [CurveTo](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [toCommand](#toCommand--) | 内部使用のみ！ |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### X1 {#X1}
```
public double X1
```

X1 座標を取得または設定します。

### X2 {#X2}
```
public double X2
```

X2 座標を取得または設定します。

### X3 {#X3}
```
public double X3
```

X3 座標を取得または設定します。

### Y1 {#Y1}
```
public double Y1
```

Y1 座標を取得または設定します。

### Y2 {#Y2}
```
public double Y2
```

Y2 座標を取得または設定します。

### Y3 {#Y3}
```
public double Y3
```

Y3 座標を取得または設定します。

### CurveTo {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```

曲線演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x1 |  | 第一点の横座標。 |
| y1 |  | 第一点の縦座標。 |
| x2 |  | 第二点の横座標。 |
| y2 |  | 第二点の縦座標。 |
| x3 |  | 第3点の横座標。 |
| y3 |  | 第3点の縦座標。 |

### CurveTo {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

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
演算子のテキスト表現。
