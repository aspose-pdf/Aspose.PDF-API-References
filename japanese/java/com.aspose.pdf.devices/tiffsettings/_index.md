---
title: "TiffSettings"
linktitle: "TiffSettings"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは PDF を TIFF にインポートするための設定を表します。"
type: docs
weight: 220
url: /ja/java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.TiffSettings

```
public final class TiffSettings extends Object
```

このクラスは PDF を TIFF にインポートするための設定を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TiffSettings](#TiffSettings--) | {@code TiffSettings} クラスの新しいインスタンスを初期化します。 |
| [TiffSettings](#TiffSettings-boolean-) | {@code TiffSettings} クラスの新しいインスタンスを初期化します。 |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.ColorDepth-) | {@code TiffSettings} クラスの新しいインスタンスを初期化します。 |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-) | {@code TiffSettings} クラスの新しいインスタンスを初期化します。 |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-) | {@code TiffSettings} クラスの新しいインスタンスを初期化します。 |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-) | {@code TiffSettings} クラスの新しいインスタンスを初期化します。 |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-) | {@code TiffSettings} クラスの新しいインスタンスを初期化します。 |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.Margins-) | {@code TiffSettings} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBrightness](#getBrightness--) | 白と黒の色変換の値境界を取得します。このパラメータは EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle、または ColorDepth.Format1bpp == 1 と組み合わせて使用できます。 |
| [getCompression](#getCompression--) | <p> 圧縮のタイプを取得します。 </p> 値: 圧縮のタイプ。 <hr> <p> デフォルト値は CompressionType.LZW です。</p> |
| [getCoordinateType](#getCoordinateType--) | ページ座標タイプ (Media/Crop ボックス) を取得します。デフォルトでは CropBox の値が使用されます。 |
| [getDepth](#getDepth--) | <p> 色深度を取得します。 </p> 値: 色深度です。 <hr> <p> デフォルト値は ColorDepth.Default です </p> |
| [getIndexedConversionType](#getIndexedConversionType--) | IndexedConversionType を取得します。 デフォルト値は Simple です。 |
| [getMargins](#getMargins--) | 余白を取得します。 |
| [getShape](#getShape--) | <p> シェイプのタイプを取得します。 </p> 値: シェイプのタイプです。 <hr> <p> デフォルト値は ShapeType.None です </p> |
| [getSkipBlankPages](#getSkipBlankPages--) | <p> 空白ページをスキップするかどうかを示す値を取得します。 </p> 値: {@code true} は空白ページをスキップする必要がある場合; それ以外は {@code false}。 <hr> <p> デフォルト値は false です </p> |
| [isUseAlternativeImageEngine](#isUseAlternativeImageEngine--) | 代替イメージングエンジンが使用されるかどうかを決定するフラグを取得します。Linux OS ではデフォルトで true が使用されます。Windows OS のデフォルト値は false です。 |
| [setBrightness](#setBrightness-float-) | 白と黒の色変換の境界値を設定します。このパラメータは EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle、または ColorDepth.Format1bpp == 1 と組み合わせて使用できます。 |
| [setCompression](#setCompression-com.aspose.pdf.devices.CompressionType-) | <p> 圧縮のタイプを設定します。 </p> 値: 圧縮のタイプです。 <hr> <p> デフォルト値は CompressionType.LZW です </p> |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | ページ座標タイプ (Media/Crop ボックス) を設定します。デフォルトでは CropBox の値が使用されます。 |
| [setDepth](#setDepth-com.aspose.pdf.devices.ColorDepth-) | <p> 色深度を取得します。 </p> 値: 色深度です。 <hr> <p> デフォルト値は ColorDepth.Default です </p> |
| [setIndexedConversionType](#setIndexedConversionType-int-) | IndexedConversionType を設定します。 |
| [setShape](#setShape-com.aspose.pdf.devices.ShapeType-) | <p> シェイプのタイプを設定します。 </p> 値: シェイプのタイプです。 <hr> <p> デフォルト値は ShapeType.None です </p> |
| [setSkipBlankPages](#setSkipBlankPages-boolean-) | <p> 空白ページをスキップするかどうかを示す値を設定します。 </p> 値: {@code true} は空白ページをスキップする必要がある場合; それ以外は {@code false}。 <hr> <p> デフォルト値は false です </p> |
| [setUseAlternativeImageEngine](#setUseAlternativeImageEngine-boolean-) | 代替イメージングエンジンが使用されるかどうかを決定するフラグを設定します。 |

### TiffSettings {#TiffSettings--}
```
public TiffSettings()
```

{@code TiffSettings} クラスの新しいインスタンスを初期化します。

### TiffSettings {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```

{@code TiffSettings} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| skipBlankPages |  | {@code true} に設定した場合 [空白ページをスキップ]。 |

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.ColorDepth-}
{@code TiffSettings} クラスの新しいインスタンスを初期化します。

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-}
{@code TiffSettings} クラスの新しいインスタンスを初期化します。

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-}
{@code TiffSettings} クラスの新しいインスタンスを初期化します。

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-}
{@code TiffSettings} クラスの新しいインスタンスを初期化します。

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-}
{@code TiffSettings} クラスの新しいインスタンスを初期化します。

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.Margins-}
{@code TiffSettings} クラスの新しいインスタンスを初期化します。

### getBrightness {#getBrightness--}
```
public float getBrightness()
```

白と黒の色変換の値境界を取得します。このパラメータは EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle、または ColorDepth.Format1bpp == 1 と組み合わせて使用できます。

**Returns:**
明るさの float 値は 0 から 1 の範囲である必要があります。デフォルト値は 0.33f です。

### getCompression {#getCompression--}
```
public CompressionType getCompression()
```

<p> 圧縮のタイプを取得します。 </p> 値: 圧縮のタイプ。 <hr> <p> デフォルト値は CompressionType.LZW です。</p>

**Returns:**
CompressionType 要素 @see CompressionType

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

ページ座標タイプ (Media/Crop ボックス) を取得します。デフォルトでは CropBox の値が使用されます。

**Returns:**
PageCoordinateType 値 @see PageCoordinateType

### getDepth {#getDepth--}
```
public ColorDepth getDepth()
```

<p> 色深度を取得します。 </p> 値: 色深度です。 <hr> <p> デフォルト値は ColorDepth.Default です </p>

**Returns:**
ColorDepth 要素 @see ColorDepth

### getIndexedConversionType {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```

IndexedConversionType を取得します。 デフォルト値は Simple です。

**Returns:**
IndexedConversionType 要素 @see IndexedConversionType

### getMargins {#getMargins--}
```
public Margins getMargins()
```

余白を取得します。

**Returns:**
Margins オブジェクト

### getShape {#getShape--}
```
public ShapeType getShape()
```

<p> シェイプのタイプを取得します。 </p> 値: シェイプのタイプです。 <hr> <p> デフォルト値は ShapeType.None です </p>

**Returns:**
ShapeType 要素 @see ShapeType

### getSkipBlankPages {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```

<p> 空白ページをスキップするかどうかを示す値を取得します。 </p> 値: {@code true} は空白ページをスキップする必要がある場合; それ以外は {@code false}。 <hr> <p> デフォルト値は false です </p>

**Returns:**
ブール値

### isUseAlternativeImageEngine {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```

代替イメージングエンジンが使用されるかどうかを決定するフラグを取得します。Linux OS ではデフォルトで true が使用されます。Windows OS のデフォルト値は false です。

**Returns:**
ブール値

### setBrightness {#setBrightness-float-}
```
public void setBrightness(float value)
```

白と黒の色変換の境界値を設定します。このパラメータは EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle、または ColorDepth.Format1bpp == 1 と組み合わせて使用できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | : 明るさの値は 0 から 1 の範囲である必要があります。デフォルト値は 0.33f です |

### setCompression {#setCompression-com.aspose.pdf.devices.CompressionType-}
<p> 圧縮のタイプを設定します。 </p> 値: 圧縮のタイプです。 <hr> <p> デフォルト値は CompressionType.LZW です </p>

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
ページ座標タイプ (Media/Crop ボックス) を設定します。デフォルトでは CropBox の値が使用されます。

### setDepth {#setDepth-com.aspose.pdf.devices.ColorDepth-}
<p> 色深度を取得します。 </p> 値: 色深度です。 <hr> <p> デフォルト値は ColorDepth.Default です </p>

### setIndexedConversionType {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```

IndexedConversionType を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | IndexedConversionType 要素 @see IndexedConversionType |

### setShape {#setShape-com.aspose.pdf.devices.ShapeType-}
<p> シェイプのタイプを設定します。 </p> 値: シェイプのタイプです。 <hr> <p> デフォルト値は ShapeType.None です </p>

### setSkipBlankPages {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```

<p> 空白ページをスキップするかどうかを示す値を設定します。 </p> 値: {@code true} は空白ページをスキップする必要がある場合; それ以外は {@code false}。 <hr> <p> デフォルト値は false です </p>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUseAlternativeImageEngine {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```

代替イメージングエンジンが使用されるかどうかを決定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| useAlternativeImageEngine |  | ブール値 |
