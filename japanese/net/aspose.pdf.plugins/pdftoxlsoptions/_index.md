---
title: "クラス PdfToXlsOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.PdfToXlsOptions クラス。XlsConverter プラグイン用の PDF から XLSX へのコンバータオプションを表します"
type: docs
weight: 9300
url: /ja/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions class

[`XlsConverter`](../xlsconverter/) プラグイン用の PDF から XLSX へのコンバータオプションを表します。

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | 出力形式。 |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | PdfConverterOptions プラグインのデータコレクションを返します。 |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | ワークシートの最初の列として空白列を挿入する必要がある場合は true を設定します。デフォルト値は false で、空白列は挿入されません。 |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | 結果のブックでワークシートの数を最小限に抑える必要がある場合は true を設定します。デフォルト値は false で、各 PDF ページが個別のワークシートとして保存されます。 |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | 操作の名前を取得します。 |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | 保存操作結果のために追加されたターゲットのコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | PdfConverter プラグインのデータコレクションに新しいデータソースを追加します。 |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | PdfToXLSXConverterOptions プラグインのデータコレクションに新しいデータソースを追加します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | .xlsx、.xls/xml、または csv ファイル形式を指定できます。デフォルト値は XLSX です。 |

### 関連項目

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


