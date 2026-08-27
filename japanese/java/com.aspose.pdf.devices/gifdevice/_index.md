---
title: "GifDevice"
linktitle: "GifDevice"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントのページを GIF 形式で保存するのに役立つ画像デバイスを表します。"
type: docs
weight: 90
url: /ja/java/com.aspose.pdf.devices/gifdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.GifDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.GifDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.GifDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.GifDevice

```
public final class GifDevice extends ImageDevice
```

PDF ドキュメントのページを GIF 形式で保存するのに役立つ画像デバイスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [GifDevice](#GifDevice--) | デフォルトの解像度で {@code GifDevice} クラスの新しいインスタンスを初期化します。 |
| [GifDevice](#GifDevice-int-int-) | 提供された画像サイズとデフォルト解像度（=150）で {@code GifDevice} クラスの新しいインスタンスを初期化します。 |
| [GifDevice](#GifDevice-int-int-com.aspose.pdf.devices.Resolution-) | デフォルトの解像度で {@code GifDevice} クラスの新しいインスタンスを初期化します。 |
| [GifDevice](#GifDevice-com.aspose.pdf.PageSize-) | デフォルトの解像度で {@code GifDevice} クラスの新しいインスタンスを初期化します。 |
| [GifDevice](#GifDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | デフォルトの解像度で {@code GifDevice} クラスの新しいインスタンスを初期化します。 |
| [GifDevice](#GifDevice-com.aspose.pdf.devices.Resolution-) | デフォルトの解像度で {@code GifDevice} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | ページを GIF に変換し、出力ストリームに保存します。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | ページを GIF に変換し、出力ストリームに保存します。 |

### GifDevice {#GifDevice--}
```
public GifDevice()
```

デフォルトの解像度で {@code GifDevice} クラスの新しいインスタンスを初期化します。

### GifDevice {#GifDevice-int-int-}
```
public GifDevice(int width, int height)
```

提供された画像サイズとデフォルト解像度（=150）で {@code GifDevice} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | 画像の出力幅。 |
| 高さ |  | 画像の出力高さ。 |

### GifDevice {#GifDevice-int-int-com.aspose.pdf.devices.Resolution-}
デフォルトの解像度で {@code GifDevice} クラスの新しいインスタンスを初期化します。

### GifDevice {#GifDevice-com.aspose.pdf.PageSize-}
デフォルトの解像度で {@code GifDevice} クラスの新しいインスタンスを初期化します。

### GifDevice {#GifDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
デフォルトの解像度で {@code GifDevice} クラスの新しいインスタンスを初期化します。

### GifDevice {#GifDevice-com.aspose.pdf.devices.Resolution-}
デフォルトの解像度で {@code GifDevice} クラスの新しいインスタンスを初期化します。

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
ページを GIF に変換し、出力ストリームに保存します。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
ページを GIF に変換し、出力ストリームに保存します。
