---
title: "HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "HTML ファイルを PDF 文書に読み込み/インポートするためのオプションを表します。"
type: docs
weight: 1960
url: /ja/java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.HtmlLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.HtmlLoadOptions

```
public final class HtmlLoadOptions extends LoadOptions
```

HTML ファイルを PDF 文書に読み込み/インポートするためのオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HtmlLoadOptions](#HtmlLoadOptions--) | 空のベースパスで html を PDF ドキュメントに変換するためのロードオプションを作成します。 |
| [HtmlLoadOptions](#HtmlLoadOptions-java.lang.String-) | 空のベースパスで html を PDF ドキュメントに変換するためのロードオプションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBasePath](#getBasePath--) | html ファイルのベースパス/URL。 |
| [getCustomLoaderOfExternalResources](#getCustomLoaderOfExternalResources--) | 場合によっては、画像や CSS などの外部リソースの内部ローダーの使用を回避し、要求されたリソースを取得するカスタムメソッドを提供する必要があります。例えば、クラウド上で Aspose.PDF を使用する際には参照ファイルへの直接アクセスが不可能です。そのような場合、特別なメソッドに配置した顧客コードを使用し、そのメソッドを参照するデリゲートをこの属性に割り当てる必要があります。 |
| [getHtmlMediaType](#getHtmlMediaType--) | レンダリング時に使用される可能なメディアタイプを取得または設定します。 |
| [getInputEncoding](#getInputEncoding--) | 解析時にこのドキュメントで使用されるエンコーディングを指定する属性を取得します。この属性が null の場合、エンコーディングはドキュメントの文字セット属性から決定されます。 |
| [getPageInfo](#getPageInfo--) | ドキュメントのページ情報を取得します |
| [getPageLayoutOption](#getPageLayoutOption--) | レイアウトオプションを取得または設定します。 |
| [isEmbedFonts](#isEmbedFonts--) | 結果文書へのフォント埋め込みを取得または設定します |
| [isPriorityCssPageRule](#isPriorityCssPageRule--) | CSSで定義された @page ルールが PageInfo で定義された値を上書きすることを指定するフラグを取得または設定します。 |
| [isRenderToSinglePage](#isRenderToSinglePage--) | 文書全体を単一ページにレンダリングするかどうかを取得または設定します |
| [setCustomLoaderOfExternalResources](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | 場合によっては、画像や CSS などの外部リソースの内部ローダーの使用を回避し、要求されたリソースを取得するカスタムメソッドを提供する必要があります。 |
| [setEmbedFonts](#setEmbedFonts-boolean-) | 結果文書へのフォント埋め込みを取得または設定します |
| [setHtmlMediaType](#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-) | レンダリング時に使用される可能なメディアタイプを取得または設定します。 |
| [setInputEncoding](#setInputEncoding-java.lang.String-) | 解析時にこの文書で使用されるエンコーディングを指定する属性を設定します。この属性が null の場合、エンコーディングは文書の文字セット属性から決定されます。 |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | 文書のページ情報を設定します |
| [setPageLayoutOption](#setPageLayoutOption-int-) | レイアウトオプションを取得または設定します。 |
| [setPriorityCssPageRule](#setPriorityCssPageRule-boolean-) | CSSで定義された @page ルールが PageInfo で定義された値を上書きすることを指定するフラグを取得または設定します。 |
| [setRenderToSinglePage](#setRenderToSinglePage-boolean-) | 文書全体を単一ページにレンダリングするかどうかを取得または設定します |

### HtmlLoadOptions {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```

空のベースパスで html を PDF ドキュメントに変換するためのロードオプションを作成します。

### HtmlLoadOptions {#HtmlLoadOptions-java.lang.String-}
空のベースパスで html を PDF ドキュメントに変換するためのロードオプションを作成します。

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

html ファイルのベースパス/URL。

**Returns:**
文字列値

### getCustomLoaderOfExternalResources {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```

場合によっては、画像や CSS などの外部リソースの内部ローダーの使用を回避し、要求されたリソースを取得するカスタムメソッドを提供する必要があります。例えば、クラウド上で Aspose.PDF を使用する際には参照ファイルへの直接アクセスが不可能です。そのような場合、特別なメソッドに配置した顧客コードを使用し、そのメソッドを参照するデリゲートをこの属性に割り当てる必要があります。

**Returns:**
ResourceLoadingStrategy インスタンス

### getHtmlMediaType {#getHtmlMediaType--}
```
public HtmlMediaType getHtmlMediaType()
```

レンダリング時に使用される可能なメディアタイプを取得または設定します。

**Returns:**
HtmlMediaType 要素

### getInputEncoding {#getInputEncoding--}
```
public String getInputEncoding()
```

解析時にこのドキュメントで使用されるエンコーディングを指定する属性を取得します。この属性が null の場合、エンコーディングはドキュメントの文字セット属性から決定されます。

**Returns:**
文字列値

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

ドキュメントのページ情報を取得します

**Returns:**
ページ情報

### getPageLayoutOption {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```

レイアウトオプションを取得または設定します。

**Returns:**
HtmlPageLayoutOption 要素 @see HtmlPageLayoutOption

### isEmbedFonts {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```

結果文書へのフォント埋め込みを取得または設定します

**Returns:**
ブール値

### isPriorityCssPageRule {#isPriorityCssPageRule--}
```
public final boolean isPriorityCssPageRule()
```

CSSで定義された @page ルールが PageInfo で定義された値を上書きすることを指定するフラグを取得または設定します。

**Returns:**
ブール値

### isRenderToSinglePage {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```

文書全体を単一ページにレンダリングするかどうかを取得または設定します

**Returns:**
ブール値

### setCustomLoaderOfExternalResources {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
場合によっては、画像や CSS などの外部リソースの内部ローダーの使用を回避し、要求されたリソースを取得するカスタムメソッドを提供する必要があります。

### setEmbedFonts {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```

結果文書へのフォント埋め込みを取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHtmlMediaType {#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-}
レンダリング時に使用される可能なメディアタイプを取得または設定します。

### setInputEncoding {#setInputEncoding-java.lang.String-}
解析時にこの文書で使用されるエンコーディングを指定する属性を設定します。この属性が null の場合、エンコーディングは文書の文字セット属性から決定されます。

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
文書のページ情報を設定します

### setPageLayoutOption {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```

レイアウトオプションを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | HtmlPageLayoutOption 要素 @see HtmlPageLayoutOption |

### setPriorityCssPageRule {#setPriorityCssPageRule-boolean-}
```
public final void setPriorityCssPageRule(boolean value)
```

CSSで定義された @page ルールが PageInfo で定義された値を上書きすることを指定するフラグを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRenderToSinglePage {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```

文書全体を単一ページにレンダリングするかどうかを取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
