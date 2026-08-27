---
title: "ToUnicodeProcessingRules"
linktitle: "ToUnicodeProcessingRules"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは、Adobe Preflight エラー \\\"Text cannot be mapped to Unicode\\\" を解決するために使用できるルールを説明します。"
type: docs
weight: 5380
url: /ja/java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ToUnicodeProcessingRules

```
public class ToUnicodeProcessingRules extends Object
```

このクラスは、Adobe Preflight エラー "Text cannot be mapped to Unicode" を解決するために使用できる規則を記述します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules--) | {@link ToUnicodeProcessingRules} クラスの新しいインスタンスを初期化します。 |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-) | CMap 名からスペースを削除する指定オプションを使用して、{@link ToUnicodeProcessingRules} クラスの新しいインスタンスを初期化します。 |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-boolean-) | 指定されたオプションで {@link ToUnicodeProcessingRules} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMapNonLinkedSymbolsOnSpace](#getMapNonLinkedSymbolsOnSpace--) | 一部のフォントは特定のテキスト記号の Unicode 情報を提供しません。この情報欠如によりエラー \"Text cannot be mapped to Unicode\" が発生します。このフラグを使用して、リンクされていない記号を Unicode の \"space\"（コード 32）にマップします。 |
| [getRemoveSpacesFromCMapNames](#getRemoveSpacesFromCMapNames--) | 一部のフォントは名前にスペースを含む ToUnicode 文字コードマップを持っています。これらのスペースが Unicode テキストマッピングでエラーを引き起こす可能性があります。このフラグは ToUnicode 文字コードマップの名前からスペースを削除するよう指示します。デフォルトは false です。 |
| [setMapNonLinkedSymbolsOnSpace](#setMapNonLinkedSymbolsOnSpace-boolean-) | 一部のフォントは特定のテキスト記号の Unicode 情報を提供しません。この情報欠如によりエラー \"Text cannot be mapped to Unicode\" が発生します。このフラグを使用して、リンクされていない記号を Unicode の \"space\"（コード 32）にマップします。 |
| [setRemoveSpacesFromCMapNames](#setRemoveSpacesFromCMapNames-boolean-) | 一部のフォントは名前にスペースを含む ToUnicode 文字コードマップを持っています。これらのスペースが Unicode テキストマッピングでエラーを引き起こす可能性があります。このフラグは ToUnicode 文字コードマップの名前からスペースを削除するよう指示します。デフォルトは false です。 |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```

{@link ToUnicodeProcessingRules} クラスの新しいインスタンスを初期化します。

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```

CMap 名からスペースを削除する指定オプションを使用して、{@link ToUnicodeProcessingRules} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| removeSpaces |  | CMap 名からスペースを削除するかどうかを示すブール値です。 |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```

指定されたオプションで {@link ToUnicodeProcessingRules} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| removeSpaces |  | CMap 名からスペースを削除すべきかどうかを示します。 |
| mapNonLinkedUnicodesOnSpace |  | リンクされていない Unicode 記号をスペースにマップすべきかどうかを示します。 |

### getMapNonLinkedSymbolsOnSpace {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```

一部のフォントは特定のテキスト記号の Unicode 情報を提供しません。この情報欠如によりエラー \"Text cannot be mapped to Unicode\" が発生します。このフラグを使用して、リンクされていない記号を Unicode の \"space\"（コード 32）にマップします。

**Returns:**
ブール値

### getRemoveSpacesFromCMapNames {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```

一部のフォントは名前にスペースを含む ToUnicode 文字コードマップを持っています。これらのスペースが Unicode テキストマッピングでエラーを引き起こす可能性があります。このフラグは ToUnicode 文字コードマップの名前からスペースを削除するよう指示します。デフォルトは false です。

**Returns:**
ブール値

### setMapNonLinkedSymbolsOnSpace {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```

一部のフォントは特定のテキスト記号の Unicode 情報を提供しません。この情報欠如によりエラー \"Text cannot be mapped to Unicode\" が発生します。このフラグを使用して、リンクされていない記号を Unicode の \"space\"（コード 32）にマップします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRemoveSpacesFromCMapNames {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```

一部のフォントは名前にスペースを含む ToUnicode 文字コードマップを持っています。これらのスペースが Unicode テキストマッピングでエラーを引き起こす可能性があります。このフラグは ToUnicode 文字コードマップの名前からスペースを削除するよう指示します。デフォルトは false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
