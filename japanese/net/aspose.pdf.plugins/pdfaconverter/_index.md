---
title: "クラス PdfAConverter"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.PdfAConverter クラス。PDF 文書を PDF/A 形式に変換し、PDF/A 準拠性の検証を行うプラグインを表します。"
type: docs
weight: 9150
url: /ja/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter class

PDF/A 形式での PDF ドキュメントの変換と PDF/A 準拠性の検証を処理するプラグインを表します。

```csharp
public sealed class PdfAConverter : IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | 指定されたオプションで PDF/A の変換または検証プロセスを開始します。 |

## 例

この例では、PDF ドキュメントが PDF/A 形式（この場合は PDF/A-1a）に準拠しているかを検証する方法を示しています。

```csharp
// 検証プロセスを設定するためのオプション クラスを作成します。
var options = new PdfAValidateOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_1A
};

// 検証対象のファイルを 1 つ以上追加します。
options.AddInput(new FileDataSource("path_to_your_first_pdf_file.pdf")); // replace with your actual file path
options.AddInput(new FileDataSource("path_to_your_second_pdf_file.pdf"));
// 必要に応じてさらにファイルを追加します。

// プラグイン インスタンスを作成します。
var plugin = new PdfAConverter();

// 検証を実行し、結果を取得します。
var resultContainer = plugin.Process(options);

// 各ファイルの検証結果は resultContainer.ResultCollection プロパティで確認してください。
for (var i = 0; i < resultContainer.ResultCollection.Count; i++)
{
    var result = resultContainer.ResultCollection[i];
    var validationResult = (PdfAValidationResult) result.Data;
    var isValid = validationResult.IsValid; // Validation result for the i-th document
}
```

この例では、PDF ドキュメントを PDF/A 形式（この場合は PDF/A-3b）に変換する方法を示しています。

```csharp
// 変換プロセスを設定するためのオプション クラスを作成します。
var options = new PdfAConvertOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_3B
};

// ソース ファイルを追加します。
options.AddInput(new FileDataSource("path_to_your_pdf_file.pdf")); // replace with your actual file path

// 変換後のファイルを保存するパスを追加します。
options.AddOutput(new FileDataSource("path_to_the_converted_file.pdf"));

// プラグイン インスタンスを作成します。
var plugin = new PdfAConverter();

// 変換を実行します。
plugin.Process(options);
```

### 関連項目

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


