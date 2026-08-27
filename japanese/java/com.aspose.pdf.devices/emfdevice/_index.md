---
title: "EmfDevice"
linktitle: "EmfDevice"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントのページを EMF 形式で保存するのに役立つ画像デバイスを表します。"
type: docs
weight: 70
url: /ja/java/com.aspose.pdf.devices/emfdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.EmfDevice

```
public final class EmfDevice extends ImageDevice
```

PDF ドキュメントのページを EMF 形式で保存するのに役立つ画像デバイスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [EmfDevice](#EmfDevice--) | デフォルトの解像度で emf に書き込まれるラスタ画像を使用して、{@code EmfDevice} クラスの新しいインスタンスを初期化します。 |
| [EmfDevice](#EmfDevice-int-int-) | 指定された画像サイズで、デフォルト解像度（=150）のラスタ画像を emf に書き込むために、{@code EmfDevice} クラスの新しいインスタンスを初期化します。 |
| [EmfDevice](#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-) | デフォルトの解像度で emf に書き込まれるラスタ画像を使用して、{@code EmfDevice} クラスの新しいインスタンスを初期化します。 |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-) | デフォルトの解像度で emf に書き込まれるラスタ画像を使用して、{@code EmfDevice} クラスの新しいインスタンスを初期化します。 |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | デフォルトの解像度で emf に書き込まれるラスタ画像を使用して、{@code EmfDevice} クラスの新しいインスタンスを初期化します。 |
| [EmfDevice](#EmfDevice-com.aspose.pdf.devices.Resolution-) | デフォルトの解像度で emf に書き込まれるラスタ画像を使用して、{@code EmfDevice} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | ページを emf に変換し、出力ストリームに保存します。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | ページを emf に変換し、出力ストリームに保存します。 |

### EmfDevice {#EmfDevice--}
```
public EmfDevice()
```

デフォルトの解像度で emf に書き込まれるラスタ画像を使用して、{@code EmfDevice} クラスの新しいインスタンスを初期化します。

### EmfDevice {#EmfDevice-int-int-}
```
public EmfDevice(int width, int height)
```

指定された画像サイズで、デフォルト解像度（=150）のラスタ画像を emf に書き込むために、{@code EmfDevice} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | 画像の出力幅。 |
| 高さ |  | 画像の出力高さ。 |

### EmfDevice {#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-}
デフォルトの解像度で emf に書き込まれるラスタ画像を使用して、{@code EmfDevice} クラスの新しいインスタンスを初期化します。

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-}
デフォルトの解像度で emf に書き込まれるラスタ画像を使用して、{@code EmfDevice} クラスの新しいインスタンスを初期化します。

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
デフォルトの解像度で emf に書き込まれるラスタ画像を使用して、{@code EmfDevice} クラスの新しいインスタンスを初期化します。

### EmfDevice {#EmfDevice-com.aspose.pdf.devices.Resolution-}
デフォルトの解像度で emf に書き込まれるラスタ画像を使用して、{@code EmfDevice} クラスの新しいインスタンスを初期化します。

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
ページを emf に変換し、出力ストリームに保存します。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
ページを emf に変換し、出力ストリームに保存します。
