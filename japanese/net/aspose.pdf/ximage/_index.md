---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XImage クラス。画像 XObject を表すクラス
type: docs
weight: 11350
url: /ja/net/aspose.pdf/ximage/
---
## XImage クラス

画像 X-Object を表すクラス。

```csharp
public sealed class XImage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | 画像に透明性が含まれている場合は true を返し、それ以外の場合は false を返します。 |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | 画像のフィルタータイプを取得します。 |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | 画像のグレースケール版を取得します。 |
| [Height](../../aspose.pdf/ximage/height/) { get; } | 画像の高さを取得します。 |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | 画像が画像マスクとして扱われるべきかどうかを示すフラグを取得します（8.9.6「マスクされた画像」を参照）。このフラグが true の場合、BitsPerComponent の値は 1 であり、Mask と ColorSpace は指定されていないものとします。マスクされていない領域は現在の非ストローク色を使用して塗りつぶされます。デフォルト値: false。 |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | 画像のメタデータ。 |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | 画像の名前を取得または設定します。ページコンテンツに参照がある画像の名前を変更すると、ドキュメントが不正になる可能性があります。この場合は XImage.Rename メソッドを使用してください。 |
| [Width](../../aspose.pdf/ximage/width/) { get; } | 画像の幅を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | XImage にステンシルマスクを追加します。 |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | 画像の色タイプを返します。 |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | コレクション内の画像の名前を返します。 |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | ソース画像から生の画像データを取得します。 |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | 両方の画像が同じオブジェクトを参照している場合は true を返します。 |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | 画像の名前を変更し、新しい名前で画像へのすべての参照を置き換えます。 |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | 画像データをストリームに JPEG 画像として保存します。 |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | 要求された形式でストリームに画像を保存します。 |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | 指定された解像度で JPEG 画像としてストリームに画像データを保存します。 |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | 要求された形式で指定された解像度でストリームに画像を保存します。 |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | 元の画像ストリームを返します。 |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)