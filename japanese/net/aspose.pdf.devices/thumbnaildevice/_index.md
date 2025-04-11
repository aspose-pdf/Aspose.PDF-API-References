---
title: Class ThumbnailDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ThumbnailDevice クラス。PDF ドキュメントのページをサムネイル画像に保存する画像デバイスを表します。
type: docs
weight: 3690
url: /ja/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice クラス

PDF ドキュメントのページをサムネイル画像に保存する画像デバイスを表します。

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | デフォルトのサムネイル画像サイズ (200x200 ピクセル) で `ThumbnailDevice` クラスの新しいインスタンスを初期化します。 |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | `ThumbnailDevice` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | ページの座標タイプ (メディア/クロップボックス) を取得または設定します。デフォルトでは CropBox 値が使用されます。 |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | フォームのプレゼンテーションモードを取得または設定します。 |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 画像出力の高さを取得します。 |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | レンダリングオプションを取得または設定します。 |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 画像の解像度を取得します。 |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 画像出力の幅を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | ページをサムネイル画像 PNG に変換し、出力ストリームに保存します。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページに対していくつかの操作を実行し、結果をファイルに保存します。 |

### 参照

* クラス [ImageDevice](../imagedevice/)
* 名前空間 [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* アセンブリ [Aspose.PDF](../../)