---
title: "Measure.NumberFormat"
linktitle: "Measure.NumberFormat"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "測定の数値形式です。"
type: docs
weight: 2940
url: /ja/java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

測定の数値形式です。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | NumberFormat クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAfterText](#getAfterText--) | ラベルの後に連結されるテキスト |
| [getBeforeText](#getBeforeText--) | ラベルの左側に連結されるテキスト。 |
| [getConvresionFactor](#getConvresionFactor--) | 前の数値形式配列要素の部分単位の値に掛けて、この数値形式の単位の値を取得するために使用される変換係数です。 |
| [getDenominator](#getDenominator--) | FractionDisplayment が ShowAsFraction の場合、この値は分数の分母です。既定値は 16 です。 |
| [getFractionDisplayment](#getFractionDisplayment--) | 分数値がどのように表示されるか。 |
| [getFractionSeparator](#getFractionSeparator--) | 数値を表示する際の小数点位置として使用されるテキストです。空文字列は既定が使用されることを示します。既定はピリオド文字です。 |
| [getPrecision](#getPrecision--) | FractionDisplayment が ShowAsDecimal の場合、この値は分数値の精度です。10 の倍数である必要があります。既定は 100 です。 |
| [getThousandsSeparator](#getThousandsSeparator--) | 数値を表示する際に千の位ごとに使用されるテキストです。空文字列はテキストが追加されないことを示します。既定はコンマです。 |
| [getUnitLabel](#getUnitLabel--) | 単位を表示するためのラベルを指定するテキスト文字列です。 |
| [isForceDenominator](#isForceDenominator--) | FractionDisplayment が ShowAsFraction の場合、この値は分数を約分するかどうかを決定します。値が true の場合、分数は約分されません。 |
| [setAfterText](#setAfterText-java.lang.String-) | ラベルの後に連結されるテキスト |
| [setBeforeText](#setBeforeText-java.lang.String-) | ラベルの左側に連結されるテキスト。 |
| [setConvresionFactor](#setConvresionFactor-double-) | 前の数値形式配列要素の部分単位の値に掛けて、この数値形式の単位の値を取得するために使用される変換係数です。 |
| [setDenominator](#setDenominator-int-) | FractionDisplayment が ShowAsFraction の場合、この値は分数の分母です。既定値は 16 です。 |
| [setForceDenominator](#setForceDenominator-boolean-) | FractionDisplayment が ShowAsFraction の場合、この値は分数を約分するかどうかを決定します。値が true の場合、分数は約分されません。 |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | 分数値がどのように表示されるか。 |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | 数値を表示する際の小数点位置として使用されるテキストです。空文字列は既定が使用されることを示します。既定はピリオド文字です。 |
| [setPrecision](#setPrecision-int-) | FractionDisplayment が ShowAsDecimal の場合、この値は分数値の精度です。10 の倍数である必要があります。既定は 100 です。 |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | 数値を表示する際に千の位ごとに使用されるテキストです。空文字列はテキストが追加されないことを示します。既定はコンマです。 |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
NumberFormat クラスのコンストラクタです。

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

ラベルの後に連結されるテキスト

**Returns:**
String オブジェクト

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

ラベルの左側に連結されるテキスト。

**Returns:**
String オブジェクト

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

前の数値形式配列要素の部分単位の値に掛けて、この数値形式の単位の値を取得するために使用される変換係数です。

**Returns:**
double 値

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

FractionDisplayment が ShowAsFraction の場合、この値は分数の分母です。既定値は 16 です。

**Returns:**
int 値です。

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

分数値がどのように表示されるか。

**Returns:**
FractionStyle の値 @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

数値を表示する際の小数点位置として使用されるテキストです。空文字列は既定が使用されることを示します。既定はピリオド文字です。

**Returns:**
文字列値

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

FractionDisplayment が ShowAsDecimal の場合、この値は分数値の精度です。10 の倍数である必要があります。既定は 100 です。

**Returns:**
int 値です。

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

数値を表示する際に千の位ごとに使用されるテキストです。空文字列はテキストが追加されないことを示します。既定はコンマです。

**Returns:**
文字列値

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

単位を表示するためのラベルを指定するテキスト文字列です。

**Returns:**
String オブジェクト

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

FractionDisplayment が ShowAsFraction の場合、この値は分数を約分するかどうかを決定します。値が true の場合、分数は約分されません。

**Returns:**
ブール値

### setAfterText {#setAfterText-java.lang.String-}
ラベルの後に連結されるテキスト

### setBeforeText {#setBeforeText-java.lang.String-}
ラベルの左側に連結されるテキスト。

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

前の数値形式配列要素の部分単位の値に掛けて、この数値形式の単位の値を取得するために使用される変換係数です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

FractionDisplayment が ShowAsFraction の場合、この値は分数の分母です。既定値は 16 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

FractionDisplayment が ShowAsFraction の場合、この値は分数を約分するかどうかを決定します。値が true の場合、分数は約分されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
分数値がどのように表示されるか。

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
数値を表示する際の小数点位置として使用されるテキストです。空文字列は既定が使用されることを示します。既定はピリオド文字です。

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

FractionDisplayment が ShowAsDecimal の場合、この値は分数値の精度です。10 の倍数である必要があります。既定は 100 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
数値を表示する際に千の位ごとに使用されるテキストです。空文字列はテキストが追加されないことを示します。既定はコンマです。

### setUnitLabel {#setUnitLabel-java.lang.String-}
