---
title: "PngOptions クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.PngOptions クラス。Png プラグイン用の Pdf から Png への変換オプションを表します"
type: docs
weight: 9330
url: /ja/net/aspose.pdf.plugins/pngoptions/
---
## PngOptions class

[`Png`](../png/) プラグイン用の Pdf から Png への変換オプションを表します。

```csharp
public sealed class PngOptions : PdfToImageOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PngOptions](pngoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 画像変換モードを取得します。 |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | `[`PdfToImage`](../pdftoimage/)` プラグインのデータコレクションを返します。 |
| override [OperationName](../../aspose.pdf.plugins/pngoptions/operationname/) { get; } | 操作の名前を返します。 |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 生成された画像の解像度値を取得または設定します。 |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 処理対象のページリストを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | `[`PdfToImage`](../pdftoimage/)` プラグインのデータコレクションに新しいデータ ソースを追加します。 |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 新しい保存データ ソースを設定します。これは . のみが使用可能です。画像をメモリ ストリームに保存したい場合は、パラメータに null を渡してください。 |

### 関連項目

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


