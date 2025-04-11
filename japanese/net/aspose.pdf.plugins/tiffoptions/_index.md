---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TiffOptions クラス。Tiff プラグインの Pdf から Tiff への変換オプションを表します
type: docs
weight: 9420
url: /ja/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions クラス

[`Tiff`](../tiff/) プラグインの Pdf から Tiff への変換オプションを表します。

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TiffOptions](tiffoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | 白と黒の色の変換の境界値を取得または設定します。このパラメータは EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle または ColorDepth.Format1bpp == 1 と共に適用できます。 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | 圧縮の種類を取得または設定します。 |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 画像変換モードを取得します。 |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | ページの座標タイプ (メディア/クロップボックス) を取得または設定します。デフォルトでは CropBox 値が使用されます。 |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | カラーデプスを取得または設定します。 |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) プラグインデータコレクションを返します。 |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | 操作の名前を返します。 |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 結果画像の解像度値を取得または設定します。 |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 処理するページのリストを取得または設定します。 |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | すべてのページを1つのマルチページTiffに保存するフラグを取得または設定します。 |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | 形状のタイプを取得または設定します。 |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | 空白ページをスキップするかどうかを示す値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | [`PdfToImage`](../pdftoimage/) プラグインデータコレクションに新しいデータソースを追加します。 |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 新しい保存データソースを設定します。メモリストリームに画像を保存したい場合は、null をパラメータとして渡します。 |

### 参照

* クラス [PdfToImageOptions](../pdftoimageoptions/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)