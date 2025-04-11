---
title: Class PdfToDocOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToDocOptions クラス。DocConverter プラグインの PDF から DOC への変換オプションを表します。
type: docs
weight: 9090
url: /ja/net/aspose.pdf.plugins/pdftodocoptions/
---
## PdfToDocOptions クラス

[`DocConverter`](../docconverter/) プラグインの PDF から DOC への変換オプションを表します。

```csharp
public sealed class PdfToDocOptions : PdfConverterOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PdfToDocOptions](pdftodocoptions/#constructor)() | デフォルトオプションで `PdfToDocOptions` オブジェクトの新しいインスタンスを初期化します。 |
| [PdfToDocOptions](pdftodocoptions/#constructor_1)(SaveFormat, ConversionMode) | 指定されたフォーマットとモードのために `PdfToDocOptions` オブジェクトの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftodocoptions/conversionmode/) { get; set; } | PDF ドキュメントがワードプロセッシングドキュメントにどのように変換されるかを制御します。 |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | PdfConverterOptions プラグインデータコレクションを返します。 |
| override [OperationName](../../aspose.pdf.plugins/pdftodocoptions/operationname/) { get; } | 操作の名前を取得します。 |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | 保存操作結果のために追加されたターゲットのコレクションを取得します。 |
| [SaveFormat](../../aspose.pdf.plugins/pdftodocoptions/saveformat/) { get; set; } | 出力ドキュメントの保存形式。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | PdfConverter プラグインデータコレクションに新しいデータソースを追加します。 |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | PdfToXLSXConverterOptions プラグインデータコレクションに新しいデータソースを追加します。 |

### 参照

* クラス [PdfConverterOptions](../pdfconverteroptions/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)