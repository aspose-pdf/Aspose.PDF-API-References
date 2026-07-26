---
title: "MoveTextPositionSetLeading"
linktitle: "MoveTextPositionSetLeading"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "TD 演算子を表すクラス（位置を移動し、リーディングを設定）。"
type: docs
weight: 400
url: /ja/java/com.aspose.pdf.operators/movetextpositionsetleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPositionSetLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPositionSetLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPositionSetLeading, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPositionSetLeading

```
public class MoveTextPositionSetLeading extends TextPlaceOperator
```

TD 演算子を表すクラス（位置を移動し、リーディングを設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MoveTextPositionSetLeading](#MoveTextPositionSetLeading-double-double-) | 演算子を初期化します。 |
| [MoveTextPositionSetLeading](#MoveTextPositionSetLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLineAndSetLeading-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getX](#getX--) | テキスト位置の X 座標です。 |
| [getY](#getY--) | テキスト位置の Y 座標です。 |
| [setX](#setX-double-) | テキスト位置の X 座標です。 |
| [setY](#setY-double-) | テキスト位置の Y 座標です。 |

### MoveTextPositionSetLeading {#MoveTextPositionSetLeading-double-double-}
```
public MoveTextPositionSetLeading(double x, double y)
```

演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x |  | テキスト位置の X 座標です。 |
| y |  | テキスト位置の Y 座標です。 |

### MoveTextPositionSetLeading {#MoveTextPositionSetLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLineAndSetLeading-}
演算子クラスのコンストラクタです。

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
