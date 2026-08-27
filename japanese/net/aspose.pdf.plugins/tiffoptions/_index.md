---
title: "TiffOptions クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.TiffOptions クラス。Tiff プラグイン用の Pdf から Tiff へのコンバータオプションを表します"
type: docs
weight: 9570
url: /ja/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions class

[`Tiff`](../tiff/) プラグイン用の Pdf から Tiff へのコンバータオプションを表します。

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TiffOptions](tiffoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | 白と黒の色変換の境界値を取得または設定します。このパラメータは EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle、または ColorDepth.Format1bpp == 1 と共に適用できます |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | 圧縮のタイプを取得または設定します。 |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 画像変換モードを取得します。 |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Page 座標タイプ（Media/Crop ボックス）を取得または設定します。デフォルトでは CropBox の値が使用されます。 |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | カラーデプスを取得または設定します。 |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | `[`PdfToImage`](../pdftoimage/)` プラグインのデータコレクションを返します。 |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | 操作の名前を返します。 |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 生成された画像の解像度値を取得または設定します。 |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 処理対象のページリストを取得または設定します。 |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | すべての Page を 1 つのマルチページ TIFF に保存できるフラグを取得および設定します。 |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | シェイプのタイプを取得または設定します。 |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | 空白ページをスキップするかどうかを示す値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | `[`PdfToImage`](../pdftoimage/)` プラグインのデータコレクションに新しいデータ ソースを追加します。 |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 新しい保存データ ソースを設定します。これは . のみが使用可能です。画像をメモリ ストリームに保存したい場合は、パラメータに null を渡してください。 |

### 関連項目

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


