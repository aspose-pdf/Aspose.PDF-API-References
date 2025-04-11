---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractorOptions クラス。TextExtractor プラグインのテキスト抽出オプションを表します
type: docs
weight: 9390
url: /ja/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions クラス

TextExtractor プラグインのテキスト抽出オプションを表します。

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | 'Raw'（デフォルト）テキストフォーマットモードで `TextExtractorOptions` オブジェクトの新しいインスタンスを初期化します。 |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | 指定されたテキストフォーマットモードのために `TextExtractorOptions` オブジェクトの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | フォーマットモードを取得します。 |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | PdfExtractor プラグインデータコレクションを返します。 |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | 操作の名前を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | PdfExtractor プラグインデータコレクションに新しいデータソースを追加します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | PDF ドキュメントをテキストに変換する際に使用できる異なるモードを定義します。`TextExtractorOptions` クラスを参照してください。 |

## 備考

`TextExtractorOptions` オブジェクトは、テキスト抽出操作のために [`TextFormattingMode`](../textextractoroptions.textformattingmode/) および他のオプションを設定するために使用されます。また、入力 PDF ドキュメントを表すデータ（ファイル、ストリーム）を追加する機能を継承します。

## 例

この例は、PDF ドキュメントのテキストコンテンツを抽出する方法を示しています。

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set TextFormattingMode (Pure,  or Raw - default)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // add input file path to data sources
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### 参照

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)