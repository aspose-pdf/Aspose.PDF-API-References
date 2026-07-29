---
title: "XslFoLoadOptions"
linktitle: "XslFoLoadOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "XSL-FO ファイルを PDF ドキュメントに読み込む/インポートするためのオプションを表します。"
type: docs
weight: 5780
url: /ja/java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.XmlLoadOptions, com.aspose.pdf.XslFoLoadOptions

```
public final class XslFoLoadOptions extends XmlLoadOptions
```

XSL-FO ファイルを PDF ドキュメントに読み込む/インポートするためのオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XslFoLoadOptions](#XslFoLoadOptions--) | xsl データなしで {@code XslFoLoadOptions} オブジェクトを作成します。 |
| [XslFoLoadOptions](#XslFoLoadOptions-java.io.InputStream-) | xsl データなしで {@code XslFoLoadOptions} オブジェクトを作成します。 |
| [XslFoLoadOptions](#XslFoLoadOptions-java.lang.String-) | xsl データなしで {@code XslFoLoadOptions} オブジェクトを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBasePath](#getBasePath--) | 読み込まれた SVG ファイルで参照されている外部リソース（存在する場合）への相対パスを検索する基礎パス/URL。 |
| [getParsingErrorsHandlingType](#getParsingErrorsHandlingType--) | ソース XSLFO ドキュメントには書式エラーが含まれる可能性があります。この列挙型はそのエラーの処理方法として考えられる戦略を列挙します。 |
| [setBasePath](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType](#setParsingErrorsHandlingType-int-) | ソース XSLFO ドキュメントには書式エラーが含まれる可能性があります。この列挙型はそのエラーの処理方法として考えられる戦略を列挙します。 |

### XslFoLoadOptions {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```

xsl データなしで {@code XslFoLoadOptions} オブジェクトを作成します。

### XslFoLoadOptions {#XslFoLoadOptions-java.io.InputStream-}
xsl データなしで {@code XslFoLoadOptions} オブジェクトを作成します。

### XslFoLoadOptions {#XslFoLoadOptions-java.lang.String-}
xsl データなしで {@code XslFoLoadOptions} オブジェクトを作成します。

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

読み込まれた SVG ファイルで参照されている外部リソース（存在する場合）への相対パスを検索する基礎パス/URL。

**Returns:**
文字列

### getParsingErrorsHandlingType {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```

ソース XSLFO ドキュメントには書式エラーが含まれる可能性があります。この列挙型はそのエラーの処理方法として考えられる戦略を列挙します。

**Returns:**
ParsingErrorsHandlingTypes 要素 @see ParsingErrorsHandlingTypes

### setBasePath {#setBasePath-java.lang.String-}


### setParsingErrorsHandlingType {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```

ソース XSLFO ドキュメントには書式エラーが含まれる可能性があります。この列挙型はそのエラーの処理方法として考えられる戦略を列挙します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| parsingErrorsHandlingType |  | ParsingErrorsHandlingTypes 要素 @see ParsingErrorsHandlingTypes |
