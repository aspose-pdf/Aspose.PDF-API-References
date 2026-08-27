---
title: "MoveTextPosition"
linktitle: "MoveTextPosition"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Td 演算子を表すクラス（テキスト位置を移動）。"
type: docs
weight: 390
url: /ja/java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPosition

```
public class MoveTextPosition extends TextPlaceOperator
```

Td 演算子を表すクラス（テキスト位置を移動）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MoveTextPosition](#MoveTextPosition-double-double-) | 演算子を初期化します。 |
| [MoveTextPosition](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-) | 演算子を初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getX](#getX--) | テキスト位置の X 座標です。 |
| [getY](#getY--) | テキスト位置の Y 座標です。 |
| [setX](#setX-double-) | テキスト位置の X 座標です。 |
| [setY](#setY-double-) | テキスト位置の Y 座標です。 |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### MoveTextPosition {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```

演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x |  | テキスト位置の X 座標です。 |
| y |  | テキスト位置の Y 座標です。 |

### MoveTextPosition {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-}
演算子を初期化します。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getX {#getX--}
```
public double getX()
```

テキスト位置の X 座標です。

**Returns:**
double 値

### getY {#getY--}
```
public double getY()
```

テキスト位置の Y 座標です。

**Returns:**
double 値

### setX {#setX-double-}
```
public void setX(double value)
```

テキスト位置の X 座標です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setY {#setY-double-}
```
public void setY(double value)
```

テキスト位置の Y 座標です。

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
