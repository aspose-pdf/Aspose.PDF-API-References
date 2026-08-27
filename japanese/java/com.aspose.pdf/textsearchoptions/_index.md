---
title: "TextSearchOptions"
linktitle: "TextSearchOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキスト検索オプションを表します"
type: docs
weight: 5290
url: /ja/java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextSearchOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextSearchOptions

```
public final class TextSearchOptions extends TextOptions
```

テキスト検索オプションを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextSearchOptions](#TextSearchOptions-boolean-) | 新しい {@code TextSearchOptions} オブジェクトのインスタンスを初期化します。正規表現の使用モードを指定します。 |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-) | 新しい TextSearchOptions オブジェクトのインスタンスを初期化します。検索対象テキストを区切る矩形を指定します。 |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | 新しい TextSearchOptions オブジェクトのインスタンスを初期化します。検索対象テキストを区切る矩形と正規表現の使用モードを指定します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getExcludeRectangles](#getExcludeRectangles--) | 検索からテキストを除外する境界を持つ矩形を取得または設定します。 |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | テキスト（フラグメント）吸収器がフォント欠如に関連するエラーを無視するかどうかを取得または設定します。true - フォントが欠如しているエラーを無視することを意味します。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。false（既定） - フォント欠如エラーが例外をスローして処理を終了させます。 |
| [getLimitToPageBounds](#getLimitToPageBounds--) | テキストがページ境界内で検索されるかどうかを取得します。 |
| [getLogTextExtractionErrors](#getLogTextExtractionErrors--) | テキスト（フラグメント）吸収器でテキスト抽出（デコード）エラーが記録されるかどうかを取得または設定します。true - テキスト抽出（デコード）エラーが記録されることを意味します。パフォーマンスが低下する可能性があります。false（既定） - エラーは記録されません。 |
| [getRectangle](#getRectangle--) | 検索対象テキストを囲む矩形を取得します。テキスト抽出やテキスト置換領域を区切る必要がある場合にこのプロパティを使用できます。 |
| [getSearchForTextRelatedGraphics](#getSearchForTextRelatedGraphics--) | テキスト検索中にテキスト関連のグラフィック（下線、背景など）を検索できるかどうかの値を取得または設定します。true - テキスト関連のグラフィックの検索が実行されます（既定値）。false - ソース文書に存在する可能性のあるグラフィック要素は無視されます。パフォーマンス上の問題がある場合や、下線・背景・クリッピングを処理する必要がない場合に設定してください。 |
| [getStoredGraphicElementsMaxCount](#getStoredGraphicElementsMaxCount--) | ページ上でテキスト関連のグラフィック（下線、背景など）を検索する要素数の上限を取得します。既定は 250 です。パフォーマンスに問題がある場合は小さい値に設定し、いくつかのグラフィック要素が見つからない場合は大きい値を試してください。 |
| [getUseFontEngineEncoding](#getUseFontEngineEncoding--) | テキスト検索にフォントエンジンのエンコーディングを使用するかどうかを取得します。true - フォントエンジンのエンコーディングが使用されます（文書のエンコーディングが不完全で検索が失敗する場合に試してください）。false - 文書のフォントエンコーディングが使用されます（既定値）。 |
| [isDotallMode](#isDotallMode--) | <p> ドットオールモードでは、式 <tt>.</tt> は改行文字を含む任意の文字にマッチします。既定ではこの式は改行文字にマッチしません。 |
| [isIgnoreShadowText](#isIgnoreShadowText--) | 検索時に通常テキストの影として表現されるテキストフラグメントを無視するかどうかを取得または設定します。true - 影のテキストが見つからないことを意味します（検索結果が近接位置で重複フラグメントを返す場合に試してください）。false - 影のテキストも通常テキストと同様に見つかります（既定値）。 |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | 正規表現が使用されているかどうかを示します。 |
| [isSearchInAnnotations](#isSearchInAnnotations--) | アノテーション内のテキスト検索を許可するかどうかの値を取得または設定します。true - アノテーション内のテキストが検索されます。false - アノテーション内のテキストは TextFragmentAbsorber で解析されません。 |
| [setDotallMode](#setDotallMode-boolean-) | ドットオールモードを有効にします。<p> ドットオールモードでは、式 <tt>.</tt> は改行文字を含む任意の文字にマッチします。既定ではこの式は改行文字にマッチしません。 |
| [setExcludeRectangles](#setExcludeRectangles-com.aspose.pdf.Rectangle:A-) | 検索からテキストを除外する境界を持つ矩形を取得または設定します。 |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | テキスト（フラグメント）吸収器がフォント欠如に関連するエラーを無視するかどうかを取得または設定します。true - フォントが欠如しているエラーを無視することを意味します。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。false（既定） - フォント欠如エラーが例外をスローして処理を終了させます。 |
| [setIgnoreShadowText](#setIgnoreShadowText-boolean-) | 検索時に通常テキストの影として表現されるテキストフラグメントを無視するかどうかを取得または設定します。true - 影のテキストが見つからないことを意味します（検索結果が近接位置で重複フラグメントを返す場合に試してください）。false - 影のテキストも通常テキストと同様に見つかります（既定値）。 |
| [setLimitToPageBounds](#setLimitToPageBounds-boolean-) | テキストがページ境界内で検索されるかどうかを設定します。 |
| [setLogTextExtractionErrors](#setLogTextExtractionErrors-boolean-) | テキスト（フラグメント）吸収器でテキスト抽出（デコード）エラーが記録されるかどうかを取得または設定します。true - テキスト抽出（デコード）エラーが記録されることを意味します。パフォーマンスが低下する可能性があります。false（既定） - エラーは記録されません。 |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | 検索対象テキストを囲む矩形を設定します。テキスト抽出やテキスト置換領域を区切る必要がある場合にこのプロパティを使用できます。 |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | 正規表現が使用されているかどうかを示します。 |
| [setSearchForTextRelatedGraphics](#setSearchForTextRelatedGraphics-boolean-) | テキスト検索中にテキスト関連のグラフィック（下線、背景など）を検索できるかどうかの値を取得または設定します。true - テキスト関連のグラフィックの検索が実行されます（既定値）。false - ソース文書に存在する可能性のあるグラフィック要素は無視されます。パフォーマンス上の問題がある場合や、下線・背景・クリッピングを処理する必要がない場合に設定してください。 |
| [setSearchInAnnotations](#setSearchInAnnotations-boolean-) | アノテーション内のテキスト検索を許可するかどうかの値を取得または設定します。true - アノテーション内のテキストが検索されます。false - アノテーション内のテキストは TextFragmentAbsorber で解析されません。 |
| [setStoredGraphicElementsMaxCount](#setStoredGraphicElementsMaxCount-int-) | ページ上でテキスト関連のグラフィック（下線、背景など）を検索する要素数の上限を設定します。既定は 250 です。パフォーマンスに問題がある場合は小さい値に設定し、いくつかのグラフィック要素が見つからない場合は大きい値を試してください。 |
| [setUseFontEngineEncoding](#setUseFontEngineEncoding-boolean-) | テキスト検索にフォントエンジンのエンコーディングを使用するかどうかを設定します。true - フォントエンジンのエンコーディングが使用されます（文書のエンコーディングが不完全で検索が失敗する場合に試してください）。false - 文書のフォントエンコーディングが使用されます（既定値）。 |

### TextSearchOptions {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```

新しい {@code TextSearchOptions} オブジェクトのインスタンスを初期化します。正規表現の使用モードを指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isRegularExpressionUsed |  | 正規表現が使用されていることを示す値です。 |

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-}
新しい TextSearchOptions オブジェクトのインスタンスを初期化します。検索対象テキストを区切る矩形を指定します。

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
新しい TextSearchOptions オブジェクトのインスタンスを初期化します。検索対象テキストを区切る矩形と正規表現の使用モードを指定します。

### getExcludeRectangles {#getExcludeRectangles--}
```
public final Rectangle [] getExcludeRectangles()
```

検索からテキストを除外する境界を持つ矩形を取得または設定します。

**Returns:**
Rectangle インスタンスの配列

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

テキスト（フラグメント）吸収器がフォント欠如に関連するエラーを無視するかどうかを取得または設定します。true - フォントが欠如しているエラーを無視することを意味します。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。false（既定） - フォント欠如エラーが例外をスローして処理を終了させます。

**Returns:**
ブール値

### getLimitToPageBounds {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```

テキストがページ境界内で検索されるかどうかを取得します。

**Returns:**
ブール値

### getLogTextExtractionErrors {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```

テキスト（フラグメント）吸収器でテキスト抽出（デコード）エラーが記録されるかどうかを取得または設定します。true - テキスト抽出（デコード）エラーが記録されることを意味します。パフォーマンスが低下する可能性があります。false（既定） - エラーは記録されません。

**Returns:**
ブール値

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

検索対象テキストを囲む矩形を取得します。テキスト抽出やテキスト置換領域を区切る必要がある場合にこのプロパティを使用できます。

**Returns:**
矩形の値

### getSearchForTextRelatedGraphics {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```

テキスト検索中にテキスト関連のグラフィック（下線、背景など）を検索できるかどうかの値を取得または設定します。true - テキスト関連のグラフィックの検索が実行されます（既定値）。false - ソース文書に存在する可能性のあるグラフィック要素は無視されます。パフォーマンス上の問題がある場合や、下線・背景・クリッピングを処理する必要がない場合に設定してください。

**Returns:**
ブール値

### getStoredGraphicElementsMaxCount {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```

ページ上でテキスト関連のグラフィック（下線、背景など）を検索する要素数の上限を取得します。既定は 250 です。パフォーマンスに問題がある場合は小さい値に設定し、いくつかのグラフィック要素が見つからない場合は大きい値を試してください。

**Returns:**
int 値です。

### getUseFontEngineEncoding {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```

テキスト検索にフォントエンジンのエンコーディングを使用するかどうかを取得します。true - フォントエンジンのエンコーディングが使用されます（文書のエンコーディングが不完全で検索が失敗する場合に試してください）。false - 文書のフォントエンコーディングが使用されます（既定値）。

**Returns:**
ブール値

### isDotallMode {#isDotallMode--}
```
public static boolean isDotallMode()
```

<p> ドットオールモードでは、式 <tt>.</tt> は改行文字を含む任意の文字にマッチします。既定ではこの式は改行文字にマッチしません。

**Returns:**
ブール値

### isIgnoreShadowText {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```

検索時に通常テキストの影として表現されるテキストフラグメントを無視するかどうかを取得または設定します。true - 影のテキストが見つからないことを意味します（検索結果が近接位置で重複フラグメントを返す場合に試してください）。false - 影のテキストも通常テキストと同様に見つかります（既定値）。

**Returns:**
ブール値

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

正規表現が使用されているかどうかを示します。

**Returns:**
ブール値

### isSearchInAnnotations {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```

アノテーション内のテキスト検索を許可するかどうかの値を取得または設定します。true - アノテーション内のテキストが検索されます。false - アノテーション内のテキストは TextFragmentAbsorber で解析されません。

**Returns:**
ブール値

### setDotallMode {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```

ドットオールモードを有効にします。<p> ドットオールモードでは、式 <tt>.</tt> は改行文字を含む任意の文字にマッチします。既定ではこの式は改行文字にマッチしません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dotallMode |  | ブール値 |

### setExcludeRectangles {#setExcludeRectangles-com.aspose.pdf.Rectangle:A-}
検索からテキストを除外する境界を持つ矩形を取得または設定します。

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

テキスト（フラグメント）吸収器がフォント欠如に関連するエラーを無視するかどうかを取得または設定します。true - フォントが欠如しているエラーを無視することを意味します。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。false（既定） - フォント欠如エラーが例外をスローして処理を終了させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setIgnoreShadowText {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```

検索時に通常テキストの影として表現されるテキストフラグメントを無視するかどうかを取得または設定します。true - 影のテキストが見つからないことを意味します（検索結果が近接位置で重複フラグメントを返す場合に試してください）。false - 影のテキストも通常テキストと同様に見つかります（既定値）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setLimitToPageBounds {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```

テキストがページ境界内で検索されるかどうかを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setLogTextExtractionErrors {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```

テキスト（フラグメント）吸収器でテキスト抽出（デコード）エラーが記録されるかどうかを取得または設定します。true - テキスト抽出（デコード）エラーが記録されることを意味します。パフォーマンスが低下する可能性があります。false（既定） - エラーは記録されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
検索対象テキストを囲む矩形を設定します。テキスト抽出やテキスト置換領域を区切る必要がある場合にこのプロパティを使用できます。

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

正規表現が使用されているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSearchForTextRelatedGraphics {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```

テキスト検索中にテキスト関連のグラフィック（下線、背景など）を検索できるかどうかの値を取得または設定します。true - テキスト関連のグラフィックの検索が実行されます（既定値）。false - ソース文書に存在する可能性のあるグラフィック要素は無視されます。パフォーマンス上の問題がある場合や、下線・背景・クリッピングを処理する必要がない場合に設定してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSearchInAnnotations {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```

アノテーション内のテキスト検索を許可するかどうかの値を取得または設定します。true - アノテーション内のテキストが検索されます。false - アノテーション内のテキストは TextFragmentAbsorber で解析されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setStoredGraphicElementsMaxCount {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```

ページ上でテキスト関連のグラフィック（下線、背景など）を検索する要素数の上限を設定します。既定は 250 です。パフォーマンスに問題がある場合は小さい値に設定し、いくつかのグラフィック要素が見つからない場合は大きい値を試してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setUseFontEngineEncoding {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```

テキスト検索にフォントエンジンのエンコーディングを使用するかどうかを設定します。true - フォントエンジンのエンコーディングが使用されます（文書のエンコーディングが不完全で検索が失敗する場合に試してください）。false - 文書のフォントエンコーディングが使用されます（既定値）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
