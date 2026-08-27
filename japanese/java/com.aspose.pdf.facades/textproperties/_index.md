---
title: "TextProperties"
linktitle: "TextProperties"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキストサイズ、色、スタイルなどのテキストプロパティを表します。"
type: docs
weight: 740
url: /ja/java/com.aspose.pdf.facades/textproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.TextProperties

```
public final class TextProperties extends Object
```

テキストサイズ、色、スタイルなどのテキストプロパティを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextProperties](#TextProperties-double-) | 指定されたテキストサイズ用に {@code TextProperties} オブジェクトを作成します |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColor](#getColor--) | テキストの色を取得します。 |
| [getTextSize](#getTextSize--) | テキストサイズを取得します。 |
| [isColorSpecified](#isColorSpecified--) | {@code Color} プロパティが指定されているかどうかを示す値を取得します。 |
| [isTextSizeSpecified](#isTextSizeSpecified--) | {@code TextSize} プロパティが指定されているかどうかを示す値を取得します。 |
| [setColor](#setColor-java.awt.Color-) | テキストの色を設定します。 |
| [setTextSize](#setTextSize-double-) | テキストサイズを設定します。 |

### TextProperties {#TextProperties-double-}
```
public TextProperties(double textSize)
```

指定されたテキストサイズ用に {@code TextProperties} オブジェクトを作成します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textSize |  | テキストサイズの値。 |

### getColor {#getColor--}
```
public Color getColor()
```

テキストの色を取得します。

**Returns:**
Color オブジェクト

### getTextSize {#getTextSize--}
```
public double getTextSize()
```

テキストサイズを取得します。

**Returns:**
double 値

### isColorSpecified {#isColorSpecified--}
```
public boolean isColorSpecified()
```

{@code Color} プロパティが指定されているかどうかを示す値を取得します。

**Returns:**
ブール値

### isTextSizeSpecified {#isTextSizeSpecified--}
```
public boolean isTextSizeSpecified()
```

{@code TextSize} プロパティが指定されているかどうかを示す値を取得します。

**Returns:**
ブール値

### setColor {#setColor-java.awt.Color-}
テキストの色を設定します。

### setTextSize {#setTextSize-double-}
```
public void setTextSize(double value)
```

テキストサイズを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |
