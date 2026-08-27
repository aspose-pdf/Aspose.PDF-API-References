---
title: "クラス ImageExtractor"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.ImageExtractor クラス。ImageExtractor プラグインを表します"
type: docs
weight: 9020
url: /ja/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor class

ImageExtractor プラグインを表します。

```csharp
public class ImageExtractor : PdfExtractor
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageExtractor](imageextractor/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable の実装です。実際には PdfExtractor には必要ありません。 |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 指定されたパラメータで PdfExtractor の処理を開始します。 |

## 備考

`ImageExtractor` オブジェクトは PDF ドキュメントからテキストを抽出するために使用されます。

## 例

この例は PDF ドキュメントから画像を抽出する方法を示しています。

```csharp
// 画像を抽出するために ImageExtractor オブジェクトを作成する
using (ImageExtractor extractor = new ImageExtractor())
{
    // ImageExtractorOptions を作成する
    imageExtractorOptions = new ImageExtractorOptions();
    
    // 入力ファイルパスをデータソースに追加します
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // 抽出プロセスを実行する
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // ResultContainer オブジェクトから画像を取得する
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### 関連項目

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


