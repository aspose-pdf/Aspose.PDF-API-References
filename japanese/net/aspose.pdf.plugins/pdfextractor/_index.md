---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExtractor クラス。PDF ドキュメントのページに発生する可能性のあるテキスト、画像、およびその他のタイプのコンテンツを抽出するための基本機能を表します。
type: docs
weight: 9060
url: /ja/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor クラス

PDF ドキュメントのページに発生する可能性のあるテキスト、画像、およびその他のタイプのコンテンツを抽出するための基本機能を表します。

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable の実装。実際には、PdfExtractor には必要ありません。 |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 指定されたパラメータで PdfExtractor の処理を開始します。 |

## 備考

[`TextExtractor`](../textextractor/) オブジェクトはテキストを抽出するために使用され、[`ImageExtractor`](../imageextractor/) は画像を抽出するために使用されます。

## 例

この例は、PDF ドキュメントのテキストコンテンツを抽出する方法を示しています。

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set instructions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### 関連項目

* インターフェース [IPlugin](../iplugin/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)