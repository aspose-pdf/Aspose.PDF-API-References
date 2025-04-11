---
title: Class DicomDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.DicomDevice クラス。PDF ドキュメントのページを Dicom 形式で保存するのに役立つ画像デバイスを表します。
type: docs
weight: 3560
url: /ja/net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice クラス

PDF ドキュメントのページを Dicom 形式で保存するのに役立つ画像デバイスを表します。

```csharp
public sealed class DicomDevice : ImageDevice
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | デフォルトの解像度で `DicomDevice` クラスの新しいインスタンスを初期化します。 |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | 提供されたページサイズで `DicomDevice` クラスの新しいインスタンスを初期化し、デフォルトの解像度 (=150) を使用します。 |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | `DicomDevice` クラスの新しいインスタンスを初期化します。結果の画像ファイルの解像度については、[`Resolution`](../resolution/) クラスを参照してください。 |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | 提供された画像の寸法で `DicomDevice` クラスの新しいインスタンスを初期化し、デフォルトの解像度 (=150) を使用します。 |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | 提供されたページサイズと解像度で `DicomDevice` クラスの新しいインスタンスを初期化します。 |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | 提供された画像の寸法と解像度で `DicomDevice` クラスの新しいインスタンスを初期化します。 |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | ページを Dicom に変換し、出力ストリームに保存します。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページに対していくつかの操作を実行し、結果をファイルに保存します。 |

### 参照

* クラス [ImageDevice](../imagedevice/)
* 名前空間 [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* アセンブリ [Aspose.PDF](../../)