---
title: "MoveTo"
linktitle: "MoveTo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "{@code operators.m} を表すクラス（移動して新しいサブパスを開始）。"
type: docs
weight: 410
url: /ja/java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.MoveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.MoveTo

```
public class MoveTo extends Operator
```

{@code operators.m} を表すクラス（移動して新しいサブパスを開始）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MoveTo](#MoveTo-double-double-) | 新しい {@code Operator.m} (move to) 演算子を初期化します。 |
| [MoveTo](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getX](#getX--) | X 座標 |
| [getY](#getY--) | Y 座標 |
| [setX](#setX-double-) | X 座標 |
| [setY](#setY-double-) | Y 座標 |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### MoveTo {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```

新しい {@code Operator.m} (move to) 演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x |  | x 座標です。 |
| y |  | y 座標です。 |

### MoveTo {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getX {#getX--}
```
public double getX()
```

X 座標

**Returns:**
double 値

### getY {#getY--}
```
public double getY()
```

Y 座標

**Returns:**
double 値

### setX {#setX-double-}
```
public void setX(double value)
```

X 座標

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setY {#setY-double-}
```
public void setY(double value)
```

Y 座標

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### toString {#toString--}
```
public String toString()
```

演算子のテキスト表現を返します。

**Returns:**
演算子のテキスト表現。
