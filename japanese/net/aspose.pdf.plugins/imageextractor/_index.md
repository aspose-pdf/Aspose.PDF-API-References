---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.ImageExtractor クラス。ImageExtractor プラグインを表します
type: docs
weight: 8890
url: /ja/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor クラス

ImageExtractor プラグインを表します。

```csharp
public class ImageExtractor : PdfExtractor
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageExtractor](imageextractor/)() | デフォルトのコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable の実装。実際には、PdfExtractor には必要ありません。 |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 指定されたパラメータで PdfExtractor 処理を開始します。 |

## 備考

`ImageExtractor` オブジェクトは、PDF ドキュメントからテキストを抽出するために使用されます。

## 例

この例は、PDF ドキュメントから画像を抽出する方法を示しています。

```csharp
// create ImageExtractor object to extract images
using (ImageExtractor extractor = new ImageExtractor())
{
    // create ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // add input file path to data sources
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // get the image from the ResultContainer object
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### 関連項目

* クラス [PdfExtractor](../pdfextractor/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)