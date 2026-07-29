---
title: "TiffDevice"
linktitle: "TiffDevice"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは、PDF ドキュメントのページを 1 つの TIFF 画像にページごとに保存するのに役立ちます。"
type: docs
weight: 210
url: /ja/java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.TiffDevice

```
public final class TiffDevice extends DocumentDevice
```

このクラスは、PDF ドキュメントのページを 1 つの TIFF 画像にページごとに保存するのに役立ちます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TiffDevice](#TiffDevice--) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-int-int-) | {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [binarizeBradley](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | 入力ストリームに対して Bradley 二値化を実行します。 |
| [getCropRectangle](#getCropRectangle--) | 画像に変換される領域を定義する矩形を取得します。デフォルトは null で、この場合画像全体がページに変換されます。 |
| [getFormPresentationMode](#getFormPresentationMode--) | フォームの表示モードを取得します。 |
| [getHeight](#getHeight--) | 画像の出力高さを取得します。 |
| [getRenderingOptions](#getRenderingOptions--) | レンダリング オプションを取得します。 |
| [getResolution](#getResolution--) | 画像の解像度を取得します。 |
| [getSettings](#getSettings--) | PDF を TIFF 画像にマッピングする設定を取得します。 |
| [getWidth](#getWidth--) | 画像の出力幅を取得します。 |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | 特定のドキュメントページを TIFF に変換し、出力ストリームに保存します。 |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | 特定のドキュメントページを TIFF に変換し、出力ストリームに保存します。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 指定されたページに対して何らかの操作を実行します（e.g.）。 |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | 画像に変換される領域を定義する矩形を設定します。 |
| [setFormPresentationMode](#setFormPresentationMode-int-) | フォームの表示モードを取得します。 |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | レンダリング オプションを設定します。 |

### TiffDevice {#TiffDevice--}
```
public TiffDevice()
```

デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```

{@code TiffDevice} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | 画像の出力幅。 |
| 高さ |  | 画像の出力高さ。 |

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
デフォルト設定で {@code TiffDevice} クラスの新しいインスタンスを初期化します。

### binarizeBradley {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
入力ストリームに対して Bradley 二値化を実行します。

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

画像に変換される領域を定義する矩形を取得します。デフォルトは null で、この場合画像全体がページに変換されます。

**Returns:**
Rectangle オブジェクト

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

フォームの表示モードを取得します。

**Returns:**
FormPresentationMode 値 @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

画像の出力高さを取得します。

**Returns:**
int 値です。

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

レンダリング オプションを取得します。

**Returns:**
レンダリング オプション。

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

画像の解像度を取得します。

**Returns:**
Resolution 要素

### getSettings {#getSettings--}
```
public TiffSettings getSettings()
```

PDF を TIFF 画像にマッピングする設定を取得します。

**Returns:**
TiffSettings 要素

### getWidth {#getWidth--}
```
public int getWidth()
```

画像の出力幅を取得します。

**Returns:**
int 値です。

### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
特定のドキュメントページを TIFF に変換し、出力ストリームに保存します。

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
特定のドキュメントページを TIFF に変換し、出力ストリームに保存します。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
指定されたページに対して何らかの操作を実行します（e.g.）。

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
画像に変換される領域を定義する矩形を設定します。

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

フォームの表示モードを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値 @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
レンダリング オプションを設定します。
