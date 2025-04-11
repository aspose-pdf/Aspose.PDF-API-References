---
title: Class PdfToImageOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToImageOptions クラス。PdfToImage プラグインのオプションを表します
type: docs
weight: 9130
url: /ja/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions クラス

[`PdfToImage`](../pdftoimage/) プラグインのオプションを表します。

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 画像変換モードを取得します。 |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) プラグインデータコレクションを返します。 |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | 操作名を返します。 |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 結果の画像の解像度値を取得または設定します。 |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 処理するページのリストを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | [`PdfToImage`](../pdftoimage/) プラグインデータコレクションに新しいデータソースを追加します。 |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 新しい保存データソースを設定します。メモリストリームに画像を保存したい場合は、パラメータとして null を渡します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | PDF ドキュメントから Jpeg 画像に変換する際に使用できるさまざまなモードを定義します。[`JpegOptions`](../jpegoptions/) クラスを参照してください。 |

## 備考

PdfImageOptions クラスは、入力 PDF ドキュメントを表すデータ（ファイル、ストリーム）を追加するための基本機能を含んでいます。

### 参照

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)