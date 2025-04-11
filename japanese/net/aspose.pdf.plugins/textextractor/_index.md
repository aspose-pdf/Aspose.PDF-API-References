---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractor クラス。TextExtractor プラグインを表します
type: docs
weight: 9380
url: /ja/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor クラス

TextExtractor プラグインを表します。

```csharp
public class TextExtractor : PdfExtractor
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextExtractor](textextractor/)() | デフォルトのコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable の実装。実際には、PdfExtractor には必要ありません。 |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 指定されたパラメータで PdfExtractor 処理を開始します。 |

## 備考

`TextExtractor` オブジェクトは、PDF ドキュメント内のテキストを抽出するために使用されます。

## 例

この例は、PDF ドキュメントのテキストコンテンツを抽出する方法を示しています。

```csharp
// create TextExtractor object to extract text in PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### 関連項目

* クラス [PdfExtractor](../pdfextractor/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)