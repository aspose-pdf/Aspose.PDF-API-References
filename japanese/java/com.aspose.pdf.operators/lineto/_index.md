---
title: "LineTo"
linktitle: "LineTo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "l 演算子を表すクラス（パスに直線を追加）。"
type: docs
weight: 380
url: /ja/java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.LineTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.LineTo

```
public class LineTo extends Operator
```

l 演算子を表すクラス（パスに直線を追加）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LineTo](#LineTo-double-double-) | ライン演算子を初期化します。 |
| [LineTo](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getX](#getX--) | ライン点のX座標。 |
| [getY](#getY--) | ライン点のY座標。 |
| [setX](#setX-double-) | ライン点のX座標。 |
| [setY](#setY-double-) | ライン点のY座標。 |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### LineTo {#LineTo-double-double-}
```
public LineTo(double x, double y)
```

ライン演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x |  | X 座標。 |
| y |  | Y 座標。 |

### LineTo {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getX {#getX--}
```
public double getX()
```

ライン点のX座標。

**Returns:**
double 値

### getY {#getY--}
```
public double getY()
```

ライン点のY座標。

**Returns:**
double 値

### setX {#setX-double-}
```
public void setX(double value)
```

ライン点のX座標。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setY {#setY-double-}
```
public void setY(double value)
```

ライン点のY座標。

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
