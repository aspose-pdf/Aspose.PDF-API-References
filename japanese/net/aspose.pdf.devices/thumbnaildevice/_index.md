---
title: "クラス ThumbnailDevice"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Devices.ThumbnailDevice クラス。pdf ドキュメントのページをサムネイル画像に保存する画像デバイスを表します。"
type: docs
weight: 3810
url: /ja/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice class

PDF ドキュメントのページをサムネイル画像として保存する画像デバイスを表します。

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | `ThumbnailDevice` クラスの新しいインスタンスを、サムネイル画像のデフォルトサイズ (200x200 ピクセル) で初期化します。 |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | `ThumbnailDevice` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | ページ座標タイプ（Media/Crop ボックス）を取得または設定します。デフォルトでは CropBox の値が使用されます。 |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | フォームの表示モードを取得または設定します。 |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 画像出力の高さを取得します。 |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | レンダリングオプションを取得または設定します。 |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 画像解像度を取得します。 |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 画像出力幅を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Page をビットマップに変換します。 |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | ページをサムネイル画像 png に変換し、出力ストリームに保存します。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページで何らかの操作を実行し、結果をファイルに保存します。 |

### 関連項目

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


