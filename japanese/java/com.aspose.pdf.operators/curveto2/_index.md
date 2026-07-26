---
title: "CurveTo2"
linktitle: "CurveTo2"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "y 演算子 (append curve to path, final point replicated) を表すクラス。"
type: docs
weight: 170
url: /ja/java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo2, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo2

```
public class CurveTo2 extends Operator
```

y 演算子 (append curve to path, final point replicated) を表すクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CurveTo2](#CurveTo2-double-double-double-double-) | 曲線演算子を初期化します。 |
| [CurveTo2](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getPoints](#getPoints--) | 曲線の点。 |

### CurveTo2 {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```

曲線演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x1 |  | 第二点の横座標。 |
| y1 |  | 第二点の縦座標。 |
| x3 |  | 第3点の横座標。 |
| y3 |  | 第3点の縦座標。 |

### CurveTo2 {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

曲線の点。

**Returns:**
Point インスタンスの配列
