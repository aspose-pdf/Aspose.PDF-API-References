---
title: "Re"
linktitle: "Re"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "re 演算子を表すクラス（パスに矩形を追加）。"
type: docs
weight: 460
url: /ja/java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Re, com.aspose.pdf.Operator, com.aspose.pdf.operators.Re

```
public class Re extends Operator
```

re 演算子を表すクラス（パスに矩形を追加）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Re](#Re--) | 目標抽出のコンストラクタ。 |
| [Re](#Re-double-double-double-double-) | 書き込みプログラムのコンストラクタ。 |
| [Re](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-) | 目標抽出のコンストラクタ。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getHeight](#getHeight--) | 矩形の高さ。 |
| [getWidth](#getWidth--) | 矩形の幅を取得します。 |
| [getX](#getX--) | 矩形の最左側のX座標。 |
| [getY](#getY--) | 矩形の底辺のY座標。 |
| [setHeight](#setHeight-double-) | 矩形の高さ。 |
| [setWidth](#setWidth-double-) | 矩形の幅を設定します。 |
| [setX](#setX-double-) | 矩形の最左側のX座標。 |
| [setY](#setY-double-) | 矩形の底辺のY座標。 |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### Re {#Re--}
```
public Re()
```

目標抽出のコンストラクタ。

### Re {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```

書き込みプログラムのコンストラクタ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x |  | 矩形の左下隅のX座標。 |
| y |  | 矩形の左下隅のY座標。 |
| 幅 |  | 矩形の幅です。 |
| 高さ |  | 矩形の高さです。 |

### Re {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-}
目標抽出のコンストラクタ。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getHeight {#getHeight--}
```
public double getHeight()
```

矩形の高さ。

**Returns:**
矩形の高さ。

### getWidth {#getWidth--}
```
public double getWidth()
```

矩形の幅を取得します。

**Returns:**
矩形の幅。

### getX {#getX--}
```
public double getX()
```

矩形の最左側のX座標。

**Returns:**
double 値

### getY {#getY--}
```
public double getY()
```

矩形の底辺のY座標。

**Returns:**
double 値

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

矩形の高さ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 矩形の高さ。 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

矩形の幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 矩形の幅。 |

### setX {#setX-double-}
```
public void setX(double value)
```

矩形の最左側のX座標。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setY {#setY-double-}
```
public void setY(double value)
```

矩形の底辺のY座標。

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
