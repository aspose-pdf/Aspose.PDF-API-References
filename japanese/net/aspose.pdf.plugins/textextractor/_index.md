---
title: "クラス TextExtractor"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.TextExtractor クラス。TextExtractor プラグインを表します"
type: docs
weight: 9530
url: /ja/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor class

TextExtractor プラグインを表します。

```csharp
public class TextExtractor : PdfExtractor
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextExtractor](textextractor/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable の実装です。実際には PdfExtractor には必要ありません。 |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 指定されたパラメータで PdfExtractor の処理を開始します。 |

## 備考

`TextExtractor` オブジェクトは PDF ドキュメントからテキストを抽出するために使用されます。

## 例

この例は、PDF ドキュメントのテキストコンテンツを抽出する方法を示しています。

```csharp
// PDF コンテンツからテキストを抽出するために TextExtractor オブジェクトを作成します
using (TextExtractor extractor = new TextExtractor())
{
    // TextExtractorOptions を作成します
    textExtractorOptions = new TextExtractorOptions();
    
    // 入力ファイルパスをデータソースに追加します
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // 抽出プロセスを実行する
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // ResultContainer オブジェクトから抽出されたテキストを取得します
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### 関連項目

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


