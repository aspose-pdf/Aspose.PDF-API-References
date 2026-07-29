---
title: "SetGrayStroke"
linktitle: "SetGrayStroke"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ストローク操作のためのグレーレベルを表すクラス。"
type: docs
weight: 650
url: /ja/java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGrayStroke

```
public class SetGrayStroke extends SetColorOperator
```

ストローク操作のためのグレーレベルを表すクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetGrayStroke](#SetGrayStroke-double-) | 指定された色でオペレータを初期化します。 |
| [SetGrayStroke](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getColor](#getColor--) | オペレータが指定した色を返します。 |
| [getGray](#getGray--) | グレーレベルの値を取得または設定します。 |
| [setGray](#setGray-double-) | グレーレベルの値を取得または設定します。 |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### SetGrayStroke {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```

指定された色でオペレータを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| グレー |  | グレーレベルの値。 |

### SetGrayStroke {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getColor {#getColor--}
```
public Color getColor()
```

オペレータが指定した色を返します。

**Returns:**
オペレータが指定した色。

### getGray {#getGray--}
```
public final double getGray()
```

グレーレベルの値を取得または設定します。

**Returns:**
double 値

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

グレーレベルの値を取得または設定します。

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
