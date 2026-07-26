---
title: "SetCMYKColorStroke"
linktitle: "SetCMYKColorStroke"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "K 演算子を表すクラス（ストローク操作のための CMYK カラーを設定）。"
type: docs
weight: 540
url: /ja/java/com.aspose.pdf.operators/setcmykcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColorStroke

```
public class SetCMYKColorStroke extends SetColorOperator
```

K 演算子を表すクラス（ストローク操作のための CMYK カラーを設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetCMYKColorStroke](#SetCMYKColorStroke-double-double-double-double-) | 演算子を初期化します。 |
| [SetCMYKColorStroke](#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getC](#getC--) | シアン成分を取得または設定します。 |
| [getColor](#getColor--) | RGB カラーを返します |
| [getK](#getK--) | 黒成分を取得または設定します。 |
| [getM](#getM--) | マゼンタ成分を取得または設定します。 |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | 黄成分を取得または設定します。 |
| [setC](#setC-double-) | シアン成分を取得または設定します。 |
| [setK](#setK-double-) | 黒成分を取得または設定します。 |
| [setM](#setM-double-) | マゼンタ成分を取得または設定します。 |
| [setY](#setY-double-) | 黄成分を取得または設定します。 |

### SetCMYKColorStroke {#SetCMYKColorStroke-double-double-double-double-}
```
public SetCMYKColorStroke(double c, double m, double y, double k)
```

演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c |  | シアンのレベル（0.0 から 1.0） |
| m |  | マゼンタのレベル（0.0 から 1.0） |
| y |  | イエローのレベル（0.0 から 1.0） |
| k |  | ブラックのレベル（0.0 から 1.0） |

### SetCMYKColorStroke {#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

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

RGB カラーを返します

**Returns:**
オペレータが指定した色。

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

### getRGBColor {#getRGBColor-double:A-double:A-}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmyk |  |  |
| rgbOut |  |  |

### getY {#getY--}
```
public final double getY()
```

黄成分を取得または設定します。

**Returns:**
実行可能な値

### setC {#setC-double-}
```
public final void setC(double value)
```

シアン成分を取得または設定します。

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

### setY {#setY-double-}
```
public final void setY(double value)
```

黄成分を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 実行可能な値 |
