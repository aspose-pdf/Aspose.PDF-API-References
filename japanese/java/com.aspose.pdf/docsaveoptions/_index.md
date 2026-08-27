---
title: "DocSaveOptions"
linktitle: "DocSaveOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Doc 形式へのエクスポート用保存オプション"
type: docs
weight: 1030
url: /ja/java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.DocSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Doc 形式へのエクスポート用保存オプション

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DocSaveOptions](#DocSaveOptions--) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBatchSize](#getBatchSize--) | バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。 |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> このハンドラは変換進行イベントを処理するために使用できます。例えば、進行バーや現在処理されたページ数に関するメッセージを表示するために使用できます。コンソールに進行状況を表示するハンドラのコード例は次のとおりです： </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre> |
| [getFormat](#getFormat--) | 出力形式を取得 |
| [getImageResolutionX](#getImageResolutionX--) | 変換された画像の X 解像度。 |
| [getImageResolutionY](#getImageResolutionY--) | 変換された画像の Y 解像度。 |
| [getMaxDistanceBetweenTextLines](#getMaxDistanceBetweenTextLines--) | このパラメータはテキスト行を段落にグループ化するために使用されます。2つの相対的なテキスト行間の最大距離を決定します。テキスト行の高さの百分率（100%単位）で指定します。 |
| [getMemorySaveModePath](#getMemorySaveModePath--) | メモリ保存モードで変換する際に一時データを保持するパス（ファイル名またはディレクトリ名）を定義します。 |
| [getMode](#getMode--) | 認識モード。 |
| [getRelativeHorizontalProximity](#getRelativeHorizontalProximity--) | PDF では、単語が文字や音節を個別に印字する演算子で内部的に表現されることがあります。そのため、単語を検出するには実際には単語である独立した文字のグループを検出する必要があります。この設定は、ソース PDF の単語認識時に、テキスト要素（文字、音節）間の空白幅を単語間の距離として扱う幅を定義します。（文字間にこの幅以上の空白が存在する場合、そのテキスト要素は別々の単語に属するとみなされます）。フォントサイズに正規化されており、1.0 は想定される単語のフォントサイズの 100% を意味します。注意！この設定は、フォントから最適値を算出できない、特定の稀に使用されるフォントがソース PDF に含まれる場合にのみ使用されます。したがって、ほとんどの場合、このパラメータは結果文書に影響を与えません。 |
| [isAddReturnToLineEnd](#isAddReturnToLineEnd--) | 段落または改行に使用されます。 |
| [isConvertType3Fonts](#isConvertType3Fonts--) | Type3 フォントの変換を取得または設定します。Type3 フォントでは、グリフがグラフィック演算子のストリームで定義されます。これにより、DOC/DOCX 出力ではテキストの代わりに画像が表示されます。このフラグを true に設定すると、Type3 フォントを TTF に変換し、結果ファイルでテキストを取得できます。 |
| [isRecognizeBullets](#isRecognizeBullets--) | 箇条書きの認識を有効にします。 |
| [isReSaveFonts](#isReSaveFonts--) | フォントの再保存手順を取得または設定します。true に設定すると、前のフォントプロパティの影響を避けるために各ページでフォントを再読み込みし、新しく作成されたフォントを最初からロードします。パフォーマンスを向上させたい場合はこのオプションを false に設定してください。既定値は true です。 |
| [setAddReturnToLineEnd](#setAddReturnToLineEnd-boolean-) | 段落または改行を使用する |
| [setBatchSize](#setBatchSize-int-) | バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。 |
| [setConvertType3Fonts](#setConvertType3Fonts-boolean-) | Type3 フォントの変換を取得または設定します。Type3 フォントでは、グリフがグラフィック演算子のストリームで定義されます。これにより、DOC/DOCX 出力ではテキストの代わりに画像が表示されます。このフラグを true に設定すると、Type3 フォントを TTF に変換し、結果ファイルでテキストを取得できます。 |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | このハンドラは、変換進行イベントを処理するために使用できます（例）。 |
| [setFormat](#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-) | 出力形式を設定 |
| [setImageResolutionX](#setImageResolutionX-int-) | 変換された画像の X 解像度。 |
| [setImageResolutionY](#setImageResolutionY-int-) | 変換された画像の Y 解像度。 |
| [setMaxDistanceBetweenTextLines](#setMaxDistanceBetweenTextLines-float-) | このパラメータはテキスト行を段落にグループ化するために使用されます。2つの相対的なテキスト行間の最大距離を決定します。テキスト行の高さの百分率（100%単位）で指定します。 |
| [setMemorySaveModePath](#setMemorySaveModePath-java.lang.String-) | メモリ保存モードで変換する際に一時データを保持するパス（ファイル名またはディレクトリ名）を定義します。 |
| [setMode](#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-) | 認識モード。 |
| [setRecognizeBullets](#setRecognizeBullets-boolean-) | 箇条書きの認識を有効にします。 |
| [setRelativeHorizontalProximity](#setRelativeHorizontalProximity-float-) | PDF では、単語が文字や音節を個別に印字する演算子で内部的に表現されることがあります。そのため、単語を検出するには実際には単語である独立した文字のグループを検出する必要があります。この設定は、ソース PDF の単語認識時に、テキスト要素（文字、音節）間の空白幅を単語間の距離として扱う幅を定義します。（文字間にこの幅以上の空白が存在する場合、そのテキスト要素は別々の単語に属するとみなされます）。フォントサイズに正規化されており、1.0 は想定される単語のフォントサイズの 100% を意味します。注意！この設定は、フォントから最適値を算出できない、特定の稀に使用されるフォントがソース PDF に含まれる場合にのみ使用されます。したがって、ほとんどの場合、このパラメータは結果文書に影響を与えません。 |
| [setReSaveFonts](#setReSaveFonts-boolean-) | フォントの再保存手順を取得または設定します。true に設定すると、前のフォントプロパティの影響を避けるために各ページでフォントを再読み込みし、新しく作成されたフォントを最初からロードします。パフォーマンスを向上させたい場合はこのオプションを false に設定してください。既定値は true です。 |

### DocSaveOptions {#DocSaveOptions--}
```
public DocSaveOptions()
```

コンストラクタ

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。

**Returns:**
int 値です。

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> このハンドラは変換進行イベントを処理するために使用できます。例えば、進行バーや現在処理されたページ数に関するメッセージを表示するために使用できます。コンソールに進行状況を表示するハンドラのコード例は次のとおりです： </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler インスタンス

### getFormat {#getFormat--}
```
public DocSaveOptions.DocFormat getFormat()
```

出力形式を取得

**Returns:**
DocFormat 要素 @see com.aspose.pdf.DocSaveOptions.DocFormat

### getImageResolutionX {#getImageResolutionX--}
```
public int getImageResolutionX()
```

変換された画像の X 解像度。

**Returns:**
int 値です。

### getImageResolutionY {#getImageResolutionY--}
```
public int getImageResolutionY()
```

変換された画像の Y 解像度。

**Returns:**
int 値です。

### getMaxDistanceBetweenTextLines {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```

このパラメータはテキスト行を段落にグループ化するために使用されます。2つの相対的なテキスト行間の最大距離を決定します。テキスト行の高さの百分率（100%単位）で指定します。

**Returns:**
float 値

### getMemorySaveModePath {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```

メモリ保存モードで変換する際に一時データを保持するパス（ファイル名またはディレクトリ名）を定義します。

**Returns:**
文字列値

### getMode {#getMode--}
```
public DocSaveOptions.RecognitionMode getMode()
```

認識モード。

**Returns:**
RecognitionMode 値 @see RecognitionMode

### getRelativeHorizontalProximity {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```

PDF では、単語が文字や音節を個別に印字する演算子で内部的に表現されることがあります。そのため、単語を検出するには実際には単語である独立した文字のグループを検出する必要があります。この設定は、ソース PDF の単語認識時に、テキスト要素（文字、音節）間の空白幅を単語間の距離として扱う幅を定義します。（文字間にこの幅以上の空白が存在する場合、そのテキスト要素は別々の単語に属するとみなされます）。フォントサイズに正規化されており、1.0 は想定される単語のフォントサイズの 100% を意味します。注意！この設定は、フォントから最適値を算出できない、特定の稀に使用されるフォントがソース PDF に含まれる場合にのみ使用されます。したがって、ほとんどの場合、このパラメータは結果文書に影響を与えません。

**Returns:**
相対的な近接度

### isAddReturnToLineEnd {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```

段落または改行に使用されます。

**Returns:**
ブール値。

### isConvertType3Fonts {#isConvertType3Fonts--}
```
public final boolean isConvertType3Fonts()
```

Type3 フォントの変換を取得または設定します。Type3 フォントでは、グリフがグラフィック演算子のストリームで定義されます。これにより、DOC/DOCX 出力ではテキストの代わりに画像が表示されます。このフラグを true に設定すると、Type3 フォントを TTF に変換し、結果ファイルでテキストを取得できます。

**Returns:**
ブール値

### isRecognizeBullets {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```

箇条書きの認識を有効にします。

**Returns:**
ブール値

### isReSaveFonts {#isReSaveFonts--}
```
public final boolean isReSaveFonts()
```

フォントの再保存手順を取得または設定します。true に設定すると、前のフォントプロパティの影響を避けるために各ページでフォントを再読み込みし、新しく作成されたフォントを最初からロードします。パフォーマンスを向上させたい場合はこのオプションを false に設定してください。既定値は true です。

**Returns:**
ブール値

### setAddReturnToLineEnd {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```

段落または改行を使用する

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値。 |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |

### setConvertType3Fonts {#setConvertType3Fonts-boolean-}
```
public final void setConvertType3Fonts(boolean value)
```

Type3 フォントの変換を取得または設定します。Type3 フォントでは、グリフがグラフィック演算子のストリームで定義されます。これにより、DOC/DOCX 出力ではテキストの代わりに画像が表示されます。このフラグを true に設定すると、Type3 フォントを TTF に変換し、結果ファイルでテキストを取得できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
このハンドラは、変換進行イベントを処理するために使用できます（例）。

### setFormat {#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-}
出力形式を設定

### setImageResolutionX {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```

変換された画像の X 解像度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setImageResolutionY {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```

変換された画像の Y 解像度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setMaxDistanceBetweenTextLines {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```

このパラメータはテキスト行を段落にグループ化するために使用されます。2つの相対的なテキスト行間の最大距離を決定します。テキスト行の高さの百分率（100%単位）で指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setMemorySaveModePath {#setMemorySaveModePath-java.lang.String-}
メモリ保存モードで変換する際に一時データを保持するパス（ファイル名またはディレクトリ名）を定義します。

### setMode {#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-}
認識モード。

### setRecognizeBullets {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```

箇条書きの認識を有効にします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRelativeHorizontalProximity {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```

PDF では、単語が文字や音節を個別に印字する演算子で内部的に表現されることがあります。そのため、単語を検出するには実際には単語である独立した文字のグループを検出する必要があります。この設定は、ソース PDF の単語認識時に、テキスト要素（文字、音節）間の空白幅を単語間の距離として扱う幅を定義します。（文字間にこの幅以上の空白が存在する場合、そのテキスト要素は別々の単語に属するとみなされます）。フォントサイズに正規化されており、1.0 は想定される単語のフォントサイズの 100% を意味します。注意！この設定は、フォントから最適値を算出できない、特定の稀に使用されるフォントがソース PDF に含まれる場合にのみ使用されます。したがって、ほとんどの場合、このパラメータは結果文書に影響を与えません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 相対的な近接度 |

### setReSaveFonts {#setReSaveFonts-boolean-}
```
public final void setReSaveFonts(boolean value)
```

フォントの再保存手順を取得または設定します。true に設定すると、前のフォントプロパティの影響を避けるために各ページでフォントを再読み込みし、新しく作成されたフォントを最初からロードします。パフォーマンスを向上させたい場合はこのオプションを false に設定してください。既定値は true です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
