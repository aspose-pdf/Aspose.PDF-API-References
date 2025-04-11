---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ImageDevice クラス。画像デバイスのための抽象クラス
type: docs
weight: 3610
url: /ja/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice クラス

画像デバイスのための抽象クラスです。

```csharp
public abstract class ImageDevice : PageDevice
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | `ImageDevice` の子孫のための抽象初期化子で、解像度を 150x150 に設定します。 |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | 提供された画像の寸法とデフォルトの解像度 (=150) で [`JpegDevice`](../jpegdevice/) クラスの新しいインスタンスを初期化します。 |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | `ImageDevice` の子孫のための抽象初期化子です。結果の画像ファイルの解像度については、[`Resolution`](./resolution/) クラスを参照してください。 |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | 提供された画像の寸法とデフォルトの解像度 (=150) で [`JpegDevice`](../jpegdevice/) クラスの新しいインスタンスを初期化します。 |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | 提供された画像の寸法と解像度で [`JpegDevice`](../jpegdevice/) クラスの新しいインスタンスを初期化します。 |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | 提供された画像の寸法と解像度で [`JpegDevice`](../jpegdevice/) クラスの新しいインスタンスを初期化します。 |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | 指定されたページに対して何らかの操作を実行します。例えば、ページをグラフィック画像に変換します。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページに対して何らかの操作を実行し、結果をファイルに保存します。 |

### 参照

* クラス [PageDevice](../pagedevice/)
* 名前空間 [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* アセンブリ [Aspose.PDF](../../)