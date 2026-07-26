---
title: "AutoTaggingSettings"
linktitle: "AutoTaggingSettings"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントにおける自動タグ付け機能の設定を提供します。{@link AutoTaggingSettings} クラスは PDF コンテンツの自動タグ付けオプションを構成できるようにします。それ。"
type: docs
weight: 230
url: /ja/java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

PDF ドキュメントにおける自動タグ付け機能の設定を提供します。{@link AutoTaggingSettings} クラスは PDF コンテンツの自動タグ付けオプションを構成できるようにします。自動タグ付けの有効化/無効化、見出し認識の戦略の指定、フォントサイズに基づく見出しレベルの定義などのプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDefault](#getDefault--) | PDF ドキュメントにおける自動タグ付け機能のデフォルト設定を取得します。デフォルト設定は自動タグ付けを有効にし、見出し認識の自動戦略を使用します。これらの設定は、PDF 形式の変換や PDF コンテンツの自動タグ付けを必要とするその他の操作のベースライン構成として使用できます。 |
| [getEnableAutoTagging](#getEnableAutoTagging--) | 自動タグ付け機能が有効かどうかを示す値を取得または設定します。有効にすると、自動タグ付け機能は PDF ドキュメントのタグ付けされたコンテンツを自動的に生成し、アクセシビリティと構造を向上させることができます。 |
| [getHeadingLevels](#getHeadingLevels--) | PDF ドキュメントにおける見出しの構造を決定するために使用される見出しレベルを取得または設定します。{@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) プロパティはフォントサイズと見出しレベルのマッピングを構成できるようにします。これは自動タグ付けプロセス中に、文書内のテキスト要素のフォントサイズに基づいて適切な見出しレベルを識別し割り当てるために使用されます。 |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | 自動タグ付け中に文書の見出しを認識するために使用される戦略を取得または設定します。{@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) プロパティは文書内で見出しがどのように識別されるかを決定します。利用可能な戦略には、アウトラインに基づく見出し認識、ヒューリスティック分析、または自動検出が含まれます。このプロパティを {@link HeadingRecognitionStrategy#None} に設定すると、見出し認識が無効になります。 |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | 自動タグ付け機能が有効かどうかを示す値を取得または設定します。有効にすると、自動タグ付け機能は PDF ドキュメントのタグ付けされたコンテンツを自動的に生成し、アクセシビリティと構造を向上させることができます。 |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | PDF ドキュメントにおける見出しの構造を決定するために使用される見出しレベルを取得または設定します。{@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) プロパティはフォントサイズと見出しレベルのマッピングを構成できるようにします。これは自動タグ付けプロセス中に、文書内のテキスト要素のフォントサイズに基づいて適切な見出しレベルを識別し割り当てるために使用されます。 |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | 自動タグ付け中に文書の見出しを認識するために使用される戦略を取得または設定します。{@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) プロパティは文書内で見出しがどのように識別されるかを決定します。利用可能な戦略には、アウトラインに基づく見出し認識、ヒューリスティック分析、または自動検出が含まれます。このプロパティを {@link HeadingRecognitionStrategy#None} に設定すると、見出し認識が無効になります。 |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

PDF ドキュメントにおける自動タグ付け機能のデフォルト設定を取得します。デフォルト設定は自動タグ付けを有効にし、見出し認識の自動戦略を使用します。これらの設定は、PDF 形式の変換や PDF コンテンツの自動タグ付けを必要とするその他の操作のベースライン構成として使用できます。

**Returns:**
AutoTaggingSettings インスタンス

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

自動タグ付け機能が有効かどうかを示す値を取得または設定します。有効にすると、自動タグ付け機能は PDF ドキュメントのタグ付けされたコンテンツを自動的に生成し、アクセシビリティと構造を向上させることができます。

**Returns:**
ブール値

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

PDF ドキュメントにおける見出しの構造を決定するために使用される見出しレベルを取得または設定します。{@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) プロパティはフォントサイズと見出しレベルのマッピングを構成できるようにします。これは自動タグ付けプロセス中に、文書内のテキスト要素のフォントサイズに基づいて適切な見出しレベルを識別し割り当てるために使用されます。

**Returns:**
HeadingLevels インスタンス

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

自動タグ付け中に文書の見出しを認識するために使用される戦略を取得または設定します。{@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) プロパティは文書内で見出しがどのように識別されるかを決定します。利用可能な戦略には、アウトラインに基づく見出し認識、ヒューリスティック分析、または自動検出が含まれます。このプロパティを {@link HeadingRecognitionStrategy#None} に設定すると、見出し認識が無効になります。

**Returns:**
HeadingRecognitionStrategy 要素

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

自動タグ付け機能が有効かどうかを示す値を取得または設定します。有効にすると、自動タグ付け機能は PDF ドキュメントのタグ付けされたコンテンツを自動的に生成し、アクセシビリティと構造を向上させることができます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
PDF ドキュメントにおける見出しの構造を決定するために使用される見出しレベルを取得または設定します。{@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) プロパティはフォントサイズと見出しレベルのマッピングを構成できるようにします。これは自動タグ付けプロセス中に、文書内のテキスト要素のフォントサイズに基づいて適切な見出しレベルを識別し割り当てるために使用されます。

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

自動タグ付け中に文書の見出しを認識するために使用される戦略を取得または設定します。{@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) プロパティは文書内で見出しがどのように識別されるかを決定します。利用可能な戦略には、アウトラインに基づく見出し認識、ヒューリスティック分析、または自動検出が含まれます。このプロパティを {@link HeadingRecognitionStrategy#None} に設定すると、見出し認識が無効になります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | HeadingRecognitionStrategy 要素 |
