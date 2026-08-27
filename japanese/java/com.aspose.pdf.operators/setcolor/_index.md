---
title: "SetColor"
linktitle: "SetColor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "sc 演算子のクラスを表す（非ストローク操作のためのカラーを設定）。"
type: docs
weight: 550
url: /ja/java/com.aspose.pdf.operators/setcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColor

```
public class SetColor extends BasicSetColorOperator
```

sc 演算子のクラスを表す（非ストローク操作のためのカラーを設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetColor](#SetColor--) | 演算子を初期化します。 |
| [SetColor](#SetColor-double-) | DeviceGray、CalGray、Indexed カラースペース用のストローク演算子の色を設定します。 |
| [SetColor](#SetColor-double:A-) | カラーコンポーネントを指定できるコンストラクタです。 |
| [SetColor](#SetColor-double-double-double-) | DeviceRGB、CalRGB、Lab カラースペース用のストローク演算子の色を設定します |
| [SetColor](#SetColor-double-double-double-double-) | CMYK カラースペースの非ストローク演算子の色を設定します。 |
| [SetColor](#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-) | 演算子を初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getB](#getB--) | 青成分を取得または設定します。値: 0.0 から 1.0 の青のレベルです。 |
| [getC](#getC--) | シアン成分を取得または設定します。 |
| [getColor](#getColor--) | まだサポートされていません。演算子で指定された色を返します。 |
| [getG](#getG--) | 緑成分を取得または設定します。値: 0.0 から 1.0 の緑のレベルです。 |
| [getK](#getK--) | 黒成分を取得または設定します。 |
| [getM](#getM--) | マゼンタ成分を取得または設定します。 |
| [getR](#getR--) | 赤成分を取得または設定します。値: 0.0 から 1.0 の赤のレベルです。 |
| [getY](#getY--) | 黄成分を取得または設定します。 |
| [setB](#setB-double-) | 青成分を取得または設定します。値: 0.0 から 1.0 の青のレベルです。 |
| [setC](#setC-double-) | シアン成分を取得または設定します。 |
| [setG](#setG-double-) | 緑成分を取得または設定します。値: 0.0 から 1.0 の緑のレベルです。 |
| [setK](#setK-double-) | 黒成分を取得または設定します。 |
| [setM](#setM-double-) | マゼンタ成分を取得または設定します。 |
| [setR](#setR-double-) | 赤成分を取得または設定します。値: 0.0 から 1.0 の赤のレベルです。 |
| [setY](#setY-double-) | 黄成分を取得または設定します。 |
| [toString](#toString--) | 色の文字列表現を返します。 |

### SetColor {#SetColor--}
```
public SetColor()
```

演算子を初期化します。

### SetColor {#SetColor-double-}
```
public SetColor(double g)
```

DeviceGray、CalGray、Indexed カラースペース用のストローク演算子の色を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| g |  | カラー値。 |

### SetColor {#SetColor-double:A-}
```
public SetColor(double[] color)
```

カラーコンポーネントを指定できるコンストラクタです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 色 |  | カラーコンポーネントの配列です。 |

### SetColor {#SetColor-double-double-double-}
```
public SetColor(double r, double g, double b)
```

DeviceRGB、CalRGB、Lab カラースペース用のストローク演算子の色を設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| r |  | 赤成分。 |
| g |  | 緑成分。 |
| b |  | 青成分。 |

### SetColor {#SetColor-double-double-double-double-}
```
public SetColor(double c, double m, double y, double k)
```

CMYK カラースペースの非ストローク演算子の色を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c |  | シアン成分。 |
| m |  | マゼンタ成分。 |
| y |  | 黄成分。 |
| k |  | 黒成分。 |

### SetColor {#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-}
演算子を初期化します。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getB {#getB--}
```
public final double getB()
```

青成分を取得または設定します。値: 0.0 から 1.0 の青のレベルです。

**Returns:**
実行可能な値

### getC {#getC--}
```
public final double getC()
```

シアン成分を取得または設定します。

**Returns:**
実行可能な値

### getColor {#getColor--}
```
public Color getColor()
```

まだサポートされていません。演算子で指定された色を返します。

**Returns:**
演算子の色。

### getG {#getG--}
```
public final double getG()
```

緑成分を取得または設定します。値: 0.0 から 1.0 の緑のレベルです。

**Returns:**
実行可能な値

### getK {#getK--}
```
public final double getK()
```

黒成分を取得または設定します。

**Returns:**
実行可能な値

### getM {#getM--}
```
public final double getM()
```

マゼンタ成分を取得または設定します。

**Returns:**
実行可能な値

### getR {#getR--}
```
public final double getR()
```

赤成分を取得または設定します。値: 0.0 から 1.0 の赤のレベルです。

**Returns:**
実行可能な値

### getY {#getY--}
```
public final double getY()
```

黄成分を取得または設定します。

**Returns:**
実行可能な値

### setB {#setB-double-}
```
public final void setB(double value)
```

青成分を取得または設定します。値: 0.0 から 1.0 の青のレベルです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 実行可能な値 |

### setC {#setC-double-}
```
public final void setC(double value)
```

シアン成分を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 実行可能な値 |

### setG {#setG-double-}
```
public final void setG(double value)
```

緑成分を取得または設定します。値: 0.0 から 1.0 の緑のレベルです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 実行可能な値 |

### setK {#setK-double-}
```
public final void setK(double value)
```

黒成分を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 実行可能な値 |

### setM {#setM-double-}
```
public final void setM(double value)
```

マゼンタ成分を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 実行可能な値 |

### setR {#setR-double-}
```
public final void setR(double value)
```

赤成分を取得または設定します。値: 0.0 から 1.0 の赤のレベルです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 実行可能な値 |

### setY {#setY-double-}
```
public final void setY(double value)
```

黄成分を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 実行可能な値 |

### toString {#toString--}
```
public String toString()
```

色の文字列表現を返します。

**Returns:**
色の文字列表現。
