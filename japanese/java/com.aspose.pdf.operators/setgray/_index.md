---
title: "SetGray"
linktitle: "SetGray"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "非ストローク操作のためのグレーレベルを設定。"
type: docs
weight: 640
url: /ja/java/com.aspose.pdf.operators/setgray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGray

```
public class SetGray extends SetColorOperator
```

非ストローク操作のためのグレーレベルを設定。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetGray](#SetGray-double-) | 書き込みプログラムのコンストラクタ。 |
| [SetGray](#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getColor](#getColor--) | オペレータが指定した色を返します。 |
| [getGray](#getGray--) | グレーレベルの値を取得または設定します。 |
| [setGray](#setGray-double-) | グレーレベルの値を取得または設定します。 |
| [toString](#toString--) | 演算子の文字列表現を返します。 |

### SetGray {#SetGray-double-}
```
public SetGray(double gray)
```

書き込みプログラムのコンストラクタ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| グレー |  | グレーレベルの値。 |

### SetGray {#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-}
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

演算子の文字列表現を返します。

**Returns:**
演算子の文字列表現。
