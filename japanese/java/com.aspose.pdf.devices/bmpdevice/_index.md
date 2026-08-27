---
title: "BmpDevice"
linktitle: "BmpDevice"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントのページを BMP 形式で保存するのに役立つ画像デバイスを表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.devices/bmpdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.BmpDevice

```
public final class BmpDevice extends ImageDevice
```

PDF ドキュメントのページを BMP 形式で保存するのに役立つ画像デバイスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BmpDevice](#BmpDevice--) | デフォルト解像度で {@code BmpDevice} クラスの新しいインスタンスを初期化します。 |
| [BmpDevice](#BmpDevice-int-int-) | 指定された画像サイズ、デフォルト解像度 (=150) で {@code BmpDevice} クラスの新しいインスタンスを初期化します。 |
| [BmpDevice](#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-) | デフォルト解像度で {@code BmpDevice} クラスの新しいインスタンスを初期化します。 |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-) | デフォルト解像度で {@code BmpDevice} クラスの新しいインスタンスを初期化します。 |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | デフォルト解像度で {@code BmpDevice} クラスの新しいインスタンスを初期化します。 |
| [BmpDevice](#BmpDevice-com.aspose.pdf.devices.Resolution-) | デフォルト解像度で {@code BmpDevice} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | ページをグラフィックにレンダリングします |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | ページを bmp に変換し、出力ストリームに保存します。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 内部使用のみ！ |

### BmpDevice {#BmpDevice--}
```
public BmpDevice()
```

デフォルト解像度で {@code BmpDevice} クラスの新しいインスタンスを初期化します。

### BmpDevice {#BmpDevice-int-int-}
```
public BmpDevice(int width, int height)
```

指定された画像サイズ、デフォルト解像度 (=150) で {@code BmpDevice} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | 画像の出力幅。 |
| 高さ |  | 画像の出力高さ。 |

### BmpDevice {#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-}
デフォルト解像度で {@code BmpDevice} クラスの新しいインスタンスを初期化します。

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-}
デフォルト解像度で {@code BmpDevice} クラスの新しいインスタンスを初期化します。

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
デフォルト解像度で {@code BmpDevice} クラスの新しいインスタンスを初期化します。

### BmpDevice {#BmpDevice-com.aspose.pdf.devices.Resolution-}
デフォルト解像度で {@code BmpDevice} クラスの新しいインスタンスを初期化します。

### process {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
ページをグラフィックにレンダリングします

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
ページを bmp に変換し、出力ストリームに保存します。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
内部使用のみ！
