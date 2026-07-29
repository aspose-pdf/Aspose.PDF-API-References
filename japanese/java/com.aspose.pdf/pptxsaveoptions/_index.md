---
title: "PptxSaveOptions"
linktitle: "PptxSaveOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "SVG 形式へのエクスポート用保存オプションです。"
type: docs
weight: 3950
url: /ja/java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.PptxSaveOptions

```
public class PptxSaveOptions extends UnifiedSaveOptions
```

SVG 形式へのエクスポート用保存オプションです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PptxSaveOptions](#PptxSaveOptions--) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> このハンドラは変換進行イベントを処理するために使用できます。たとえば、プログレスバーや現在処理されたページ数に関するメッセージを表示するために使用できます。コンソールに進行状況を表示するハンドラのコード例は次のとおりです: </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre> |
| [getImageResolution](#getImageResolution--) | 画像の解像度 (dpi) を取得または設定します。デフォルトは 192 dpi です。 |
| [getSeparateImages](#getSeparateImages--) | true に設定すると、画像は他のすべてのグラフィックから分離されます。 |
| [getSlidesAsImages](#getSlidesAsImages--) | true に設定すると、すべてのコンテンツが画像として認識されます（ページごとに1つ）。 |
| [isOptimizeTextBoxes](#isOptimizeTextBoxes--) | テキスト列の認識を切り替えます。 |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | このハンドラは、変換進行イベントを処理するために使用できます（例）。 |
| [setImageResolution](#setImageResolution-int-) | 画像の解像度 (dpi) を取得または設定します。デフォルトは 192 dpi です。 |
| [setOptimizeTextBoxes](#setOptimizeTextBoxes-boolean-) | テキスト列の認識を切り替えます。 |
| [setSeparateImages](#setSeparateImages-boolean-) | true に設定すると、画像は他のすべてのグラフィックから分離されます。 |
| [setSlidesAsImages](#setSlidesAsImages-boolean-) | true に設定すると、すべてのコンテンツが画像として認識されます（ページごとに1つ）。 |

### PptxSaveOptions {#PptxSaveOptions--}
```
public PptxSaveOptions()
```

コンストラクタ

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> このハンドラは変換進行イベントを処理するために使用できます。たとえば、プログレスバーや現在処理されたページ数に関するメッセージを表示するために使用できます。コンソールに進行状況を表示するハンドラのコード例は次のとおりです: </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler インスタンス

### getImageResolution {#getImageResolution--}
```
public final int getImageResolution()
```

画像の解像度 (dpi) を取得または設定します。デフォルトは 192 dpi です。

**Returns:**
int 値です。

### getSeparateImages {#getSeparateImages--}
```
public boolean getSeparateImages()
```

true に設定すると、画像は他のすべてのグラフィックから分離されます。

**Returns:**
ブール値

### getSlidesAsImages {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```

true に設定すると、すべてのコンテンツが画像として認識されます（ページごとに1つ）。

**Returns:**
ブール値

### isOptimizeTextBoxes {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```

テキスト列の認識を切り替えます。

**Returns:**
ブール値

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
このハンドラは、変換進行イベントを処理するために使用できます（例）。

### setImageResolution {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```

画像の解像度 (dpi) を取得または設定します。デフォルトは 192 dpi です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setOptimizeTextBoxes {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```

テキスト列の認識を切り替えます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSeparateImages {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```

true に設定すると、画像は他のすべてのグラフィックから分離されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSlidesAsImages {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```

true に設定すると、すべてのコンテンツが画像として認識されます（ページごとに1つ）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
