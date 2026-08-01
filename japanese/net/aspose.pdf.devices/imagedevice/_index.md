---
title: "クラス ImageDevice"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Devices.ImageDevice クラス。画像デバイス用の抽象クラスです。"
type: docs
weight: 3730
url: /ja/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

画像デバイス用の抽象クラスです。

```csharp
public abstract class ImageDevice : PageDevice
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | `ImageDevice` の派生クラス用の抽象初期化子で、解像度を 150x150 に設定します。 |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | 提供された画像サイズとデフォルト解像度 (=150) を使用して、[`JpegDevice`](../jpegdevice/) クラスの新しいインスタンスを初期化します。 |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | `ImageDevice` の派生クラス用の抽象初期化子です。結果画像ファイルの解像度については、[`Resolution`](./resolution/) クラスを参照してください。 |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | 提供された画像サイズとデフォルト解像度 (=150) を使用して、[`JpegDevice`](../jpegdevice/) クラスの新しいインスタンスを初期化します。 |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | 提供された画像サイズと解像度を使用して、[`JpegDevice`](../jpegdevice/) クラスの新しいインスタンスを初期化します。 |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | 提供された画像サイズと解像度を使用して、[`JpegDevice`](../jpegdevice/) クラスの新しいインスタンスを初期化します。 |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | 指定された Page でいくつかの操作を実行します。例として、Page をグラフィック画像に変換します。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページで何らかの操作を実行し、結果をファイルに保存します。 |

### 関連項目

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


