---
title: "DicomDevice"
linktitle: "DicomDevice"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントのページを DICOM 形式で保存するのに役立つ画像デバイスを表します。"
type: docs
weight: 50
url: /ja/java/com.aspose.pdf.devices/dicomdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.DicomDevice

```
public final class DicomDevice extends ImageDevice
```

PDF ドキュメントのページを DICOM 形式で保存するのに役立つ画像デバイスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DicomDevice](#DicomDevice--) | デフォルト解像度で {@link DicomDevice} クラスの新しいインスタンスを初期化します。 |
| [DicomDevice](#DicomDevice-int-int-) | 指定された画像サイズで、デフォルト解像度 (=150) の {@link DicomDevice} クラスの新しいインスタンスを初期化します。 |
| [DicomDevice](#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-) | デフォルト解像度で {@link DicomDevice} クラスの新しいインスタンスを初期化します。 |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-) | デフォルト解像度で {@link DicomDevice} クラスの新しいインスタンスを初期化します。 |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | デフォルト解像度で {@link DicomDevice} クラスの新しいインスタンスを初期化します。 |
| [DicomDevice](#DicomDevice-com.aspose.pdf.devices.Resolution-) | デフォルト解像度で {@link DicomDevice} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | ページを Dicom に変換し、出力ストリームに保存します。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 指定されたページに対して何らかの操作を実行します（e.g.）。 |

### DicomDevice {#DicomDevice--}
```
public DicomDevice()
```

デフォルト解像度で {@link DicomDevice} クラスの新しいインスタンスを初期化します。

### DicomDevice {#DicomDevice-int-int-}
```
public DicomDevice(int width, int height)
```

指定された画像サイズで、デフォルト解像度 (=150) の {@link DicomDevice} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | 画像の出力幅。 |
| 高さ |  | 画像の出力高さ。 |

### DicomDevice {#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-}
デフォルト解像度で {@link DicomDevice} クラスの新しいインスタンスを初期化します。

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-}
デフォルト解像度で {@link DicomDevice} クラスの新しいインスタンスを初期化します。

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
デフォルト解像度で {@link DicomDevice} クラスの新しいインスタンスを初期化します。

### DicomDevice {#DicomDevice-com.aspose.pdf.devices.Resolution-}
デフォルト解像度で {@link DicomDevice} クラスの新しいインスタンスを初期化します。

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
ページを Dicom に変換し、出力ストリームに保存します。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
指定されたページに対して何らかの操作を実行します（e.g.）。
