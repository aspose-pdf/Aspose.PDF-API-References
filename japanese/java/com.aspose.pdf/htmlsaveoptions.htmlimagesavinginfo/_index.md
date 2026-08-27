---
title: "HtmlSaveOptions.HtmlImageSavingInfo"
linktitle: "HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは、PDFからHTMLへの変換中に外部リソース画像ファイルの保存に関連するデータの集合を表します"
type: docs
weight: 2070
url: /ja/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo, com.aspose.pdf.SaveOptions.ResourceSavingInfo, com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo

```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

このクラスは、PDFからHTMLへの変換中に外部リソース画像ファイルの保存に関連するデータの集合を表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HtmlImageSavingInfo](#HtmlImageSavingInfo--) | HtmlImageSavingInfo の新しいインスタンスを作成します |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | カスタムコードに、生成された HTML ページファイルのセットのどのページに保存された画像が対応するかを伝えます。ページ分割がオフの場合、この値は常に '1' を含みます。なぜならその場合は HTML ページが 1 つだけ生成されるからです。 |
| [getImageType](#getImageType--) | HTML で参照される保存画像のタイプを表します。コンバータによって設定され、カスタムコードで何をすべきか決定する際に使用できます。 |
| [getParentType](#getParentType--) | 保存された画像は HTML 自体に属する場合や、HTML に埋め込まれた SVG から抽出される場合があります。このプロパティは、処理された画像の親のタイプが何であるかをカスタムコードに伝えることができます。コンバータによって設定され、カスタムコードでその画像に対して何をすべきか（例: 画像をどこに保存するか、または親のコンテンツでどのように参照すべきか）を決定する際に使用できます。 |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | カスタムコードに、保存された画像が元の PDF ドキュメントのどのページに対応するかを伝えます。元のドキュメントのすべてのページが保存されない可能性があるため、この値は元の PDF のホストページ番号を示します。何らかの理由で元のページ番号が不明な場合は、常に '1' を返します。 |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | カスタムコードに、生成された HTML ページファイルのセットのどのページに保存された画像が対応するかを伝えます。ページ分割がオフの場合、この値は常に '1' を含みます。なぜならその場合は HTML ページが 1 つだけ生成されるからです。 |
| [setImageType](#setImageType-int-) | HTML で参照される保存画像のタイプを表します。コンバータによって設定され、カスタムコードで何をすべきか決定する際に使用できます。 |
| [setParentType](#setParentType-int-) | 保存された画像は HTML 自体に属する場合や、HTML に埋め込まれた SVG から抽出される場合があります。このプロパティは、処理された画像の親のタイプが何であるかをカスタムコードに伝えることができます。コンバータによって設定され、カスタムコードでその画像に対して何をすべきか（例: 画像をどこに保存するか、または親のコンテンツでどのように参照すべきか）を決定する際に使用できます。 |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | カスタムコードに、保存された画像が元の PDF ドキュメントのどのページに対応するかを伝えます。元のドキュメントのすべてのページが保存されない可能性があるため、この値は元の PDF のホストページ番号を示します。何らかの理由で元のページ番号が不明な場合は、常に '1' を返します。 |

### HtmlImageSavingInfo {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```

HtmlImageSavingInfo の新しいインスタンスを作成します

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

カスタムコードに、生成された HTML ページファイルのセットのどのページに保存された画像が対応するかを伝えます。ページ分割がオフの場合、この値は常に '1' を含みます。なぜならその場合は HTML ページが 1 つだけ生成されるからです。

**Returns:**
int 値です。

### getImageType {#getImageType--}
```
public int getImageType()
```

HTML で参照される保存画像のタイプを表します。コンバータによって設定され、カスタムコードで何をすべきか決定する際に使用できます。

**Returns:**
HtmlImageType 要素 @see HtmlImageType

### getParentType {#getParentType--}
```
public int getParentType()
```

保存された画像は HTML 自体に属する場合や、HTML に埋め込まれた SVG から抽出される場合があります。このプロパティは、処理された画像の親のタイプが何であるかをカスタムコードに伝えることができます。コンバータによって設定され、カスタムコードでその画像に対して何をすべきか（例: 画像をどこに保存するか、または親のコンテンツでどのように参照すべきか）を決定する際に使用できます。

**Returns:**
ImageParentTypes 要素 @see ImageParentTypes

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

カスタムコードに、保存された画像が元の PDF ドキュメントのどのページに対応するかを伝えます。元のドキュメントのすべてのページが保存されない可能性があるため、この値は元の PDF のホストページ番号を示します。何らかの理由で元のページ番号が不明な場合は、常に '1' を返します。

**Returns:**
int 値です。

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

カスタムコードに、生成された HTML ページファイルのセットのどのページに保存された画像が対応するかを伝えます。ページ分割がオフの場合、この値は常に '1' を含みます。なぜならその場合は HTML ページが 1 つだけ生成されるからです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlHostPageNumber |  | int 値です。 |

### setImageType {#setImageType-int-}
```
public void setImageType(int imageType)
```

HTML で参照される保存画像のタイプを表します。コンバータによって設定され、カスタムコードで何をすべきか決定する際に使用できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageType |  | HtmlImageType 要素 @see HtmlImageType |

### setParentType {#setParentType-int-}
```
public void setParentType(int parentType)
```

保存された画像は HTML 自体に属する場合や、HTML に埋め込まれた SVG から抽出される場合があります。このプロパティは、処理された画像の親のタイプが何であるかをカスタムコードに伝えることができます。コンバータによって設定され、カスタムコードでその画像に対して何をすべきか（例: 画像をどこに保存するか、または親のコンテンツでどのように参照すべきか）を決定する際に使用できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| parentType |  | ImageParentTypes 要素 @see ImageParentTypes |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

カスタムコードに、保存された画像が元の PDF ドキュメントのどのページに対応するかを伝えます。元のドキュメントのすべてのページが保存されない可能性があるため、この値は元の PDF のホストページ番号を示します。何らかの理由で元のページ番号が不明な場合は、常に '1' を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pdfHostPageNumber |  | int 値です。 |
