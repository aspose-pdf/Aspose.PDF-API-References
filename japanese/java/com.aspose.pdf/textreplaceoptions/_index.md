---
title: "TextReplaceOptions"
linktitle: "TextReplaceOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキスト置換オプションを表します"
type: docs
weight: 5250
url: /ja/java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextReplaceOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextReplaceOptions

```
public final class TextReplaceOptions extends TextOptions
```

テキスト置換オプションを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextReplaceOptions](#TextReplaceOptions--) | デフォルトの調整とスコープ（ReplaceAdjustment.None と Scope.REPLACE_FIRST）用に {@code TextReplaceOptions} オブジェクトの新しいインスタンスを初期化します。 |
| [TextReplaceOptions](#TextReplaceOptions-int-) | 指定された置換後アクション用に {@code TextReplaceOptions} オブジェクトの新しいインスタンスを初期化します。 |
| [TextReplaceOptions](#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-) | デフォルトの調整とスコープ（ReplaceAdjustment.None と Scope.REPLACE_FIRST）用に {@code TextReplaceOptions} オブジェクトの新しいインスタンスを初期化します。 |
| [TextReplaceOptions](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | デフォルトの調整とスコープ（ReplaceAdjustment.None と Scope.REPLACE_FIRST）用に {@code TextReplaceOptions} オブジェクトの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAdjustmentNewLineSpacing](#getAdjustmentNewLineSpacing--) | 置換調整が強制的に新しいテキスト行を作成する場合に使用される行間の値を取得または設定します。期待される値は置換されたテキストのフォントサイズの倍率です。デフォルトは 1.2 です。 |
| [getFontSizeAdjustmentAction](#getFontSizeAdjustmentAction--) | {@code TextReplaceOptions.Rectangle}（{@link #getRectangle}/{@link #setRectangle(Rectangle)}）で定義された境界内に収まるようにフォントサイズを調整するポリシーを取得または設定します。 |
| [getLeftAdjustment](#getLeftAdjustment--) | TextReplaceOptions を使用する際に置換されたテキストの左位置調整を取得します: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [getRectangle](#getRectangle--) | 置換後のテキストを収める矩形を取得または設定します。 |
| [getReplaceAdjustmentAction](#getReplaceAdjustmentAction--) | テキストフラグメントの置換後に実行されるアクションを取得します（短くするため）。 |
| [getReplaceScope](#getReplaceScope--) | テキスト置換操作が適用されるスコープを取得します。 |
| [getRightAdjustment](#getRightAdjustment--) | TextReplaceOptions を使用する際に置換されたテキストの右位置調整を設定または取得します: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |
| [isIgnoreParagraphs](#isIgnoreParagraphs--) | テキスト置換後にページ上のテキストを調整する際、個別の段落を無視するかどうかを示す値を取得または設定します。 |
| [setAdjustmentNewLineSpacing](#setAdjustmentNewLineSpacing-double-) | 置換調整が強制的に新しいテキスト行を作成する場合に使用される行間の値を取得または設定します。期待される値は置換されたテキストのフォントサイズの倍率です。デフォルトは 1.2 です。 |
| [setFontSizeAdjustmentAction](#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-) | TextReplaceOptions.Rectangle（getRectangle() / setRectangle(Rectangle)）で定義された境界内に収まるようにフォントサイズを調整するポリシーを取得または設定します。 |
| [setIgnoreParagraphs](#setIgnoreParagraphs-boolean-) | テキスト置換後にページ上のテキストを調整する際、個別の段落を無視するかどうかを示す値を取得または設定します。 |
| [setLeftAdjustment](#setLeftAdjustment-double-) | TextReplaceOptions を使用する際に置換されたテキストの左位置調整を設定または取得します: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | 置換後のテキストを収める矩形を取得または設定します。 |
| [setReplaceAdjustmentAction](#setReplaceAdjustmentAction-int-) | テキストフラグメントの置換後に実行されるアクションを設定します（短くするため）。 |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | テキスト置換操作が適用されるスコープを設定します。 |
| [setRightAdjustment](#setRightAdjustment-double-) | TextReplaceOptions を使用する際に置換されたテキストの右位置調整を設定します: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### TextReplaceOptions {#TextReplaceOptions--}
```
public TextReplaceOptions()
```

デフォルトの調整とスコープ（ReplaceAdjustment.None と Scope.REPLACE_FIRST）用に {@code TextReplaceOptions} オブジェクトの新しいインスタンスを初期化します。

### TextReplaceOptions {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int adjustment)
```

指定された置換後アクション用に {@code TextReplaceOptions} オブジェクトの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 調整 |  | ReplaceAdjustment オブジェクトです。 @see ReplaceAdjustment |

### TextReplaceOptions {#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-}
デフォルトの調整とスコープ（ReplaceAdjustment.None と Scope.REPLACE_FIRST）用に {@code TextReplaceOptions} オブジェクトの新しいインスタンスを初期化します。

### TextReplaceOptions {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
デフォルトの調整とスコープ（ReplaceAdjustment.None と Scope.REPLACE_FIRST）用に {@code TextReplaceOptions} オブジェクトの新しいインスタンスを初期化します。

### getAdjustmentNewLineSpacing {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```

置換調整が強制的に新しいテキスト行を作成する場合に使用される行間の値を取得または設定します。期待される値は置換されたテキストのフォントサイズの倍率です。デフォルトは 1.2 です。

**Returns:**
double 値

### getFontSizeAdjustmentAction {#getFontSizeAdjustmentAction--}
```
public final TextReplaceOptions.FontSizeAdjustment getFontSizeAdjustmentAction()
```

{@code TextReplaceOptions.Rectangle}（{@link #getRectangle}/{@link #setRectangle(Rectangle)}）で定義された境界内に収まるようにフォントサイズを調整するポリシーを取得または設定します。

**Returns:**
FontSizeAdjustment 要素

### getLeftAdjustment {#getLeftAdjustment--}
```
public final double getLeftAdjustment()
```

TextReplaceOptions を使用する際に置換されたテキストの左位置調整を取得します: - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
double 値

### getRectangle {#getRectangle--}
```
public final Rectangle getRectangle()
```

置換後のテキストを収める矩形を取得または設定します。

**Returns:**
矩形インスタンス

### getReplaceAdjustmentAction {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```

テキストフラグメントの置換後に実行されるアクションを取得します（短くするため）。

**Returns:**
ReplaceAdjustment 要素 @see ReplaceAdjustment

### getReplaceScope {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```

テキスト置換操作が適用されるスコープを取得します。

**Returns:**
int 値 @see Scope

### getRightAdjustment {#getRightAdjustment--}
```
public final double getRightAdjustment()
```

TextReplaceOptions を使用する際に置換されたテキストの右位置調整を設定または取得します: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
double 値

### isIgnoreParagraphs {#isIgnoreParagraphs--}
```
public final boolean isIgnoreParagraphs()
```

テキスト置換後にページ上のテキストを調整する際、個別の段落を無視するかどうかを示す値を取得または設定します。

**Returns:**
boolean 値

### setAdjustmentNewLineSpacing {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```

置換調整が強制的に新しいテキスト行を作成する場合に使用される行間の値を取得または設定します。期待される値は置換されたテキストのフォントサイズの倍率です。デフォルトは 1.2 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setFontSizeAdjustmentAction {#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-}
TextReplaceOptions.Rectangle（getRectangle() / setRectangle(Rectangle)）で定義された境界内に収まるようにフォントサイズを調整するポリシーを取得または設定します。

### setIgnoreParagraphs {#setIgnoreParagraphs-boolean-}
```
public final void setIgnoreParagraphs(boolean value)
```

テキスト置換後にページ上のテキストを調整する際、個別の段落を無視するかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setLeftAdjustment {#setLeftAdjustment-double-}
```
public final void setLeftAdjustment(double value)
```

TextReplaceOptions を使用する際に置換されたテキストの左位置調整を設定または取得します: - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
置換後のテキストを収める矩形を取得または設定します。

### setReplaceAdjustmentAction {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```

テキストフラグメントの置換後に実行されるアクションを設定します（短くするため）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ReplaceAdjustment 要素 @see ReplaceAdjustment |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
テキスト置換操作が適用されるスコープを設定します。

### setRightAdjustment {#setRightAdjustment-double-}
```
public final void setRightAdjustment(double value)
```

TextReplaceOptions を使用する際に置換されたテキストの右位置調整を設定します: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |
