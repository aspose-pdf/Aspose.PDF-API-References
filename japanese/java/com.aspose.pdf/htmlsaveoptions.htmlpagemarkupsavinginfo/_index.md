---
title: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "HtmlSaveOptions の SplitToPages プロパティが設定されている場合、PDF から HTML への変換中に複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このクラスはその集合を表します。"
type: docs
weight: 2100
url: /ja/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo

```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo extends Object
```

HtmlSaveOptions の SplitToPages プロパティが有効な場合、PDFからHTMLへの変換中に複数のHTMLファイル（変換されたページごとに1つのHTMLファイル）が作成されます。このクラスは、PDFからHTMLへの変換中に1つのHTMLページのマークアップをカスタム保存することに関連するデータの集合を表します

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getContentStream](#getContentStream--) | コンバータによって設定されます。保存された HTML をストリームとして表します。 |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | コンバータによって設定されます。SplitToPages プロパティが設定されている場合、変換中に複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このプロパティは保存された HTML ページファイルの順序番号を含みます。このプロパティはカスタムコードのロジックで HTML ページの処理方法や保存場所を決定するために使用できます。ページ分割がオフになっている場合、この値は常に '1' を含み、なぜならその場合、ソース文書全体に対して 1 つの大きな HTML ページが生成されるからです。 |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | コンバータによって設定されます。SplitToPages プロパティが設定されている場合、変換中に複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このプロパティはカスタムコードに対し、元の PDF のどのページから保存された HTML マークアップが作成されたかを示します。元のページ番号が不明であるか SplitOnPages=false の場合、このプロパティは常に '0' を含み、コンバータが提供された HTML マークアップファイルに対して正確な元 PDF のページ番号を供給できないことを示します。 |
| [getSupposedFileName](#getSupposedFileName--) | コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定ファイル名です。カスタムコードでコンテンツの処理方法や保存場所を決定する際に使用できます。 |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | 必要に応じてカスタムコードで設定する必要があります。このフラグは、何らかの理由で提供された HTML マークアップをカスタムコードではなく、コンバータの標準的な方法でコンバータ自身のコードで処理すべき場合、カスタムコードで \"true\" に設定しなければなりません。したがって、カスタムコードでこのフラグを設定すると、カスタムコードが参照ファイルを処理せず、コンバータが自ら処理することを意味します。 |
| [setContentStream](#setContentStream-java.io.InputStream-) | コンバータによって設定されます。保存された HTML をストリームとして表します。 |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | 必要に応じてカスタムコードで設定する必要があります。このフラグは、何らかの理由で提供された HTML マークアップをカスタムコードではなく、コンバータの標準的な方法でコンバータ自身のコードで処理すべき場合、カスタムコードで \"true\" に設定しなければなりません。したがって、カスタムコードでこのフラグを設定すると、カスタムコードが参照ファイルを処理せず、コンバータが自ら処理することを意味します。 |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | コンバータによって設定されます。SplitToPages プロパティが設定されている場合、変換中に複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このプロパティは保存された HTML ページファイルの順序番号を含みます。このプロパティはカスタムコードのロジックで HTML ページの処理方法や保存場所を決定するために使用できます。ページ分割がオフになっている場合、この値は常に '1' を含み、なぜならその場合、ソース文書全体に対して 1 つの大きな HTML ページが生成されるからです。 |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | コンバータによって設定されます。SplitToPages プロパティが設定されている場合、変換中に複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このプロパティはカスタムコードに対し、元の PDF のどのページから保存された HTML マークアップが作成されたかを示します。元のページ番号が不明であるか SplitOnPages=false の場合、このプロパティは常に '0' を含み、コンバータが提供された HTML マークアップファイルに対して正確な元 PDF のページ番号を供給できないことを示します。 |
| [setSupposedFileName](#setSupposedFileName-java.lang.String-) | コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定ファイル名です。カスタムコードでコンテンツの処理方法や保存場所を決定する際に使用できます。 |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

コンバータによって設定されます。保存された HTML をストリームとして表します。

**Returns:**
InputStream インスタンス

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

コンバータによって設定されます。SplitToPages プロパティが設定されている場合、変換中に複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このプロパティは保存された HTML ページファイルの順序番号を含みます。このプロパティはカスタムコードのロジックで HTML ページの処理方法や保存場所を決定するために使用できます。ページ分割がオフになっている場合、この値は常に '1' を含み、なぜならその場合、ソース文書全体に対して 1 つの大きな HTML ページが生成されるからです。

**Returns:**
int 値です。

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

コンバータによって設定されます。SplitToPages プロパティが設定されている場合、変換中に複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このプロパティはカスタムコードに対し、元の PDF のどのページから保存された HTML マークアップが作成されたかを示します。元のページ番号が不明であるか SplitOnPages=false の場合、このプロパティは常に '0' を含み、コンバータが提供された HTML マークアップファイルに対して正確な元 PDF のページ番号を供給できないことを示します。

**Returns:**
int 値です。

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定ファイル名です。カスタムコードでコンテンツの処理方法や保存場所を決定する際に使用できます。

**Returns:**
文字列値

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

必要に応じてカスタムコードで設定する必要があります。このフラグは、何らかの理由で提供された HTML マークアップをカスタムコードではなく、コンバータの標準的な方法でコンバータ自身のコードで処理すべき場合、カスタムコードで \"true\" に設定しなければなりません。したがって、カスタムコードでこのフラグを設定すると、カスタムコードが参照ファイルを処理せず、コンバータが自ら処理することを意味します。

**Returns:**
ブール値

### setContentStream {#setContentStream-java.io.InputStream-}
コンバータによって設定されます。保存された HTML をストリームとして表します。

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

必要に応じてカスタムコードで設定する必要があります。このフラグは、何らかの理由で提供された HTML マークアップをカスタムコードではなく、コンバータの標準的な方法でコンバータ自身のコードで処理すべき場合、カスタムコードで \"true\" に設定しなければなりません。したがって、カスタムコードでこのフラグを設定すると、カスタムコードが参照ファイルを処理せず、コンバータが自ら処理することを意味します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| customProcessingCancelled |  | ブール値 |

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

コンバータによって設定されます。SplitToPages プロパティが設定されている場合、変換中に複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このプロパティは保存された HTML ページファイルの順序番号を含みます。このプロパティはカスタムコードのロジックで HTML ページの処理方法や保存場所を決定するために使用できます。ページ分割がオフになっている場合、この値は常に '1' を含み、なぜならその場合、ソース文書全体に対して 1 つの大きな HTML ページが生成されるからです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlHostPageNumber |  | int 値です。 |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

コンバータによって設定されます。SplitToPages プロパティが設定されている場合、変換中に複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このプロパティはカスタムコードに対し、元の PDF のどのページから保存された HTML マークアップが作成されたかを示します。元のページ番号が不明であるか SplitOnPages=false の場合、このプロパティは常に '0' を含み、コンバータが提供された HTML マークアップファイルに対して正確な元 PDF のページ番号を供給できないことを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pdfHostPageNumber |  | int 値です。 |

### setSupposedFileName {#setSupposedFileName-java.lang.String-}
コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定ファイル名です。カスタムコードでコンテンツの処理方法や保存場所を決定する際に使用できます。
