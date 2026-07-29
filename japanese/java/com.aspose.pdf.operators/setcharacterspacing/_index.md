---
title: "SetCharacterSpacing"
linktitle: "SetCharacterSpacing"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Tc 演算子を表すクラス（文字間隔を設定）。"
type: docs
weight: 500
url: /ja/java/com.aspose.pdf.operators/setcharacterspacing/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetCharacterSpacing, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetCharacterSpacing, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetCharacterSpacing, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetCharacterSpacing

```
public class SetCharacterSpacing extends TextStateOperator
```

Tc 演算子を表すクラス（文字間隔を設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetCharacterSpacing](#SetCharacterSpacing-double-) | 演算子を初期化します。 |
| [SetCharacterSpacing](#SetCharacterSpacing-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetCharacterSpacing-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getCharSpacing](#getCharSpacing--) | 文字間隔を取得します。 |
| [setCharSpacing](#setCharSpacing-double-) | 文字間隔を設定します。 |

### SetCharacterSpacing {#SetCharacterSpacing-double-}
```
public SetCharacterSpacing(double charSpacing)
```

演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| charSpacing |  | 文字間隔。 |

### SetCharacterSpacing {#SetCharacterSpacing-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetCharacterSpacing-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getCharSpacing {#getCharSpacing--}
```
public double getCharSpacing()
```

文字間隔を取得します。

**Returns:**
文字間隔。

### setCharSpacing {#setCharSpacing-double-}
```
public void setCharSpacing(double value)
```

文字間隔を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 文字間隔。 |
