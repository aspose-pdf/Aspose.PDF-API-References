---
title: "クラス XImage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.XImage クラス。画像 XObject を表すクラス"
type: docs
weight: 11540
url: /ja/net/aspose.pdf/ximage/
---
## XImage class

画像 X-Object を表すクラスです。

```csharp
public sealed class XImage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | 画像に透明性が含まれている場合は true を返し、そうでない場合は false を返します。 |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | 画像フィルターのタイプを取得します。 |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | 画像のグレースケール版を取得します。 |
| [Height](../../aspose.pdf/ximage/height/) { get; } | 画像の高さを取得します。 |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | 画像がイメージマスクとして扱われるかどうかを示すフラグを取得します（8.9.6「Masked Images」参照）。このフラグが true の場合、BitsPerComponent の値は 1 であり、Mask と ColorSpace は指定されません。マスクされていない領域は現在の非ストロークカラーで塗りつぶされます。既定値: false。 |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | 画像のメタデータ。 |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | 画像名を取得または設定します。ページコンテンツで参照されている画像の名前を変更すると、ドキュメントが正しくなくなる可能性があることに注意してください。その場合は XImage.Rename メソッドを使用してください。 |
| [Width](../../aspose.pdf/ximage/width/) { get; } | 画像の幅を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | XImage にステンシルマスクを追加します。 |
| [GetAlternativeText](../../aspose.pdf/ximage/getalternativetext/)(Page) | XImage の代替テキストを含む文字列のリストを返します。 |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | 画像のカラータイプを返します。 |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | コレクション内の画像の名前を返します。 |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | ソース画像から生の画像データを取得します。 |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | 両方の画像が同じオブジェクトを参照している場合は true を返します。 |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | 画像の名前を変更し、画像へのすべての参照を新しい名前に置き換えます。 |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | 画像データを JPEG 画像としてストリームに保存します。 |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | 画像を要求された形式でストリームに保存します。 |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | 指定された解像度で JPEG 画像として画像データをストリームに保存します。 |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | 指定された解像度で要求された形式の画像をストリームに保存します。 |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | 元の画像ストリームを返します。 |
| [TrySetAlternativeText](../../aspose.pdf/ximage/trysetalternativetext/)(string, Page) | ページ上の XImage の代替テキストを設定します。 |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


