---
title: Class PdfAConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAConverter クラス。PDF/A 形式の PDF ドキュメントの変換を処理し、PDF/A 準拠の検証を行うプラグインを表します。
type: docs
weight: 9000
url: /ja/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter クラス

PDF/A 形式の PDF ドキュメントの変換を処理し、PDF/A 準拠の検証を行うプラグインを表します。

```csharp
public sealed class PdfAConverter : IPlugin
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | デフォルトのコンストラクター。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | 指定されたオプションで PDF/A 変換または検証プロセスを開始します。 |

## 例

この例は、PDF ドキュメントが PDF/A 形式 (この場合は PDF/A-1a) に準拠しているかを検証する方法を示しています。

```csharp
// Create the options class to set up the validation process
var options = new PdfAValidateOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_1A
};

// Add one or more files to be validated
options.AddInput(new FileDataSource("path_to_your_first_pdf_file.pdf")); // replace with your actual file path
options.AddInput(new FileDataSource("path_to_your_second_pdf_file.pdf"));
// add more files as needed

// Create the plugin instance
var plugin = new PdfAConverter();

// Run the validation and get results
var resultContainer = plugin.Process(options);

// Check the resultContainer.ResultCollection property for validation results for each file:
for (var i = 0; i < resultContainer.ResultCollection.Count; i++)
{
    var result = resultContainer.ResultCollection[i];
    var validationResult = (PdfAValidationResult) result.Data;
    var isValid = validationResult.IsValid; // Validation result for the i-th document
}
```

この例は、PDF ドキュメントを PDF/A 形式 (この場合は PDF/A-3b) に変換する方法を示しています。

```csharp
// Create the options class to set up the conversion process
var options = new PdfAConvertOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_3B
};

// Add the source file
options.AddInput(new FileDataSource("path_to_your_pdf_file.pdf")); // replace with your actual file path

// Add the path to save the converted file
options.AddOutput(new FileDataSource("path_to_the_converted_file.pdf"));

// Create the plugin instance
var plugin = new PdfAConverter();

// Run the conversion
plugin.Process(options);
```

### 関連項目

* インターフェース [IPlugin](../iplugin/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)