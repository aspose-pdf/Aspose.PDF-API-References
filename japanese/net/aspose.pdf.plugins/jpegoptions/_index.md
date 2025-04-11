---
title: Class JpegOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.JpegOptions クラス。Jpeg プラグインの Pdf から Jpeg への変換オプションを表します
type: docs
weight: 8920
url: /ja/net/aspose.pdf.plugins/jpegoptions/
---
## JpegOptions クラス

[`Jpeg`](../jpeg/) プラグインの Pdf から Jpeg への変換オプションを表します。

```csharp
public sealed class JpegOptions : PdfToImageOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [JpegOptions](jpegoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 画像変換モードを取得します。 |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) プラグインデータコレクションを返します。 |
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | 操作の名前を返します。 |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 結果の画像の解像度値を取得または設定します。 |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 処理するページのリストを取得または設定します。 |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | Jpeg の品質を取得および設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | [`PdfToImage`](../pdftoimage/) プラグインデータコレクションに新しいデータソースを追加します。 |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 新しい保存データソースを設定します。メモリストリームに画像を保存したい場合は、パラメータとして null を渡します。 |

### 参照

* クラス [PdfToImageOptions](../pdftoimageoptions/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)