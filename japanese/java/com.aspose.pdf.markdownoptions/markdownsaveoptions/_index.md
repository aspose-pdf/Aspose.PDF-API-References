---
title: "MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Markdown 形式でのドキュメント保存オプションクラスを表します。"
type: docs
weight: 60
url: /ja/java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

Markdown 形式でのドキュメント保存オプションクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | マークダウン形式でドキュメントを保存するためのインスタンスオプションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | マークダウンにコンテンツを抽出する矩形領域を取得または設定します。 |
| [getEmphasisStyle](#getEmphasisStyle--) | 生成されたドキュメントの強調スタイルを取得または設定します。 |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | ベクターグラフィックを抽出すべきかどうかを示すプロパティを取得および設定します。 |
| [getHeadingLevels](#getHeadingLevels--) | フォントサイズ認識ヘッダー戦略で使用する期待される見出しレベルを定義します。このプロパティの値が設定されている場合、ヘッダー認識 {@link HeadingRecognitionStrategy#Heuristic} 戦略が選択され、{@link HeadingRecognitionStrategy#Auto} 戦略が設定されていても、ドキュメントにブックマークが含まれている場合でも適用されます。 |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | 見出し認識戦略を取得または設定します。 |
| [getHeadingStyle](#getHeadingStyle--) | 生成されたドキュメントの見出しスタイルを取得または設定します。 |
| [getLineBreakStyle](#getLineBreakStyle--) | 生成されたドキュメントの改行スタイルを取得または設定します。 |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | 画像などのドキュメントリソースを保存するディレクトリ名を取得および設定します。値が指定されていない場合、画像はマークダウンファイルと同じディレクトリに書き込まれます。これはパスではなく、名前だけです！このディレクトリは、保存されたマークダウンファイルがあるディレクトリ内に自動的に作成されます。 |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | 画像などのドキュメントリソースを保存するディレクトリ名を取得および設定します。このディレクトリは、保存されたマークダウンファイルがあるディレクトリ内に自動的に作成されます。 |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | 下付き文字と上付き文字の変換を許可するかどうかを取得および設定します。この値はデフォルトで true です。 |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | テキストの左側および右側に画像を挿入するために img タグの使用を許可するかどうかを取得および設定します。この場合、マークダウンビューアではテキストが画像の周りに折り返されます。 |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | マークダウンにコンテンツを抽出する矩形領域を取得または設定します。 |
| [setEmphasisStyle](#setEmphasisStyle-int-) | 生成されたドキュメントの強調スタイルを取得または設定します。 |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | ベクターグラフィックを抽出すべきかどうかを示すプロパティを取得および設定します。 |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | フォントサイズ認識ヘッダー戦略で使用する期待される見出しレベルを定義します。このプロパティの値が設定されている場合、ヘッダー認識 {@link HeadingRecognitionStrategy#Heuristic} 戦略が選択され、{@link HeadingRecognitionStrategy#Auto} 戦略が設定されていても、ドキュメントにブックマークが含まれている場合でも適用されます。 |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | 見出し認識戦略を取得または設定します。 |
| [setHeadingStyle](#setHeadingStyle-int-) | 生成されたドキュメントの見出しスタイルを取得または設定します。 |
| [setLineBreakStyle](#setLineBreakStyle-int-) | 生成されたドキュメントの改行スタイルを取得または設定します。 |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | 画像などのドキュメントリソースを保存するディレクトリ名を取得および設定します。値が指定されていない場合、画像はマークダウンファイルと同じディレクトリに書き込まれます。これはパスではなく、名前だけです！このディレクトリは、保存されたマークダウンファイルがあるディレクトリ内に自動的に作成されます。 |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | 画像などのドキュメントリソースを保存するディレクトリ名を取得および設定します。このディレクトリは、保存されたマークダウンファイルがあるディレクトリ内に自動的に作成されます。 |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | 下付き文字と上付き文字の変換を許可するかどうかを取得および設定します。この値はデフォルトで true です。 |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | テキストの左側および右側に画像を挿入するために img タグの使用を許可するかどうかを取得および設定します。この場合、マークダウンビューアではテキストが画像の周りに折り返されます。 |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

マークダウン形式でドキュメントを保存するためのインスタンスオプションを作成します。

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

マークダウンにコンテンツを抽出する矩形領域を取得または設定します。

**Returns:**
矩形インスタンス

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

生成されたドキュメントの強調スタイルを取得または設定します。

**Returns:**
EmphasisStyle 要素

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

ベクターグラフィックを抽出すべきかどうかを示すプロパティを取得および設定します。

**Returns:**
ブール値

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

フォントサイズ認識ヘッダー戦略で使用する期待される見出しレベルを定義します。このプロパティの値が設定されている場合、ヘッダー認識 {@link HeadingRecognitionStrategy#Heuristic} 戦略が選択され、{@link HeadingRecognitionStrategy#Auto} 戦略が設定されていても、ドキュメントにブックマークが含まれている場合でも適用されます。

**Returns:**
HeadingLevels インスタンス

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

見出し認識戦略を取得または設定します。

**Returns:**
HeadingRecognitionStrategy 要素

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

生成されたドキュメントの見出しスタイルを取得または設定します。

**Returns:**
HeadingStyle 要素

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

生成されたドキュメントの改行スタイルを取得または設定します。

**Returns:**
LineBreakStyle 要素

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

画像などのドキュメントリソースを保存するディレクトリ名を取得および設定します。値が指定されていない場合、画像はマークダウンファイルと同じディレクトリに書き込まれます。これはパスではなく、名前だけです！このディレクトリは、保存されたマークダウンファイルがあるディレクトリ内に自動的に作成されます。

**Returns:**
文字列値

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

画像などのドキュメントリソースを保存するディレクトリ名を取得および設定します。このディレクトリは、保存されたマークダウンファイルがあるディレクトリ内に自動的に作成されます。

**Returns:**
文字列値

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

下付き文字と上付き文字の変換を許可するかどうかを取得および設定します。この値はデフォルトで true です。

**Returns:**
ブール値

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

テキストの左側および右側に画像を挿入するために img タグの使用を許可するかどうかを取得および設定します。この場合、マークダウンビューアではテキストが画像の周りに折り返されます。

**Returns:**
ブール値

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
マークダウンにコンテンツを抽出する矩形領域を取得または設定します。

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

生成されたドキュメントの強調スタイルを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | EmphasisStyle 要素 |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

ベクターグラフィックを抽出すべきかどうかを示すプロパティを取得および設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
フォントサイズ認識ヘッダー戦略で使用する期待される見出しレベルを定義します。このプロパティの値が設定されている場合、ヘッダー認識 {@link HeadingRecognitionStrategy#Heuristic} 戦略が選択され、{@link HeadingRecognitionStrategy#Auto} 戦略が設定されていても、ドキュメントにブックマークが含まれている場合でも適用されます。

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

見出し認識戦略を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | HeadingRecognitionStrategy 要素 |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

生成されたドキュメントの見出しスタイルを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | HeadingStyle 要素 |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

生成されたドキュメントの改行スタイルを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | LineBreakStyle 要素 |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
画像などのドキュメントリソースを保存するディレクトリ名を取得および設定します。値が指定されていない場合、画像はマークダウンファイルと同じディレクトリに書き込まれます。これはパスではなく、名前だけです！このディレクトリは、保存されたマークダウンファイルがあるディレクトリ内に自動的に作成されます。

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
画像などのドキュメントリソースを保存するディレクトリ名を取得および設定します。このディレクトリは、保存されたマークダウンファイルがあるディレクトリ内に自動的に作成されます。

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

下付き文字と上付き文字の変換を許可するかどうかを取得および設定します。この値はデフォルトで true です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

テキストの左側および右側に画像を挿入するために img タグの使用を許可するかどうかを取得および設定します。この場合、マークダウンビューアではテキストが画像の周りに折り返されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
