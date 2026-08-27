---
title: "ThumbnailDevice"
linktitle: "ThumbnailDevice"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントのページをサムネイル画像として保存する画像デバイスを表します。"
type: docs
weight: 200
url: /ja/java/com.aspose.pdf.devices/thumbnaildevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.ThumbnailDevice

```
public final class ThumbnailDevice extends ImageDevice
```

PDF ドキュメントのページをサムネイル画像として保存する画像デバイスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ThumbnailDevice](#ThumbnailDevice--) | サムネイル画像 (200x200 ピクセル) のデフォルトサイズで {@link ThumbnailDevice} クラスの新しいインスタンスを初期化します。 |
| [ThumbnailDevice](#ThumbnailDevice-int-int-) | {@link ThumbnailDevice} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [processInternal](#processInternal-com.aspose.pdf.Page-java.io.OutputStream-) | ページをサムネイル画像 PNG に変換し、出力ストリームに保存します。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 指定されたページに対して何らかの操作を実行します（e.g.）。 |

### ThumbnailDevice {#ThumbnailDevice--}
```
public ThumbnailDevice()
```

サムネイル画像 (200x200 ピクセル) のデフォルトサイズで {@link ThumbnailDevice} クラスの新しいインスタンスを初期化します。

### ThumbnailDevice {#ThumbnailDevice-int-int-}
```
public ThumbnailDevice(int width, int height)
```

{@link ThumbnailDevice} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | サムネイル画像の出力幅。 |
| 高さ |  | サムネイル画像の出力高さ。 |

### processInternal {#processInternal-com.aspose.pdf.Page-java.io.OutputStream-}
ページをサムネイル画像 PNG に変換し、出力ストリームに保存します。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
指定されたページに対して何らかの操作を実行します（e.g.）。
