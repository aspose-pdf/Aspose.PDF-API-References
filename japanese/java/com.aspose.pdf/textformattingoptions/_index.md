---
title: "TextFormattingOptions"
linktitle: "TextFormattingOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキスト書式設定オプションを表します"
type: docs
weight: 5080
url: /ja/java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextFormattingOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextFormattingOptions

```
public final class TextFormattingOptions extends TextOptions
```

テキスト書式設定オプションを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextFormattingOptions](#TextFormattingOptions--) | 未定義のワードラップモードで {@code TextFormattingOptions} オブジェクトの新しいインスタンスを初期化します。 |
| [TextFormattingOptions](#TextFormattingOptions-int-) | 指定されたワードラップモード用に {@code TextFormattingOptions} オブジェクトの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFirstLineIndent](#getFirstLineIndent--) | 先頭行のインデント値を取得または設定します。 |
| [getHyphenSymbol](#getHyphenSymbol--) | <p> ハイフン化プロセスで使用されるハイフン記号を取得または設定します。 </p><hr> ハイフン描画を除去するには（ラップ処理はそのまま）HyphenSymbol に空文字列 string.Empty を設定してください。 |
| [getLineSpacing](#getLineSpacing--) | 行間モードを取得します。デフォルト値は LineSpacingMode.FontSize です。 |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | 以降の行のインデント値を取得または設定します。 |
| [getWrapMode](#getWrapMode--) | ワードラップモードを取得します。デフォルト値は WordWrapMode.NoWrap です。 |
| [setFirstLineIndent](#setFirstLineIndent-float-) | 先頭行のインデント値を取得または設定します。 |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | <p> ハイフン化プロセスで使用されるハイフン記号を取得または設定します。 </p><hr> ハイフン描画を除去するには（ラップ処理はそのまま）HyphenSymbol に空文字列 string.Empty を設定してください。 |
| [setLineSpacing](#setLineSpacing-int-) | 行間モードを設定します。デフォルト値は LineSpacingMode.FontSize です。 |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | 以降の行のインデント値を取得または設定します。 |
| [setWrapMode](#setWrapMode-int-) | ワードラップモードを設定します。デフォルト値は WordWrapMode.NoWrap です。 |

### TextFormattingOptions {#TextFormattingOptions--}
```
public TextFormattingOptions()
```

未定義のワードラップモードで {@code TextFormattingOptions} オブジェクトの新しいインスタンスを初期化します。

### TextFormattingOptions {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```

指定されたワードラップモード用に {@code TextFormattingOptions} オブジェクトの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| wrapMode |  | ワードラップモード。@see WordWrapMode |

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

先頭行のインデント値を取得または設定します。

**Returns:**
float 値

### getHyphenSymbol {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```

<p> ハイフン化プロセスで使用されるハイフン記号を取得または設定します。 </p><hr> ハイフン描画を除去するには（ラップ処理はそのまま）HyphenSymbol に空文字列 string.Empty を設定してください。

**Returns:**
文字列値

### getLineSpacing {#getLineSpacing--}
```
public int getLineSpacing()
```

行間モードを取得します。デフォルト値は LineSpacingMode.FontSize です。

**Returns:**
int 値 @see LineSpacingMode

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

以降の行のインデント値を取得または設定します。

**Returns:**
float 値

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

ワードラップモードを取得します。デフォルト値は WordWrapMode.NoWrap です。

**Returns:**
WordWrapMode 値 @see WordWrapMode

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

先頭行のインデント値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
<p> ハイフン化プロセスで使用されるハイフン記号を取得または設定します。 </p><hr> ハイフン描画を除去するには（ラップ処理はそのまま）HyphenSymbol に空文字列 string.Empty を設定してください。

### setLineSpacing {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```

行間モードを設定します。デフォルト値は LineSpacingMode.FontSize です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値 @see LineSpacingMode |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

以降の行のインデント値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

ワードラップモードを設定します。デフォルト値は WordWrapMode.NoWrap です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | WordWrapMode 値 @see WordWrapMode |
