---
title: Class PdfToXlsOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToXlsOptions クラス。XlsConverter プラグインの PDF から XLSX への変換オプションを表します。
type: docs
weight: 9150
url: /ja/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions クラス

[`XlsConverter`](../xlsconverter/) プラグインの PDF から XLSX への変換オプションを表します。

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | 出力形式。 |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | PdfConverterOptions プラグインデータコレクションを返します。 |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | ワークシートの最初の列として空白の列を挿入する必要がある場合は true に設定します。デフォルト値は false です。これは、空白の列が挿入されないことを意味します。 |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | 結果のワークブック内のワークシートの数を最小限に抑える必要がある場合は true に設定します。デフォルト値は false です。これは、各 PDF ページを別々のワークシートとして保存することを意味します。 |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | 操作の名前を取得します。 |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | 保存操作結果のために追加されたターゲットのコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | PdfConverter プラグインデータコレクションに新しいデータソースを追加します。 |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | PdfToXLSXConverterOptions プラグインデータコレクションに新しいデータソースを追加します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | .xlsx、.xls/xml または csv ファイル形式を指定できます。デフォルト値は XLSX です。 |

### 参照

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)