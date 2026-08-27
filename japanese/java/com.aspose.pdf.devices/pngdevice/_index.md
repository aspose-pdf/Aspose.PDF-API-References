---
title: "PngDevice"
linktitle: "PngDevice"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントのページを PNG 形式で保存するのに役立つ画像デバイスを表します。"
type: docs
weight: 160
url: /ja/java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PngDevice

```
public final class PngDevice extends ImageDevice
```

PDF ドキュメントのページを PNG 形式で保存するのに役立つ画像デバイスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PngDevice](#PngDevice--) | デフォルト解像度で {@code PngDevice} クラスの新しいインスタンスを初期化します。 |
| [PngDevice](#PngDevice-int-int-) | 指定された画像サイズで、デフォルト解像度 (=150) の {@code PngDevice} クラスの新しいインスタンスを初期化します。 |
| [PngDevice](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | デフォルト解像度で {@code PngDevice} クラスの新しいインスタンスを初期化します。 |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-) | デフォルト解像度で {@code PngDevice} クラスの新しいインスタンスを初期化します。 |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | デフォルト解像度で {@code PngDevice} クラスの新しいインスタンスを初期化します。 |
| [PngDevice](#PngDevice-com.aspose.pdf.devices.Resolution-) | デフォルト解像度で {@code PngDevice} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [isTransparentBackground](#isTransparentBackground--) | 画像が透過背景かどうかを取得または設定します。 |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | ページを PNG に変換し、出力ストリームに保存します。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | ページを PNG に変換し、出力ストリームに保存します。 |
| [processToBufferedImage](#processToBufferedImage-com.aspose.pdf.Page-) | ページを BufferedImage に変換します。 |
| [processToBufferedImageBinarized](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | ページを Bradley 二値化で BufferedImage に変換します。 |
| [setTransparentBackground](#setTransparentBackground-boolean-) | 画像が透過背景かどうかを取得または設定します。 |

### PngDevice {#PngDevice--}
```
public PngDevice()
```

デフォルト解像度で {@code PngDevice} クラスの新しいインスタンスを初期化します。

### PngDevice {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```

指定された画像サイズで、デフォルト解像度 (=150) の {@code PngDevice} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | 画像の出力幅。 |
| 高さ |  | 画像の出力高さ。 |

### PngDevice {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
デフォルト解像度で {@code PngDevice} クラスの新しいインスタンスを初期化します。

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-}
デフォルト解像度で {@code PngDevice} クラスの新しいインスタンスを初期化します。

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
デフォルト解像度で {@code PngDevice} クラスの新しいインスタンスを初期化します。

### PngDevice {#PngDevice-com.aspose.pdf.devices.Resolution-}
デフォルト解像度で {@code PngDevice} クラスの新しいインスタンスを初期化します。

### isTransparentBackground {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```

画像が透過背景かどうかを取得または設定します。

**Returns:**
ブール値

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
ページを PNG に変換し、出力ストリームに保存します。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
ページを PNG に変換し、出力ストリームに保存します。

### processToBufferedImage {#processToBufferedImage-com.aspose.pdf.Page-}
ページを BufferedImage に変換します。

### processToBufferedImageBinarized {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
ページを Bradley 二値化で BufferedImage に変換します。

### setTransparentBackground {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```

画像が透過背景かどうかを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
