---
title: "CurveTo1"
linktitle: "CurveTo1"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "v 演算子 (append curve to path, initial point replicated) を表すクラス。"
type: docs
weight: 160
url: /ja/java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo1, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo1

```
public class CurveTo1 extends Operator
```

v 演算子 (append curve to path, initial point replicated) を表すクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CurveTo1](#CurveTo1-double-double-double-double-) | 曲線演算子を初期化します。 |
| [CurveTo1](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子セレクターを受け取ります。 |
| [getPoints](#getPoints--) | 曲線の点。 |

### CurveTo1 {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```

曲線演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x2 |  | 第二点の横座標。 |
| y2 |  | 第二点の縦座標。 |
| x3 |  | 第3点の横座標。 |
| y3 |  | 第3点の縦座標。 |

### CurveTo1 {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子セレクターを受け取ります。

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

曲線の点。

**Returns:**
Point インスタンスの配列
