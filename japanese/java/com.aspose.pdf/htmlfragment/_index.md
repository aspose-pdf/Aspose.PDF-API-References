---
title: "HtmlFragment"
linktitle: "HtmlFragment"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "HTML フラグメントを表します。"
type: docs
weight: 1950
url: /ja/java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.HtmlFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class HtmlFragment extends FormattedFragment
```

HTML フラグメントを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HtmlFragment](#HtmlFragment-java.lang.String-) | HtmlFragment クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone](#deepClone--) | HTML フラグメントをクローンします。 |
| [getHtmlLoadOptions](#getHtmlLoadOptions--) | このクラスのインスタンスに HTML をロード（およびレンダリング）するために使用される HtmlLoadOptions を取得します。特定のインスタンスに対して HTML のインポート設定を個別に使用する必要がある場合（例：インポートされた HTML の BasePath を指定したり、外部リソースのローダーを指定したりする場合）に使用してください。パラメーターがデフォルト（null）の場合、標準の HTML ローディングオプションが使用されます。 |
| [getRectangle](#getRectangle--) | HtmlFragment の矩形を取得します |
| [getTextState](#getTextState--) | フォントを取得または設定します |
| [isBreakWords](#isBreakWords--) | 単語の改行を取得または設定します |
| [isParagraphHasMargin](#isParagraphHasMargin--) | 段落がデフォルトの余白を持つかどうかを取得または設定します。余白がない場合は 0 になります |
| [setBreakWords](#setBreakWords-boolean-) | 単語の改行を取得または設定します |
| [setHtmlLoadOptions](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | このクラスのインスタンスに HTML をロード（およびレンダリング）するために使用される HtmlLoadOptions を設定します。特定のインスタンスに対して HTML のインポート設定を個別に使用する必要がある場合（例：インポートされた HTML の BasePath を指定したり、外部リソースのローダーを指定したりする場合）に使用してください。パラメーターがデフォルト（null）の場合、標準の HTML ローディングオプションが使用されます。 |
| [setParagraphHasMargin](#setParagraphHasMargin-boolean-) | 段落がデフォルトの余白を持つかどうかを取得または設定します。余白がない場合は 0 になります |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | フォントを取得または設定します |

### HtmlFragment {#HtmlFragment-java.lang.String-}
HtmlFragment クラスの新しいインスタンスを初期化します。

### deepClone {#deepClone--}
```
public Object deepClone()
```

HTML フラグメントをクローンします。

**Returns:**
クローンされた HTML フラグメントオブジェクトです。

### getHtmlLoadOptions {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```

このクラスのインスタンスに HTML をロード（およびレンダリング）するために使用される HtmlLoadOptions を取得します。特定のインスタンスに対して HTML のインポート設定を個別に使用する必要がある場合（例：インポートされた HTML の BasePath を指定したり、外部リソースのローダーを指定したりする場合）に使用してください。パラメーターがデフォルト（null）の場合、標準の HTML ローディングオプションが使用されます。

**Returns:**
HtmlLoadOptions の値

### getRectangle {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

HtmlFragment の矩形を取得します

**Returns:**
java.awt.geom.Rectangle2D.Float instance

### getTextState {#getTextState--}
```
public TextState getTextState()
```

フォントを取得または設定します

**Returns:**
TextState オブジェクト

### isBreakWords {#isBreakWords--}
```
public final boolean isBreakWords()
```

単語の改行を取得または設定します

**Returns:**
ブール値

### isParagraphHasMargin {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```

段落がデフォルトの余白を持つかどうかを取得または設定します。余白がない場合は 0 になります

**Returns:**
ブール値

### setBreakWords {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```

単語の改行を取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHtmlLoadOptions {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
このクラスのインスタンスに HTML をロード（およびレンダリング）するために使用される HtmlLoadOptions を設定します。特定のインスタンスに対して HTML のインポート設定を個別に使用する必要がある場合（例：インポートされた HTML の BasePath を指定したり、外部リソースのローダーを指定したりする場合）に使用してください。パラメーターがデフォルト（null）の場合、標準の HTML ローディングオプションが使用されます。

### setParagraphHasMargin {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```

段落がデフォルトの余白を持つかどうかを取得または設定します。余白がない場合は 0 になります

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setTextState {#setTextState-com.aspose.pdf.TextState-}
フォントを取得または設定します
