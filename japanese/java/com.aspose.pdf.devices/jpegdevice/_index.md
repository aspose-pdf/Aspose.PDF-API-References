---
title: "JpegDevice"
linktitle: "JpegDevice"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントのページを JPEG 形式で保存するのに役立つ画像デバイスを表します。"
type: docs
weight: 130
url: /ja/java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.JpegDevice

```
public final class JpegDevice extends ImageDevice
```

PDF ドキュメントのページを JPEG 形式で保存するのに役立つ画像デバイスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [JpegDevice](#JpegDevice--) | デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](#JpegDevice-int-) | {@code JpegDevice} クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](#JpegDevice-int-int-) | 指定された画像サイズ、デフォルト解像度 (=150) および最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-) | デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-) | デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | ページを jpeg に変換し、出力ストリームに保存します。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | ページを jpeg に変換し、出力ストリームに保存します。 |

### JpegDevice {#JpegDevice--}
```
public JpegDevice()
```

デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。

### JpegDevice {#JpegDevice-int-}
```
public JpegDevice(int quality)
```

{@code JpegDevice} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 品質 |  | 画像の圧縮レベルを指定します。品質の有用な値の範囲は 0 から 100 です。指定した数値が小さいほど圧縮率が高くなり、画像の品質は低くなります。0 は最低品質の画像、100 は最高品質の画像を示します。 |

### JpegDevice {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```

指定された画像サイズ、デフォルト解像度 (=150) および最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | 画像の出力幅。 |
| 高さ |  | 画像の出力高さ。 |

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-}
デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-}
デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
デフォルトの解像度と最大品質で {@code JpegDevice} クラスの新しいインスタンスを初期化します。

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
ページを jpeg に変換し、出力ストリームに保存します。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
ページを jpeg に変換し、出力ストリームに保存します。
