---
title: "SetRGBColorStroke"
linktitle: "SetRGBColorStroke"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "RG 演算子を表すクラス（ストローク演算子のための RGB カラーを設定）。"
type: docs
weight: 720
url: /ja/java/com.aspose.pdf.operators/setrgbcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColorStroke

```
public class SetRGBColorStroke extends SetColorOperator
```

RG 演算子を表すクラス（ストローク演算子のための RGB カラーを設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetRGBColorStroke](#SetRGBColorStroke-java.awt.Color-) | カラーで演算子を初期化します。 |
| [SetRGBColorStroke](#SetRGBColorStroke-double-double-double-) | 書き込みプログラムのコンストラクタ。 |
| [SetRGBColorStroke](#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getB](#getB--) | 青成分を取得または設定します。値: 0.0 から 1.0 の青のレベルです。 |
| [getCMYKColor](#getCMYKColor-double:A-double:A-) |  |
| [getColor](#getColor--) | オペレータが指定した色を返します。 |
| [getG](#getG--) | 緑成分を取得または設定します。値: 0.0 から 1.0 の緑のレベルです。 |
| [getR](#getR--) | 赤成分を取得または設定します。値: 0.0 から 1.0 の赤のレベルです。 |
| [setB](#setB-double-) | 青成分を取得または設定します。値: 0.0 から 1.0 の青のレベルです。 |
| [setG](#setG-double-) | 緑成分を取得または設定します。値: 0.0 から 1.0 の緑のレベルです。 |
| [setR](#setR-double-) | 赤成分を取得または設定します。値: 0.0 から 1.0 の赤のレベルです。 |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### SetRGBColorStroke {#SetRGBColorStroke-java.awt.Color-}
カラーで演算子を初期化します。

### SetRGBColorStroke {#SetRGBColorStroke-double-double-double-}
```
public SetRGBColorStroke(double r, double g, double b)
```

書き込みプログラムのコンストラクタ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| r |  | 0.0 から 1.0 までの赤のレベル |
| g |  | 0.0 から 1.0 までの緑のレベル |
| b |  | 0.0 から 1.0 までの青のレベル |

### SetRGBColorStroke {#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getB {#getB--}
```
public final double getB()
```

青成分を取得または設定します。値: 0.0 から 1.0 の青のレベルです。

**Returns:**
実行可能な値

### getCMYKColor {#getCMYKColor-double:A-double:A-}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rgb |  |  |
| cmykOut |  |  |

### getColor {#getColor--}
```
public Color getColor()
```

オペレータが指定した色を返します。

**Returns:**
オペレータが指定した色。

### getG {#getG--}
```
public final double getG()
```

緑成分を取得または設定します。値: 0.0 から 1.0 の緑のレベルです。

**Returns:**
実行可能な値

### getR {#getR--}
```
public final double getR()
```

赤成分を取得または設定します。値: 0.0 から 1.0 の赤のレベルです。

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

### setG {#setG-double-}
```
public final void setG(double value)
```

緑成分を取得または設定します。値: 0.0 から 1.0 の緑のレベルです。

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

### toString {#toString--}
```
public String toString()
```

演算子のテキスト表現を返します。

**Returns:**
演算子のテキスト表現。
