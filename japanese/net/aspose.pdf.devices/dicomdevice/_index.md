---
title: "クラス DicomDevice"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Devices.DicomDevice クラス。PDF Document のページを Dicom 形式で保存するのに役立つ画像デバイスを表します。"
type: docs
weight: 3680
url: /ja/net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice class

PDF ドキュメントのページを DICOM 形式で保存するのに役立つ画像デバイスを表します。

```csharp
public sealed class DicomDevice : ImageDevice
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | `DicomDevice` クラスの新しいインスタンスをデフォルトの解像度で初期化します。 |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | 指定されたページサイズ、デフォルトの解像度 (=150) で、`DicomDevice` クラスの新しいインスタンスを初期化します。 |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | `DicomDevice` クラスの新しいインスタンスを初期化します。結果画像ファイルの解像度については、[`Resolution`](../resolution/) クラスを参照してください。 |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | 指定された画像サイズ、デフォルトの解像度 (=150) で、`DicomDevice` クラスの新しいインスタンスを初期化します。 |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | 提供されたページサイズと解像度で `DicomDevice` クラスの新しいインスタンスを初期化します。 |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | 提供された画像寸法と解像度で `DicomDevice` クラスの新しいインスタンスを初期化します。 |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | ページを Dicom に変換し、出力ストリームに保存します。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページで何らかの操作を実行し、結果をファイルに保存します。 |

### 関連項目

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


