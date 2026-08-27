---
title: "XpsSaveOptions"
linktitle: "XpsSaveOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "XPS 形式へのエクスポート用保存オプション"
type: docs
weight: 5770
url: /ja/java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.XpsSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

XPS 形式へのエクスポート用保存オプション

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XpsSaveOptions](#XpsSaveOptions--) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBatchSize](#getBatchSize--) | バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。 |
| [getDefaultFont](#getDefaultFont--) | デフォルトのフォント名を取得/設定します。埋め込みフォント名がシステムに見つからない場合に使用されます。 |
| [getSaveTransparentTexts](#getSaveTransparentTexts--) | 透明な（OCR処理された）テキストを保持するかどうかを示します。 |
| [getUseEmbeddedTrueTypeFonts](#getUseEmbeddedTrueTypeFonts--) | 埋め込みTrueTypeフォントを使用するフラグを取得/設定します。埋め込みTrueTypeフォントの使用を回避すると、変換時間を短縮できます。 |
| [isUseNewImagingEngine](#isUseNewImagingEngine--) | UseNewImagingEngine オプションを取得または設定します。 |
| [setBatchSize](#setBatchSize-int-) | バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。 |
| [setDefaultFont](#setDefaultFont-java.lang.String-) | デフォルトのフォント名を取得/設定します。埋め込みフォント名がシステムに見つからない場合に使用されます。 |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | 透明な（OCR処理された）テキストを保持するかどうかを示します。 |
| [setUseEmbeddedTrueTypeFonts](#setUseEmbeddedTrueTypeFonts-boolean-) | 埋め込みTrueTypeフォントを使用するフラグを取得/設定します。埋め込みTrueTypeフォントの使用を回避すると、変換時間を短縮できます。 |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | UseNewImagingEngine オプションを取得または設定します。 |

### XpsSaveOptions {#XpsSaveOptions--}
```
public XpsSaveOptions()
```

コンストラクタ

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。

**Returns:**
int 値です。

### getDefaultFont {#getDefaultFont--}
```
public final String getDefaultFont()
```

デフォルトのフォント名を取得/設定します。埋め込みフォント名がシステムに見つからない場合に使用されます。

**Returns:**
文字列値

### getSaveTransparentTexts {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```

透明な（OCR処理された）テキストを保持するかどうかを示します。

**Returns:**
ブール値

### getUseEmbeddedTrueTypeFonts {#getUseEmbeddedTrueTypeFonts--}
```
public final boolean getUseEmbeddedTrueTypeFonts()
```

埋め込みTrueTypeフォントを使用するフラグを取得/設定します。埋め込みTrueTypeフォントの使用を回避すると、変換時間を短縮できます。

**Returns:**
ブール値

### isUseNewImagingEngine {#isUseNewImagingEngine--}
```
@Deprecated public final boolean isUseNewImagingEngine()
```

UseNewImagingEngine オプションを取得または設定します。

**Returns:**
boolean 値 @deprecated UseNewImagingEngine は非推奨です

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setDefaultFont {#setDefaultFont-java.lang.String-}
デフォルトのフォント名を取得/設定します。埋め込みフォント名がシステムに見つからない場合に使用されます。

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```

透明な（OCR処理された）テキストを保持するかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUseEmbeddedTrueTypeFonts {#setUseEmbeddedTrueTypeFonts-boolean-}
```
public final void setUseEmbeddedTrueTypeFonts(boolean value)
```

埋め込みTrueTypeフォントを使用するフラグを取得/設定します。埋め込みTrueTypeフォントの使用を回避すると、変換時間を短縮できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public final void setUseNewImagingEngine(boolean value)
```

UseNewImagingEngine オプションを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | boolean 値 @deprecated UseNewImagingEngine は非推奨です |
