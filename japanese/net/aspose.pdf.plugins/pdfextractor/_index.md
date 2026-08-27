---
title: "PdfExtractor クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.PdfExtractor クラス。PDF Document の Page 上に存在する可能性のあるテキスト、画像、その他のコンテンツを抽出する基本機能を表します"
type: docs
weight: 9210
url: /ja/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

PDF ドキュメントのページに存在する可能性のあるテキスト、画像、その他のコンテンツを抽出する基本機能を表します。

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable の実装です。実際には PdfExtractor には必要ありません。 |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 指定されたパラメータで PdfExtractor の処理を開始します。 |

## 備考

[`TextExtractor`](../textextractor/) オブジェクトはテキストを抽出するために使用され、[`ImageExtractor`](../imageextractor/) は画像を抽出するために使用されます。

## 例

この例は、PDF ドキュメントのテキストコンテンツを抽出する方法を示しています。

```csharp
// PDF コンテンツを抽出するために TextExtractor オブジェクトを作成します
using (TextExtractor extractor = new TextExtractor())
{
    // 指示を設定するために TextExtractorOptions オブジェクトを作成します
    textExtractorOptions = new TextExtractorOptions();
    
    // 入力ファイルパスをデータソースに追加します
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // 抽出プロセスを実行する
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // ResultContainer オブジェクトから抽出されたテキストを取得します
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### 関連項目

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


